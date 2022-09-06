# 本项目为使用TypeScript重构的一个axios库（2022年9月6日20:18:43）

<br/>

# 需求分析 

## Features（特性）

- 在浏览器端使用XMLHttpRequest对象通讯
- 支持Promise API
- 支持请求和响应的拦截器
- 支持请求数据和响应数据的转换
- 支持请求的取消
- JSON数据的自动转换
- 客户端防止XSRF（跨站伪造请求）

注：本项目未涉及axios在Node中的实现。

<br/>

# 初始化项目

## TypeScript library starter

一个开源的TypeScript开发基础库的脚手架工具，能够帮助开发者快速初始化一个TypeScript项目。

### 使用方式

```javascript
git clone https://github.com/alexjoverm/typescript-library-starter.git ts-axios
cd ts-axios

npm install
```
