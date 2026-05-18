- # 项目记忆

  ## 项目信息
  - 纯静态个人简历网站
  - 城市规划师（13年工作经验）转行 GIS 开发

  ## 技术栈
  - HTML5 / CSS3 / JavaScript
  - Materialize 1.0.0（CSS + JS，本地化于 assets/vendor/materialize/）
  - Material Icons（本地化于 assets/vendor/materialize/MaterialIcons-Regular.ttf）
  - Font Awesome 4.7.0（仅保留用于 GitHub 图标，本地化于 assets/vendor/font-awesome/）
  - Typed.js（首页打字效果，本地化于 assets/vendor/typed.js/）
  - 部署于 GitHub Pages：seeking001.github.io
  - 本地开发：VS Code + Live Server

  ## 文件结构
  - index.html — 主页面（单页，多 section）
  - assets/css/style.css — 所有自定义样式（按模块分组，中文注释）
  - assets/vendor/ — 第三方库
  - assets/img/ — 图片资源

  ## 关键约束
  - 优先使用 Materialize 原生类和组件，不写冗余 CSS
  - 不使用 !important，不使用暴力模式覆盖（特殊情况除外）
  - 资源本地化（适应国内网络和随时随地顺畅打开）