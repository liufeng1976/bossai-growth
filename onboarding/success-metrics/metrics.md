# First Success Metrics

> P2 · 衡量首次使用体验

---

## Time To First Success（TTFS）

**定义：** 从用户首次安装到完成第一次成功 AI 生成的累计时间。

**目标值：** TTFS ≤ 5 分钟

**测量节点：**

| 节点 | 说明 | 目标 |
|------|------|------|
| T0 | 安装完成，首次启动 | — |
| T1 | 完成 AI Connections 配置 | ≤ 2 分钟 |
| T2 | 完成首次生成 | ≤ 3 分钟 |
| TTFS | T0 → T2 总时间 | ≤ 5 分钟 |

## 分段指标

### 安装到首次连接 AI（T0 → T1）

- 目标：≤ 2 分钟
- 测量：安装完成 → AI Connections 配置成功
- 优化：简化 Wizard，提供跳过和体验模式

### 首次连接到首次生成（T1 → T2）

- 目标：≤ 3 分钟
- 测量：AI Connections 配置成功 → 第一次生成成功
- 优化：首页推荐任务，一键执行

## 数据记录

每次安装记录：

```yaml
user_id: ""
install_time: ""
ai_connected_time: ""
ai_connected_provider: ""
first_generation_time: ""
first_generation_type: ""
first_success_time: ""
ttfs_seconds: 0
ttfs_target_met: true/false
```

## 每周报告

| 指标 | 本周 | 上周 | 目标 |
|------|------|------|------|
| 安装数 | | | — |
| AI 连接率 | | | 70% |
| 首次生成率 | | | 60% |
| 平均 TTFS | | | ≤ 5 min |
| TTFS 达标率 | | | 80% |
