<p align="center">
  <a href="https://cdn.itwcreativeworks.com/assets/operst/images/logo/operst-brandmark-black-x.svg">
    <img src="https://cdn.itwcreativeworks.com/assets/operst/images/logo/operst-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/operst/operst.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/operst.svg">
  <img src="https://img.shields.io/bundlephobia/min/operst.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/operst/operst.svg">
  <img src="https://img.shields.io/npm/dm/operst.svg">
  <img src="https://img.shields.io/node/v/operst.svg">
  <img src="https://img.shields.io/website/https/operstagency.com.svg">
  <img src="https://img.shields.io/github/license/operst/operst.svg">
  <img src="https://img.shields.io/github/contributors/operst/operst.svg">
  <img src="https://img.shields.io/github/last-commit/operst/operst.svg">
  <br>
  <br>
  <a href="https://operstagency.com">Site</a> | <a href="https://www.npmjs.com/package/operst">NPM Module</a> | <a href="https://github.com/operst/operst">GitHub Repo</a>
  <br>
  <br>
  <strong>operst</strong> is the official npm module of <a href="https://operstagency.com">Operst</a>, a digital marketing agency that delivers comprehensive advertising solutions. Our expert services will maximize your ROAS to get more leads and grow your business.
</p>

## Operst Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## Features
* Getting proxy lists

### Getting an API key
You can use so much of `operst` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Operst account](https://operstagency.com/authentication/signup).

## Install Operst
### Install via npm
Install with npm if you plan to use `operst` in a Node project or in the browser.
```shell
npm install operst
```
If you plan to use `operst` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const operst = new (require('operst'))({
  // Not required, but having one removes limits (get your key at https://operstagency.com).
  apiKey: 'api_test_key'
});
```

### Install via CDN
Install with CDN if you plan to use Operst only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/operst@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var operst = new Operst({
    // Not required, but having one removes limits (get your key at https://operstagency.com).
    apiKey: 'api_test_Key'
  });
</script>
```

### Use without installation
You can use `operst` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## Using Operst
After you have followed the install step, you can start using `operst` to maximize your ROAS to get more leads and grow your business

For a more in-depth documentation of this library and the Operst service, please visit the official Operst website.

## Use without installation
### Use Operst with `curl`
```shell
# Standard
curl -X POST https://api.operstagency.com
```

## What Can Operst do?
Operst is a [digital marketing agency](https://operstagency.com) that delivers comprehensive advertising solutions. Our expert services will maximize your ROAS to get more leads and grow your business

## Final Words
If you are still having difficulty, we would love for you to post
a question to [the Operst issues page](https://github.com/operst/operst/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
