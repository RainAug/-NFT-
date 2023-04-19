# NFT后台管理系统

## 运行环境
```
nodejs版本：14.18.3

npm版本： 8.19.4

cnpm版本：9.0.1
```
## 安装依赖

```
#安装淘宝镜像cnpm
npm install -g cnpm -registry=https://registry.npm.taobao.org

检查cnpm安装结果： cnpm --version

进入项目根目录： cnpm 安装 cnpm i 或者 cnpm install
```
## 启动项目
```
本地启动 cnpm run dev

部署：
构建： cnpm run build
发布： 将dist包部署到服务器上
```
## 项目介绍
```
router/index.js  项目路由
.env.production  配置服务端地址
vue.config.js中 process.env.VUE_APP_BASE_API.target  配置本地启动访问服务端地址
src/api  配置后端接口

```
