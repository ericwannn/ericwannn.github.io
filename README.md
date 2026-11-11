# Observation Point

A glimpse at the edge — https://ericwannn.github.io

个人博客，基于 [Jekyll](https://jekyllrb.com/) + [NexT 主题](https://github.com/Simpleyyt/jekyll-theme-next)。

## 本地预览

```bash
bundle install
bundle exec jekyll serve
```

## 写文章

在 `_posts/` 下新建 `YYYY-MM-DD-slug.md`，开头写 front matter：

```yaml
---
layout: post
title: "标题"
date: 2026-01-01 00:00:00 +0800
categories: Programming
tags: python, notes
---
```

推送到 `master` 后由 GitHub Pages 自动构建。

## 站点配置

站点标题、作者、社交链接、统计/评论开关都在 `_config.yml`。
