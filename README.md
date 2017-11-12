# React Redux Tiny Snippets for Atom

[![apm](https://img.shields.io/apm/v/react-redux-tiny-snippets.svg)](https://atom.io/packages/react-redux-tiny-snippets)

Tiny Snippets of React Redux for [Atom](https://atom.io/) editor.

This package autocompletes..

- connect `mapStateToProps`, `mapDispatchToProps`, `mergeProps` with JSDOC comments.

#### example

```javascript
// Typing `mapstatetoprops` leads...

/**
 * map state to props
 * @param  {object} state    state tree
 * @param  {object} ownProps own props
 * @return {object}          state props
 */
const mapStateToProps = (state, ownProps) => {
  return {
    $1
  }
}
```

## Installation

Run the following command:

```shell
$ apm install react-reduz-tiny-snippets
```

Alternatively go to `Atom > Preferences > Packages` and search for `react-redux-tiny-snippets`.

## Development

```shell
git clone git@github.com:kamataryo/react-redux-tiny-snippets.git
cd react-redux-tiny-snippets
npm install
npm run build
```

## Contribution

Issues and PRs are welcome.

## Release Note

### 0.0.0

- release
