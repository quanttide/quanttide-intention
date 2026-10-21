# 量潮愿景 — 贡献指南

## 目录结构

```
quanttide-intention/
├── docs/              → 意图文档站（MyST）
├── README.md          → 项目定位与结构
├── CHANGELOG.md       → 版本变更记录
└── CONTRIBUTING.md    → 本文件
```

## 内容规范

- 文档用中文、MyST Markdown
- 新增文档需注册进 `docs/myst.yml` 的 toc
- 意图文档回答"我们要什么、为什么"，不写执行细节

## 提交流程

1. 在子模块内提交推送（Conventional Commits）
2. 回到父仓库更新子模块指针，提交推送
3. 变更记录写入 CHANGELOG.md
