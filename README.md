# 镜像的世界

基于 [Claude Typora Theme](https://github.com/Tsumugii24/claude-typora-theme) 排版风格构建的静态网站。

## 内容

- **镜像的世界：关于巴黎叙事中刘国梁形象的断想** — 一篇关于乒乓球领域舆论叙事的深度分析文章。

## 本地预览

直接在浏览器中打开 `docs/index.html` 即可预览。

## GitHub Pages 部署

1. 进入仓库 **Settings → Pages**
2. **Source** 选择 **Deploy from a branch**
3. **Branch** 选择 `main`，文件夹选择 `/docs`
4. 点击 **Save**
5. 网站将发布在 `https://somewhere-anywhere.github.io/mirroring-LGL/`

## 技术说明

- 使用 Pandoc 将 Markdown 转换为 HTML
- 采用 Claude Typora Theme 的排版样式
- 图片带说明文字（figcaption）
- 字体自包含，离线可用
