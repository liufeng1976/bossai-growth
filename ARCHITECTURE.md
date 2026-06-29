# BossAI Architecture Overview

## 产品架构

**Desktop（V1）** — 本地桌面应用，Windows 10+，BYO AI，一次买断。
**Cloud（V2）** — 团队协作、云端同步、订阅制。
**Marketplace（V2）** — Workflow / Template / Connector / AI Workers 市场。
**Business OS（V3+ Vision）** — 企业 AI 工作操作平台。

## 技术架构

```
User → Director → AI Profiles → Provider Router → AI Providers → Asset Library
         ↓
      Project Memory
         ↓
      Business Context
```

## 项目架构

bossai-desktop/ — 产品代码仓库（Electron + React + TypeScript）
bossai-growth/ — 商业运营仓库（GTM / Sales / Customer Success / Brand）

## 核心模块

| 模块 | 说明 | 状态 |
|------|------|------|
| Director | 自然语言任务规划与执行引擎 | V1 |
| Capability Bus | 统一能力总线，executeCapability() 单一入口 | V1 |
| Provider Framework | 25+ AI Provider 统一接入 | V1 |
| AI Profiles | 用户选择目标，系统选择模型 | V1.1 Candidate |
| Asset Library | 本地资产持久化存储 | V1 |
| Project Memory | 项目级品牌/产品/偏好记忆 | V1 |
| Business Context | 业务级上下文配置 | V1（Schema Only） |
| Workflow Templates | 预设多步骤工作流 | V1（Schema Only） |
| Provider Profiles | 模型配置档案 | V1（Schema Only） |
| AI Connections Hub | 统一 AI 服务配置入口 | V1.1 Candidate |
| Task Engine | 工作类型驱动的 AI 调度引擎 | V2 Vision |
| Workflow Engine | 可视化工作流编辑器 | V2 Vision |
| Business OS | 企业业务操作系统 | V3+ Vision |
