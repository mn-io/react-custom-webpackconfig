# react-custom-webpackconfig

Use Create React App (Typescript) with custom config without ejecting.

Add a postinstall script to your package.json:
`"postinstall": "node config/postinstall.js"`

Current config adds LESS-Loader.
In order to use non Typescript version, adapt `destDir` within `postinstall.js`
