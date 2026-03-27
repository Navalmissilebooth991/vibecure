# VibeCure

Security scanning skill for AI coding assistants. Scans Node.js/Express backends for paid endpoint abuse and billing attacks (EDoS).

## Repository Structure

- `skills/vibecure/SKILL.md` — The skill definition (Agent Skills standard)
- `skills/vibecure/lib/prepare.js` — Service detection engine
- `skills/vibecure/lib/service-signatures.json` — Provider import patterns (22+ providers)
- `skills/vibecure/lib/managed-services.md` — Firebase, Auth0, Cognito, Supabase, Clerk coverage
- `skills/vibecure/references/` — Fix templates, trust proxy guide, credential classification
- `skills/vibecure/evals/` — Tessl eval scenarios

## Usage

Run `/vibecure` in any compatible AI assistant to scan the current project.

## Install

```
npx skills add vibecure/vibecure
```
