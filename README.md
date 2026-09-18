# StayStereo 支持网站

StayStereo 的公开支持与隐私政策网站，使用纯静态 HTML 和 CSS，通过 GitHub Pages 发布。

- [中文支持](https://the-eric-kwok.github.io/staystereo-support/)
- [English Support](https://the-eric-kwok.github.io/staystereo-support/en/)
- [隐私政策](https://the-eric-kwok.github.io/staystereo-support/privacy.html)
- [Privacy Policy](https://the-eric-kwok.github.io/staystereo-support/en/privacy.html)
- [问题反馈 / Issues](https://github.com/the-eric-kwok/staystereo-support/issues)

## 维护

中文页面位于 `index.html` 和 `privacy.html`，英文页面位于 `en/`，共享样式位于 `assets/style.css`。修改文案时同步两种语言。隐私政策发生实质变化时同步更新日期。

在仓库的 Settings → Pages 中选择 Deploy from a branch、`main` 分支和根目录 `/`。推送后自动部署，无需安装依赖或运行构建。

本地预览：在此目录运行 `python3 -m http.server 8000`，访问 `http://localhost:8000`。
