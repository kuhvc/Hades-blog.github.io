---
title: Hexo博客搭建指南
date: 2026-07-17 14:28:30
tags: [Hexo, 博客, 教程]
categories: [技术]
---

## 前言

本文将介绍如何使用Hexo搭建一个个人技术博客。

## 环境准备

- Node.js (推荐v18+)
- npm或yarn

## 安装Hexo

```bash
npm install -g hexo-cli
```

## 初始化博客

```bash
hexo init my-blog
cd my-blog
npm install
```

## 安装主题

这里使用Next主题：

```bash
npm install hexo-theme-next
```

## 本地运行

```bash
hexo server
```

访问 http://localhost:4000 即可预览博客。

## 部署到GitHub Pages

1. 创建GitHub仓库
2. 修改 `_config.yml` 配置部署信息
3. 执行部署命令

```bash
hexo clean && hexo deploy
```

## 总结

Hexo是一个快速、简洁的静态博客框架，非常适合技术博客。