# BossAI Desktop V1.0 Early Access

## 产品简介

BossAI Desktop 是一款 AI 原生内容工作台。使用你自己的 API Key，一句话即可完成聊天、图片、视频、音频创作。所有数据保存在本地，无需云依赖，无需订阅。

**核心定位：** 一个工作台，无限 AI。

**目标用户：** 电商运营、社媒营销、内容创作者、创业者、营销团队。

---

## 核心能力

### Director 智能工作流

输入自然语言任务（如"帮我制作美国宠物保健品 TikTok 广告"），BossAI 自动：
1. 理解任务目标
2. 拆解为多步骤执行计划
3. 调用对应 AI Provider
4. 顺序执行并保存结果

用户不需要手动切换任何工具或模型。

### 双模式设计

**Professional Mode：** 直接进入 AI Chat、AI Image、AI Video、AI Audio，适合有经验的用户。
**Director Mode：** 一句自然语言描述需求，AI 自动完成整个工作流。

### 统一 Provider 管理

API Center 一站式管理所有 AI Provider：
- 25+ Provider 统一接入
- API Key 保存/修改/删除
- 健康检查 / 连接测试
- 启用/禁用

### 本地资产库（Asset Library）

- 所有生成内容自动保存
- 按项目分类
- 支持按类型筛选（对话/图片/视频/音频）
- 不丢失任何创作记录

### 项目记忆（Project Memory）

BossAI 记住你的：
- 品牌名称和描述
- 品牌语气
- 目标客户
- 产品列表
- 默认 Provider
- 工作流历史

每次工作不需要重复配置。

---

## 系统架构

```
Business Layer
  Business Context
  Director
  Project Memory
  Workflow Templates
  Capability Bus
    Provider Profiles
    Provider Router
    AI Providers (25+)
  Asset Library
  Project
```

---

## 支持 Provider

| 类型 | Provider |
|------|----------|
| LLM | DeepSeek / OpenAI / Claude / Gemini / 通义千问 / Kimi / GLM / MiniMax |
| 图片 | GPT Image (DALL-E) / 即梦 / 豆包 / Flux |
| 视频 | 即梦 / 可灵 / Seedance / MiniMax / Wan / Veo / Runway / Pika / Luma |
| 音频 | Fish Audio / ElevenLabs / MiniMax Speech / 豆包语音 |

---

## 适用行业

- **电商运营：** 批量制作商品主图、详情页文案、推广视频
- **社媒运营：** 每日短视频、小红书笔记、朋友圈文案
- **内容创作：** 脚本写作、配图生成、视频制作
- **品牌营销：** 多渠道内容分发、广告素材制作
- **教育培训：** 课程推广内容、学员案例

---

## 典型场景

| 场景 | 一句话指令 |
|------|-----------|
| TikTok 广告 | "帮我制作美国宠物保健品 TikTok 广告" |
| 小红书种草 | "生成一篇小红书种草笔记配图" |
| 电商产品 | "为 Shopify 新品生成内容包" |
| 短视频系列 | "每天做一条 AI 行业趋势短视频" |
| 营销邮件 | "写一封新品发布邮件并配图" |

---

## 价格

| 套餐 | 价格 | 适用 |
|------|------|------|
| Starter | ¥99 | 个人创作者 |
| Professional | ¥299 | 专业创作者（推荐） |
| Business | ¥999 | 企业/工作室 |
| Enterprise | 定制 | 大型组织 |

- 一次性购买，永久使用
- 10 次免费试用
- 自带 API Key，模型费用直接付给 Provider
- V1.x 免费更新

---

## 路线图

| 版本 | 计划 |
|------|------|
| V1.0 | Desktop + Director + Provider Framework + Asset Library + i18n |
| V1.1 | Business Context UI + Provider Profile Editor + Workflow Templates |
| V2.0 | AI Workers + Workflow Engine + SaaS + Team |

---

## 联系方式

官网：https://bossai.dev
GitHub：github.com/liufeng1976/ai-shop-copilot
邮箱：[联系方式待补充]
