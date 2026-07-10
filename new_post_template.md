# 新文章模板 / New Post Template

将此文件复制为 _posts/YYYY-MM-DD-your-title.md 然后编辑内容并提交到 main 分支。下面是可直接复制的最小模板：

---
title: "你的文章标题"
date: 2026-07-10 10:00:00 +0800
layout: post
categories: [随笔]
tags: [茶]
---

第一段：这是文章的开头。用 Markdown 写作���段落、列表、代码块、图片等。

<!--more-->

继续写正文：详细内容放在这里。

图片示例：

![描述](/assets/images/your-image.jpg)

说明：
- 文件名格式必须为 _posts/YYYY-MM-DD-your-title.md（例如：_posts/2026-07-11-cup-of-tea.md）。
- date 字段可用你想显示的时间，Jekyll 会以 front matter 的 date 为准。
- layout: post 会使用仓库中的 _layouts/post.html 渲染。
- 如果只想先保存但不发布，可以把文件放到 _drafts/ 目录（无日期前缀）。

快速在 GitHub 网页上发布：
1. 进入仓库 → Add file → Create new file。
2. 在文件名处输入 `_posts/YYYY-MM-DD-your-title.md`。
3. 粘贴模板内容并替换标题/日期/正文。
4. Commit 到 main。

祝写作愉快！如果你要我把此模板复制为实际的新文件（我已创建），或想我同时创建 assets/images/ 目录示例，都告诉我。