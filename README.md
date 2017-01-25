# react-redux-sublime-snippets

Sublime snippets for [React](http://facebook.github.io/react/docs/component-specs.html) and [Redux](http://redux.js.org/)

## Installation

```
cd /Users/<username>/Library/Application\ Support/Sublime\ Text\ 3/Packages/ 

git clone https://github.com/mackness/babel-sublime-snippets.git react-redux-snippets
```

## Using the "React: wrap in a component" snippet

First, select a block of JSX. Then, from the Command Palette select "React: wrap in a component". Or, you can set up a key binding.

To set a key binding, go to "Preferences: Key Bindings - User" from the Command Palette and add an entry like this:

```json
{
  "keys": ["ctrl+shift+,"],
  "command": "insert_snippet",
  "args": {
    "name": "Packages/Babel Snippets/react_wrap.sublime-snippet"
  }
}
```

## Available snippets

### React

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rcf→`   | functional component skeleton |
| `rrc→`   | react redux container |
| `cdm→`   | `componentDidMount() {…}` |
| `cdup→`  | `componentDidUpdate(prevProps, prevState) {…}` |
| `cwm→`   | `componentWillMount() {…}` |
| `cwr→`   | `componentWillReceiveProps(nextProps) {…}` |
| `cwun→`  | `componentWillUnmount() {…}` |
| `cwup→`  | `componentWillUpdate(nextProps, nextState) {…}` |
| `fdn→`   | `React.findDOMNode(…)` |
| `gdp→`   | `getDefaultProps() {…}` |
| `gis→`   | `getInitialState() {…}` |
| `ren→`   | `render() {…}` |
| `sst→`   | `this.setState(…)` |
| `scu→`   | `shouldComponentUpdate(nextProps, nextState) {…}` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `pt→`    | `propTypes { ... }` |
| `pta→`   | `PropTypes.arrayOf` |
| `ptai→`  | `PropTypes.arrayOf (Instances)` |
| `ptb→`   | `PropTypes.bool` |
| `pte→`   | `PropTypes.element` |
| `ptf→`   | `PropTypes.func` |
| `pti→`   | `PropTypes.instanceOf` |
| `ptn→`   | `PropTypes.number` |
| `ptn→`   | `PropTypes.node` |
| `pto→`   | `PropTypes.object` |
| `ptof→`  | `PropTypes.oneOf (Enum)` |
| `ptof→`  | `PropTypes.objectOf` |
| `ptoft→` | `PropTypes.oneOfType (Union)` |
| `pts→`   | `PropTypes.string` |
| `ptsp→`  | `PropTypes.shape` |

## Notes

  * Unsupported React API snippets: `displayName`, `forceUpdate`, `getDOMNode` (use `React.findDOMNode`), `ismounted`, `mixins`, `replaceProps`, `replaceState`, `setProps`, `statics`.

## Snippet(ing)

Read [Extending Sublime Text » Snippets](http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/extensibility/snippets.html).
