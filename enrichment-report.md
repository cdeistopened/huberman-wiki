# Huberman Plugin Enrichment Report

**Date:** 2026-03-26
**Principle:** Every reference article must serve a skill. No orphans.

---

## Summary

- **Before:** 18 orphan framework articles, 5 orphan decompositions, 1 orphan index (24 total orphans)
- **After:** 0 orphans. All 66 reference articles (58 frameworks + 5 decompositions + 3 indexes) are wired to at least one skill.
- **New articles created:** 2 cross-pollination frameworks
- **Skills edited:** 10 of 12 plugin skills

---

## Orphan Wiring (18 framework articles + 5 decompositions + 1 index)

### Sleep Optimizer (5 articles wired)

| Article | Why |
|---------|-----|
| `melatonin-warning.md` | Directly relevant to sleep supplement decisions |
| `napping-protocol.md` | Sleep management tool for daytime recovery |
| `temperature-minimum.md` | Circadian phase-shifting anchor point |
| `jet-lag-protocol.md` | Travel/shift work circadian adjustment |
| `evening-sunset-viewing.md` | Evening light signal priming melatonin release |

### Exercise Protocol Builder (3 articles wired)

| Article | Why |
|---------|-----|
| `endurance-training-protocol.md` | Endurance programming beyond Zone 2 |
| `flexibility-stretching-protocol.md` | Stretching types and timing relative to training |
| `sauna-growth-hormone-protocol.md` | Recovery tool with GH and cardiovascular benefits |

### Focus Optimizer (4 articles wired)

| Article | Why |
|---------|-----|
| `creatine-for-brain.md` | Cognitive ATP support for sustained mental work |
| `acetylcholine-focus-system.md` | The attention spotlight neurochemical |
| `caffeine-timing-rule.md` | Quick-reference timing for focus without sleep disruption |
| `ultradian-work-cycles.md` | Complementary ultradian cycle reference |

### Morning Routine Designer (2 articles wired)

| Article | Why |
|---------|-----|
| `morning-sunlight-viewing.md` | Complementary morning light reference |
| `caffeine-timing-rule.md` | Quick-reference caffeine delay rule |

### Dopamine Masterclass (1 article wired)

| Article | Why |
|---------|-----|
| `dopamine-baseline-management.md` | Practical baseline protection strategies |

### Stress Toolkit (2 articles wired)

| Article | Why |
|---------|-----|
| `depression-multi-pathway-model.md` | Beyond-serotonin depression pathways |
| `meditation-types-comparison.md` | Meditation type matching with 13-min threshold |

### Cold Exposure Guide (1 article wired)

| Article | Why |
|---------|-----|
| `deliberate-cold-exposure.md` | Comprehensive cold exposure overview |

### Supplement Stack Evaluator (2 articles wired)

| Article | Why |
|---------|-----|
| `melatonin-warning.md` | Melatonin label accuracy and hormone concerns |
| `sleep-supplements-stack.md` | Alternative sleep stack formulation reference |

### Neuroplasticity Workshop (1 article wired)

| Article | Why |
|---------|-----|
| `nsdr-yoga-nidra.md` | Quick-reference NSDR for learning consolidation |

### Episode Recommender (1 article wired)

| Article | Why |
|---------|-----|
| `by-supplement.md` | Supplement index for episode discovery |

### Ask Huberman Router (5 decompositions + 2 enrichments wired)

| Article | Why |
|---------|-----|
| `decomposition-sleep-circadian.md` | Domain source map for sleep routing |
| `decomposition-exercise-performance.md` | Domain source map for exercise routing |
| `decomposition-neurochemistry-focus.md` | Domain source map for focus routing |
| `decomposition-nutrition-supplements.md` | Domain source map for supplement routing |
| `decomposition-stress-mental-health.md` | Domain source map for stress routing |
| `hormozi-value-equation-health-protocols.md` | Protocol comparison meta-framework |
| `balaji-truth-classifier-health-claims.md` | Health claim evaluation meta-framework |

---

## Cross-Pollination Enrichment (2 new articles)

### 1. Hormozi Value Equation for Health Protocols

**Location:** `references/frameworks/hormozi-value-equation-health-protocols.md`
**Wired to:** ask-huberman (router), supplement-stack-evaluator

Adapts Hormozi's `Value = (Dream Outcome x Likelihood) / (Time Delay x Effort)` to health protocol evaluation. Includes:
- Scoring rubric mapping each variable to health context
- Scored examples: morning sunlight (36), cold exposure (9.3), tongkat ali (2.1)
- Evidence tier taxonomy matching Huberman's hedge language to evidence quality
- Practical application: forces structured comparison instead of "try everything"

### 2. Balaji Truth Type Classifier for Health Claims

**Location:** `references/frameworks/balaji-truth-classifier-health-claims.md`
**Wired to:** ask-huberman (router), supplement-stack-evaluator

Applies Balaji's truth type taxonomy (scientific, political, social, commercial) to health claims. Includes:
- Truth type definitions with health-specific examples
- Table of Huberman positions where scientific truth contradicts political truth (melatonin, saturated fat, sunlight)
- Social truth persistence examples (detox diets, dopamine fasting, "no pain no gain")
- Commercial truth examples (multivitamins, pre-workout, anabolic window)
- Nutrition as the domain where truth types collide most violently

---

## Duplicate Articles Identified (Not Removed)

Six pairs of near-duplicate articles exist. The enriched versions (with frontmatter) are the primary references; the thinner versions are now wired as secondary references to appropriate skills.

| Primary (Referenced) | Secondary (Now Wired) | Wired To |
|---------------------|----------------------|----------|
| `morning-sunlight-protocol.md` | `morning-sunlight-viewing.md` | morning-routine-designer |
| `sleep-supplement-stack.md` | `sleep-supplements-stack.md` | supplement-stack-evaluator |
| `nsdr-yoga-nidra-protocol.md` | `nsdr-yoga-nidra.md` | neuroplasticity-workshop |
| `ultradian-cycle-focus-blocks.md` | `ultradian-work-cycles.md` | focus-optimizer |
| `caffeine-adenosine-protocol.md` | `caffeine-timing-rule.md` | focus-optimizer, morning-routine-designer |
| `dopamine-baseline-peak-dynamics.md` | `dopamine-baseline-management.md` | dopamine-masterclass |

**Recommendation:** In a future cleanup pass, merge each pair into a single canonical article to reduce reference bloat. The thinner versions could become "See also" redirects.

---

## Final State

| Metric | Before | After |
|--------|--------|-------|
| Total reference articles | 64 | 66 (+2 enrichment) |
| Orphan articles | 24 | 0 |
| Skills with Related Frameworks section | 10 | 10 (all enriched) |
| Cross-pollination frameworks | 0 | 2 |
| Decomposition files wired to router | 0 | 5 |
