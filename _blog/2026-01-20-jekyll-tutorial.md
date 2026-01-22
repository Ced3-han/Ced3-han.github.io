---
layout: blog_post
title: "Jekyll静态网站生成器入门"
date: 2026-01-20 15:30:00 +0800
category: "技术"
tags: ["Jekyll", "Web开发", "教程"]
excerpt: "本文介绍了如何使用Jekyll搭建个人网站，包括基本配置和常用功能。"
---

## Jekyll简介

Jekyll是一个简单的静态网站生成器，特别适合用于搭建个人博客和项目主页。

### 主要特点

1. **简单易用**: 使用Markdown编写内容
2. **GitHub Pages支持**: 可以免费托管在GitHub上
3. **主题丰富**: 有大量现成的主题可供选择
4. **灵活定制**: 支持Liquid模板语言

### 快速开始

```bash
# 安装Jekyll
gem install jekyll bundler

# 创建新站点
jekyll new my-site

# 进入目录并运行
cd my-site
bundle exec jekyll serve
```

### 目录结构

- `_posts/`: 博客文章目录
- `_layouts/`: 布局模板
- `_includes/`: 可复用的页面组件
- `_config.yml`: 配置文件

### 总结

Jekyll是一个强大而简洁的静态网站生成工具，非常适合技术博客和个人主页的搭建。
