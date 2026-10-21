# 量潮愿景

转变轴：意图散在各领域仓 → 一处可查阅的意图汇总。起点是 `domains/<领域>/data/intention` 与各板块目录里的分散文件，终点是外部或内部读者能在一处读到一致口径的意图。

**现状（2026-10-21 核）**：板块意图页已有 35 篇，落在 `assets/default/company/<板块>/`（qtadmin / qtdata / qtclass / qtcloud / qtrecurit 等均在列）；本仓 `docs/myst.yml` 已存在；发布流水线不在本仓，而在子仓 `assets/default/company/.github/workflows/`（`deploy.yml`、`deploy-oss.yml`）。意图的正本已按领域分散，`domains/quanttide-human/data/intention`、`domains/quanttide-pay/data/intention` 各自带 `myst.yml`。

## 当前阶段

- [x] 仓库初始化（参考 quanttide-platform 结构）
- [x] 各板块意图文档填充：板块以 `assets/default/company/` 下的目录为准，已有 35 篇
- [ ] 定正本与同步方向：原条目写的「主意图（quanttide-tech/data/intention）」已不存在，意图现分散在 `domains/<领域>/data/intention`。要定的是汇总层与领域仓谁是正本、同步朝哪个方向走。达成标志：改动任一处意图，另一处能跟上且不出现两份不同说法
- [ ] 发布归属：本仓没有 `.github/workflows`，现有发布在子仓。达成标志：本仓站点有可访问 URL 并在推 `main` 后自动更新；或明确本仓只作汇总、不发布

## 待办优先级

1. 定正本与同步方向——它不定，下面的建站与发布都是给可能过时的内容建站
2. 发布归属（本仓发还是子仓发）
3. 与 journal → intention 流程的衔接
