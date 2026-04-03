# Product Disco — 产品方案生成器

一句话需求，交付完整产品方案。

## 它能做什么

Product Disco 是一个 Claude 插件，内置 **10 个专业 AI Agent** 接力协作，帮你把一个模糊的产品想法变成三份可交付的文档：

1. **PRD 文档** — 完整的产品需求文档，开发团队可以直接用
2. **交互式 Demo** — 单文件 HTML 原型，浏览器打开就能点击操作
3. **流程图** — 技术侧 + 业务侧双视角 Mermaid 流程图

## 10 个 Agent 分工

| 步骤 | Agent | 做什么 |
|------|-------|--------|
| 1 | 需求澄清官 | 挑战你的假设，挖出真实需求 |
| 2 | 竞品研究官 | 联网调研市场现状，识别差异化机会 |
| 3 | 业务规划师 | 定义功能清单和优先级（P0/P1/P2） |
| 4 | 技术架构师 | 设计系统架构和数据流 |
| 5 | PRD 起草官 | 撰写完整 PRD 文档 |
| 6 | 验收定义官 | 为每个核心功能定义可量化的验收标准 |
| 7 | 严格评审官 | 独立打分评审 PRD，不合格自动重写 |
| 8 | 风险侦察兵 | 识别全链路风险，生成 Go/No-Go 清单 |
| 9 | Demo 设计官 | 生成可点击的 HTML 交互原型 |
| 10 | 流程架构师 | 输出技术+业务双视角流程图 |

## 核心特点

- **绝不编造数据**：需要数据时会主动问你要，不会自己瞎编数字
- **版本管理**：内置版本追踪，迭代时自动保留历史版本，不会覆盖之前的成果
- **多语言适配**：你用中文它就输出中文，用英文就输出英文
- **适用任何产品类型**：AI Agent、SaaS 工具、内部平台、App、API 都能用

## 怎么用

### 安装

在 Claude 桌面端（Cowork 模式）里打开 `product-disco.plugin` 文件，点击「Accept」即可。不需要 API Key，不需要装任何东西。

### 启动

对话中说以下任意一句就会触发：

- "Product Disco"
- "帮我写 PRD"
- "帮我做产品方案"
- "做个 demo"
- "分析一下这个需求"

然后描述你的产品想法就行。

### 举个例子

> "Product Disco：我需要一个系统，自动把不同供应商的同款产品匹配起来，方便比价。"

10 个 Agent 会依次带你走完：需求澄清 → 竞品调研 → 功能规划 → 架构设计 → PRD → 验收标准 → 评审 → 风险评估 → Demo → 流程图，最终交付完整方案。

### 版本管理

当你回来迭代同一个产品时，Product Disco 会自动检测历史版本并询问你：

1. **继续迭代** — 在当前版本基础上优化（如 MVP-v1.0 → MVP-v1.1）
2. **新建版本** — 开启新阶段（如 V1、V2）
3. **从头开始** — 归档历史，重新来过

版本命名规则：`[阶段]-v[主版本].[次版本]`（如 `MVP-v1.0`、`V1-v2.1`）

## 分享方式

把 `product-disco.plugin` 文件通过飞书、邮件发，对方在 Claude 桌面端打开文件，点击接受就能直接使用。

---

# Product Disco — One Idea In, Full Spec Out

Turn a one-line product idea into a complete, deliverable product plan.

## What It Does

Product Disco is a Claude plugin with **10 specialized AI agents** that collaborate in sequence to transform a rough idea into three professional deliverables:

1. **PRD Document** — A complete, dev-ready product requirements document
2. **Interactive Demo** — A single-file HTML prototype, clickable in any browser
3. **Flow Diagrams** — Dual-perspective Mermaid diagrams (technical + business)

## The 10 Agents

| Step | Agent | What It Does |
|------|-------|-------------|
| 1 | Requirement Clarifier | Challenges your assumptions, uncovers the real need |
| 2 | Competitive Researcher | Scans the market via web search, identifies gaps |
| 3 | Business Planner | Defines features and priorities (P0/P1/P2) |
| 4 | Tech/AI Architect | Designs the system architecture and data flow |
| 5 | PRD Drafter | Writes the complete PRD document |
| 6 | Acceptance Criteria Designer | Defines testable acceptance criteria |
| 7 | Strict Reviewer | Scores the PRD, forces rewrites if needed |
| 8 | Risk Scout | Maps risks and creates a Go/No-Go checklist |
| 9 | Demo Designer | Builds a clickable HTML prototype |
| 10 | Flow Architect | Generates tech and business flow diagrams |

## Key Features

- **No fabricated data**: Always asks you for real data, never makes up numbers
- **Version management**: Built-in version tracking — iterate safely without losing previous work
- **Language adaptive**: Responds in whatever language you use
- **Works for any product type**: AI agents, SaaS tools, internal platforms, mobile apps, APIs, and more

## How to Use

### Install

Open the `product-disco.plugin` file in Claude desktop app (Cowork mode) and click "Accept." No API keys or external tools required.

### Get Started

Say any of these trigger phrases in a conversation:

- "Product Disco"
- "Help me write a PRD"
- "Build a product spec"
- "Create a product plan"
- "Make a demo"

Then describe your product idea.

### Example

> "Product Disco: I need a system that automatically matches products from different suppliers for price comparison."

The 10 agents will walk you through: Requirement clarification → Competitive research → Feature planning → Architecture → PRD → Acceptance criteria → Review → Risk assessment → Demo → Flow diagrams.

### Version Management

When you come back to iterate on a product, Product Disco detects existing versions and asks:

1. **Continue iterating** — Build on current version (e.g., MVP-v1.0 → MVP-v1.1)
2. **New version** — Start a new stage (e.g., V1, V2)
3. **Start fresh** — Archive everything, restart from scratch

Version format: `[Stage]-v[Major].[Minor]` (e.g., `MVP-v1.0`, `V1-v2.1`)

## How to Share

Send the `product-disco.plugin` file to anyone via any messaging app or email. They open it in the Claude desktop app and click accept — ready to use.

---

Built by Product Disco Team.
