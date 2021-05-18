# Boilerplate for Node Packages in typescript

[![npm version](https://badge.fury.io/js/mypackage.svg)](https://www.npmjs.com/package/mypackage)
[![npm version](https://img.shields.io/npm/v/mypackage.svg)](https://www.npmjs.com/package/mypackage)
[![Build and Test Package](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/yarn.yml/badge.svg)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/yarn.yml)
[![Build and Test Package and (publish)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/publish.yml/badge.svg)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/publish.yml)
[![Code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)
[![Bundlephobia](https://badgen.net/bundlephobia/min/mypackage)](https://bundlephobia.com/result?p=mypackage)

This is a minimalist boilerplate template for Node NPM packages written in Typescript

## Get started

### Install

`yarn`

### Build

`yarn build`

### Test

`yarn test`

### CI

Continuous integration is included and works with github actions.

### Adjust Configuration

Make sure you change the path of the badge (both links and images to link to your package/repo). In `package.json` make sure you point to your github repo

## Publish

In order to publish your package, add the secret variable `NPM_AUTH_TOKEN` to the list of secret variables and release a new version

### Release a new version

```
npm version {patch,minor,major}
git push origin master --tags
```
