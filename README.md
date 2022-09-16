# Registering provider

## Setup

Install the package `npm i -s @saqibahmed515/adonis-newrelic` Add new relic provider in the top of providers list.

```js
// server/app.js

const providers = [
  `@saqibahmed515/adonis-newrelic/providers/Provider`
  // ...
];
```

In the root directory of the project add `newrelic.js`. You can either download `newrelic.js` from your newrelic dashboard or copy from `node_modules/newrelic/newrelic.js` and update your app name and license key.

This project is a fork of `@furbana/adonis-newrelic` with a memory leak fix mentioned in [this PR](https://github.com/Frubana/adonis-newrelic/pull/9).

