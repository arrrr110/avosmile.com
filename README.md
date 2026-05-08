# Leesmum 网站首页克隆项目

一个基于静态 HTML/CSS 构建的企业网站首页，复制自 `https://leesmum.com/cn`。

## 项目概述

本项目是乐世买（Leesmum）官方网站中文首页的静态克隆版本，展示了公司的产品系列、新闻资讯和联系方式。

## 功能特点

- **响应式设计**：完美适配桌面端和移动端设备
- **现代UI设计**：采用渐变色彩和卡片式布局
- **平滑导航**：支持页面内锚点跳转
- **交互效果**：悬停动画和过渡效果

## 页面结构

```
├── 导航栏        - 首页、关于我们、产品、新闻与信息、联系我们
├── Hero区域      - 主标题和公司简介
├── 关于我们      - 公司使命和服务介绍
├── 产品展示      - 藏红花系列、有机蘑菇系列、超级食品系列
├── 新闻资讯      - 6篇新闻文章卡片
├── 联系我们      - 电话、电子邮件、地址信息
└── 页脚          - 网站链接和备案信息
```

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 样式设计（Grid、Flexbox、动画）
- **SVG** - 图标资源

## 快速开始

### 本地开发

```bash
# 安装依赖
npm install -g http-server

# 启动开发服务器
http-server -p 8080

# 访问地址
http://localhost:8080
```

### 部署方式

**腾讯云 CloudBase**（推荐）：

```bash
# 安装 CloudBase CLI
npm install -g @cloudbase/cli

# 登录
tcb login

# 部署
tcb hosting deploy index.html --env-id <your-env-id>
```

**Vercel**：

```bash
# 安装 Vercel CLI
npm install -g vercel

# 部署
vercel --prod
```

## 部署地址

- **腾讯云 CloudBase**: https://cloud1-1gfyi6az06806a08-1353760793.tcloudbaseapp.com

## 许可证

MIT License

## 说明

本项目仅用于学习和展示目的，版权归原网站所有。