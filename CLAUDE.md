# Ask Huberman — Health & Science Coaching Plugin

An AI health and science coach built from 137 episodes of Huberman Lab. Not a chatbot pretending to be Andrew Huberman — a structured library of real protocols, real dosages, real timings, and real quotes from the podcast. Every recommendation traces back to a specific episode.

## Quick Start

Ask any health, neuroscience, or performance question:
- "I can't sleep through the night — what does Huberman recommend?"
- "Design me a morning routine"
- "Should I take magnesium? What form and dosage?"
- "I want to improve my focus for deep work"
- "Teach me about dopamine"
- "Build me a training program for strength and longevity"

Or use a specific skill directly:

### Decision Skills (You bring your situation, get personalized protocols)
- `/ask-huberman:morning-routine-designer` — Design a science-backed morning routine
- `/ask-huberman:sleep-optimizer` — Audit and fix sleep issues
- `/ask-huberman:supplement-stack-evaluator` — Evaluate supplements with exact dosages
- `/ask-huberman:exercise-protocol-builder` — Design a training protocol
- `/ask-huberman:stress-toolkit` — Match stress tools to your situation
- `/ask-huberman:focus-optimizer` — Protocols for sustained focus

### Tutor Skills (Learn the science, then apply)
- `/ask-huberman:dopamine-masterclass` — How dopamine actually works
- `/ask-huberman:neuroplasticity-workshop` — How to rewire habits and learn faster
- `/ask-huberman:cold-exposure-guide` — Science, protocols, and contraindications
- `/ask-huberman:gut-brain-connection` — Microbiome, fermented foods, mood

### Utility
- `/ask-huberman:episode-recommender` — Find the right episode to listen to

## What's Inside

### 12 Interactive Skills
Decision-making and tutor frameworks that walk you through a specific health question step by step. Each one asks about your situation, applies protocols extracted from the archive, and delivers a structured output with specific numbers.

### 50+ Protocol and Framework Guides
Detailed written guides on specific protocols — from the sleep supplement stack to the physiological sigh to Zone 2 cardio. Each one includes specific dosages, timings, temperatures, and source episodes. Organized across five domains: Sleep & Circadian, Exercise & Performance, Neurochemistry & Focus, Stress & Mental Health, Nutrition & Supplements.

### 137 Searchable Transcripts
The full Huberman Lab archive, polished and indexed. Claude can search these to answer any question with direct quotes and episode citations.

### Progressive Disclosure
You don't need to read 137 transcripts. The system works in layers:
1. **Ask a question** — Claude routes to the right skill or protocol
2. **Go deeper** — Claude reads the source transcript for more context
3. **Go deepest** — Claude searches across all transcripts for related insights

## The Key Difference: Specific Numbers

Huberman is ALL about specific numbers. This plugin preserves that precision in every response:

| Generic AI Response | Ask Huberman Response |
|--------------------|----------------------|
| "Consider magnesium supplementation" | "Magnesium threonate 145mg, 30-60 minutes before sleep" |
| "Get morning sunlight" | "Sunlight within 30-60 min of waking: 5 min (bright), 10 min (cloudy), 20-30 min (very overcast)" |
| "Try cold showers" | "45-60F (7-15C), 1-5 min per session, 11 min total per week across 2-4 sessions" |
| "Delay your caffeine" | "Wait 90-120 minutes after waking before first caffeine" |
| "Take fish oil for mood" | "1000mg+ EPA (above DHA content) — the EPA fraction is what matters for mood effects" |

## How It's Built

This plugin was built by the [Creative Intelligence Agency](https://creativeintel.agency), decomposing 137 episodes into protocols and frameworks using Claude Code's skill extraction pipeline. Every protocol traces back to a specific episode and specific quotes — nothing is invented or paraphrased beyond what's in the source material.

Source: [Huberman Lab](https://www.youtube.com/@hubaboratoryab) by Andrew Huberman, PhD (Stanford School of Medicine)

## Important Disclaimer

This is an educational tool that organizes information from a public podcast. It is not medical advice. Always consult a qualified healthcare provider before starting any supplement, exercise, or health protocol. Andrew Huberman himself emphasizes this point frequently.

---

Built by [Creative Intelligence Agency](https://creativeintel.agency). See all plugins at [creativeintel.agency/plugins](https://creativeintel.agency/plugins).
