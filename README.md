# Ahamed Basha J: AI/ML Engineer Programme

This is the working repository of Ahamed Basha J (Basha) for a 20-week AI/ML engineering programme. The Principal Mentor is Srinivasan Gurukannan.

All of Basha's programme code is committed here. Mentors and coaches read this repository to see what he has built.

## How the programme uses this repository

- The programme runs for 20 weeks, 5 learning days a week, 4 hours a day. The cloud provider is Microsoft Azure.
- Each learning day ends with working code committed to this repository.
- Each week has its own folder (`week-01\`, `week-02\`, and so on), and each day has a folder inside it. Week folders are added as the weeks start.
- Day 5 of each week is an assessment day: a live check without AI, an evidence pack, and a hand-off to the mentor.
- Basha works in the order the plan sets. The Principal Mentor decides when he moves on.

The programme objective and the approved plan are in `programme\`. Read them first.

## Folder layout

| Folder or file | What it holds |
|---|---|
| `README.md` | This file. |
| `.gitignore` | Files Git must not track (virtual environments, caches, outputs). |
| `programme\` | The programme objective, the approved 20-week plan, and a short guide to them. |
| `week-01\` | Week 1 work. Week 1 is a redo of the earlier Days 1-4 with new training material. |
| `archive\first-attempt-2026-11\` | Basha's first-attempt notebooks (day 01, day 02, day 03), kept unchanged as a record. |

Later weeks follow the same pattern: `week-02\`, `week-03\`, and so on, each with `day-01\` to `day-05\` folders as the work is done.

## Rules

1. **No secrets.** Never commit passwords, API keys, tokens, connection strings, or Azure credentials. Keep them in environment variables or a secrets store, and keep them out of notebooks too. If a secret is committed by mistake, tell the mentor at once. Do not just delete the file, because Git keeps the history.
2. **Synthetic data only.** Use made-up data. Never commit real client, customer, employer or personal data.
3. **Commit often.** Commit small pieces of working code, with a short plain message that says what changed. At least one commit at the end of every learning day.
4. **Do not delete earlier work.** Move or archive it instead.
5. **Your own Azure subscription.** If you create one for learning, you own it and pay for any cost. Follow section 5 of the plan.

## Getting started

1. Read `programme\README.md`.
2. Read `week-01\README.md` to see where this week's work goes.
3. Create a virtual environment in the project folder (`python -m venv .venv`). It is ignored by Git.
