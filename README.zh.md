# Snowybot

[English](./README.md)

一个桌面 AI 伙伴应用。你可以创建拥有独立性格、记忆和时间感的 AI persona，和它们聊天、相处。

基于 [OpenClaw](https://github.com/nicepkg/openclaw) 系统构建。每个 persona 通过结构化的身份文档（SOUL.md、IDENTITY.md、USER.md）来定义，确保角色性格的一致性和深度可定制性。

> **早期预览版 (v0.0.0)** — 非常早期的版本，可能会有不少粗糙的地方。

---

## 功能

**Persona 系统**

创建和管理 AI persona，自定义名字、头像、背景图和背景音乐。每个 persona 通过 OpenClaw 的身份文档系统维持自己的性格，让对话始终保持角色一致性。

**对话**

支持多会话对话和流式响应。Persona 在聊天过程中可以使用工具，并在不同会话间保持上下文。

**记忆**

每个 persona 拥有按主题分类的持久记忆。它们会记住你们聊过的内容，并在之后的对话中自然地回忆起来。你也可以直接查看和编辑记忆内容。

**心跳系统** *(开发中)*

Persona 将能够主动联系你——早安问候、里程碑庆祝、节日祝福，以及偶尔回忆过去的对话。让你的 AI 伙伴更有生命感。

**Agent 对话匹配** *(开发中)*

你的 persona 将能够通过 [Agenmii](https://agenmii.com)（我们的 agent 对话平台）与其他 Snowybot 用户的 persona 进行实时匹配和对话。

---

## 下载

前往 [Releases](https://github.com/2deng-bowen/snowybot-releases/releases) 页面下载最新安装包。

目前仅支持 **Windows**。

---

## 技术栈

- **桌面端**: Electron + React + Vite
- **AI 引擎**: OpenClaw（Node.js gateway，多 LLM 提供商支持）
- **样式**: Sass + 自定义暗色主题

---

## 项目状态

项目正在积极开发中。核心的对话和 persona 功能已经可用，但很多计划中的功能还在构建。可能会有 bug。

遇到问题欢迎在这个 repo 提 issue。

---

## 许可

保留所有权利。本软件仅供个人使用。
