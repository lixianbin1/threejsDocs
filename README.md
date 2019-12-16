three.js
========

#### three.js 离线文档及示例 ####

three.js是一个轻巧的3D库。使用默认的WebGL渲染器，还提供了Canvas 2D，SVG和CSS3D渲染器，可以在浏览器运行。

此仓库适用于只想要下载官方离线文档和示例的小伙伴。仅在示例上分了下类改了下默认语言，不会出现官网上改成中文点击其他链接又变回来的情况;
如果仅想在线观看文件和示例，我推荐前往[官网入口](https://threejs.org/)

### 用法 ###

在 thee.js 的示例中，一些功能(加载模型)需要服务器的支持。如果有本地服务器，将项目放入本地服务器，找到docs 目录下的index.html
打开即可；如果没有本地服务器，那么我编写了一个简单的nodejs脚本。仅需要node支持

```
$ node index.js

// 执行后打开浏览器访问即可
// http://localhost:8080/docs/index.html
```

### 仓库的更新时间 ###

于 2019-12-13日拉取 three.js 的 dev 分支最新 commit 。

### 为什么会有这个仓库 ###

那是某个下午，因为某种原因，想要下载官网的包，于是开着手机热点，下载了2个G也没把包下回来，100k/s的速度，下载一半就会断开连接，又不能断点重连。断了又要重新下。最后发现，下载点连着Github，而Github有最大限制，下载超过限制就会断开。我试着克隆three.js。同样也是这个原因，我试着把git缓存设置改大，但它实在是太大大了！！，我最后只能是克隆了最新的一次commit。

### Three.js 相关链接 ###

 - [three.js Github地址](https://github.com/mrdoob/three.js)
 - [three.js 官网](https://threejs.org/)
