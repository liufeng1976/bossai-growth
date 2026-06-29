# AI Connections Wizard 重新设计

> P0 · TTFS 影响最大环节

---

## 当前问题

Welcome Wizard 第二步「配置 API」中使用了：
- "API Key"
- "Provider"
- "Endpoint"
- "Base URL"
- "Test Connection"

非技术用户看不懂。大量用户在此步骤放弃。

## 重新设计方案

### 页面标题

**原：** 配置 API
**新：** 连接你的 AI

### 页面说明

**原：** 至少配置一个 LLM Provider 即可开始创作。API Key 仅保存在本机。
**新：** 选择你想使用的 AI 服务，填入密钥即可开始。你的密钥仅保存在本机，不会上传。

### 选项名称

| 原词 | 新词 |
|------|------|
| DeepSeek | DeepSeek AI |
| OpenAI | OpenAI |
| Claude | Claude AI |
| Gemini | Gemini AI |
| API Key | 密钥 |
| Base URL | 服务地址（可选） |
| Test Connection | 测试连接 |

### 布局

每个 AI 服务显示为一张卡片：
- 左侧：服务名称 + 图标
- 右侧：连接状态（未连接/已连接）
- 点击后展开输入表单

表单内：
- 密钥（密码输入框）
- 服务地址（可选，折叠状态）

### 增加「跳过」按钮

- 文字："先看看 BossAI 能做什么"
- 点击后进入 Experience Mode（Demo 模式）
- 用户随时可以回来配置

### 增加「没有 AI 密钥？」按钮

- 点击后进入 Getting Started 教程
- 教用户如何申请 DeepSeek/OpenAI/Claude/Gemini 的密钥

### 成功状态

连接成功后显示：
- 🟢 已连接
- 服务名称 + 对勾
- 下一步按钮："开始使用 BossAI"
