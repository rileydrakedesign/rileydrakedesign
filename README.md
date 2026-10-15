# Hi, I’m Riley! 👋

**AI engineer.** I build production systems where LLMs and agents do real work, and the infrastructure that keeps them reliable.

Lead developer & DevOps lead at **FAM Brands** · Founder of **Ontology CPG** · Los Angeles

[Email](mailto:rileydrakedesign@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rileydrake-ai) · Open to FDE, agent engineering, and AI platform roles

---

## Production work

### Heimdall
**FAM Brands** · Apparel product-lifecycle platform, from market research to a style in PLM

![React](https://img.shields.io/badge/React-1F2328?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-1F2328?style=flat-square&logo=nodedotjs&logoColor=5FA04E) ![Python](https://img.shields.io/badge/Python-1F2328?style=flat-square&logo=python&logoColor=3776AB) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F2328?style=flat-square&logo=postgresql&logoColor=4169E1) ![Redis](https://img.shields.io/badge/Redis-1F2328?style=flat-square&logo=redis&logoColor=FF4438) ![Azure](https://img.shields.io/badge/Azure-1F2328?style=flat-square)

- **Intelligence:** nightly scrapers, plus a vision-model Chrome extension that covers 537 retailers with no per-site parsers
- **Operations:** end-to-end sample purchasing (approvals, orders, returns, refunds) for 9,400+ requests
- **Design:** AI Studio on an async multi-provider render pipeline, 44,000+ jobs at 99% completion
- **Platform:** one Postgres schema (120+ tables, 57 triggers enforcing business rules) behind 537 endpoints

> 87 monthly users · 15k products tracked · I wrote ~half of 650+ merged PRs

### Agent-CI
**FAM Brands** · Delivery platform for a team of humans and parallel Claude Code sessions

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1F2328?style=flat-square&logo=githubactions&logoColor=2088FF) ![Azure](https://img.shields.io/badge/Azure-1F2328?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude%20Code-1F2328?style=flat-square&logo=claude&logoColor=D97757) ![OIDC](https://img.shields.io/badge/OIDC-1F2328?style=flat-square&logo=openid&logoColor=F78C40)

- **Coordination:** stateless skills for collision checks across PRs and worktrees, lane routing, and a merge gate
- **Delivery:** 18 workflows; Azure slot deploys with health-checked automatic rollback; no static secrets
- **Scope:** coordination advises but never blocks; AI review is comment-only

> 5% → 100% PR-driven trunk · 2.7 → ~27 merged PRs/week · 2 reverts in 658 PRs

### Agent Brain Platform
**Ontology CPG** · Agentic ERP for a CPG brand selling into Target, Albertsons, UNFI, and KeHE

![TypeScript](https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=3178C6) ![FastAPI](https://img.shields.io/badge/FastAPI-1F2328?style=flat-square&logo=fastapi&logoColor=009688) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F2328?style=flat-square&logo=postgresql&logoColor=4169E1) ![Next.js](https://img.shields.io/badge/Next.js-1F2328?style=flat-square&logo=nextdotjs&logoColor=FFFFFF) ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-1F2328?style=flat-square&logo=cloudflareworkers&logoColor=F38020) ![Claude Managed Agents](https://img.shields.io/badge/Claude%20Managed%20Agents-1F2328?style=flat-square&logo=claude&logoColor=D97757) ![MCP](https://img.shields.io/badge/MCP-1F2328?style=flat-square&logo=modelcontextprotocol&logoColor=FFFFFF)

- **Knowledge as code:** agents edit a Git-versioned company wiki only through PRs gated by ontology and provenance CI
- **Zero-credential agents:** every data call is checked against a 96-view read surface and run as bound SQL on a read-only role
- **Five services:** orchestrator, data plane, operator console, MCP connector, knowledge base

> ~340K lines · 1,888 merged PRs · ~4,850 tests · production in ~3 months with a two-person team

---

## Open source

**[agentctl](https://github.com/rileydrakedesign/agentctl)** · Static analysis for agent context: token budgets per model, redundant MCP tools, contradictory instructions, and a CI gate on regressions.<br>
![TypeScript](https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=3178C6) ![MCP](https://img.shields.io/badge/MCP-1F2328?style=flat-square&logo=modelcontextprotocol&logoColor=FFFFFF)

**[wikiforge](https://github.com/rileydrakedesign/wikiforge)** · `npx wforge-cli init` scaffolds LLM-maintained wikis with lifecycle rules and maturity gates on autonomous mode.<br>
![TypeScript](https://img.shields.io/badge/TypeScript-1F2328?style=flat-square&logo=typescript&logoColor=3178C6) ![npm](https://img.shields.io/badge/npm-1F2328?style=flat-square&logo=npm&logoColor=CB3837)

## Other projects

**[Agents for X](https://github.com/rileydrakedesign/agents-for-x)** · LLM SaaS on a 5-provider gateway with token-budget admission and circuit breakers; 33-tool MCP server on npm. *Retired.*<br>
![Next.js](https://img.shields.io/badge/Next.js-1F2328?style=flat-square&logo=nextdotjs&logoColor=FFFFFF) ![Supabase](https://img.shields.io/badge/Supabase-1F2328?style=flat-square&logo=supabase&logoColor=3FCF8E) ![Redis](https://img.shields.io/badge/Redis-1F2328?style=flat-square&logo=redis&logoColor=FF4438) ![Stripe](https://img.shields.io/badge/Stripe-1F2328?style=flat-square&logo=stripe&logoColor=635BFF) ![MCP](https://img.shields.io/badge/MCP-1F2328?style=flat-square&logo=modelcontextprotocol&logoColor=FFFFFF)

**[AIStudyBuddy](https://github.com/rileydrakedesign/AIStudyBuddy)** · RAG study assistant with hybrid search, reciprocal rank fusion, intent-routed retrieval, and page-level citations. *Retired.*<br>
![React](https://img.shields.io/badge/React-1F2328?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-1F2328?style=flat-square&logo=nodedotjs&logoColor=5FA04E) ![FastAPI](https://img.shields.io/badge/FastAPI-1F2328?style=flat-square&logo=fastapi&logoColor=009688) ![MongoDB](https://img.shields.io/badge/MongoDB-1F2328?style=flat-square&logo=mongodb&logoColor=47A248)
