# 临书 (tmpbook)

Python developer working at the intersection of AI agents and practical, reliable tooling. I care about code that survives real-world edge cases — race conditions, lazy installs, and the bugs that only show up in production.

## What I'm working on

- Contributing to [hermes-agent](https://github.com/NousResearch/hermes-agent) — an open-source personal AI agent that runs the same core across a CLI, a messaging gateway (Telegram, Discord, Slack, and ~20 other platforms), a TUI, and a desktop app.
  - Recent fix: [rebind `TypeHandler` after lazy dependency install](https://github.com/NousResearch/hermes-agent/pull/87184) — fixed a poisoned module-state bug that silently broke Telegram reconnects for ~50 hours.
- AI agent infrastructure — lazy dependency management, gateway platform adapters, and making agent tooling robust enough to run unattended.

## Tech stack

- Languages: Python, TypeScript, Bash
- AI & agent tooling: OpenAI, LangChain, Anthropic
- Tools & platforms: Git, GitHub, Docker, Linux

## Quick facts

- I enjoy hunting down the "should never happen" bugs — the ones that only manifest after a restart races with a dependency reinstall.
- I believe good fixes cover the whole bug class, not just the one site a reporter happened to hit.
- Currently exploring: making agent systems more observable and self-healing.

## Stats

- 526 stars earned
- 146 forks
- 112 followers
- 53 public repos

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=tmpbook&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=tmpbook&theme=github_dark" />
</p>

*Open to interesting conversations about AI agents, Python, and open source.*
