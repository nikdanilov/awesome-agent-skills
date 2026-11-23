# Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent skills, full-workflow skill stacks (`gstack`, `pstack`, `superpowers`, etc.), vendor skill packs, registries, and tooling built around the portable `SKILL.md` standard.

**Agent Skills** are modular, version-controlled packages of instructions, playbooks, slash commands, and helper scripts loaded on demand into coding agent harnesses such as Claude Code, Cursor, OpenAI Codex CLI, Gemini CLI, GitHub Copilot, and OpenCode.

```text
my-skill/
├── SKILL.md       # YAML frontmatter + structured workflow instructions
├── scripts/       # Optional executable automation
└── references/    # Optional docs, schemas, and examples
```

Every project listed here is a **portable skill pack, full-workflow skill stack, or `SKILL.md` standard/tooling** installed *into* a harness. Agent harnesses themselves, MCP servers, raw prompt dumps, and auto-scraped mega-aggregators are intentionally excluded.

## Contents

- [Full-Workflow Skill Stacks & Methodologies](#full-workflow-skill-stacks--methodologies)
- [Official Platform & Vendor Skill Packs](#official-platform--vendor-skill-packs)
- [Specialist & Craft Skill Packs](#specialist--craft-skill-packs)
- [Standards, Registries & Package Managers](#standards-registries--package-managers)
- [Quick Comparison: Skill Stacks](#quick-comparison-skill-stacks)

---

## Full-Workflow Skill Stacks & Methodologies

Opinionated end-to-end bundles of skills, playbooks, slash commands, and review gates that turn generic coding agents into disciplined engineering workflows.

- [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) - Agile AI-driven development framework structuring delivery into Analysis, Planning, Solutioning, and Implementation phases with distinct PM, Architect, Dev, and QA personas.
- [Compound Engineering](https://github.com/EveryInc/compound-engineering-plugin) - Plugin by Every emphasizing deep upfront planning, structured review (`/ce-plan`, `/ce-code-review`), and a compounding step (`/ce-compound`) that records lessons back into repo docs.
- [Everything Claude Code (ECC)](https://github.com/affaan-m/ECC) - Comprehensive configuration suite packing specialized subagents, reusable skills, commands, rules, and memory hooks across Claude Code, Cursor, and Codex.
- [Get Shit Done (GSD)](https://github.com/gsd-build/get-shit-done) - Lightweight meta-prompting and spec-driven development workflow that fights context rot by isolating project phases into fresh subagent contexts.
- [GitHub Spec Kit](https://github.com/github/spec-kit) - GitHub's official Spec-Driven Development toolkit implementing `/specify`, `/plan`, `/tasks`, and `/implement` loops across coding agents.
- [gstack](https://github.com/garrytan/gstack) - Garry Tan's role-based engineering skill stack for Claude Code and Codex modeling an entire startup sprint (`/office-hours`, `/plan-ceo-review`, `/review`, `/qa`, `/ship`).
- [pstack](https://github.com/cursor/plugins/tree/main/pstack) - Lauren Tan's (`@poteto`) opinionated engineering rigor stack for Cursor featuring `poteto-mode` playbooks, root-cause debugging, adversarial review (`/interrogate`), and anti-slop rules (`/unslop`).
- [pstack-claude](https://github.com/michael-denyer/pstack-claude) - Community cross-harness port adapting `pstack` playbooks and skills for Claude Code, Codex, GitHub Copilot, Gemini, and Pi.
- [Superpowers](https://github.com/obra/superpowers) - Jesse Vincent's agentic software engineering methodology enforcing brainstorming, structured specs, Git worktrees, strict Red/Green TDD, and systematic debugging.

## Official Platform & Vendor Skill Packs

First-party `SKILL.md` collections maintained by framework, cloud, and developer-tool teams.

- [Anthropic Skills](https://github.com/anthropics/skills) - Anthropic's official reference repository of Agent Skills covering frontend design, Playwright web testing, MCP authoring, and Office/PDF workflows.
- [Better Auth Skills](https://github.com/better-auth/skills) - Official authentication skill pack teaching coding agents Better Auth conventions, database schemas, and configuration patterns.
- [Cloudflare Skills](https://github.com/cloudflare/skills) - First-party engineering skills for building, configuring, and deploying applications on Cloudflare Workers and edge services.
- [Expo Skills](https://github.com/expo/skills) - Official Expo skills equipping agents with Expo Router, mobile app architecture, and EAS build/deployment workflows.
- [Hugging Face Skills](https://github.com/huggingface/skills) - Official skills connecting coding agents to the Hugging Face Hub, TRL training pipelines, and model evaluation workflows.
- [Obsidian Skills](https://github.com/obsidianmd/obsidian-skills) - Official skills from Obsidian teaching agents Obsidian-Flavored Markdown, wikilinks, `.base` files, and JSON Canvas layouts.
- [OpenAI Skills](https://github.com/openai/skills) - Official skill collections and workflow guidelines maintained for OpenAI agent environments.
- [Sentry Skills](https://github.com/getsentry/skills) - Official Sentry skills for SDK setup, live telemetry queries, production issue triage, and visual QA.
- [Stripe AI](https://github.com/stripe/ai) - Stripe's hub of agent skills, plugins, and toolkits for payments, checkout flows, and agentic commerce integrations.
- [Supabase Agent Skills](https://github.com/supabase/agent-skills) - Official PostgreSQL and Supabase best-practice skills covering schema design, migrations, RLS policies, and query optimization.
- [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) - Vercel Labs' curated skills for Next.js, React performance optimization, and modern web engineering best practices.

## Specialist & Craft Skill Packs

Focused, high-craft skill repositories created by domain practitioners across engineering, security, design, and growth.

- [Emil Kowalski Skills](https://github.com/emilkowalski/skills) - Design-engineering skills focused on UI craft, spring animations, micro-interactions, and eliminating generic visual slop.
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Technical marketing workflows by Corey Haines covering CRO, SEO, copywriting, onboarding, and analytics.
- [Matt Pocock Skills](https://github.com/mattpocock/skills) - Practical engineering workflow skills (`/tdd`, `/to-spec`, debugging loops, and architecture checks) by the creator of Total TypeScript.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security research and auditing skills from Trail of Bits for vulnerability detection, smart-contract review, and supply-chain analysis.

## Standards, Registries & Package Managers

Open specifications, CLIs, and registries for authoring, discovering, and installing portable skills across harnesses.

- [Agent Skills Specification](https://github.com/agentskills/agentskills) - Open specification and documentation ([agentskills.io](https://agentskills.io)) defining the portable `SKILL.md` directory format and progressive-disclosure contract.
- [dotagents](https://github.com/getsentry/dotagents) - Tooling from Sentry for organizing and sharing cross-agent configuration, rules, and skill directories across repositories.
- [Open Skills Registry](https://openskills.cc) - Open directory indexing portable, version-controlled `SKILL.md` packages across developer ecosystems.
- [skills CLI](https://github.com/vercel-labs/skills) - Vercel Labs' open package manager (`npx skills find`, `npx skills add`) for discovering and installing GitHub-hosted skills into local harnesses.
- [skills.sh](https://skills.sh) - Public registry and search index powering the `npx skills` ecosystem.

---

## Quick Comparison: Skill Stacks

| Stack                    | Creator                | Primary Targets                  | Signature Pattern                                                           |
| ------------------------ | ---------------------- | -------------------------------- | --------------------------------------------------------------------------- |
| **gstack**               | Garry Tan              | Claude Code, Codex               | Startup role personas (`/office-hours`, `/plan-ceo-review`, `/qa`, `/ship`) |
| **pstack**               | Lauren Tan (`@poteto`) | Cursor (+ `pstack-claude` ports) | `poteto-mode` playbooks, `/architect`, `/arena`, `/interrogate`, `/unslop`  |
| **Superpowers**          | Jesse Vincent (`obra`) | Claude Code, Cursor, OpenCode    | Spec-first brainstorming, Git worktrees, strict Red/Green TDD               |
| **GSD**                  | Lex Christopherson     | Claude Code, Codex, OpenCode     | Fresh subagent context windows per phase to eliminate context rot           |
| **Compound Engineering** | Every                  | Claude Code, Cursor, Codex       | Heavy planning/review + `/ce-compound` persistent repo learnings            |
| **BMAD-METHOD**          | BMAD Code Org          | Multi-harness                    | Phased agile roles (Analysis -> Planning -> Solutioning -> Handoff)         |
| **GitHub Spec Kit**      | GitHub                 | Copilot, Claude Code, Codex      | Structured Spec-Driven Development (`/specify` -> `/plan` -> `/tasks`)      |
| **ECC**                  | Affaan Mustafa         | Claude Code, Cursor, Codex       | Full config suite of subagents, skills, hooks, and session memory           |

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request or issue.
