---
title: 用 Hexo + Fluid 搭建免费个人博客
date: 2026-08-14 20:40:00
tags:
  - Hexo
  - 博客搭建
  - 教程
categories:
  - 技术
---

# 用 Hexo + Fluid 搭建免费个人博客

本文记录我的博客搭建过程，全程免费，无需购买服务器。

## 技术栈

| 组件 | 说明 |
|---|---|
| [Hexo](https://hexo.io) | 快速、简洁且高效的静态博客框架 |
| [Fluid](https://hexo.fluid-dev.com/) | 一款 Material Design 风格的 Hexo 主题 |
| [GitHub Pages](https://pages.github.com/) | 免费的静态网站托管 |

## 搭建步骤

### 1. 安装 Hexo

```bash
npm install -g hexo-cli
```

### 2. 初始化博客

```bash
hexo init my-blog
cd my-blog
npm install
```

### 3. 安装 Fluid 主题

```bash
npm install hexo-theme-fluid
```

然后在站点根目录的 `_config.yml` 中设置：

```yaml
theme: fluid
```

### 4. 写文章

```bash
hexo new post "我的第一篇博客"
```

### 5. 本地预览

```bash
hexo server
```

浏览器打开 `http://localhost:4000` 即可预览。

### 6. 部署到 GitHub Pages

使用 GitHub Actions 自动部署，推送到 `main` 分支即可自动构建发布。

## 小结

整个搭建过程不到 10 分钟，而且完全免费。后续我会继续分享更多博客优化的技巧，敬请期待！
