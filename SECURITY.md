# Security Policy

## Reporting a vulnerability

Please do not report security problems in public issues.

Report them privately through either channel:

- **GitHub:** [open a private vulnerability report](https://github.com/beatra-ai/beatra-skills/security/advisories/new) on `beatra-ai/beatra-skills`
- **Email:** [support@beatra.ai](mailto:support@beatra.ai) with the subject line `[security]`

Include the skill name and version, the steps to reproduce, and the impact you observed. Never include your own API key or account password.

We acknowledge reports within 3 business days and tell you what we will do next.

## Scope

In scope:

- Skill packages published under `beatra-ai`, including their `scripts/`
- The release pipeline that publishes those packages, including archive integrity and SHA-256 verification
- Beatra services a skill talks to: `beatra.ai`, `console.beatra.ai`, `docs.beatra.ai`, `cdn.beatra.ai`

Out of scope:

- Problems in the agent that runs a skill (Claude Code, Codex, OpenClaw). Report those to the agent's vendor.
- Generated content you disagree with, when it involves no security impact. Use a bug report instead.

## Supported versions

Only the latest published version of each skill receives fixes. Installed skills check for a new version at most once a day, so updating is usually automatic.

---

## 安全问题反馈（中文）

请不要在公开 issue 里报告安全问题，改用 [GitHub 私密漏洞报告](https://github.com/beatra-ai/beatra-skills/security/advisories/new)，或发邮件到 [support@beatra.ai](mailto:support@beatra.ai)，标题加 `[security]`。请写明 Skill 名称和版本、复现步骤和影响，不要附上你自己的 API Key 或密码。我们会在 3 个工作日内回复。
