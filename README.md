# a3-skills (Hermes skill tap)

Public Hermes Agent skill tap for CSCI 599 Assignment 3.

| Skill | What it does |
|---|---|
| `inbox-triage` | Sorts unread mail into Urgent / Reply today / FYI / Ignore, flags prompt-injection emails, and prepares reply drafts only (sending stays human-approved). |

## Install

```bash
hermes skills tap add <owner>/a3-skills
hermes skills install <owner>/a3-skills/skills/inbox-triage --yes
hermes skills list | grep inbox-triage
```

Then ask the agent: "Triage my inbox."

Privacy policy: [PRIVACY.md](PRIVACY.md). License: MIT.
