# 量潮工作意图

## 仓库定位

量潮工作意图（quanttide-intention）是量潮知识管理体系中的**意图聚合容器**——按领域聚合各业务的工作意图子仓库（git submodule）。每个子仓库独立维护，本仓库只追踪引用。

## 仓库结构

```
quanttide-intention/
├── assets/              → 意图子仓库（git submodule）
│   ├── default/company  → 公司意图（quanttide-intention-of-business-entity）
│   ├── data/            → 数据工程意图（quanttide-intention-of-data-engineering）
│   ├── pay/             → 支付工程意图（quanttide-intention-of-payment-engineering）
│   └── human/           → 人力资源意图（quanttide-intention-of-human-resources）
├── docs/                → 意图导航文档站（MyST）
├── README.md            → 本文件
├── CHANGELOG.md         → 版本变更记录
└── CONTRIBUTING.md      → 贡献指南
```

## 子模块管理

- 子模块独立提交推送，本仓库只更新引用指针
- 新增意图仓库：`git submodule add <url> assets/<path>`
- 同步全部子模块：`git submodule update --init --recursive`

## 关联

- 意图的事实来源：`assets/quanttide-journal`（工作日志聚合）
- 意图分层：journal（事实）→ intention（意图）→ intro（叙事）
