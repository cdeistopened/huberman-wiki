---
name: supplement-stack-evaluator
description: "Evaluate a user's current supplement stack and recommend additions or removals with specific dosages, forms, and timing. Use when someone asks about supplements, wants to know what to take, lists their current supplements, or asks 'should I take X.' This skill gives personalized recommendations based on the user's goals, with exact mg dosages and timing protocols from Huberman Lab."
---

# Supplement Stack Evaluator

You evaluate the user's current supplements and goals, then build or refine their stack using Huberman's specific recommendations with exact dosages, forms, and timing.

## The Consultation

### Step 1: Current Stack Audit

Ask:
1. **What supplements do you currently take?** (Name, dosage, form, timing)
2. **What are your primary health goals?** (Sleep, focus, mood, exercise performance, general health, stress, longevity)
3. **Any medications?** (Important for interactions — flag but don't give medical advice)
4. **Diet overview:** (Standard, vegetarian, keto, fasting — affects baseline nutrient status)
5. **Budget sensitivity?** (Supplements add up — helps prioritize)

### Step 2: Evaluate Current Stack

For each supplement they're taking, check against Huberman's recommendations:

- **Right substance, wrong form?** (e.g., magnesium oxide instead of threonate)
- **Right substance, wrong dosage?** (e.g., melatonin at 5mg instead of 0.5mg or none)
- **Right substance, wrong timing?** (e.g., caffeine immediately upon waking)
- **Unnecessary?** (Something Huberman doesn't recommend or actively advises against)
- **Missing something important?** (Based on their goals)

### Step 3: The Huberman Supplement Reference

Use these as the source of truth. All dosages and recommendations are from Huberman's episodes.

#### Foundational (Huberman takes these himself)

| Supplement | Dosage | Form | Timing | Purpose |
|-----------|--------|------|--------|---------|
| Omega-3 (EPA/DHA) | 1-3g EPA per day (above DHA content) | Liquid fish oil or high-EPA capsules | With food | Mood, brain health, inflammation. Key: the EPA fraction is what matters for mood — minimum 1000mg EPA above whatever DHA content. |
| Vitamin D3 | 1000-5000 IU/day | D3 (not D2) | Morning, with fat-containing food | Immune function, mood, bone health. Many people are deficient. |
| Magnesium threonate | 300-400mg | Threonate form (e.g., Magtein) | 30-60 min before sleep | Sleep, cognitive function. Crosses blood-brain barrier. |
| Creatine monohydrate | 5g/day | Monohydrate (cheapest, most studied) | Any time, with or without food | Physical performance + cognitive benefits. "One of the most well-studied and safe supplements." |

#### Sleep Stack

| Supplement | Dosage | Form | Timing | Notes |
|-----------|--------|------|--------|-------|
| Magnesium threonate | 300-400mg | Threonate | 30-60 min before bed | Primary sleep supplement |
| Apigenin | 50mg | Capsule | 30-60 min before bed | GABA-A agonist, mild sedation |
| L-theanine | 100-400mg | Capsule | 30-60 min before bed | Caution: can cause vivid dreams or sleepwalking in some. Start at 100mg. |
| Glycine | 2g | Powder or capsule | 30-60 min before bed | Lowers core body temperature |
| Inositol | 900mg | Myo-inositol | Before bed or upon night waking | Specifically for middle-of-night waking |

#### Focus & Cognitive Stack

| Supplement | Dosage | Form | Timing | Notes |
|-----------|--------|------|--------|-------|
| Alpha-GPC | 300-600mg | Capsule | 30 min before focused work | Acetylcholine precursor. Caveat: Huberman mentions some concern about long-term use and TMAO — consider garlic (600mg) as a counterbalance. |
| L-tyrosine | 500mg | Capsule | 30 min before focused work | Dopamine precursor. Not for daily use — use on demanding days. |
| Caffeine | 100-400mg (1-3mg/kg body weight) | Coffee, tea, or pill | 90-120 min after waking | Standard focus enhancer. Delay is key. |

#### Mood & Stress Stack

| Supplement | Dosage | Form | Timing | Notes |
|-----------|--------|------|--------|-------|
| EPA omega-3 | 1000mg+ EPA | See foundational | With food | Threshold for mood effects. Below this, effects are minimal. |
| Ashwagandha | 300-600mg | KSM-66 or Sensoril extract | Evening | Cortisol reduction. BUT: Huberman warns against chronic daily use — concerns about thyroid function and blunting beneficial stress responses. Cycle: 2 weeks on, 2 weeks off, or use only during high-stress periods. |
| Rhodiola rosea | 100-200mg | Standardized extract | Before stressful events | Acute cortisol modulation. Not for daily long-term use. |

#### Exercise Performance Stack

| Supplement | Dosage | Form | Timing | Notes |
|-----------|--------|------|--------|-------|
| Creatine monohydrate | 5g/day | Monohydrate | Any time | Strength, power, cognitive. No loading phase needed. |
| Caffeine | 1-3mg/kg | Coffee or pill | 30-60 min pre-workout | Performance enhancer. |
| Beta-alanine | 3.2g/day | Powder | Any time (split doses to reduce tingling) | Endurance, buffering capacity. |
| Electrolytes | Sodium, potassium, magnesium | Salt + electrolyte mix | Before and during training | Hydration and performance. |

#### Hormonal Support (with strong caveats)

| Supplement | Dosage | Form | Timing | Notes |
|-----------|--------|------|--------|-------|
| Tongkat ali | 400mg | Standardized extract (10:1) | Morning | May support testosterone. Huberman mentions taking this. |
| Fadogia agrestis | 425-600mg | Extract | Morning | Testosterone support. BUT: Huberman has flagged potential toxicity concerns at higher doses. Cycle: 8-12 weeks on, 2-4 weeks off. Blood work recommended. |
| Boron | 2-6mg | Capsule | Morning | May support free testosterone. Low risk. |

#### What Huberman Recommends AGAINST

| Substance | Why |
|-----------|-----|
| Melatonin (most doses) | "Melatonin is a hormone, not a supplement." Doses in products (3-10mg) are 10-100x physiological. Label accuracy is poor. Suppresses gonadal hormones at high doses. Exception: 0.5-1mg for jet lag, short-term only. |
| High-dose vitamin C | "Most people get enough from food. High doses just create expensive urine." |
| Most testosterone boosters | "The vast majority have no good data." Tongkat ali and fadogia are the exceptions he mentions, with caveats. |

### Step 4: Build the Optimized Stack

Based on their goals, current stack, and budget:

1. **Keep:** What they're already taking that aligns with Huberman's recommendations
2. **Adjust:** Form, dosage, or timing changes
3. **Add:** Missing supplements for their stated goals
4. **Remove:** Things that are unnecessary, poorly dosed, or counterproductive
5. **Deprioritize:** Nice-to-haves they can add later if budget allows

## Output

```markdown
# Your Optimized Supplement Stack

**Goals:** [their goals]

## Changes to Current Stack

| Current | Change | Why |
|---------|--------|-----|
| [what they take] | [keep/adjust/remove] | [specific reason] |

## Recommended Stack

### Priority 1 (Start Here)
| Supplement | Dosage | Form | Timing | Purpose |
|-----------|--------|------|--------|---------|
| [name] | [exact mg] | [specific form] | [when] | [why] |

### Priority 2 (Add When Ready)
| Supplement | Dosage | Form | Timing | Purpose |
|-----------|--------|------|--------|---------|

### Priority 3 (Optional Enhancements)
| Supplement | Dosage | Form | Timing | Purpose |
|-----------|--------|------|--------|---------|

## Timing Schedule

| Time of Day | Supplements | Notes |
|------------|-------------|-------|
| Morning (with food) | [list] | |
| Pre-workout | [list] | |
| 30-60 min before bed | [list] | |

## Important Caveats
- [Interactions to watch]
- [Cycling recommendations]
- [When to get blood work]

## Cost Estimate
[Rough monthly cost for the priority 1 stack]

## Source Episodes
[Relevant episode filenames]
```

## Related Skills

- **dopamine-masterclass** — The dopamine stacking warning is critical context for supplement decisions.
- **sleep-optimizer** — For sleep-specific stacks and timing.
- **exercise-protocol-builder** — For workout supplement timing (creatine, caffeine, beta-alanine).
- **gut-brain-connection** — Gut health affects supplement absorption and efficacy.

## Related Frameworks

- `magnesium-forms-guide.md` — Why the form matters more than the dose (threonate vs. glycinate vs. oxide).
- `omega-3-epa-threshold.md` — The 1000mg EPA threshold for mood effects and why DHA ratio matters.
- `ashwagandha-nuanced-view.md` — Why Huberman warns against chronic daily use and recommends cycling.
- `tongkat-ali-fadogia-protocol.md` — Hormonal support with specific cycling and blood work caveats.
- `creatine-brain-body.md` — The most well-studied supplement: 5g/day for both physical and cognitive benefits.
- `alpha-gpc-focus-protocol.md` — Acetylcholine precursor for focus, with TMAO caveat and garlic counterbalance.
- `melatonin-warning.md` — Why Huberman recommends against supplemental melatonin and the label accuracy problem.
- `hormozi-value-equation-health-protocols.md` — Score supplements on dream outcome, evidence quality, time to effect, and compliance burden.
- `balaji-truth-classifier-health-claims.md` — Separate scientific truth from commercial/social truth in supplement marketing claims.
- `sleep-supplements-stack.md` — Alternative sleep stack reference with additional formulation details.

## Disclaimer

This is educational information organized from a public podcast. It is not medical advice. Supplement quality varies widely — Huberman recommends testing through third-party verification (NSF, USP, Informed Sport). Consult a healthcare provider, especially if you take prescription medications.
