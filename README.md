# Christmas.7

粉白冬日主题的 3D 互动圣诞树，纯前端单文件实现，可离线打开，也可部署为静态站点。

## 在线预览

https://seven-70.github.io/Christmas.7/

## 项目特性

- 粒子圣诞树、飘雪、礼物盒与雪人组成的完整冬日场景
- 粉白配色与泛光光晕
- 背景音乐 `november-25.mp3`
- 支持自定义收件人名字

## 自定义收件人

编辑 `recipient.js`，只改双引号里的名字，保存后刷新页面：

```js
window.FROSTLIGHT_RECIPIENT = "脆煞条";
```

## 本地运行与部署

把 `index.html`、`recipient.js`、`november-25.mp3` 放在同一目录，双击 `index.html` 即可打开；上传到任意静态托管（本仓库已启用 GitHub Pages）即可在线访问。
