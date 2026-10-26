# reelcrew support

The place to **report bugs, request features and ask questions** about reelcrew: the CLI,
its video skills, setup and updates, accounts and licensing, and the studio.

This repository holds no product source code. It exists so every reelcrew user, and every
agent working on a user's behalf, can reach the team in one place.

## What this repository covers

| Product | What it is |
|---------|------------|
| **reelcrew CLI** | The `reelcrew` command: `setup`, `doctor`, `skills`, `keys`, `fetch`, `compose`, `render`, `check`, `report`, `update` |
| **Video skills** | The skill packs an agent runs through the CLI (whiteboard, machine explainer, paper walkthrough, talking head, mascot 3D, news photo short, and the others listed by `reelcrew skills ls`) |
| **Setup and updates** | `install.sh`, `reelcrew setup`, `reelcrew update`, Python and system packages the doctor asks for |
| **Accounts and licensing** | Login, seats, leases, orders, the update window |
| **Studio** | The review surface where you pin comments on frames |

## How to get help

- **Found a bug?** → [Open a bug report](../../issues/new?template=bug_report.yml)
- **Have an idea?** → [Open a feature request](../../issues/new?template=feature_request.yml)
- **A question, feedback, or "how do I"?** → [Start a discussion](../../discussions)

### Before you post

1. **Search first.** Check [open issues](../../issues) and [discussions](../../discussions); add to an existing thread instead of opening a second one.
2. **Run the doctor.** `reelcrew doctor` tells you what is installed and what is missing; paste its output into the report.
3. **Let reelcrew write the report.** After an error, `reelcrew report` collects the error log, the doctor output and the version into one redacted file you can paste. It removes your home folder, user name, host name, emails and keys.
4. **One issue, one problem.** Two unrelated problems are two issues.
5. **Redact.** No API keys, tokens, license keys, emails, or paths on your machine in anything you post.

## For agents filing on a user's behalf

Claude Code, Codex and other agents report problems here too. Read [`AGENTS.md`](AGENTS.md):
it gives the exact body layout to use when you cannot fill the web form, and the rules
(search first, redact, no labels).

## Security issues

Do **not** file security vulnerabilities as public issues or discussions. See
[`SECURITY.md`](SECURITY.md) for the private channel.

---

Maintained by the reelcrew team.
