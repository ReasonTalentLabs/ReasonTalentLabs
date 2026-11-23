# Chris Coultas, PhD

I'm an I-O psychologist and talent executive, and I build working AI systems
for the people side of business. I spent my career in enterprise talent
management, most recently as a Senior Director at McKesson. Now I run
[Reason Talent](https://reasontalent.com), and I build software the way I
built talent programs: start from the science, design the whole system, and
test it before anyone depends on it.

I don't hand-write most of the code. I write the specs, set the guardrails,
review the work, and direct Claude Code agents to build it. Nothing ships
until it passes the automated tests.

## What I've shipped

| Project | What it is | Status |
|---|---|---|
| **Spherikal** | A chief of staff for the people part of a manager's job. It learns how each person on the team works and gets the manager ready for every one-on-one and every hard conversation. | Closed source, in active development |
| [**Genuine Intelligence: Org Design Simulator**](https://github.com/ReasonTalentLabs/genuine-intelligence-org-design) | Ten Claude skills that model reorgs, M&A, and redeployment with the human impact scored next to the structure. Privacy rules and "never name who goes" are enforced by tests. [Try the demo.](https://reasontalentlabs.github.io/genuine-intelligence-org-design/demo/) | Open source, Apache-2.0 |
| [**Job Search OS**](https://github.com/ReasonTalentLabs/job-search-OS) | A Claude plugin with eight skills that runs a job search end to end: career interview, achievement bank, tailored resumes, interview practice, and a weekly learning loop. | Open source |
| [**Manager Accountability Toolkit**](https://github.com/ReasonTalentLabs/accountabilityOS) | Three Claude skills that turn Gallup's accountability research into a weekly habit: set clear goals, check in on evidence, and walk into reviews with a real record. | Open source |

## Spherikal, by the numbers

The code is private, so here is what's behind it (November 2026):

- 2,400+ commits since June 2026
- 570+ automated test files
- 279 database migrations
- A push gate that stops any AI agent from pushing code that fails type
  checks, lint, or tests, with CI as the backstop
- Next.js, TypeScript, Supabase (Postgres), and Vercel

## How I build with AI

- **Spec first.** Every build starts with a written brief: who it's for,
  what it must never do, and how we'll know it works.
- **Rules live in code.** If a rule matters, like privacy, fairness, or
  "the AI doesn't decide who goes," a test enforces it. A policy page
  isn't enough.
- **Several agents at once.** I run parallel Claude Code agents on separate
  branches, then review and merge what holds up.
- **Science before features.** I start from what the research says about
  people at work, then decide what the software should do.

## Background

- PhD, Industrial-Organizational Psychology
- Enterprise talent leader: succession, assessment, performance management,
  and employee listening
- Cut new-hire turnover from 19% to 9%, moved engagement from the 60th to
  the 75th percentile, and took survey time-to-insight from three weeks to
  three days
- Early AI adopter in talent work: found that managers using Copilot had
  more engaged teams
- Author of *Driven Not Drained*

[reasontalent.com](https://reasontalent.com) ·
[LinkedIn](https://www.linkedin.com/in/chriscoultas)
