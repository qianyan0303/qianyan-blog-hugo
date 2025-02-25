# 千岩的AI喵能芝士店 🤖🐱🧀

> 芝士就是力量！这里不仅有浓浓的芝士香，更有满满的技术知识！

这是一个充满"芝士"的技术博客，在这里，知识就像芝士一样浓郁醇厚、层次丰富。我们将 AI 技术、猫咪生活和芝士美食完美融合，用轻松愉快的方式分享技术知识。本站基于 Hugo 框架构建，采用 Stack 主题，支持全站搜索功能。

## ✨ 特色芝士

- 🤖 **AI技术芝士**：深入浅出的人工智能技术解析
- 🐱 **喵星人芝士**：与猫咪相处的点点滴滴
- 🧀 **美食芝士**：探索美食与技术的完美邂逅
- 🔍 **搜索芝士**：强大的全站搜索功能
- 📱 **响应式芝士**：完美适配各种设备
- 🌙 **暗黑芝士**：护眼的暗色模式

## 🛠️ 技术芝士

- 🏗️ [Hugo](https://gohugo.io/) - 高效的静态网站生成器
- 🎨 [Stack Theme](https://github.com/CaiJimmy/hugo-theme-stack) - 优雅的主题模板
- 🚀 GitHub Pages - 可靠的托管服务
- ⚡ GitHub Actions - 自动化部署工具

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

## 📝 创建新芝士

```bash
hugo new content/post/your-post-name.md
```

芝士配方（文章前置参数）示例：
```yaml
---
title: "你的芝士标题"
description: "芝士描述"
date: 2024-02-25
image: "/img/your-image.jpg"
categories:
    - 技术芝士
tags:
    - AI芝士
    - 猫咪芝士
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

## 🤝 芝士贡献

欢迎投稿你的芝士！无论是技术分享、猫咪故事还是美食探索，我们都非常期待。请随时提交 Issue 和 Pull Request！

## 📜 芝士许可

本项目采用 MIT 许可证。请尽情享用这些美味的芝士！ 