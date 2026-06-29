# BossAI V1.1 Candidate：AI Profiles

**Status:** V1.1 Candidate（仅设计，不立即开发）  
**Priority:** P0（高于完整 AI Connections Hub）  
**Owner:** BossAI Growth  

---

## 背景

AI Connections Hub 提案已提交，但范围偏大（含 Recommended AI、Benchmark、Cost Estimator、Guide、Health Monitor），适合在第一批客户反馈后再决定是否完整开发。当前 V1.1 更高优先级是 AI Profiles。

## 定位

AI Profiles 不是 Provider Manager，不是 API Center，不是 AI Marketplace。它是面向老板的 AI 使用模式。用户选择目标，BossAI 自动选择已连接的 AI 服务。

## 预设 Profile

**Fast / 极速模式** — 最快完成任务，优先 DeepSeek Flash、Gemini Flash 等低延迟模型，适合快速文案、短内容、草稿。

**Budget / 低成本模式** — 尽量降低 API 消耗，优先低成本模型和免费额度模型，适合大量生成、批量草稿、测试。

**Quality / 高质量模式** — 质量优先，优先 Claude、GPT、Gemini Pro 等高质量模型，适合重要文案、正式发布、品牌内容。

**Chinese / 中文优先** — 中文理解和中文内容效果最好，优先 DeepSeek、通义、Kimi、GLM 等中文模型，适合小红书、公众号、抖音、国内电商。

**Global / 海外内容** — 英文内容、跨境营销、TikTok、Amazon、Shopify，优先 OpenAI、Claude、Gemini、DeepSeek 等英文能力强的模型。

**Visual / 图片创作** — 图片输出质量优先，优先 GPT Image、即梦图片、豆包图片、Flux。

**Video / 视频创作** — 视频生成稳定优先，优先可灵、即梦、Seedance、MiniMax、Veo、Runway 等已连接视频服务。

## 与 Director 的关系

Director 不再直接问用户要用哪个模型。而是问用户希望这次任务更快、更省钱、更高质量、更适合中文、更适合海外还是更适合视频。BossAI 根据 AI Profile 和当前已连接的 AI Connections 自动选择 Provider。

## 与 BYO AI 的关系

AI Profiles 不改变 BYO AI。BossAI 不提供 API Key，不转售 Token。BossAI 只根据用户已连接的 AI 服务做推荐和调度。如果某个 Profile 需要的 AI 未连接，则提示当前模式需要连接相应 AI 服务，并引导用户进入 AI Connections Wizard。

## V1.1 优先级建议

P0：AI Connections Wizard、Welcome / First Success 优化、AI Profiles（Fast / Budget / Quality / Chinese / Global）。P1：免费 AI 推荐、一键连接测试、First Success Metric / TTFS。P2：AI Benchmark、AI Guide、Cost Estimator、Health Monitor。P3：完整 AI Connections Hub、AI Marketplace、AI Recommendation Engine。

## 产品原则

BossAI V1.1 的目标不是增加更多模型，而是降低用户首次成功门槛。不要让用户理解 DeepSeek、Claude、Gemini 之间的差异。让用户只需要选择"我要快、我要省钱、我要高质量、我要中文效果好、我要做海外内容"。BossAI 自动完成模型选择。这符合 BossAI 的核心原则：Work First、BYO AI、Provider Agnostic、Local First、Human First。

## 说明

本提案仅作为 V1.1 Candidate 更新，不要立即开发。等待第一批真实用户反馈后再决定是否进入正式 Roadmap。
