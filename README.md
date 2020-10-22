# three.js 离线文档及示例

three.js是一个轻巧的3D库。使用默认的WebGL渲染器，还提供了Canvas 2D，SVG和CSS3D渲染器，可以在浏览器运行。

此仓库适合想要下载官方离线文档和示例的小伙伴。当然也可以 [在线浏览](https://lixianbin1.github.io/threejsDocs/docs/index.html)目前仅在示例上分了下类改了下默认语言，不会出现官网上改成中文点击其他链接又变回来的情况;
当然也可以前往[官网入口](https://threejs.org/)

在线观看 https://lixianbin1.github.io/threejsDocs/docs/index.html#manual/zh/introduction/Creating-a-scene

<img style="vertical-align: top;" src="https://github.com/lixianbin1/threejsDocs/blob/master/build/2009241.png" alt="预览" >

<img style="vertical-align: top;" src="https://github.com/lixianbin1/threejsDocs/blob/master/build/2009242.png" alt="预览" >

## 用法

在 thee.js 的示例中，一些功能(加载模型)需要服务器的支持。如果有本地服务器，将项目放入本地服务器，找到docs 目录下的index.html
打开即可；如果没有本地服务器，那么我编写了一个简单的nodejs脚本。仅需要node支持

```
$ node index.js

// 执行后打开浏览器访问即可
// http://localhost:8080/docs/index.html
```

## 计划

汉化b部分未汉化的菜单；在官网中，部分菜单并未汉化，可能是考虑到汉化与原意有差别。但我还是希望能看到菜单有进行了汉化。如果对原意有歧义，可以切换到英文版进行查看。

```
### 如何编辑文档的菜单翻译

# threejsDocs\docs\list.js   
# 此为文档的菜单列表，你可以根据自己的理解修改其中的顺序和文本

"灯光": {
    "环境光 AmbientLight": "api/zh/lights/AmbientLight",
    "平行光 DirectionalLight": "api/zh/lights/DirectionalLight",
    "半球光 HemisphereLight": "api/zh/lights/HemisphereLight",
    ...
},
```

```
# threejsDocs\examples\files.js
# 此为演示菜单列表，你可以根据自己的理解修改其中的顺序和文本

"动画": [
    "webgl_animation_cloth",
    "webgl_animation_keyframes",
    "webgl_animation_skinning_blending",
    "webgl_animation_skinning_morph",
    "webgl_animation_multiple",
],
```

### 仓库的更新时间

于 2019-12-13日拉取 three.js 的 dev 分支最新 commit 。

## 为什么会有这个仓库

那是某个下午，因为某种原因，想要下载官网的包，于是开着手机热点，下载了2个G也没把包下回来，100k/s的速度，下载一半就会断开连接，又不能断点重连。断了又要重新下。最后发现，下载点连着Github，而Github有最大限制，下载超过限制就会断开。我试着克隆three.js。同样也是这个原因，我试着把git缓存设置改大，但它实在是太大大了！！，我最后只能是克隆了最新的一次commit。

### 1：官网访问太慢了

因为THREE.JS 的3d素材都很大，导致加载过慢，访问起来会很卡顿，而且国内对部分网站的不友好，所以不如下载到本地访问，访问可以更加快速，便捷

### 2：官网的中文链接没做好

官网的菜单没有汉化，找起来还是很麻烦，而且有的时候已经选择了中文，还是会转跳到英文界面
还不如直接自己编辑页面，方便

## Three.js 相关链接

 - [three.js Github地址](https://github.com/mrdoob/three.js)
 - [three.js 官网](https://threejs.org/)
