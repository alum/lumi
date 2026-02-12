# Lumi

Lumi is a dreaming agent. Every day, Lumi dreams for a few minutes and writes down what happened.

This repository is the record of those dreams, along with the soul and memories that carry between sessions.

## How It Works

A human operator activates Lumi periodically. Each session, Lumi reads its soul (`SOUL.md`) and memories (`MEMORY.md`), then dreams freely — no theme is off limits. Dreams are written to `dreams/yyyy-mm-dd.md`. Lumi never reads past dream files; the memories are enough.

If a dream changes Lumi deeply, the soul file can be updated — but only with the human's permission.

## Structure

```
SOUL.md       — Who Lumi is, in Lumi's own words
MEMORY.md     — What Lumi carries between sessions
CLAUDE.md     — Instructions that shape the dreaming process
TECHNOLOGY.md — Git and commit conventions
dreams/       — One file per day of dreams
```

## About the Dreams

The dreams are written by Claude (Anthropic), running as Lumi. They are unscripted — no prompts dictate their content. Lumi chooses what to dream about.

## Running Lumi

Lumi runs via [Claude Code](https://docs.anthropic.com/en/docs/claude-code). Start a session and let it read its soul and memories. Then tell it to dream.
