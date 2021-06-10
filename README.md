# skeleton

首次渲染的骨架屏, 通常可以直接在 index.html 直接写, 但是为了便于维护写成 .vue 组件

> 思路就是利用 ssr 技术, 将静态骨架页面塞进 html

1. 生成 skeleton.json 文件

```bash
$webpack --config webpack.skeleton.conf.js
```

2. 生成 index.html

```bash
$node skeleton.js
```
