weui.js
=====

[![npm version](https://img.shields.io/npm/v/weui.js.svg)](https://www.npmjs.org/package/weui.js/)


### 概述

[WeUI](https://github.com/Tencent/weui.git) 的轻量级 js 封装。

注意：由于微信小程序不支持dom操作，所以weui.js并不适用于小程序。不过WeUI也为小程序开发了另外的版本，详情请看：https://github.com/Tencent/weui-wxss/

### 手机预览

![qrcode](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https%3A%2F%2Fxyz71148.github.io%2Fweui.js%2Fdist%2Fexample%2Findex.html)

[预览](https://xyz71148.github.io/weui.js/dist/example/index.html)


### 开发

安装

```shell
git clone https://github.com/Tencent/weui.js.git
cd weui.js
npm install
npm start
```

编译

```shell
npm run build
```


### 使用

#### global 

```html
<link rel="stylesheet" href="https://res.wx.qq.com/open/libs/weui/2.0.1/weui.min.css">
<script type="text/javascript" src="https://res.wx.qq.com/open/libs/weuijs/1.2.1/weui.min.js"></script>
<script type="text/javascript">
    weui.alert('alert');
</script>
```

#### import as module

```javascript
import 'weui';
import weui from 'weui.js';

weui.alert('alert');
```

### 文档

[Documents](https://xyz71148.github.io/weui.js)

### 贡献

如果你有好的意见或建议，欢迎给我们提issue或pull request。

### License
The MIT License(http://opensource.org/licenses/MIT)

请自由地享受和参与开源
