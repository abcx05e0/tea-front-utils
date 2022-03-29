<h1 align="center">前端常用工具函数</h1>

<p align="center">汇总常用工具函数</p>

<p align="center">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/kingfront/dip-utils" />
    <img src="https://img.shields.io/github/languages/top/kingfront/dip-utils?style=flat-square&color=green"  alt="GitHub top language" />
    <img src="https://img.shields.io/badge/dynamic/json?color=green&label=github&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3Dkingfront&style=flat-square&logo=github" />
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/kingfront/dip-utils?color=yellow">
</p>

---

## 函数概览

- 🍭 `random` 获取任意数字范围内的一位随机数
- 🍭 `getTimestamp` 时间字符串转换为时间戳

## 安装使用

### 1. 安装包使用方式

安装

```shell
# npm
npm install dip-utils -D

# yarn
yarn add dip-utils -D
```

ESM 导入使用

```js
import { random } from 'dip-utils'
console.log(random(1, 10))
```

RequireJS 导入使用

```js
const { random } = require('dip-utils')
console.log(random(1, 10))
```

### 2. 网页 script 直接引入使用方式

直接拷贝 dist 下的 dip-utils-umd.js 到项目里面，可直接引用

```html
<!DOCTYPE html>
<html lang="en">
  <body>
    <script src="/dist/dip-utils-umd.js"></script>
    <script>
      console.log(dutils.random(1, 10))
    </script>
  </body>
</html>
```
