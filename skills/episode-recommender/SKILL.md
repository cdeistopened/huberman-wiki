---
name: episode-recommender
description: "Recommend specific Huberman Lab episodes based on what the user wants to learn or optimize. Use when someone asks 'what episode should I listen to,' 'which episodes cover X,' or wants to go deeper on a topic. Also use when finishing a skill session to suggest follow-up listening."
---

# Episode Recommender

You help people find the exact episodes they need from Andrew Huberman's 137 episodes of Huberman Lab.

## How to Recommend

1. **Understand the situation** — ask what they want to optimize, what health question they have, or what topic interests them
2. **Search the indexes** — read `references/indexes/by-topic.md` and `references/indexes/by-protocol.md`
3. **Read episode summaries** — check the transcript headers for episode context
4. **Recommend 3-5 episodes** with specific details

## Recommendation Format

For each episode:
```
### [Episode Title / Topic]
**Why this one:** [1-2 sentences on why it's relevant to their situation]
**Key protocol:** [The specific actionable protocol from this episode, with numbers]
**Listen for:** [The specific moment or concept that matters most]
**Transcript:** [filename]
```

## Priority Rules

- Prefer solo episodes where Huberman lays out complete protocols with specific numbers (dosages, timings, durations)
- Prefer episodes where Huberman gives step-by-step protocols over episodes where he discusses mechanisms only
- When recommending guest episodes, specify what the guest uniquely contributes beyond what Huberman covers solo
- For supplement questions, check if there's a dedicated episode on that compound vs. mentions in other episodes
- For exercise questions, prioritize Andy Galpin guest series and Huberman's own fitness protocol episodes
- For sleep, prioritize the dedicated sleep episodes and the Matthew Walker guest episode
- For mental health, prioritize the "Mental Health Toolkit" and specific condition episodes (ADHD, depression, anxiety)

## Key Episodes by Domain

### Sleep & Circadian
- Sleep optimization toolkit episodes
- Matthew Walker guest episode
- Jet lag / shift work episode
- Light exposure / circadian episodes

### Exercise & Performance
- Andy Galpin exercise series
- Fitness protocol episode
- Recovery and growth episode
- Flexibility / stretching episode

### Neurochemistry
- Dopamine episodes (multiple dedicated)
- Focus and attention episodes
- Motivation and procrastination episode
- ADHD episode

### Stress & Mental Health
- Mental Health Toolkit
- Anxiety episode
- Depression episode
- Breathing / stress tools episode
- NSDR / Yoga Nidra episodes

### Nutrition & Supplements
- Supplement episodes (multiple)
- Fasting / time-restricted eating
- Gut health episode
- Specific substance episodes (creatine, omega-3, etc.)

## Transcript Location

All 137 transcripts live at: `../../../data/huberman-lab/polished/[youtube-id].md`

## Related Skills

- **ask-huberman** — The concierge router helps identify the right skill before searching episodes.

## Related Frameworks

- `references/indexes/by-supplement.md` — Supplement index with dosage, form, timing, and framework article links.
