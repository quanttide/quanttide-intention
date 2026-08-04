# 量潮工作意图

## 意图子仓库

| 路径 | 意图 | 仓库 |
|------|------|------|
| `default/company` | 公司意图（业务实体） | quanttide-intention-of-business-entity |
| `data/` | 数据工程意图 | quanttide-intention-of-data-engineering |
| `pay/` | 支付工程意图 | quanttide-intention-of-payment-engineering |
| `human/` | 人力资源意图 | quanttide-intention-of-human-resources |

## 意图分层

```
journal（事实层）→ intention（意图层）→ intro（叙事层）
```

- 意图文档记录"我们要什么、为什么"
- 细节与执行留在 journal 与各工程仓库
- 更新方向单向：journal → intention

## 元工程

工作意图是元工程体系的关键资产：AI 生成 + 人类整理，人机长期对齐的载体。
