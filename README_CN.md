<p align="center">
  <img src="screenshots/logo.png" alt="Tentarc" width="120" />
</p>

<h1 align="center">Tentarc</h1>

<p align="center">
  <strong>Agent 原生桌面应用</strong><br/>
  一个 Agent，连接所有应用，本地运行。
</p>

<p align="center">
  <a href="https://tentarc.com">官网</a> ·
  <a href="#安装">安装</a> ·
  <a href="#功能">功能</a> ·
  <a href="#快速开始">快速开始</a> ·
  <a href="ROADMAP.md">路线图</a> ·
  <a href="README.md">English</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Platform" />
  <img src="https://img.shields.io/badge/status-beta-orange" alt="Status" />
</p>

---

<p align="center">
  <img src="screenshots/index.png" alt="Tentarc" width="720" />
</p>

---

## Tentarc 是什么？

Tentarc 将您的应用、API 和数据连接到一个流畅的界面中。体验 Claude Code 加持的原生 Agent 多任务处理。

从飞书、Slack、Telegram 或 Discord 发一条消息 — Agent 在你的电脑上本地执行，然后把结果发回给你。不需要配置文件，不需要安装向导。你说你想要什么，Agent 自己搞定。

> 你可以把它理解为 Claude Code — 但不只是写代码，而是处理桌面上的一切。

## 开箱即用

**"连接 Linear / Gmail / Slack..."**
告诉 Agent "添加 Linear"。它会找到对应的 API，读文档，配置认证，自动完成一切。

**"我有一个 MCP 配置。"**
粘贴进来就行，Agent 处理剩下的。

**"本地工具呢？"**
完全支持。指向一个 npx 命令、Python 脚本，或任何本地程序。

**"能接入自定义 API 吗？"**
粘贴 OpenAPI spec、接口地址、文档截图 — 你有什么就给什么，它自己搞明白。

**"怎么创建新 Skill？"**
描述这个 Skill 应该做什么，给它一些上下文。Agent 搞定剩下的。

**"改完配置需要重启吗？"**
不需要。一切即时生效。用 `@` 提及新 Skill 或 Service，对话中间就能用。

## 安装

| 平台 | 下载 |
|------|------|
| macOS (Apple Silicon) | [Tentarc-arm64.dmg](https://download.tentarc.com/releases/latest/Tentarc-arm64.dmg) |
| macOS (Intel) | [Tentarc-x64.dmg](https://download.tentarc.com/releases/latest/Tentarc-x64.dmg) |
| Windows | [Tentarc-x64.exe](https://download.tentarc.com/releases/latest/Tentarc-x64.exe) |
| Linux | [Tentarc-x64.AppImage](https://download.tentarc.com/releases/latest/Tentarc-x64.AppImage) |

或访问 [tentarc.com/download](https://tentarc.com/download) 获取更多选项。

## 功能

### Apps — 你的消息，一个 Agent

连接你的消息平台，让 Agent 统一处理 **飞书、Telegram、Slack、Discord** 上的对话 — 微信和 iMessage 即将支持。

从手机发一条消息，Agent 在你的电脑上执行，结果自动回传。无论你在哪，Agent 随时可达。

### Services — 连接你的数据

一键集成 Linear、GitHub、Notion、Slack、Jira、Google Drive、Gmail、Calendar、Outlook、Teams、OneDrive、Obsidian — 还有更多。

无需手动配置。告诉 Agent 你想连什么，它自动处理认证和接入。

### Skills — 扩展能力

浏览、安装、创建 Skill，赋予 Agent 新的超能力 — 从浏览器自动化、PDF 处理到前端设计和代码生成。

描述你想要的 Skill，导入现有的，或在不同工作区之间共享。

### 多会话收件箱

不只是单个聊天 — 而是完整的收件箱，带工作流状态：

**待办 → 进行中 → 待审核 → 完成**

标记重要会话、归档旧会话、AI 自动生成标题、完整历史记录持久化到磁盘。

### 权限模式

| 模式 | 行为 |
|------|------|
| **探索** | 只读。Agent 只能看，不能动。 |
| **确认编辑** | 写操作前需要你批准。（默认） |
| **全自动** | 完全自动驾驶。Agent 执行一切。 |

对话中按 **SHIFT+TAB** 切换模式。

### 自定义模型

Anthropic、OpenRouter、Vercel AI Gateway、MiniMax、智谱 GLM、Kimi、火山引擎、Ollama，或任何自定义端点。一次配置，所有供应商。

### 更多...

- **流式响应** — 实时进度展示
- **Diff 查看器** — 接受前审核所有文件变更
- **文件附件** — 拖放图片、PDF、Office 文档
- **后台任务** — 长时间运行的操作带进度跟踪
- **主题** — 15+ 内置主题，可按工作区自定义
- **自动更新** — 始终保持最新版本

## 截图

<table>
  <tr>
    <td><img src="screenshots/skills.png" alt="Skills" width="420" /></td>
    <td><img src="screenshots/services.png" alt="Services" width="420" /></td>
  </tr>
  <tr>
    <td align="center">Skills</td>
    <td align="center">Services</td>
  </tr>
  <tr>
    <td><img src="screenshots/workspaces.png" alt="工作区设置" width="420" /></td>
    <td><img src="screenshots/apis.png" alt="API 配置" width="420" /></td>
  </tr>
  <tr>
    <td align="center">工作区设置</td>
    <td align="center">API 配置</td>
  </tr>
</table>

## 快速开始

1. **安装** — 从上方下载安装包，或访问 [tentarc.com](https://tentarc.com/download)
2. **连接** — 使用 Anthropic、OpenRouter、Ollama 或任何兼容的 API 端点
3. **添加 Service** — 对 Agent 说 "添加 Gmail"，然后跟着提示操作
4. **开始使用** — 创建会话，添加 Skill，连接更多 Service

## 路线图

详见 [ROADMAP.md](ROADMAP.md)。

- [x] 多会话收件箱 + 工作流状态
- [x] Apps — 飞书、Telegram、Slack、Discord
- [x] Services — Linear、GitHub、Notion、Google、Slack、Microsoft 等
- [x] Skills 系统
- [x] 自定义模型（Anthropic、OpenRouter、Ollama 等）
- [x] 权限模式（探索 / 确认编辑 / 全自动）
- [x] 主题系统
- [ ] **定时任务** ← 开发中
- [ ] **长期记忆** ← 开发中
- [ ] **Skills / Services / Apps 优化** ← 开发中
- [ ] 自动化工作流
- [ ] 移动端 App

## 社区

- [报告 Bug](https://github.com/tentarcai/tentarc-agent/issues)
- [功能建议](https://github.com/tentarcai/tentarc-agent/issues)
- [讨论区](https://github.com/tentarcai/tentarc-agent/discussions)

## 许可证

[CC BY 4.0](LICENSE)

---

<p align="center">
  <a href="https://tentarc.com">tentarc.com</a>
</p>
