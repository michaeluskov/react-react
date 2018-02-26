# react-react

[![npm](https://img.shields.io/npm/v/react-react.svg?style=flat-square)](https://www.npmjs.com/package/react-react)

Impressive state management toolkit for react

### Cons
* Easy to use
* Easy to read and maintain
* Low barrier to entry
* Full react compatible
* Small size
* Flow and Typescript support

### Installation

```bash
yarn add react-react
```

or 

```bash
npm install react-react
```

### How to use

First you should create component:

```javascript
import * as React from "react-react";

class MyComponent extends React.Component {
    
}
```

To set state use `setState` function. For example

```javascript
foo() {
    this.setState({ bar: "value" })
}
```

Access to state via `state` field:

```javascript
render() {
    return <div>{this.state.bar}</div>
}
```