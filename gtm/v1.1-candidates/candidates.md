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

## V1.1 初步范围（待客户验证后确认）

**可能包含（基于预判，非决策）：**

1. Business Context UI — 可视化编辑品牌信息
2. Workflow Template Selector — 预设工作流
3. 视频状态轮询 — Director 完成后显示生成进度
4. i18n 即时刷新 — 切换语言无需重启
5. 配置持久化统一 — localStorage + IPC 一致

**不包含（已确认不属于 V1.1）：**

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
