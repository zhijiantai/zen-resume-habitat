---
id: zen-resume
path: ~/Documents/code/zen-resume-habitat
source_repo: null
title: Zen Capability Resume Habitat
purpose: 以 evidence-derived World Slice 維護可審計、可持續更新的能力履歷
---

# Zen Capability Resume Habitat

這是一個以 `zen-capability-world-v1` 為基礎的履歷 Habitat。它不把自我描述直接當成能力證明，而是將歷史行為、工程 artifact、研究實驗與反證條件整理成可檢查的第三人稱能力模型。

## Load Order

1. `README.md` — 公開履歷與閱讀指南
2. `world-slice-index.yaml` — World Slice inventory
3. `ws-zen-capability-world-v1.yaml` — 原始能力模型
4. `.ai/habitat_rules.md` — 範圍與證據規則
5. `.ai/roles/gm.md` — 維護角色
6. `.ai/state.yaml` — 當前狀態

## Habitat Structure

```text
zen-resume-habitat/
├── README.md
├── index.md
├── world-slice-index.yaml
├── ws-zen-capability-world-v1.yaml
└── .ai/
    ├── habitat_rules.md
    ├── roles/gm.md
    └── state.yaml
```

## Maintenance Rule

新增履歷 claim 時，先記錄 observation 與 provenance，再推導 capability；保留 contradictory evidence、alternative explanations 與 falsification conditions。任何 unsupported mechanism 仍標示為 hypothesis。
