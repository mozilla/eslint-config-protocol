# eslint-config-protocol

[![Build Status](https://travis-ci.org/mozilla/eslint-config-protocol.svg?branch=master)](https://travis-ci.org/mozilla/eslint-config-protocol)

A shared [ESLint](https://eslint.org/) config for [Protocol](https://github.com/mozilla/protocol/) related projects.

## Installation

```
npm install @mozilla-protocol/eslint-config --save-dev
```

## Configuration

For browser environments, extend your `.eslintrc.js` config file with default rule set:

```
extends: "@mozilla-protocol/eslint-config"
```

For Node environments, extend the `index-node` rule set:

```
extends: "@mozilla-protocol/eslint-config/index-node"
```






