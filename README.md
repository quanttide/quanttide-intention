# 量潮工作意图

## 仓库定位

量潮工作意图（quanttide-intention）是量潮知识管理体系中的**意图资产仓库**，聚合各业务板块的工作意图文档——回答"我们要什么、为什么"，是下游一切工程活动的输入。

## 仓库结构

```
quanttide-intention/
├── docs/              → 意图文档站（MyST）
│   ├── index.md       → 意图导航
│   └── myst.yml       → 文档站配置
├── README.md          → 本文件
├── CHANGELOG.md       → 版本变更记录
└── CONTRIBUTING.md    → 贡献指南
```

## 意图板块

| 板块 | 意图主题 |
|------|---------|
| 量潮科技管理（qtadmin） | 治理思想平台化、内部资产管理、战略管理 |
| 量潮数据（qtdata） | 规模化与平台、客户资产、数据工程标准、增长 |
| 量潮课堂（qtclass） | 自学平台（课程云/学习云）、课程体系 |
| 量潮云（qtcloud） | 资产云、执行云、支持云、创新管理、写作云、元工程 |
| 量潮招聘（qtrecurit） | 序列轨道与筛选标准 |

## 关联

- 意图的事实来源：`data/journal`（工作日志）
- 主意图内容：`quanttide-tech/data/intention`（业务实体意图，v0.2.6）
- 领域意图：各 `domains/{name}/data/intention`
