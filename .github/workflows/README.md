# Boilerplate for Node Packages in typescript

[![Build and Test Package](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/yarn.yml/badge.svg)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/yarn.yml)
[![Build and Test Package and (publish)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/publish.yml/badge.svg)](https://github.com/Nexysweb/boilerplate-node-package/actions/workflows/publish.yml)

This is a minimalist boilerplate templates for Node NPM packages written in Typescript

## Get started

### Install

`yarn`

### Build

`yarn build`

### Test

`yarn test`

### CI

Continuous integration is included and works with github actions.

## Publish

In order to publish your package, add the secret variable `NPM_AUTH_TOKEN` to the list of secret variables and release a new version

### Release a new version

```
npm version {patch,minor,major}
git push origin master --tags
```
