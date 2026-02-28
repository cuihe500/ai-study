# AI Study - AI编程入门指南

一本面向 AI 初学者的编程入门书籍，基于 [Docusaurus](https://docusaurus.io/) 构建。

## 项目简介

本书旨在帮助 AI 初学者和开发者掌握 AI 辅助编程的技能，从工具使用到原理理解，从基础技能到实战项目，循序渐进地引导读者进入 AI 编程的世界。

### 目标读者

- AI 初学者
- 想用 AI 辅助编程的开发者
- 对 AI Agent 感兴趣的技术爱好者

### 核心内容

- **入门基础**：AI 编程工具介绍与基础技能
- **原理理解**：LLM、Token、上下文窗口等核心概念
- **开发实战**：前端、后端开发与项目实战
- **Agent 专题**：AI Agent 概念、多智能体协作、MCP 协议
- **最佳实践**：高效提示词模式、迭代开发流程

## 快速开始

### 环境要求

- Node.js >= 20.0
- npm

### 安装依赖

```bash
npm install
```

### 本地开发

```bash
npm start
```

启动本地开发服务器，访问 http://localhost:3000 查看网站。

### 构建部署

```bash
# 构建静态网站
npm run build

# 本地预览构建结果
npm run serve
```

## 项目结构

```
.
├── docs/                    # 书籍内容目录
│   ├── DESIGN.md           # 设计文档（目录结构与编写指南）
│   ├── intro.md            # 前言
│   ├── chapter-01/         # 第一章：AI与编程的初次相遇
│   ├── chapter-02/         # 第二章：AI编码工具详解
│   └── ...                 # 更多章节
├── src/                    # 自定义组件和样式
│   ├── components/         # React 组件
│   ├── css/                # 自定义样式
│   └── pages/              # 自定义页面
├── static/                 # 静态资源
├── docusaurus.config.ts    # Docusaurus 配置
├── sidebars.ts             # 侧边栏配置
└── CLAUDE.md               # Claude Code 项目指南
```

## 技术栈

- [Docusaurus 3.9.2](https://docusaurus.io/) - 静态网站生成器
- [React 19](https://react.dev/) - UI 框架
- [TypeScript](https://www.typescriptlang.org/) - 类型安全
- [Mermaid](https://mermaid.js.org/) - 图表支持

## 文档编写

书籍内容位于 `docs/` 目录，采用 Markdown 格式编写。在编写前请先阅读 `docs/DESIGN.md` 了解整体结构和编写指南。

新建章节时，可在对应目录下创建 `.md` 文件，并按需添加 `_category_.json` 定义分类信息。

## 许可证

Copyright © 2026 崔昌赫 & 鹿一萍 With ❤️