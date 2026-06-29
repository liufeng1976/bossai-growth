# BossAI Lead Database

> 每个 Lead 记录来源、行业、联系方式、跟进状态
> 目标：每周新增 50+ Lead

---

## Lead 记录模板

```yaml
lead_id: L-001
status: new | contacted | demo_scheduled | trial | activated | paid | lost
priority: high | medium | low

# 来源
source: xiaohongshu | wechat_group | referral | website | wechat_moment | other
source_url: ""
referrer: ""

# 基本信息
name: ""
company: ""
title: ""
industry: ecommerce | education | media | agency | creator | other
scale: solo | 2-10 | 11-50 | 50+
country: CN | US | other
contact:
  wechat: ""
  email: ""
  phone: ""

# 兴趣
interest: content_creation | short_video | ecommerce | marketing | other
pain_points: []
budget: low | medium | high
urgency: immediate | this_month | this_quarter | exploring

# 跟进
first_contact: YYYY-MM-DD
last_contact: YYYY-MM-DD
next_action: ""
next_action_date: YYYY-MM-DD
notes: ""
```

---

## Lead 来源渠道

| 渠道 | 优先级 | 获取方式 | 预计转化率 |
|------|--------|---------|-----------|
| 小红书评论/私信 | 高 | 在相关笔记下评论或私信 | 5% |
| 微信群 | 高 | 加入电商/运营/AI 群，自然推荐 | 8% |
| 朋友推荐 | 最高 | 现有客户/朋友介绍 | 20% |
| 官网下载 | 中 | 自然流量 | 3% |
| 公众号 | 中 | 投稿/合作 | 5% |
| 朋友圈 | 中 | 朋友分享 | 4% |
| 行业 KOL | 高 | 付费合作/资源互换 | 10% |

## 目标 Lead 画像

### 优先（高转化率）

| 画像 | 特征 | 痛点 | 推荐话术 |
|------|------|------|---------|
| 电商运营 | 每天做商品图/短视频 | 工具多、效率低、成本高 | "一句话生成商品内容包" |
| 个人创作者 | 短视频博主/自媒体 | 不会写文案/不会做图 | "AI 帮你完成内容" |
| 创业公司 | 没有内容团队 | 老板自己干 | "一个人就是一个内容团队" |
| MCN/工作室 | 内容产出压力大 | 人力成本高 | "效率提升 10 倍" |

### 次优先

| 画像 | 特征 |
|------|------|
| 广告公司 | 提案需要快速出素材 |
| 培训机构 | 课程推广内容 |
| 跨境电商 | 多语言内容需求 |
