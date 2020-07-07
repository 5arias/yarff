# yarff - Yet Another React Form(ik) Framework

> Create complex forms via json

[![NPM](https://img.shields.io/npm/v/yarff.svg)](https://www.npmjs.com/package/yarff) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save yarff
```

## Usage

```tsx
import React, { Component } from 'react'

import MyComponent from 'yarff'
import 'yarff/dist/index.css'

class Example extends Component {
  render() {
    return <MyComponent />
  }
}
```

## Features
- [Schema](#schema)
- [Branching](#branching)
- [Conditional Fields](#conditional-fields)
- [Content Fields](#content-fields)
- [Dynamic Checkbox/Radio/Select Choices](#dynamic-checkbox/radio/select-choices)
- [Repeatable Fields & Field Sets](#repeatable-fields-&-field-sets)

### Schema
The `Form` component provides a simple standardized way to create single and
multi-page web forms using only a JSON schema.

Form pages consist of an `id`, `title` (optional), `description` (optional),
and an array of field objects.

Fields use the field components in this design system and are declared via the
`type` key in each field object. Fields support all props listed within that
component's documentation - including required props. The following fields
are currently supported:

- `content`
- `checkbox`
- `radio`
- `repeatable`
- `select`
- `text`
- All other valid HTML input types will be rendered by the Field component.

### Branching

### Conditional Fields

### Content Fields

### Dynamic Checkbox/Radio/Select Choices

### Repeatable Fields & Field Sets

## License

MIT © [5arias](https://github.com/5arias)
