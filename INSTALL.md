# Installing Ask Huberman

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and working

## Installation

```bash
claude install-plugin github:cdeistopened/huberman-wiki
```

Or add the plugin directory manually:

```bash
# From your project directory
claude plugin add /path/to/huberman-wiki/plugin
```

Or add it to your `.claude/settings.json`:

```json
{
  "plugins": [
    "/path/to/huberman-wiki/plugin"
  ]
}
```

## First Question to Try

```
Design me a morning routine
```

This routes to the Morning Routine Designer — the skill that synthesizes Huberman's most-cited protocols (morning sunlight, delayed caffeine, cold exposure, exercise timing) into a personalized schedule based on your wake time, goals, and constraints.

## Other Good Starting Questions

- "I can't sleep through the night — what does Huberman recommend?"
- "Should I take magnesium? What form and dosage?"
- "Build me a training program for strength and longevity"
- "Teach me about dopamine"
- "I want to improve my focus for deep work"

## Troubleshooting

- **Skills not showing:** Make sure the plugin path is correct and Claude Code has been restarted
- **Transcripts not found:** The plugin references data in relative paths — ensure the full wiki directory is present
- **Generic answers:** Try invoking a specific skill directly: `/ask-huberman:morning-routine-designer`

## Learn More

Visit [creativeintel.agency](https://creativeintel.agency) for more Ask [Creator] plugins.
