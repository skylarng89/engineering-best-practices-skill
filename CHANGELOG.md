# Changelog

All notable changes to this skill are documented here.  
Format: [CalVer](https://calver.org) — `YYYY.MINOR.PATCH`

---

## [2026.1.0] — 2026-05-20

### Added

- Initial public release
- Coverage for 16 stacks: Node.js, Next.js, NestJS, Java, Spring Boot, Python, Elixir, Phoenix, Erlang, Rust, Go, React, Vue, Nuxt, Astro, SQL/NoSQL
- Universal principles: zero trust, OWASP Top 10, idempotency, atomicity/Saga, concurrency, OpenTelemetry, WCAG 2.2 AA
- Per-stack version baselines (2026-accurate)
- Known CVEs and gotchas:
  - Next.js CVE-2025-29927 — middleware auth bypass mitigation
  - Valkey 9.1 RC — production pin to 9.0.x
  - Spring Boot 3.4 EOL — upgrade path to 4.0
- Java 25 virtual threads + Structured Concurrency guidance
- Spring Boot 4.0 / Spring Framework 7 patterns
- Nuxt 4 `srcDir: 'app/'` layout
- Astro 5 islands architecture
- Supply-chain attack hardening (Node.js, Python, Rust, Go)
- Pre-merge and pre-production checklists
- AgentSkills.io 0.2 compliant frontmatter
- MIT license
- `.well-known` discovery endpoints
- GitHub Actions: validate + release workflows
- Eval scenarios for trigger and output correctness

---

<!-- next release -->
<!-- ## [2026.2.0] — 2026-MM-DD -->
