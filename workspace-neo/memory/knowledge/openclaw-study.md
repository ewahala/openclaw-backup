# OpenClaw 文档学习笔记

## 核心概念
- **Gateway**: 单一进程，连接多个聊天渠道到AI代理
- **Channels**: WhatsApp, Telegram, Discord, iMessage等
- **Agents**: 隔离的工作空间，支持多代理

## 调研可用工具
1. **web_search** - Brave Search (默认) / Perplexity / Gemini / Grok / Kimi
2. **web_fetch** - 网页内容提取
3. **browser** - 浏览器自动化（JS heavy网站）
4. **skills** - 可安装扩展技能

## 配置
- 配置文件: `~/.openclaw/openclaw.json`
- Skills目录: `~/.openclaw/skills` (managed), `<workspace>/skills` (workspace)

## 学习计划
- [x] 基础概念
- [ ] 配置深入
- [ ] Tools深入
- [ ] 自动化工作流
- [ ] 每周检查文档更新