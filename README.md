# vue-i18n-starter

> A Vue.js starter project for i18n websites

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```
The default language, supported languages and fallback language can be setup inside `constants/trans.js`.
 
Inside the `router/index.js` the beforeEnter guard calls the `Trans.routeMiddleware`. That will redirect the user to a valid language route if the current one is not supported.
 
