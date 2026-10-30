---
title: "第一篇：把博客重新搭起来"
description: "为什么要有一个自己的地方，以及这个站点是怎么搭起来的。"
date: "2026-10-30"
draft: false
sticky: false
tags: ["随笔", "Astro"]
categories: ["建站"]
series: []
comments: false
sidebar:
  enable: true
  toc: true
  relatedPosts: true
---

# 第一篇：把博客重新搭起来

社交平台上的东西越来越碎，也越来越容易被淹没。于是想给自己留一个安静的地方：不用追热点，不用想措辞，写完就放着。

## 这个站点

- **框架**：Astro，输出纯静态文件，默认几乎不带 JS。
- **主题**：Navfolio，一个偏"安静的开发者笔记本"的起始模板。
- **内容**：Markdown / MDX，写进 `src/content/blog/` 就是一篇新文章。
- **搜索**：Pagefind 在构建时生成索引，支持 `Ctrl+K` 唤起。
- **部署**：GitHub Pages，推送到仓库就自动构建发布。

## 接下来想做的事

1. 把以前散落在各处的笔记整理过来；
2. 给项目和简短记录也留出位置；
3. 保持克制，不为了更新而更新。

如果你也想搭一个类似的地方，模板在这里：<https://github.com/dodolalorc/astro-navfolio>。

```bash
# 本地写作时需要一条命令
bun run dev
```
