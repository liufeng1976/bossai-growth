# BossAI Onboarding Sprint 001

> 目标：让第一次安装的用户在 5 分钟内完成第一次成功生成
> 关键指标：Time To First Success（TTFS）≤ 5 分钟

---

## P0：AI Connections Wizard

**当前问题：** Welcome Wizard 中出现 "API Key"、"Endpoint"、"API" 等技术词汇，非技术用户看不懂。

**解决方案：** 重新设计 AI Connections Wizard，把 "配置 API" 改为 "连接你的 AI"。不要出现 API、Endpoint、Token、Base URL 等技术词。

**详细设计：** `api-wizard/redesign.md`

## P0：Getting Started

**当前问题：** 没有 API Key 的用户直接卡住，不知道去哪申请。

**解决方案：** 增加 "没有 AI Key？" 按钮，点击后进入 Getting Started 图文教程，教用户 5 分钟内完成 DeepSeek/OpenAI/Claude/Gemini 的 API Key 申请。

**详细设计：** `getting-started/guide.md`

## P0：Experience Mode

**当前问题：** 没有 API Key 就无法体验产品。

**解决方案：** 增加 Experience Mode，内置 Demo Project、Demo Assets、Demo Chat、Demo Director。用户不配置 API 也能看到 BossAI 能做什么。

**详细设计：** `experience-mode/design.md`

## P1：First Generation

**当前问题：** 用户进入首页后不知道要输入什么。

**解决方案：** 首页提供推荐任务一键体验按钮，不用自己写 Prompt。

**详细设计：** `first-generation/design.md`

## P1：Success Feedback

**当前问题：** 生成成功后没有明确的成功反馈。

**解决方案：** 第一次生成成功后展示 🎉 成功页面，显示耗时、保存位置、下一步建议。

**详细设计：** `first-generation/success-feedback.md`

## P2：Success Metrics

**当前问题：** 没有衡量首次使用体验的指标。

**解决方案：** 新增 First Success Metric，记录安装时间、首次连接 AI 时间、首次生成时间、第一次成功时间。目标 TTFS ≤ 5 分钟。

**详细设计：** `success-metrics/metrics.md`
