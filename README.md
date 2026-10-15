# Hi, I’m Riley 👋

**AI engineer.** I build production systems where LLMs and agents do real work, and the infrastructure that keeps them reliable.

Lead developer & DevOps lead at **FAM Brands** · Founder of **Ontology CPG** · Los Angeles

[Email](mailto:rileydrakedesign@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rileydrake-ai) · Open to FDE, agent engineering, and AI platform roles

---

## Production work

### Heimdall
**FAM Brands** · Apparel product-lifecycle platform, from market research to a style in PLM
`React` `Node` `Python` `Postgres` `Redis` `Azure`

- **Intelligence:** nightly scrapers, plus a vision-model Chrome extension that covers 537 retailers with no per-site parsers
- **Operations:** end-to-end sample purchasing (approvals, orders, returns, refunds) for 9,400+ requests
- **Design:** AI Studio on an async multi-provider render pipeline, 44,000+ jobs at 99% completion
- **Platform:** one Postgres schema (120+ tables, 57 triggers enforcing business rules) behind 537 endpoints

> 87 monthly users · 15k products tracked · I wrote ~half of 650+ merged PRs

### Agent-CI
**FAM Brands** · Delivery platform for a team of humans and parallel Claude Code sessions
`GitHub Actions` `Azure` `Claude Code` `OIDC`

- **Coordination:** stateless skills for collision checks across PRs and worktrees, lane routing, and a merge gate
- **Delivery:** 18 workflows; Azure slot deploys with health-checked automatic rollback; no static secrets
- **Scope:** coordination advises but never blocks; AI review is comment-only

> 5% → 100% PR-driven trunk · 2.7 → ~27 merged PRs/week · 2 reverts in 658 PRs

### Agent Brain Platform
**Ontology CPG** · Agentic ERP for a CPG brand selling into Target, Albertsons, UNFI, and KeHE
`TypeScript` `FastAPI` `Postgres` `Next.js` `Cloudflare Workers` `Claude Managed Agents`

- **Knowledge as code:** agents edit a Git-versioned company wiki only through PRs gated by ontology and provenance CI
- **Zero-credential agents:** every data call is checked against a 96-view read surface and run as bound SQL on a read-only role
- **Five services:** orchestrator, data plane, operator console, MCP connector, knowledge base

> ~340K lines · 1,888 merged PRs · ~4,850 tests · production in ~3 months with a two-person team

---

## Open source

| Project | What it does | Stack |
| --- | --- | --- |
| **[agentctl](https://github.com/rileydrakedesign/agentctl)** | Static analysis for agent context: token budgets per model, redundant MCP tools, contradictory instructions, and a CI gate on regressions. 153 tests. | TypeScript, MCP SDK |
| **[wikiforge](https://github.com/rileydrakedesign/wikiforge)** | `npx wforge-cli init` scaffolds LLM-maintained wikis with lifecycle rules and maturity gates on autonomous mode. On npm. | TypeScript |

## Other projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[Agents for X](https://github.com/rileydrakedesign/agents-for-x)** | LLM SaaS on a 5-provider gateway with token-budget admission and per-provider circuit breakers; 33-tool MCP server on npm. 245 tests. *Retired.* | Next.js, Supabase, Redis |
| **[AIStudyBuddy](https://github.com/rileydrakedesign/AIStudyBuddy)** | RAG study assistant: hybrid vector and keyword search with reciprocal rank fusion, intent-routed retrieval, page-level citations. *Retired.* | React, Node, FastAPI, MongoDB |
