# 🍃 Cheng · 茶与哲思

> 在代码与茶汤之间游走的行者。分享茶文化、技术思考与人生感悟。

欢迎来到我的个人博客！这是一个用 **Jekyll + GitHub Pages** 搭建的独立写作空间，记录我对中国茶文化、技术实践和生活哲学的思考。

## ✨ 关于这个博客

### 初心
茶教会我**"静"**——静观叶展，静听水沸，静待回甘。  
编程也需要这份静思——深度思考代码的逻辑、系统的设计、技术的本质。

这个博客就是这两个世界的交汇点：
- 📝 **茶事随笔**：品茶过程中的感悟与茶文化知识
- 💻 **技术笔记**：编程学习、项目总结、工具分享
- 🧘 **生活感悟**：阅读反思、人生思考、审美记录

### 特色
- ✅ 完全自主：不依赖第三方平台，掌控自己的内容
- ✅ 开源透明：所有源码开放，欢迎学习和借鉴
- ✅ 简洁专注：极简设计，避免视觉噪音和信息过载
- ✅ 深色模式：护眼且优雅的阅读体验

## 🚀 快速开始

### 前置要求
- Ruby 2.7+
- Jekyll 4.0+
- Bundler

### 本地运行

```bash
# 1. 克隆仓库
git clone https://github.com/Cheng81446/cheng81446.github.io.git
cd cheng81446.github.io

# 2. 安装依赖
bundle install

# 3. 启动本地服务器
bundle exec jekyll serve

# 4. 在浏览器打开
open http://127.0.0.1:4000
```

服务器默认监听 `http://localhost:4000`，文件改动会自动刷新。

## 📁 项目结构

```
.
├── _config.yml           # Jekyll 配置文件（站点标题、描述、主题等）
├── _layouts/             # 页面布局模板
│   ├── default.html      # 默认布局
│   └── post.html         # 文章布局
├── _posts/               # 博客文章存放处（Markdown 格式）
├── assets/               # 静态资源（图片、样式、脚本）
│   └── images/           # 文章配图目录
├── index.html            # 主页（个人卡片和快捷链接）
├── about.md              # 关于我页面（可选）
├── Gemfile               # Ruby 依赖配置
└── README.md             # 本文件
```

## ✍️ 撰写文章

### 创建新文章

在 `_posts/` 目录下创建 Markdown 文件，文件名格式为：
```
YYYY-MM-DD-title.md
```

例如：`2026-07-13-tea-meditation.md`

### 文章Front Matter模板

```yaml
---
layout: post
title: "文章标题"
date: 2026-07-13
categories: 
  - 茶事隨筆
tags:
  - 茶文化
  - 品茶
description: "文章摘要或简短描述"
---

# 文章内容开始

你的 Markdown 内容...
```

### 文章分类
- 🍃 **茶事隨筆**：茶文化、品茶体验、茶器具
- 💡 **技術筆記**：编程、开发工具、技术深度思考
- 🌟 **生活感悟**：生活哲学、阅读笔记、审美思考
- 📚 **書籍閱讀**：读书笔记、书评推荐

### 添加图片

将图片放在 `assets/images/` 目录，然后在文章中引用：
```markdown
![图片描述](/assets/images/your-image.png)
```

## 🎨 自定义配置

编辑 `_config.yml` 修改：

```yaml
title: Cheng · 茶与哲思          # 网站标题
description: "用茶与代码记录生活" # 网站描述
author: Cheng                     # 作者名称
url: "https://cheng81446.github.io" # 网站 URL
email: cpcixora@gmail.com         # 联系邮箱
timezone: Asia/Shanghai           # 时区
```

## 🎯 后续计划

- [ ] 添加文章搜索功能
- [ ] 集成评论系统（Giscus）
- [ ] 增加 RSS 订阅
- [ ] 建立分类/标签归档页面
- [ ] 优化移动端阅读体验
- [ ] 添加暗色模式完整适配

## 📊 技术栈

| 组件 | 选择 |
|------|------|
| **静态生成器** | Jekyll 4.3 |
| **托管平台** | GitHub Pages |
| **主题** | Minima (自定义) |
| **样式** | 原生 CSS3 |
| **脚本** | 原生 JavaScript |
| **Markdown** | kramdown |
| **代码高亮** | Rouge |

## 🤝 如何贡献

如果你发现 Bug 或有优化建议，欢迎提 Issue 或 Pull Request！

虽然这是我的个人博客，但如果内容对你有帮助，可以：
- ⭐ Star 这个仓库
- 💬 在 Issue 中留言交流
- 🔗 分享给需要的人

## 📖 学习资源

- [Jekyll 官方文档](https://jekyllrb.com/)
- [GitHub Pages 指南](https://pages.github.com/)
- [Markdown 语法](https://www.markdownguide.org/)
- [kramdown 文档](https://kramdown.getgems.org/)

## 📮 联系我

- 🐙 **GitHub**: [@Cheng81446](https://github.com/Cheng81446)
- ✉️ **邮箱**: cpcixora@gmail.com
- 🌐 **博客**: [https://cheng81446.github.io](https://cheng81446.github.io)

## 📄 许可证

MIT License - 随意使用和修改，但请保留原作者署名。

---

<div align="center">

**茶不过两种姿态：浮、沉；**  
**饮茶人不过两种姿势：拿起、放下。**

✨ Built with Jekyll · Hosted on GitHub Pages ✨

</div>
