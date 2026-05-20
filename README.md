# Engineering Best Practices 2026

[![AgentSkills.io](https://img.shields.io/badge/AgentSkills.io-0.2-blue)](https://agentskills.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Version](https://img.shields.io/badge/version-2026.1.0-orange)](CHANGELOG.md)
[![Validate Skill](https://github.com/skylarng89/engineering-best-practices-skill/actions/workflows/validate.yml/badge.svg)](https://github.com/skylarng89/engineering-best-practices-skill/actions/workflows/validate.yml)

A comprehensive [AgentSkills.io](https://agentskills.io) skill for AI coding agents. Covers best practices across **16 languages and frameworks** — with security, performance, idempotency, concurrency, atomicity, observability, and accessibility baked in.

---

## What It Covers

| Stack       | Baseline                                           |
| ----------- | -------------------------------------------------- |
| Node.js     | 22 LTS / 24                                        |
| Next.js     | 15.2.3+                                            |
| NestJS      | 11+                                                |
| Java        | 21 LTS / 25 LTS                                    |
| Spring Boot | 4.0 (SB 3.5 supported)                             |
| Python      | 3.12+ / 3.13                                       |
| Elixir      | 1.17+ / OTP 27+                                    |
| Phoenix     | 1.7+                                               |
| Erlang      | OTP 27+                                            |
| Rust        | 1.80+ stable                                       |
| Go          | 1.23+ / 1.24                                       |
| React       | 19                                                 |
| Vue         | 3.5+                                               |
| Nuxt        | 4 / 3.15+                                          |
| Astro       | 5+                                                 |
| SQL / NoSQL | PostgreSQL, MySQL, MongoDB, Redis/Valkey, DynamoDB |

**Cross-cutting topics:** OWASP Top 10, zero trust auth, virtual threads (Java 25), supply-chain hardening, OpenTelemetry, WCAG 2.2 AA, idempotency keys, Saga pattern, pre-merge and pre-production checklists.

**Known CVEs and gotchas included:**

- Next.js CVE-2025-29927 — middleware auth bypass (patch + architectural lesson)
- Valkey 9.1 RC — pin to 9.0.x for production
- Spring Boot 3.4 EOL — upgrade path to 4.0

---

## Installation

<details>
<summary><strong>Claude Code</strong></summary>

**Via CLI (recommended)**

```bash
npx skills add skylarng89/engineering-best-practices-skill
```

**Manual**

```bash
mkdir -p ~/.claude/skills/engineering-best-practices-2026
curl -o ~/.claude/skills/engineering-best-practices-2026/SKILL.md \
  https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

</details>

<details>
<summary><strong>Cursor</strong></summary>

**Via CLI (recommended)**

```bash
npx skills add skylarng89/engineering-best-practices-skill
```

**Manual**

```bash
mkdir -p ~/.cursor/skills/engineering-best-practices-2026
curl -o ~/.cursor/skills/engineering-best-practices-2026/SKILL.md \
  https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

</details>

<details>
<summary><strong>Windsurf</strong></summary>

**Via CLI (recommended)**

```bash
npx skills add skylarng89/engineering-best-practices-skill
```

**Manual**

```bash
mkdir -p ~/.windsurf/skills/engineering-best-practices-2026
curl -o ~/.windsurf/skills/engineering-best-practices-2026/SKILL.md \
  https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

</details>

<details>
<summary><strong>Kilo Code</strong></summary>

**Via Kilo Marketplace UI** — search for `engineering-best-practices-2026` and click Install.

**Via CLI**

```bash
npx skills add skylarng89/engineering-best-practices-skill
```

**Manual**

```bash
mkdir -p ~/.kilo/skills/engineering-best-practices-2026
curl -o ~/.kilo/skills/engineering-best-practices-2026/SKILL.md \
  https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

</details>

<details>
<summary><strong>Goose (Block) / OpenCode / Codex CLI</strong></summary>

**Via CLI**

```bash
npx skills add skylarng89/engineering-best-practices-skill
```

**Manual** — download `SKILL.md` and place it in your agent's skills directory:

```bash
curl -O https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

Then follow your agent's documentation for loading local skill files.

</details>

<details>
<summary><strong>Any agent — raw download</strong></summary>

```bash
curl -O https://raw.githubusercontent.com/skylarng89/engineering-best-practices-skill/main/SKILL.md
```

Place `SKILL.md` anywhere your agent looks for skills, or paste its contents directly into your system prompt / project instructions.

</details>

<details>
<summary><strong>MCP Server (self-hosted / well-known discovery)</strong></summary>

If you host an MCP server, agents can discover and fetch this skill automatically via the `.well-known` endpoints:

```
GET /.well-known/skills/index.json
GET /.well-known/agent-skills/engineering-best-practices-2026/skill.md
```

Point your agent at your server URL and it will pick up the skill without manual installation.

</details>

---

## Usage

Once installed, the skill triggers automatically when you ask your agent to:

- Write, review, or refactor code in any supported stack
- Audit code for security issues
- Optimise performance or fix N+1 queries
- Set up a CI/CD pipeline
- Design a database schema

**Example prompts:**

```
Review this Spring Boot service for security issues.
Write a Next.js App Router page that fetches user data.
Design a PostgreSQL schema for a multi-tenant SaaS.
Set up a NestJS module with rate limiting and JWT auth.
```

---

## Compatibility

| Agent                       | Supported |
| --------------------------- | --------- |
| Claude Code                 | ✅        |
| Cursor                      | ✅        |
| Windsurf                    | ✅        |
| GitHub Copilot (agent mode) | ✅        |
| Kilo Code                   | ✅        |
| OpenCode                    | ✅        |
| Goose (Block)               | ✅        |
| Codex CLI                   | ✅        |

---

## Versioning

This skill uses [CalVer](https://calver.org): `YYYY.MINOR.PATCH`

See [CHANGELOG.md](CHANGELOG.md) for the full history.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## License

MIT © 2026 [Patrick Aziken](https://github.com/skylarng89) / [Upperloft Creations Limited](https://upperloftcreations.com)
