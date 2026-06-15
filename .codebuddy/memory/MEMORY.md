# Blog 项目记忆

## 项目概况
- 位置: `/Users/cangcang/Documents/code/Blog/`
- 类型: Material Design 3 风格博客站点
- 入口: `index.html` 跳转到 `main/index.html`
- 文章存储在 `page/` 目录 (Markdown)

## 关键约定
- 使用 MD3 设计系统，支持深色/浅色主题切换
- `.content-wrapper` 是通用布局容器（flex row），文章页用它实现正文+TOC双栏。首页用 `#homeView` 覆盖为 `flex-direction: column`
- 导航配置在 `main/config.json` 中
- 框架: 纯 HTML/CSS/JS，无构建工具
