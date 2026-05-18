# 个人作品集网站

> 城市规划师 → GIS 开发者 · 13 年规划经验 + 3 年开发实战

个人简历主页，展示技能、项目作品与联系方式。

## 技术栈

- **HTML5 / CSS3 / JavaScript** — 纯静态单页应用
- **Materialize 1.0.0** — UI 框架（本地化托管）
- **Typed.js** — 首页打字效果
- **Font Awesome 4.7.0** — GitHub 图标
- **GitHub Pages** — 部署托管

## 特性

- 响应式设计（桌面侧边导航 / 移动端顶部导航）
- 作品卡片悬停翻转 + 点击展开详情
- 全资源本地化，国内网络顺畅访问
- SEO / Open Graph / Favicon 完整配置

## 本地开发

```bash
# 克隆仓库
git clone https://github.com/seeking001/seeking001.github.io.git

# 使用 Live Server（VS Code 插件）启动
# 右键 index.html → Open with Live Server
```

也可直接用浏览器打开 `index.html`（部分功能需要 Live Server 支持）。

## 部署

本站部署于 GitHub Pages 仓库 `seeking001/seeking001.github.io`。推送 `main` 分支后自动发布：

```bash
git push origin main
```

访问 https://seeking001.github.io/

## 目录结构

```
├── index.html              # 主页面
├── assets/
│   ├── css/
│   │   └── style.css       # 自定义样式
│   ├── img/                # 图片资源
│   ├── vendor/             # 第三方库（本地化）
│   └── resume/             # 简历 PDF
├── REASONIX.md             # 项目记忆（Reasonix 协作用）
└── README.md
```

## 许可

MIT License
