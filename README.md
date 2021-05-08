# vue3.0安装

## 1.安装Node.js
```
https://nodejs.org/en/
```
查看版本号：
```
node -v 
npm -v
```
**cnpm代替npm 国内直接使用 npm 的官方镜像是非常慢的，推荐使用淘宝 NPM 镜像：**
```
sudo npm install -g cnpm --registry=https://registry.npm.taobao.org
```

**安装Vue.js 的官方命令行工具：**
```
cnpm install -g vue-cli
```


# Vite (推荐)
### Vite 是一个 web 开发构建工具，由于其原生 ES 模块导入方式，可以实现闪电般的冷服务器启动。

### 通过在终端中运行以下命令，可以使用 Vite 快速构建 Vue 项目。
**1.全局安装 create-vite-app：**
```
cnpm i -g create-vite-app
```

### 创建项目 vue3-test：
```
create-vite-app vue3-test
```
### 运行项目:
```
cd vue3-test
cnpm install
cnpm run dev
```
### 效果如图：
![Image text](https://www.runoob.com/wp-content/uploads/2021/02/62FB6F27-456F-46CF-8892-93D6A3E6F341.jpg)