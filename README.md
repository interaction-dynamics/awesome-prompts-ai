# Awesome Prompts AI

Curated list of prompts and AI documentation

## Opinionated Claude Setup

A batteries-included starting point to initialize Claude Code with the plugins we reach for on every project. Run these from your repo root:

```sh
npx plugins add vercel/vercel-plugin
npx plugins add caveman
npx plugins add rtk
npx plugins add nextjs-plugin
```

What each one gives you:

- **[vercel/vercel-plugin](https://vercel.com/ai-gateway)** — Wires Claude Code into the Vercel AI Gateway for deploys, env management, and preview URLs without leaving the terminal.
- **[caveman](https://lnkd.in/egZNirCW)** — Forces caveman-style terse output; ~75% fewer output tokens with no accuracy loss.
- **[rtk](https://lnkd.in/eMYtBZYZ)** — Rust Token Killer proxy that filters terminal noise; 60–90% reduction, zero dependencies.
- **nextjs-plugin** — Next.js-aware scaffolding, routing conventions, and server-component hints for App Router projects.


- [AI gateway](https://vercel.com/ai-gateway)
- [AI Agents orchestrator](https://botpress.com/)
- [article about ai agents orchestration](https://botpress.com/blog/ai-agent-orchestration)
- [Remoto](https://www.remoto.sh/): to control your terminal from your mobile phone
- [Claude code write/edit](https://ai-sdk.dev/providers/community-providers/claude-code)
- [Github mcp server](https://github.com/github/github-mcp-server)
- [Python atomic agents framework](https://github.com/BrainBlend-AI/atomic-agents)
- [Reddit about AI Agent framework](https://www.reddit.com/r/AI_Agents/comments/1kjowzp/whats_the_best_framework_for_productiongrade_ai)
- [Praison AI Agents framework](https://docs.praison.ai/)
- [KaibanJS AI Agents framework](https://docs.kaibanjs.com/)
- [MastraAI](https://mastra.ai)
- [Claude Code Skills](https://code.claude.com/docs/en/skills)

## Claude Code Skills

Prompts, plugins, and skills to extend Claude Code's capabilities.

1. **[Superpowers](https://github.com/obra/superpowers)** — An agentic skills framework & software development methodology shipped as a folder of markdown files; 14 skills covering brainstorming, TDD, planning, and more. 150K+ GitHub stars.

2. **[Frontend Design](https://claude.com/plugins/frontend-design)** *(by Anthropic)* — Official Anthropic skill that pushes Claude to make deliberate aesthetic choices before writing any code; bans overused fonts and enforces bold typography, purposeful color, and intentional animation. 277K+ installs.

3. **[Code Review](https://claude.com/plugins/code-review)** *(by Anthropic)* — Official Anthropic code review plugin; multiple agents analyze diffs in parallel, each looking for a different class of issue, then post inline PR comments ranked by severity.

4. **[Security Review](https://github.com/anthropics/claude-code-security-review)** *(by Anthropic)* — AI-powered GitHub Action that runs on every PR to detect SQL injection, XSS, auth flaws, and other vulnerabilities; also available as a `/security-review` slash command in the terminal.

5. **[Claude Mem](https://github.com/thedotmack/claude-mem)** — Persistent memory MCP plugin that captures session context (architecture decisions, conventions, bug fixes) and injects relevant memories at the start of future sessions. Everything stored locally in `.claude-mem/`.

6. **[claude-stack-plugin](https://github.com/bdarbaz/claude-stack-plugin)** — Unified plugin that merges Superpowers, GSD, Compound, and more into one install; ships 27 skills, 12 agents, 6 hooks, and 8 rules under a single `/s:` namespace.

7. **[deepsec](https://www.npmjs.com/package/deepsec)** (`npx deepsec`) — Zero-config security scanner for Claude Code projects; runs via `npx deepsec` to audit your codebase for secrets, misconfigurations, and vulnerabilities without any install step.

## Token Optimization

Tools and techniques to reduce token usage and context size.

1. **[Caveman Claude](https://lnkd.in/egZNirCW)** — Makes Claude talk like a caveman; slashes 75% of output tokens with zero loss in accuracy.

2. **[RTK (Rust Token Killer)](https://lnkd.in/eMYtBZYZ)** — A blazing fast proxy that filters terminal output; 60-90% reduction and completely dependency-free.

3. **[Code Review Graph](https://lnkd.in/eERHS2Si)** — Claude reads only what matters using a Tree-sitter graph; an unbelievable 49x token reduction on huge monorepos.

4. **[Context Mode](https://lnkd.in/eYKNAtss)** — Sandboxes raw output into SQLite instead of your context; a staggering 98% context reduction on logs & GitHub.

5. **[Claude Token Optimizer](https://lnkd.in/enUerETF)** — Brilliant setup prompts that optimize any project; 90% token savings, taking docs from 11K to 1.3K.

6. **[Token Optimizer](https://lnkd.in/eCgcwWMS)** — Hunts down the invisible ghost tokens eating your context; fully restores and protects your context quality.

7. **[Token Optimizer MCP](https://lnkd.in/eTieqZzR)** — Adds aggressive caching and compression to your MCP tools; 95%+ token reduction through pure intelligence.

8. **[Claude Context](https://lnkd.in/ewTqDbYh)** — Zilliz's hybrid vector search MCP; makes your entire codebase the context for 40% less cost.

9. **[Claude Token Efficient](https://lnkd.in/e6vCHuES)** — Just drop one CLAUDE.md file into your repo; enforces strict terseness with zero code changes.

10. **[Token Savior](https://lnkd.in/ed63xR3F)** — Navigates your code by symbols, not giant files; 97% reduction on code navigation with persistent memory.
