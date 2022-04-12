# React NPM Package Starter

> React npm package starter with typescript and rollup.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/schemesonic/react-npm-starter/graphs/commit-activity)
[![NPM](https://img.shields.io/npm/v/@paraboly/react-apexcharts-dynamic-config.svg)](https://www.npmjs.com/package/@schemesonic/react-npm-starter)
[![Netlify Status](https://api.netlify.com/api/v1/badges/ed06153b-5f15-4305-b897-22ed648b95ae/deploy-status)](https://app.netlify.com/sites/react-npm-starter/deploys)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

---

## Demo

| Example 1                                          |                     Example 2                      |                     Example 3                      |
| -------------------------------------------------- | :------------------------------------------------: | :------------------------------------------------: |
| ![Example UI 1](https://picsum.photos/id/1002/200) | ![Example UI 2](https://picsum.photos/id/1003/200) | ![Example UI 3](https://picsum.photos/id/1024/200) |

> https://react-apexcharts-dynamic-config.netlify.app

---

## Install

```bash
npm install --save @paraboly/react-apexcharts-dynamic-config
```

---

## Usage

```tsx
import React from 'react';
import ReactNpmStarter from '@schemesonic/react-npm-starter';

const example = (): JSX.Element => {
  const options = { someProps: [] };

  return <ReactNpmStarter prop={options} onChange={opt => console.log(opt)} />;
};

export default example;
```

## Details

| Props    |        Definition         |                         Type | Default | Required |
| -------- | :-----------------------: | ---------------------------: | ------: | -------: |
| prop     |       Example prop        |                       `Prop` |    null |     true |
| onChange | Example callback function | `(updatedOpt: Prop) => void` |    null |     true |

---

## Licence

[MIT](./LICENSE) License © [SchemeSonic](https://github.com/jaredpalmer/tsdx)

This starter is derived from [tsdx](https://github.com/jaredpalmer/tsdx)

> For more information about starter please check https://tsdx.io/
