# BossAI Customer CRM

> 目标：从 0 → 10 → 100 个付费客户
> 每个客户记录以下信息

---

## 客户记录模板

```yaml
customer_id: C-001
status: trial | active | expired | churned
acquisition_channel: wechat | xiaohongshu | referral | website | other

# 基本信息
name: ""
company: ""
industry: ecommerce | education | media | agency | other
scale: solo | small-team | medium | enterprise
country: CN | US | other
contact:
  wechat: ""
  email: ""
  phone: ""

# 销售信息
trial_started: YYYY-MM-DD
trial_ended: YYYY-MM-DD
license_activated: YYYY-MM-DD
license_type: starter | professional | business | enterprise
license_code: ""
price_paid: 0

# 使用信息
api_providers:
  - deepseek
  - openai
  - kling
  - other
usage_frequency: daily | weekly | monthly | rarely
features_used:
  - director
  - chat
  - image
  - video
  - asset_library
  - api_center
monthly_api_cost_estimate: ""

# 反馈
bugs_reported: []
feature_requests: []
satisfaction_score: 1-5
nps_score: 0-10
last_contact: YYYY-MM-DD
notes: ""

# 续费
will_renew: yes | no | undecided
churn_risk: low | medium | high
churn_reason: ""
```

---

## 客户列表

| ID | 名称 | 行业 | 状态 | License | 使用频率 | 满意度 | 续费 |
|----|------|------|------|---------|---------|--------|------|
| C-001 | | | trial | | | | |
| C-002 | | | trial | | | | |

---

## 使用说明

1. 每个付费客户创建一个 YAML 记录文件，文件名为 `C-XXX.md`
2. 活跃客户每周至少联系一次
3. 满意度低于 3 分立即升级处理
4. 高风险客户（churn_risk=high）需在 weekly-report 中说明
