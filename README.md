# 初始版

郭建华 UI/UX 作品网站的高清副本。GitHub Pages 部署，为 Sites 版本提供独立访问地址。

## 修改和预览

- `index.html`：页面内容及分享信息。
- `assets/css/style.css`：样式。
- `assets/js/stage.js`、`shaders.js`：WebGL 场景和效果。
- `assets/img/portrait-clear.webp`：高清人物图片。

无需构建。在此目录运行 `python3 -m http.server 8143 --bind 127.0.0.1` 即可预览。

## 发布

GitHub Pages 从 `main` 分支根目录发布。修改、提交并推送后，GitHub 自动更新网站。

此目录是独立副本；Sites 版本源码位于本地 `sites/chushiban/dist/`，两处发布不会自动同步。
当前页面含展示首页与作品占位区，尚未接入作品集下载和访问统计。
