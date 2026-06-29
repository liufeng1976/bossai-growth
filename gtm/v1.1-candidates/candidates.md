# BossAI V1.1 Candidates

> 所有需求必须来自真实客户。不要来自开发者想象。
> 当前状态：等待第一批客户反馈后填充

---

## 记录模板

```yaml
candidate_id: C-001
status: collected | evaluating | planned | rejected
customer_count: 0
customer_ids: []
business_value: high | medium | low
development_cost: high | medium | low
priority: P0 | P1 | P2 | P3
description: ""
notes: ""
```

---

## 当前候选（待填充）

| ID | 需求 | 客户数 | 商业价值 | 开发成本 | 优先级 |
|----|------|--------|---------|---------|--------|
| | (等待客户反馈) | | | | |

---

## V1.1 优先级排序（待客户验证后确认）

### P0（最高优先级）

1. AI Connections Wizard — 重新设计配置流程，去技术词汇，增加跳过和体验模式
2. Welcome / First Success 优化 — 推荐任务一键执行，🎉 成功反馈页面
3. AI Profiles — Fast / Budget / Quality / Chinese / Global / Visual / Video

### P1（高优先级）

4. 免费 AI 推荐 — 新手推荐、免费额度推荐
5. 一键连接测试 — 配置完成后自动测试
6. First Success Metric / TTFS — 首次成功时间测量

### P2（中优先级）

7. AI Benchmark — 延迟/可用性测试
8. AI Guide — 图文教程（申请 API Key）
9. Cost Estimator — 费用估算
10. Health Monitor — 持续连接状态监控

### P3（低优先级）

11. 完整 AI Connections Hub
12. AI Marketplace
13. AI Recommendation Engine
14. Business Context UI
15. Workflow Template Selector

### 已确认不属于 V1.1

- 视频状态轮询
- i18n 即时刷新
- 配置持久化统一
- AI Workers
- Workflow Engine
- SaaS 同步
- MCP/HTTP API
- 团队协作

---

## 优先级调整规则

1. 1 个客户提出 → P2 观察
2. 2 个客户提出 → P1 评估
3. 3 个及以上客户提出 → P0/P1 执行
4. 付费客户需求优先级高于试用客户
5. Bug 类自动 P0
6. 每月重新排序
