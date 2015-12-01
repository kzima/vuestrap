Vuestrap
=========

Vuestrap is a Javascript wrapper for Bootstrap 4 components.

Primarily used as a foundation to an open source library of components built with Vue.js, but could be used in any project that needs Bootstrap 4 components.

The Concept
=========

![alt text](https://github.com/kzima/vuestrap/raw/master/assets/web-components-concept.png "Web components")

Usage
=========

```js
npm install vuestrap
```

You can import individual components like so:

```
import 'vuestrap/core'
import 'vuestrap/alert'
```

To import all components:

```
import 'vuestrap/components'
```

To import everything (components and core):

```
import 'vuestrap'
```

*Note: You will need <a href="https://github.com/babel/babel-loader">Babel Loader</a> in your Webpack config file to support ES6 syntax.


List of components using vuestrap
=========
- [Base Vuestrap Components](http://kzima.github.io/vuestrap-base-components/#/alert) - A complete set of Bootstrap 4 components -- *by kzima*
- [Svg Icons](http://kzima.github.io/vuestrap-icons/#/icons) - A complementary set of svg icons wrapped in a `<icon>` component -- *by kzima*
- [Docs for web components](http://kzima.github.io/vuestrap-docs/#/demo) - A small app with `<docs-search>` and `<docs-demo>` components to showcase other web components -- *by kzima*

TODO
=========
- update to Bootstrap 4 stable version (as soon as it is ready)
