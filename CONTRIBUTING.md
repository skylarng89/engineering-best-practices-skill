# Contributing

Contributions are welcome — corrections, new stack coverage, updated version baselines, and additional gotchas all help.

---

## Types of Contributions

| Type            | Examples                                                        |
| --------------- | --------------------------------------------------------------- |
| **Bug fix**     | Wrong version baseline, broken code snippet, incorrect guidance |
| **Update**      | New LTS release, deprecated API, new CVE                        |
| **New content** | Additional stack section, missing best practice                 |
| **Quality**     | Eval scenarios, CI improvements                                 |

---

## Process

1. **Open an issue first** for anything beyond a typo fix — describe the change and why.
2. Fork the repo and create a branch: `fix/nextjs-cve-update`, `feat/bun-section`, etc.
3. Make your changes in `SKILL.md` (and any other relevant files).
4. Update `CHANGELOG.md` under a new `[Unreleased]` section.
5. Bump the version in the `SKILL.md` frontmatter if the change is substantive:
   - Patch (`2026.1.1`): corrections, version updates, minor additions
   - Minor (`2026.2.0`): new stack section, significant new content
6. Open a PR — the validate workflow must pass before review.

---

## Frontmatter Rules

The `SKILL.md` frontmatter must comply with the [AgentSkills.io 0.2 spec](https://agentskills.io/specification):

- `name`: lowercase, hyphens only, no leading/trailing hyphens
- `description`: must include usage triggers and keywords; used by agents for skill discovery
- `license`: must remain `MIT`
- `metadata.version`: CalVer `YYYY.MINOR.PATCH`

Run validation locally before pushing:

```bash
npx skills validate SKILL.md
```

---

## Style Guide

- Keep instructions **agent-readable**: imperative, specific, no fluff.
- Use code blocks for all examples.
- Reference specific versions — avoid "latest".
- Cite CVEs by number where applicable.
- Keep the Universal Principles section stack-agnostic.

---

## Code of Conduct

Be respectful. Technical disagreements are fine; personal attacks are not.

---

## Questions?

Open an issue or email [patrick@upperloftcreations.com](mailto:patrick@upperloftcreations.com).
