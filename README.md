# mount-middlewares


一般在controller里会调用多个model来完成一个业务逻辑，当然也有人是按照spring的做法，抽象一个service层，无论怎样，你都希望有一个东西可以把所有models都放到一个对象上管理

默认加载app/models路径里的所有内容

为moajs设计，没有做通用路径适配，欢迎fork

## Install

    npm install --save mount-models

## Usages

```
var $models = require('mount-models');
console.log($models);
```