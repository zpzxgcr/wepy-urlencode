urlencode [![Build Status] [![Coverage Status](https://coveralls.io/repos/node-modules/urlencode/badge.png)](https://coveralls.io/r/node-modules/urlencode)
=======

[![NPM](https://nodei.co/npm/wepy-urlencode.png?downloads=true&stars=true)](https://nodei.co/npm/wepy-urlencode/)



## Install

```bash
$ npm install wepy-urlencode -S
```

## Usage

```js
import {urlencode,urldecode} from "wepy-urlencode";
var urlencode = require('urlencode');

console.log(urlencode('你好')); // 默认 utf-8
console.log(urlencode('苏千', 'gbk')); // '%CB%D5%C7%A7'


```


## License

[MIT](LICENSE.txt)
