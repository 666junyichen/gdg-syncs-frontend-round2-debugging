# GDG SYNCS Frontend Round 2 - Debugging Challenge

## 中文简介

这是 GDG SYNCS 前端挑战赛 Round 2 的调试项目。比赛目标是在不重写应用、不改变既有视觉设计的前提下，基于提供的代码仓库修复前端缺陷，并恢复老师端与学生端的核心流程。

本仓库保留了调试后的前端代码、部署配置与公开说明文件，适合直接导入 Vercel 进行部署。

## English Overview

This repository contains a submission for **Round 2 of the GDG SYNCS frontend challenge**, which focused on front-end debugging. The goal was to repair defects in the provided codebase without rebuilding the application or changing its existing visual design.

The repository includes the repaired front-end files, deployment configuration, and supporting public-facing documentation for GitHub presentation and Vercel deployment.

## 中文修复重点

- 登录入口与角色流转
- 老师端任务分配流程
- 学生端任务查看与提交流程
- Settings 页面中的资料更新与数据操作
- 本地存储键值与跨页面状态同步
- 日期输入格式统一与部署入口稳定性

## Repair Highlights

- Login entry flow and role-based routing
- Teacher task assignment workflow
- Student task viewing and submission flow
- Settings page profile and data actions
- Local storage consistency across screens
- Date input normalization and deployment entry handling

## 技术栈 / Tech Stack

- HTML
- CSS
- JavaScript
- GitHub
- Vercel

## 仓库结构 / Repository Structure

```text
.
├── index.html
├── login.html
├── teacher-dashboard.html
├── student-dashboard.html
├── tasks.html
├── settings.html
├── css/
├── js/
├── vercel.json
├── 项目说明.md
└── docs/
    ├── highlights.md
    └── 交付说明.md
```

## 本地预览 / Local Preview

```bash
python -m http.server 4173
```

Open:

```text
http://127.0.0.1:4173/login.html
```

## 部署说明 / Deployment

This repository is intended for Vercel deployment. The deployed entry experience should begin from the login flow.