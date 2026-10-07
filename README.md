# python-journey# python-journey
 
> One person, 52 weeks, 25 hours a week, from "hello world" to employable Python developer.
> Everything I read, write, break, fix and learn, committed in public.
 
![Python](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)
![Progress](https://img.shields.io/badge/Progress-Week%2000%20of%2052-2f6f8f)
![Hours](https://img.shields.io/badge/Logged-0%20%2F%201%2C220%20h-1f7a5c)
![Track](https://img.shields.io/badge/Track-Intensive%20(25%20h%2Fweek)-b8860b)
![License](https://img.shields.io/badge/License-MIT-green)
 
<!-- TIP: change only the numbers in the badge URLs above, once a week. -->
<!-- TIP: badges break on spaces - use %20 for a space. Check the preview before committing. -->
 
**Started:** Monday 5 October 2026   **Week 52 ends:** Sunday 3 October 2027
**Currently:** Week 1 - Environment, mindset and your first program
 
---
 
## What this repository is
 
This is the working log of a self-taught Python developer following a structured 52-week
curriculum: **1,220 planned hours**, four phases, eight milestone projects, and four formal
gate reviews. It is not a portfolio of finished products - it is the honest record of getting
there: exercises, notes, failed first drafts, debugging journals, and the projects that came
out the other side. Everything here is written by me, in public, in order. If a week looks
messy, that is because the week was messy.
 
## How this repository is organised
 
```
python-journey/
├── README.md              <- you are here
├── LICENSE
├── .gitignore
├── weeks/                 <- one folder per week: week-01/, week-02/, ...
│   ├── week-01/
│   │   ├── README.md      <- what this week covered, what I got stuck on
│   │   ├── exercises/     <- drills and practice problems
│   │   └── notes.md       <- written in my own words, not copied
├── journal/               <- weekly retrospectives + the debugging journal
│   ├── week-01.md
│   └── debugging.md       <- every bug that cost me more than 30 minutes
├── cheatsheets/           <- stdlib, pytest, git, regex - rewritten by hand
├── katas/                 <- small repeatable exercises I re-do for fluency
└── docs/
    ├── curriculum.md      <- the full 52-week plan
    ├── book-list.md
    └── setup.md           <- how to reproduce my environment
```
 
<!-- TIP: GitHub renders the README inside any folder you browse into. A one-paragraph README
     in each weeks/week-NN/ folder costs two minutes and makes the whole repo navigable. -->
 
## Progress
 
| Phase | Weeks | Theme | Hours | Status |
|---|---|---|---|---|
| 1 | 1-13 | Foundations - syntax, scripts, testing, first shipped CLI | 305 | Not started |
| 2 | 14-26 | Core proficiency - stdlib, OOP, data, packaging, Git/GitHub | 285 | Not started |
| 3 | 27-40 | Professional practice - APIs, architecture, typing, CI, PyPI | 340 | Not started |
| 4 | 41-52 | Specialisation and career - capstone, open source, job search | 290 | Not started |
 
**Gate reviews** (formal self-assessment, scored 0-4): Week 13 / 26 / 40 / 52
**Deload weeks** (15 h instead of 25 h, planned recovery): 6, 10, 14, 19, 23, 26, 33, 49
 
## Milestone projects
 
Each one gets its own repository, so it can have its own README, releases and URL.
 
| Code | Project | Weeks | Repo | Status |
|---|---|---|---|---|
| P1 | Personal Finance Tracker (CLI) | 11-13 | _link when created_ | Not started |
| P2 | Automation Suite (files, data, reports) | 15-18 | _link when created_ | Not started |
| P3 | Inventory and Order Management System (OOP) | 20-21, 34, 36 | _link when created_ | Not started |
| P4 | Production REST API | 27-31, 35 | _link when created_ | Not started |
| P5 | Full-Stack Web Application | 37-38 | _link when created_ | Not started |
| P6 | Published Open-Source Python Package | 39 | _link when created_ | Not started |
| P7 | Specialisation Capstone (2,000+ lines) | 41-48 | _link when created_ | Not started |
| P8 | Portfolio and Career Launch | 50-52 | _link when created_ | Not started |
 
## How I work
 
- **Weekly rhythm:** read, then drill, then build, then review. Roughly 6 h reading, 10 h
  exercises, 6 h project work and 3 h review in Phase 1; the project share grows every phase.
- **Commits:** one small commit per finished block of work - never one commit per week.
- **Commit prefixes:** feat, fix, refactor, test, docs, chore, style, perf, and `learn:` for
  exercises, katas and curriculum notes.
- **Issues are my to-do list.** Every week starts as an issue with the week's tasks as a
  checklist, and I close it on Sunday.
- **Deload weeks are not failures.** They are planned recovery, and they are in the plan on
  purpose.
 
## Running anything in here
 
Every week's code is plain Python. There is no install step.
 
```bash
git clone https://github.com/YOUR-USERNAME/python-journey
cd python-journey
 
# from week 10 onward, one environment per project
uv venv && source .venv/bin/activate      # Windows: .venv\Scripts\activate
uv pip install -r weeks/week-10/requirements.txt
 
python weeks/week-10/exercises/exercise_01.py
```
 
<!-- TIP: only ever paste commands you have actually run. -->
 
## What I am using
 
Python 3.14 - VS Code - Git + GitHub (gh CLI) - uv - pytest - ruff - mypy - pre-commit -
GitHub Actions. Full list and versions in docs/setup.md.
 
## Journal
 
- [Week 1 - what surprised me](journal/week-01.md)
- [The debugging journal](journal/debugging.md) - every bug that cost me more than 30 minutes,
  with the fix written down so I never pay for it twice
 
<!-- TIP: this list is the most-read part of a learning repo. Add one line every Sunday. -->
 
## Feedback
 
I am a beginner and this repository is a record of learning, not a claim of expertise. If you
spot something wrong, an issue explaining *why* it is wrong will teach me more than the
original mistake did. Be kind, be specific.
 
## Licence
 
MIT - see LICENSE. Notes and exercises are my own; anything quoted is attributed in place.
 
