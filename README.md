# Zen Capability Resume

> Evidence-derived resume habitat for Zen Tai

這不是傳統的職缺匹配評估，也不是人格分類或自我宣傳。這是一份以歷史行為、工程 artifacts、研究實驗與可反駁條件為基礎的**第三人稱能力模型**。

## Profile

Zen Tai appears to be a **model-oriented systems engineer** who repeatedly:

- converts ambiguous systems into explicit entities, relations, constraints, and hypotheses;
- updates or retires models when reliable evidence conflicts with them;
- reasons about uncertainty through competing explanations and graded confidence;
- externalizes working context into portable artifacts for humans and AI systems;
- turns recurring reasoning or engineering friction into reusable tools and workflows.

這段總結是對 `zen-capability-world-v1` 的壓縮，不是獨立的新證據。完整 evidence contract 與 boundaries 請見 [`ws-zen-capability-world-v1.yaml`](./ws-zen-capability-world-v1.yaml)。

## Strongest Supported Capabilities

| Capability | Evidence-based description | Confidence |
|---|---|---:|
| Explicit model construction | 將複雜或模糊系統轉成可操作的 representation：entities、relations、constraints、states、invariants、hypotheses。 | High |
| Evidence-driven model revision | 以 prediction → evidence → contradiction → assumption inspection → revision/retirement 的循環修正模型。 | High |
| Uncertainty reasoning | 使用 Bayesian reasoning、likelihood comparison、hidden-state models 與 graded confidence，避免把 belief 當 fact。 | High |
| Problem externalization | 將隱含脈絡轉成 World Slice、Coding Blueprint、Habitat state 等可攜 artifact。 | High |
| Reusable tool construction | 從重複 friction 找出機制，進一步自動化、外部化、dogfood、refine。 | High |

## Plausible, Still Under Validation

以下是合理但尚未完全建立的 hypotheses，不應在沒有新 evidence 時寫成確定能力：

- **Structural cross-domain transfer** — 能否把一個 domain 的深層 structural pattern 有效映射到另一個 domain。
- **Explanation as model validation** — 解釋與互動提問是否同時用來暴露自身模型缺口。
- **Knowledge compression** — 是否主要透過 relational models 連接新知，而非儲存孤立 facts。
- **Mental simulation** — 模型穩定後，是否會透過改變 state、entity 或 constraint 來模擬下游結果。

## Working Method

```text
Observe complexity
  → construct model
  → expose structure
  → generate hypotheses
  → predict evidence
  → update model
  → externalize or build tool
  → communicate / delegate
  → use questions and failures to reveal missing structure
```

## Evidence Contract

- Observation ≠ capability。
- Capability 必須來自 repeated behavior 的 inference。
- Self-description 不是 independent evidence。
- Contradictory evidence 與 alternative explanations 必須保留。
- Unsupported mechanisms 只能標成 hypothesis。
- Implementation evidence 優先於 narrative claim。
- Confidence 不得高於 evidence。

## Boundaries

模型建立能力不等於模型必然正確。主要風險包括：

1. **Model misspecification** — 錯誤的 boundaries 或 relations 會排除真實解法。
2. **Narrative coherence** — 解釋可能比 implementation evidence 更完整；`SEALer_G` 是已知警示案例。
3. **Structural mapping error** — surface similarity 可能被誤認為 structural equivalence。
4. **Prior model dominance** — 既有模型可能影響 evidence 的注意與解讀。
5. **Initial modeling cost** — 缺乏 semantic/structural anchor 的問題，初始建模成本可能較高。

## How to Read This Resume

- 想看公開摘要：讀本頁。
- 想看 claim 如何由 observations 推導：讀 `ws-zen-capability-world-v1.yaml` 的 `observations`、`capabilities`。
- 想看尚未證實的部分：讀 `hypotheses`、`boundaries`、`predictions`。
- 想挑戰模型：讀 `falsification`，提出能削弱或推翻 claim 的 evidence。
- 想加入新材料：先增加 observation/provenance，再更新 inference；不要直接改高階 conclusion。

## Status

- World Slice: `zen-capability-world-v1`
- Model type: evidence-derived capability model
- Perspective: third person
- Overall confidence: medium-high
- Current state: initial version; designed for evidence-backed iteration

## Repository Map

- [`index.md`](./index.md) — Habitat entry protocol
- [`world-slice-index.yaml`](./world-slice-index.yaml) — inventory and roadmap
- [`ws-zen-capability-world-v1.yaml`](./ws-zen-capability-world-v1.yaml) — source World Slice
- [`.ai/`](./.ai/) — local Habitat operating state; not part of the public resume narrative
