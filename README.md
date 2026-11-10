# Claude Best Practices Skill

A practical reference for improving modern web application security, browser compatibility, performance, and code quality. Use this skill when reviewing a web project, modernizing implementation patterns, auditing security, or checking production readiness.

## What It Covers

- **Security:** HTTPS, HSTS, Content Security Policy, security headers, dependency vulnerability checks, input sanitization, and secure cookies.
- **Browser compatibility:** HTML5 structure, character encoding, responsive viewport configuration, feature detection, and polyfills.
- **Deprecated APIs:** Safer alternatives to synchronous XHR, `document.write`, and obsolete browser features.
- **Error handling:** Runtime error capture, promise rejection handling, React error boundaries, and user-facing error behavior.
- **Performance:** Deferred resources, efficient event handling, memory cleanup, and asset loading practices.
- **Code quality:** Semantic HTML, valid markup, image sizing, permissions, and privacy-aware UX.
- **Auditing:** A practical checklist and tools for reviewing security, compatibility, code quality, and UX.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-best-practices-skill.git ~/.claude/skills/best-practices
```

## Using the Skill

Ask Claude to apply the guidance to a concrete task:

```text
Use the best-practices skill to review this web application for security,
browser compatibility, performance, and code quality issues.
```

You can also request a focused review of CSP and security headers, dependency vulnerabilities, React error handling, or semantic HTML. Provide the relevant files or repository context for a useful assessment.

## Recommended Review Workflow

1. Identify the framework, runtime, browsers, and deployment environment.
2. Inspect the relevant source, configuration, and dependencies.
3. Prioritize security and correctness issues before stylistic improvements.
4. Explain the risk and impact of each finding.
5. Recommend changes that fit the existing stack.
6. Verify changes with appropriate audits, tests, or browser checks.

## References

The detailed guidance and examples are maintained in [SKILL.md](SKILL.md), including security headers, dependency audits, input sanitization, compatibility, error handling, performance, markup quality, permissions, and audit checklists.
