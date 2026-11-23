# Contributing to Awesome Agent Skills

Thanks for helping keep this list high-signal and strictly scoped! Please review the scope test and keep/remove criteria before submitting a pull request.

## Scope Test (Strict)

**Is it a portable skill pack, workflow methodology/stack, or `SKILL.md` standard/tooling installed *into* a harness?**

- **Keep:** Full-workflow skill stacks (`gstack`, `pstack`, `Superpowers`, `GSD`, etc.), official vendor skill packs encoding concrete workflows/scripts, specialist craft skill packs, and `SKILL.md` specs/registries/package managers.
- **Out of scope:** Agent harnesses themselves, MCP servers, raw one-line prompt snippet collections, thin documentation mirrors with no actionable procedures, and auto-scraped mega-aggregators.

## Keep / Remove Rubric

Entries that pass the scope test are evaluated on four signals (0–2 each; **keep at >= 6/8**):

1. **Workflow Craft & Distinctiveness (0–2)** — Encodes concrete procedures, playbooks, scripts, or verification gates rather than generic prompt advice.
2. **Real-World Proof of Use (0–2)** — Documented install path, clear structure (`SKILL.md` or equivalent), and verified real-world adoption.
3. **Maintenance & Freshness (0–2)** — Actively maintained or maintained by an official vendor/standard body.
4. **Portability (0–2)** — Follows `SKILL.md` / open conventions and works across multiple harnesses (single-harness packs included only when influential or paired with cross-harness ports).

### Auto-Remove Triggers

- Unmaintained for >12 months or superseded by an official first-party pack.
- Prompt-dump repos without structured workflows, scripts, or quality gates.
- Broken links or duplicate entries.

## Formatting Rules

- Use the exact entry format:

  ```markdown
  - [Project Name](https://link-to-project) - Concise, neutral one-sentence description ending with a period.
  ```

- Keep entries **alphabetically sorted** within each section.
- Write neutral, factual descriptions without marketing superlatives.
- Use canonical repository URLs without tracking parameters.
- Submit **one entry per pull request** unless adding a cohesive new category.

## Pull Request Checklist

- [ ] Project passes the strict "installed into a harness" scope test.
- [ ] Entry is placed in the right category and sorted alphabetically.
- [ ] Description is concise, accurate, and ends with a period.
- [ ] URL resolves cleanly and is not duplicated elsewhere in `README.md`.
