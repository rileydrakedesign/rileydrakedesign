# Hi, I’m Riley! 👋

I build production systems where LLMs and agents do real work, and the infrastructure that keeps them reliable. Lead developer and DevOps lead at FAM Brands; founder of Ontology CPG. Los Angeles.

## Production work *(private)*

**Heimdall** · FAM Brands · React, Node, Python, Postgres, Redis, Azure
Apparel product-lifecycle platform, from market research to a style in PLM. Scrapers, a vision-model Chrome extension (537 retailers, no per-site parsers), and a colorway harvester feed a 15,000-product library with price history on every change; a sample workflow runs 9,400+ purchase requests; AI Studio runs design tools on an async multi-provider render pipeline (44,000+ jobs, 99% completed). One Postgres schema (120+ tables, 57 triggers enforcing business rules) behind 537 endpoints. 87 monthly active users; I wrote ~half of its 650+ merged PRs.

**Agent-CI** · FAM Brands · GitHub Actions, Azure, Claude Code
Git workflow as a protocol for humans and parallel Claude Code sessions: stateless skills for collision checks across PRs and worktrees, lane routing, and a merge gate; Azure slot deploys with health-checked automatic rollback, OIDC-only auth. Trunk went from 5% to 100% PR-driven; merged PRs from 2.7 to ~27/week; 2 reverts in 658 PRs.

**Agent Brain Platform** · Ontology CPG · TypeScript, Python/FastAPI, Postgres, Next.js, Cloudflare Workers, Claude Managed Agents
Agentic ERP for a CPG brand selling into Target, Albertsons, UNFI, and KeHE. Claude agents maintain a Git-versioned company knowledge base, where every edit is a PR gated by ontology-lint and provenance CI, and draft work against Postgres without ever holding a credential: the orchestrator checks each call against a 96-view read surface and runs it as bound-parameter SQL on a read-only role. Five services, ~340K lines, 1,888 merged PRs, ~4,850 tests; two-person team, production in ~3 months.

## Open source

**[agentctl](https://github.com/rileydrakedesign/agentctl)** · TypeScript, MCP SDK
Static analysis for agent context: connects to MCP servers, budgets token cost per model, flags redundant tools and contradictory instructions, and fails CI when context regresses. 153 tests.

**[wikiforge](https://github.com/rileydrakedesign/wikiforge)** · TypeScript · on npm as `wforge-cli`
Scaffolds LLM-maintained knowledge bases for Claude Code, Cursor, or Codex: agent personas, workflow skills, and lifecycle rules (supersession, decay and re-verification, contradiction flags), with maturity gates that keep autonomous mode off until the wiki is large enough. 32 tests, CI on Node 18/20/22.

## Other projects

**[Agents for X](https://github.com/rileydrakedesign/agents-for-x)** · Next.js, Supabase, Redis · retired
LLM SaaS on a 5-provider gateway with token-budget admission, Retry-After-aware backoff, and per-provider circuit breakers; 33-tool MCP server on npm. 245 tests.

**[AIStudyBuddy](https://github.com/rileydrakedesign/AIStudyBuddy)** · React, Node, Python/FastAPI, MongoDB Atlas · retired
RAG study assistant with hybrid vector and keyword search merged by reciprocal rank fusion, and an intent router (regex first, a small-model tiebreak) that picks a retrieval profile per question; answers cite and link the source page. Shipped to students, with a Canvas LMS integration.

---

[rileydrakedesign@gmail.com](mailto:rileydrakedesign@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rileydrake-ai) · Open to FDE, agent engineering, and AI platform roles
