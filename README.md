# 吕佳霖 · 个人主页

静态个人主页，使用纯 HTML + CSS 手写，无框架、无构建步骤。用于集中展示我的教育背景、项目经历、科研与求职方向。

## 技术说明
- 单页静态站点：`index.html` + `style.css`，零运行时依赖。
- 响应式布局，适配桌面端与移动端。
- 字体来自 Google Fonts（Inter / Space Grotesk / Noto Sans SC）。
- 部署方式：GitHub Pages（main 分支根目录）。

## 本地预览
直接用浏览器打开 `index.html` 即可；或起一个本地静态服务器：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 目录结构
- `index.html` — 页面结构与内容
- `style.css` — 样式
- `assets/CV.pdf` — 简历 PDF
- `assets/avatar.jpg` — 头像照片

## 内容维护
页面内容（教育、项目、技能等）直接在 `index.html` 中编辑；视觉样式集中在 `style.css` 顶部的 CSS 变量（`--bg` / `--text` / `--accent` 等），改色或改字体只需调整这几个变量。
