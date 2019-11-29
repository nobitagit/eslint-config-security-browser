# Eslint config security (browser)

A collection of rules and plugins aimed at highlighting potential security threats in client side JavaScript codebases.

## Installation

```sh
yarn add -D eslint-config-security-browser
# or
npm i -D eslint-config-security-browser
```

Make sure that you also install the peerdeps:

```sh
yarn add -D eslint-plugin-no-unsanitized eslint-plugin-prototype-pollution-security-rules eslint-plugin-scanjs-rules
# or
npm i -D eslint-plugin-no-unsanitized eslint-plugin-prototype-pollution-security-rules eslint-plugin-scanjs-rules
```

Finally add the `eslint-config-security-browser` to your Eslint config:

```js
  // ...
  extends: [
    'eslint-config-security-browser'
  ],
  plugins: [
  // ...
```

## Credits

This config is based off [Jakob Wilkin's Linting For Bugs & Vulnerabilities article and demo](https://medium.com/greenwolf-security/linting-for-bugs-vulnerabilities-49bc75a61c6) and made available to anyone on npm.

## License

MIT
