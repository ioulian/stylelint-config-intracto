# stylelint-config-intracto

## Introduction

This repository contains sample linting configs for, .scss files. Currently they are all based on recommended configs and prettier.

## How to use

### Installing

To install this repo, run:

```bash
yarn global add install-peerdeps
install-peerdeps --dev "@yulian.alexeyev/stylelint-config-intracto"
```

And then create a file `.stylelintrc.json`. Add this config if your codebase is based on SCSS:

```json
{
  "extends": ["@yulian.alexeyev/stylelint-config-intracto/scss"]
}
```
