# Hi, I'm Ana 👋

### Senior Backend / Full Stack Engineer · Node.js · TypeScript · AWS · GraphQL

Software engineer with **8+ years in production systems**, most recently at **Allergan Data Labs (AbbVie)** and **Intel**, plus 2 years leading and mentoring engineering teams.

I work on the layer where reliability meets cost: event-driven services that don't drop messages, APIs that hold under load, and observability you can actually debug at 3am.

📍 Zaragoza, Spain · 🗣️ English & Spanish
💼 Open to backend and full-stack roles — hybrid in Zaragoza or remote from Spain

### 👉 [**My CV, as an interactive page**](https://ana-izaguirre.github.io/) 👈

Searchable, in two languages, downloadable as a one-page PDF. One static page with
no framework and no runtime dependencies, gated in CI on Lighthouse 100 across all
four categories and 100% test coverage. Each project opens into a case study. [Source](https://github.com/ana-izaguirre/ana-izaguirre.github.io)

---

## 🚀 Featured Projects

### [trainer-flow](https://github.com/ana-izaguirre/trainer-flow)
Telegram-based workout planning where the AI proposes and the trainer decides. The constraint is structural, not a policy: there is no `DRAFT → SENT` transition, so no routine can reach a client without a human approving it.

Built under **Spec Driven Development** — no code without an approved spec. A pure-domain `_core/` that the linter forbids from importing Deno, npm or `fetch`; **1,500+ tests**; **mutation testing** with a per-file policy in CI; 100% coverage on the authorization module, denied cases included.

**TypeScript · Deno · Supabase (PostgreSQL) · Gemini · Telegram · Stryker**

### [mcp-docs-search](https://github.com/ana-izaguirre/mcp-docs-search)
MCP server that gives AI agents keyword search over markdown docs. **One runtime dependency**, SQLite FTS5, no vector database and no API keys — plus a retrieval-evaluation harness that publishes its own metrics in CI. `mypy --strict` across source, tests and evals.

**Python · SQLite FTS5 · MCP · pytest · mypy**

### [latino-migra](https://github.com/ana-izaguirre/latino-migra) · [Live](https://latino-migra.vercel.app)
Web platform for Latin American students migrating: verified scholarships, visa guides with official sources, and a Gemini-powered assistant. A server-side proxy keeps the model keys out of the browser; a scheduled workflow refreshes scholarship deadlines on its own.

**React 19 · TypeScript · Express · Firestore · Vercel · Playwright**

### [prot-spam-sim](https://github.com/ana-izaguirre/prot-spam-sim) · [Live](https://ana-izaguirre.github.io/prot-spam-sim/)
Interactive simulator that makes an MPI parallelisation visible: why a triangular workload refuses to balance, and how blocking sends collapse at 128 processes. Companion to my master's thesis in High Performance Computing.

**Astro · TypeScript · Playwright**

---

## 🛠️ Tech Stack

<p>
<img alt="Node.js, TypeScript, Express, GraphQL, Python, PostgreSQL, MongoDB" src="https://skillicons.dev/icons?i=nodejs,ts,expressjs,graphql,python,postgresql,mongodb&perline=7" />
<br>
<img alt="AWS, Docker, Kubernetes, GitHub Actions, React, Angular, Supabase, Deno" src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,react,angular,supabase,deno&perline=8" />
</p>

**Also working with:**
Snowflake · Datadog · AWS SNS / SQS / Lambda · RabbitMQ · CI/CD (GitHub Actions) · Jest · Cypress

---

## 🤝 How I work

🤖 **AI-assisted development** — OpenCode, Claude Code and agentic coding tools in my daily workflow
📟 **Production ownership** — on-call rotation, incident response, Datadog alerting
👥 **Mentoring** — onboarding engineers into unfamiliar codebases
🌐 **Distributed teams** — 6+ years with US-based engineering orgs
📐 **Specs before code** — decisions written down and reviewed before they are implemented

---

## 📫 Connect

🌐 [ana-izaguirre.github.io](https://ana-izaguirre.github.io/) — interactive CV
💼 [LinkedIn](https://www.linkedin.com/in/ana-izaguirre/) — full experience and background
✉️ ana.izaguirrematamoros@gmail.com
