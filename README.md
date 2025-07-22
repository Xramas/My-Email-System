<!-- markdownlint-disable-file MD033 MD045 -->

# 🚀 Cloudflare 临时邮箱 - 免费搭建临时邮件服务

<p align="center">
  <a href="https://temp-mail-docs.awsl.uk" target="_blank">
    <img alt="docs" src="https://img.shields.io/badge/docs-grey?logo=vitepress">
  </a>
  <a href="https://github.com/Xramas/My-Email-System/releases/latest" target="_blank">
    <img src="https://img.shields.io/github/v/release/Xramas/My-Email-System">
  </a>
  <a href="https://github.com/Xramas/My-Email-System/blob/main/LICENSE" target="_blank">
    <img alt="MIT License" src="https://img.shields.io/github/license/Xramas/My-Email-System">
  </a>
  <a href="https://github.com/Xramas/My-Email-System/graphs/contributors" target="_blank">
    <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Xramas/My-Email-System">
  </a>
  <a href="https://github.com/Xramas/My-Email-System">
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Xramas/My-Email-System">
  </a>
  <a href="https://github.com/Xramas/My-Email-System">
    <img src="https://img.shields.io/github/last-commit/Xramas/My-Email-System">
  </a>
</p>

<p align="center">
  <a href="README.md">🇨🇳 中文文档</a> |
  <a href="README_EN.md">🇺🇸 English Document</a>
</p>

> 本项目仅供学习和个人用途，请勿将其用于任何违法行为，否则后果自负。

## 🎉 功能完整的临时邮箱服务

- 🆓 **完全免费** - 基于 Cloudflare 免费服务构建，零成本运行
- ⚡ **高性能** - Rust WASM 邮件解析，响应速度极快
- 🎨 **现代化界面** - 响应式设计，支持多语言，操作简便

## 📚 部署文档 - 快速开始

[📖 部署文档](https://temp-mail-docs.awsl.uk) | [🚀 Github Action 部署文档](https://temp-mail-docs.awsl.uk/zh/guide/actions/github-action.html)

<a href="https://temp-mail-docs.awsl.uk/zh/guide/actions/github-action.html">
  <img src="https://deploy.workers.cloudflare.com/button" alt="Deploy to Cloudflare Workers" height="32">
</a>

## 📝 更新日志

查看 [CHANGELOG](CHANGELOG.md) 了解最新更新内容。

## 🎯 在线体验

立即体验 → [https://mail.awsl.uk/](https://mail.awsl.uk/)

## 🏗️ 技术架构

<details>
<summary>点击展开技术架构详情</summary>

### 🏛️ 系统架构

- **数据库**: Cloudflare D1
- **前端部署**: Cloudflare Pages
- **后端部署**: Cloudflare Workers
- **邮件转发**: Cloudflare Email Routing

### 🛠️ 技术栈

- **前端**: Vue 3 + Vite + TypeScript
- **后端**: TypeScript + Cloudflare Workers
- **邮件解析**: Rust WASM (mail-parser-wasm)
- **数据库**: Cloudflare D1 (SQLite)
- **存储**: Cloudflare KV + R2 (可选 S3)
- **代理服务**: Python SMTP/IMAP Proxy Server

### 📦 主要组件

- **Worker**: 核心后端服务
- **Frontend**: Vue 3 用户界面
- **Mail Parser WASM**: Rust 邮件解析模块
- **SMTP Proxy Server**: Python 邮件代理服务
- **Pages Functions**: Cloudflare Pages 中间件
- **Documentation**: VitePress 文档站点

</details>

## 📄 License

本项目采用 [MIT License](https://github.com/Xramas/My-Email-System/blob/main/LICENSE)。

## 🤝 Contributing

欢迎通过 PR 和 Issues 贡献功能或反馈问题。
