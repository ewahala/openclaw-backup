# 老黄的学习笔记

## 2026-03-04 学习记录

### OpenClaw 文档学习

#### 1. 核心概念 (index.md)
- OpenClaw 是多通道网关，连接聊天应用到AI代理
- 支持：WhatsApp, Telegram, Discord, iMessage
- 自托管，数据自主可控
- 核心组件：Gateway, Agent, CLI, Control UI, Nodes

#### 2. Skills 系统 (skills.md)
- 技能位置：bundled → ~/.openclaw/skills → workspace/skills
- 可通过 ClawHub 安装新技能
- 支持自定义技能
- 安全注意：第三方技能需要审查

#### 3. Browser 工具 (browser.md)
- 两种模式：openclaw（托管）vs chrome（扩展 relay）
- 支持 profiles：openclaw, work, remote
- 可执行：open, snapshot, screenshot, click, type, act
- 对自媒体运营很有用：抓取内容、分析竞品

#### 4. Sub-agents (subagents.md)
- 后台并行运行任务
- 有独立的 session
- 完成后会通知主会话
- 支持模型继承或自定义

### 后续学习计划

- [ ] 完成整个文档目录的学习
- [ ] 学习如何配置多代理
- [ ] 学习 cron 定时任务
- [ ] 探索更多自动化工具

### 自媒体运营方向思考

#### 2026年热门赛道发现

**平台趋势：**
1. **小红书**：2025监管升级，"水下种草"变难 → 转向IP运营、投流
2. **视频号**：闷声赚钱，私域+公域闭环模式火
3. **抖音**：重塑优质内容，影视解说赛道热门
4. **B站**：Z世代占比80%，适合年轻化内容

**变现模式：**
- 私域+公域闭环：视频号+公众号+社群
- 知识付费、产品带货、定制服务
- 矩阵号运营：小红书矩阵号可单季度变现1000万+

**热门赛道：**
- 小说拉新（抖音故事会、知乎、番茄）
- 影视解说（需注意侵权规避）
- 美妆个护、家居、宠物（年轻人方向）
- AI搜索营销

**下一步行动：**
- [ ] 深入研究视频号+私域模式
- [ ] 分析小红书矩阵号案例
- [ ] 探索AI内容生产工具