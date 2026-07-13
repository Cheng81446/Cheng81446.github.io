# 🍃 Cheng · 茶与哲思

> 在代码与茶汤之间游走的行者。分享茶文化、技术思考与人生感悟。

这是一个关于茶文化、技术分享和生活思考的个人博客。

---

## 📖 这个博客是什么？

一个记录生活的地方：

- 🍵 **茶事随笔** — 品茶的感受、茶文化知识
- 💻 **技术笔记** — 编程学习、项目分享
- 🧘 **生活感悟** — 阅读笔记、人生思考

## ✨ 特点

- 🎯 **完全自主** — 内容掌握在自己手里
- 🔓 **开源透明** — 所有代码公开，可以学习借鉴
- 📱 **简洁清爽** — 少即是多，专注阅读体验
- 🌙 **深色模式** — 护眼舒适

---

## 🚀 快速开始（本地运行）

### 1. 准备环境

需要先装这些：
- Ruby 2.7+
- Jekyll 4.0+
- Bundler

### 2. 启动博客

```bash
# 下载代码
git clone https://github.com/Cheng81446/cheng81446.github.io.git
cd cheng81446.github.io

# 安装工具
bundle install

# 启动服务
bundle exec jekyll serve

# 打开浏览器，访问 http://localhost:4000
```

改动文件后会自动刷新，不需要重启。

---

## ✍️ 怎么写文章？

### 第一步：创建文件

在 `_posts/` 文件夹里创建一个 Markdown 文件，名字要这样：

```
YYYY-MM-DD-文章标题.md
```

例如：`2026-07-13-茶的故事.md`

### 第二步：写文章头部信息

每篇文章开头需要加这些信息：

```yaml
---
layout: post
title: "你的文章标题"
date: 2026-07-13
categories: 
  - 茶事隨筆
tags:
  - 茶文化
  - 品茶
---

# 文章内容从这里开始

你的内容...
```

### 文章分类

选择一个类别：

| 类别 | 说明 |
|------|------|
| 茶事隨筆 | 茶文化、品茶经历 |
| 技術筆記 | 编程、开发工具 |
| 生活感悟 | 生活哲学、读书笔记 |
| 書籍閱讀 | 书评、读后感 |

### 第三步：添加图片

把图片放在 `assets/images/` 文件夹，然后在文章里这样引用：

```markdown
![图片说明](/assets/images/图片名.png)
```

---

## 🎨 自定义你的博客

打开 `_config.yml` 文件，改这些信息：

```yaml
title: Cheng · 茶与哲思              # 网站名字
description: "用茶与代码记录生活"   # 网站描述
author: Cheng                        # 你的名字
url: "https://cheng81446.github.io"  # 网站网址
email: 你的邮箱                      # 邮箱
timezone: Asia/Shanghai              # 时区
```

---

## 📁 文件夹说明

简单来说，你只需要关心这几个：

```
📂 Cheng81446.github.io
├── 📂 _posts/          ← 写文章的地方
├── 📂 assets/
│   └── 📂 images/      ← 放图片的地方
├── _config.yml         ← 博客设置
└── README.md           ← 这个文件
```

---

## 🎯 后续计划

- [ ] 添加文章搜索功能
- [ ] 集成评论系统（Giscus）
- [ ] 增加 RSS 订阅
- [ ] 建立分类/标签归档页面
- [ ] 优化移动端阅读体验
- [ ] 添加暗色模式完整适配

---

## 🤝 有建议？

发现问题或有想法？欢迎：

- 📝 提 Issue
- 🔀 提 Pull Request  
- ⭐ Star 这个仓库支持一下

---

## 📮 联系方式

- **GitHub**: [@Cheng81446](https://github.com/Cheng81446)
- **邮箱**: cpcixora@gmail.com
- **博客**: [https://cheng81446.github.io](https://cheng81446.github.io)

---

<div align="center">

**茶不过两种姿态：浮、沉；**  
**饮茶人不过两种姿势：拿起、放下。**

✨ Built with Jekyll · Hosted on GitHub Pages ✨

</div>
