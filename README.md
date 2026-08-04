## Nick Fulton

**I don't demo AI to people. I show them my Tuesday.**

Product manager in enterprise software. Founder of an AI consulting
practice. I build agentic systems on Claude Code and run my job and my
life on them, in production, with verification behind them.

| | |
|---|---|
| **Client work** | 2 engagements since Feb 2026. One delivered through full handoff, one in delivery. Fixed fee, quantified success metric, designed to end. |
| **At work** | Co-leading an AI operating model rollout across my product team. Shared knowledge store, three adopted process templates, a rubric-based grader in daily use. |
| **At home** | 40+ scheduled automations across two isolated instances, under one registry with freshness checks and run-truth monitoring. |

### Start here

- **[agentic-systems-portfolio](https://github.com/njfulton/agentic-systems-portfolio)**
  — how the whole thing fits together: sanitized skill examples,
  orchestration code, and the guardrail design behind 40+ production
  automations.
- **[x-mcp](https://github.com/njfulton/x-mcp)** — an MCP server I use
  every day for research feeds: RSS, X, arXiv, Hacker News, Reddit, and
  YouTube transcripts. Python. The tests fake all HTTP, so the suite runs
  offline and deterministically.
- **[workout-app](https://github.com/njfulton/workout-app)** — an
  ordinary app built the way everything here gets built. Kotlin, Compose,
  Room, 138 commits of real iterative history. Claude Code doing the
  work, me doing the deciding.

### How I think about building this

**Guardrails as architecture, not policy.** The MCP layer blocks deletes
and external sends outright, so a prompt can't talk its way past them.
Finance automations propose but cannot move money. My personal wiki sits
behind a structural privacy gate: its pointer is deliberately absent from
every business configuration, so it can't leak by accident.

**Verification before trust.** Every registry entry declares an evidence
path on disk, so health checks stat artifacts instead of believing a
prior claim. Golden-set regression evals rerun on any skill edit. Before
I trusted the reviewer subagent that closes my highest-stakes pipelines,
I planted defects in test drafts and checked that it caught them.

**Adversarial verification at scale.** Fan out finders by dimension,
dedupe in plain code, then independent skeptics try to refute every
finding before a human sees it, defaulting to "refuted" on uncertainty.
At work this scored a 744-item backlog across 50 clusters; the skeptic
pass cut a 100-ticket removal list to 42 upheld.

**Designed to end.** Client engagements train the client's staff first,
so the system keeps running after I'm gone. No retainer dependency.

Most of the systems stay private: they're full of my actual life and my
employer's work. The patterns are public, and I'm glad to walk through
any of them live.

njfulton@gmail.com ·
[LinkedIn](https://www.linkedin.com/in/njfulton)
