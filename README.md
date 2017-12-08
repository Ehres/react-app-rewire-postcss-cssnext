# react-app-rewire-postcss-cssnext
Add the cssnext webpack plugin to your create-react-app via react-app-rewired

# Install

npm:
```bash
$ npm install --saveDev react-app-rewire-postcss-cssnext
```

yarn:
```bash
$ yarn add --dev react-app-rewire-postcss-cssnext
```

# Add it to your project

* [Rewire your app](https://github.com/timarney/react-app-rewired#how-to-rewire-your-create-react-app-project) than modify `config-overrides.js`

```javascript
const rewireCSSNext = require('react-app-rewire-postcss-cssnext');

/* config-overrides.js */
module.exports = function override(config, env) {
  config = rewireCSSNext(config, env);
  return config;
}
```
