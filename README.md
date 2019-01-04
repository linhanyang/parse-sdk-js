# Parse SDK for JavaScript

此版本基于V2.1.0做了针对小程序api接口调整，可直接编译成小程序支持的版本。

## 如何使用

```
git clone https://github.com/linhanyang/parse-sdk-js.git
cd parse-sdk-js
yarn install
```
安装完成后，会自动进行编译，将编译结果放置dist目录下。

可直接拷贝wechatapp/parse.min.js版本到小程序中使用。

## 源码修改说明

修改了以下几部分内容：

- request请求方法
- localStorage本地存储对象
- WeSocket对象

详细修改内容可参见提交记录。