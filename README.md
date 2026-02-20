# /monetize

A Claude Code skill that sets up the [Paid](https://www.paid.ai) SDK in your project — handling pricing, billing, and usage tracking for AI agents.

## Setup

Copy `monetize.md` into the `.claude/commands/` directory at the root of your repo:

```bash
mkdir -p .claude/commands
cp monetize.md .claude/commands/monetize.md
```

## Usage

Run the skill from Claude Code:

```
/monetize
```

This will walk you through a step-by-step integration with Paid, including environment detection, SDK installation, autoinstrumentation, and signal setup.
