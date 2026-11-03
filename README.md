<div align="center">

<a href="https://cloudthinker.io"><img src="assets/logo.svg" alt="CloudThinker" height="56" /></a>

<h3>Frontier Investigation Agents</h3>

<p>You get paged. The root cause is already waiting.<br />
Agents dig through your logs, metrics, deploys and code, then hand you the fix to approve.</p>

<a href="https://cloudthinker.io">Website</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://docs.cloudthinker.io">Docs</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://cloudthinker.io/platform">Platform</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://cloudthinker.io/pricing">Pricing</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="../../issues">Report Issue</a>

</div>

<br />

> **Public Issue Tracker** — This repository is for customers and community members to [open issues](../../issues) to report bugs, request features, or ask questions. Our Product team actively monitors and triages all submissions.

---

## What CloudThinker does

CloudThinker builds Frontier Investigation Agents. They find the root cause behind a production issue or vulnerability, then hand your engineers the fix to approve.

| Daily production | What you get | Capability |
| :--- | :--- | :--- |
| **Incidents** | Why production broke, and the rollback. | [Resolve](https://cloudthinker.io/resolve) |
| **Pull requests** | What will break, before you merge. | [Review](https://cloudthinker.io/code-review) |
| **Vulnerabilities** | Which CVEs are actually reachable, and the patch. | [Cyber](https://cloudthinker.io/cyber) |
| **Cost spikes** | Why the bill jumped, and what to shut down. | [Optimize](https://cloudthinker.io/optimize) |
| **Routine operations** | Patching, rotations and runbooks, done on schedule. | [Automation](https://cloudthinker.io/automation) |
| **Your workflows** | Teach agents your team's runbooks and skills. | [Customize](https://cloudthinker.io/customize) |

## How it works

1. **Detect (MTTD).** Your monitoring, plus detectors for what it misses.
2. **Investigate (MTTI).** Evidence from every source. Root cause in minutes.
3. **Resolve (MTTR).** Fix proposed, run or approved by policy.

## Same model. Better investigator.

On the public [SREGym-Lite leaderboard](https://sregym.com/leaderboard) (October 2026), CloudThinker on GPT-6 Astra (low) resolves **100%** of incidents end to end, with the fewest tokens of any agent at 100%. On Claude Opus 5 it resolves **76.5%**, against 70.6% for Claude Code on the same model.

## Read-only to start

- **Scoped access.** Agents only see what you connect, and start with read-only permissions.
- **Approval by policy.** Rollbacks, PRs and patches wait for an engineer's OK, unless your policy lets that action run on its own.
- **Full audit trail.** Every query and every action is logged, with who approved it.
- **Run it your way.** Managed SaaS, or [self-hosted sandboxes](https://cloudthinker.io/self-hosted-sandboxes) inside your own cloud. Bring your own model, or use ours.

SOC 2 Type II · AWS Advanced Tier Services Partner · AWS AI Services Competency — see the [Trust Center](https://cloudthinker.io/security).

## Works with the stack you already run

AWS, Google Cloud, Azure, Kubernetes, Datadog, Grafana, PagerDuty, Slack, GitHub and GitLab, among [others](https://cloudthinker.io/connections). Connecting takes about 30 minutes.

## Open source from CloudThinker

| Repository | What it is |
| :--- | :--- |
| [cloudthinker-cli](https://github.com/cloudthinker-ai/cloudthinker-cli) | The CloudThinker CLI: login, headless chat, code review, job runner. See [cloudthinker.io/cli](https://cloudthinker.io/cli). |
| [CloudSkills](https://github.com/cloudthinker-ai/CloudSkills) | Community registry of agent skills that run on CloudThinker. |
| [cloudthinker-runbook-hub](https://github.com/cloudthinker-ai/cloudthinker-runbook-hub) | Copy-pasteable incident runbooks for cloud engineering teams. |
| [eager-tools](https://github.com/cloudthinker-ai/eager-tools) | Eager tool dispatch for streaming LLM agents. |

---

## Issue Tracker

This repository serves as CloudThinker's public issue tracker:

- **Report bugs** — Describe the issue, steps to reproduce, and expected behavior
- **Request features** — Share your use case and how a new feature would help
- **Ask questions** — Get help from the CloudThinker team and community

Please use the [issue templates](../../issues/new/choose) when available to help us triage faster.

---

<div align="center">

<a href="https://cloudthinker.io">Website</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://docs.cloudthinker.io">Documentation</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://cloudthinker.io/platform">Platform</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://cloudthinker.io/pricing">Pricing</a>&nbsp;&nbsp;&bull;&nbsp;&nbsp;<a href="https://cloudthinker.io/contact">Contact</a>

<br />

<sub>See <a href="LICENSE">LICENSE</a> for details.</sub>

</div>
