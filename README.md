# 千岩的AI喵能芝士店

这是一个基于 Hugo 框架的个人博客网站，主题为 AI 技术、猫咪生活和芝士美食。站点使用 Stack 主题构建，支持搜索功能。

## 特性

- 🤖 AI 技术分享
- 🐱 猫咪故事
- 🧀 芝士探索
- 🔍 全站搜索
- 📱 响应式设计
- 🌙 暗色模式

## 技术栈

- [Hugo](https://gohugo.io/) - 静态网站生成器
- [Stack Theme](https://github.com/CaiJimmy/hugo-theme-stack) - 主题
- GitHub Pages - 托管服务
- GitHub Actions - 自动部署

## 本地开发

### 前置要求

- [Hugo Extended](https://gohugo.io/installation/) (推荐使用最新版本)
- Git

### 安装步骤

1. 克隆仓库：
```bash
git clone https://github.com/qianyan-blog/qianyan-blog-hugo.git
cd qianyan-blog-hugo
```

2. 初始化子模块：
```bash
git submodule update --init --recursive
```

3. 启动本地服务器：
```bash
hugo server -D
```

4. 访问本地站点：
- 打开浏览器访问 `http://localhost:1313`（或终端显示的其他端口）

## 创建新文章

```bash
hugo new content/post/your-post-name.md
```

文章前置参数示例：
```yaml
---
title: "文章标题"
description: "文章描述"
date: 2024-02-25
image: "/img/your-image.jpg"
categories:
    - 分类名
tags:
    - 标签1
    - 标签2
---
```

## 部署

本站使用 GitHub Pages 托管，通过 GitHub Actions 自动部署。

### 部署步骤

1. 创建 GitHub 仓库：
   - `qianyan-blog.github.io`（网站托管）
   - `qianyan-blog-hugo`（源代码）

2. 推送代码：
```bash
# 添加远程仓库
git remote add origin https://github.com/qianyan-blog/qianyan-blog-hugo.git

# 提交更改
git add .
git commit -m "更新说明"
git push -u origin master
```

3. 配置 GitHub Pages：
   - 在仓库设置中启用 GitHub Pages
   - 选择 GitHub Actions 作为部署来源

推送代码后，GitHub Actions 将自动构建并部署网站。

## 贡献指南

欢迎提交 Issue 和 Pull Request！

## 许可证

本项目采用 MIT 许可证。 