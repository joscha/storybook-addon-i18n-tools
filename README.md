# I18n Toolbox Storybook Add-on

[![Greenkeeper badge](https://badges.greenkeeper.io/joscha/storybook-addon-i18n-tools.svg)](https://greenkeeper.io/)

[![Build Status](https://travis-ci.org/joscha/storybook-addon-i18n-tools.svg?branch=master)](https://travis-ci.org/joscha/storybook-addon-i18n-tools)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)


The i18n toolbox addon can be used to swap text direction in stories. This addon works with [React Storybook](https://github.com/kadirahq/react-storybook).

![Screencast of the add-on](docs/animation.gif)

## Getting Started

First, install the addon

```shell
npm install -D storybook-addon-i18n-tools
```

Add this line to your `addons.js` file (create this file inside your storybook config directory if needed).

```js
import 'storybook-addon-i18n-tools/register';
```

Import the addon in your storybook config to initialize it:

```js
import 'storybook-addon-i18n-tools';
```

## Known issues
* Toggle button state does not reset [when navigating away from the current story](https://github.com/kadirahq/react-storybook/issues/568) (PR would be 💖)
