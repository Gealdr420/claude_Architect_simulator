# Claude Architect Simulator (CCAR-F Field Manual)

An interactive study console for the **Claude Certified Architect – Foundations (CCAR-F)** exam, in one self-contained web page ([`index.html`](index.html)).

## Open it

Download or clone the repo and open `index.html` in any modern browser. It needs no install or server; it only loads fonts from Google Fonts. Your study progress and drill score are saved in that browser.

## What's inside

| Tab | What it does |
|---|---|
| **Notes** | 55 topic notes across the five exam domains (weights 27/20/20/18/15%): what each concept is, when and where to use it, keywords, the "exam lens" (how it's tested and the usual trap), and a reference snippet. Tick topics as studied. |
| **Live flows** | 21 step-through animated diagrams: the agent loop, tool use, orchestrator and subagents, pipelines, hooks, CLAUDE.md loading, skills, CI, MCP, RAG, prompt caching, batches, compaction and more. |
| **Command reference** | 136 searchable entries: Claude Code CLI flags, slash commands, settings files, hook events and exit codes, frontmatter, Agent SDK, Claude API parameters, MCP methods. |
| **When to use what** | A comparison of Claude Code extension points, plus 29 scenario → decision cards. |
| **Drill** | 38 exam-style scenario questions with explanations, filters (unanswered / missed), shuffle and score. |
| **Making of** | A replay of the Claude Code session that built the page, one model call at a time: an agent-loop state graph whose nodes feed a live context map, a call inspector (context window, payload, harness loop), framework layers, orchestration view and token budget. |

Figures and product details reflect Claude Code and the Claude API as of 2026. Features change, so check the official documentation before relying on an exact flag or limit.
