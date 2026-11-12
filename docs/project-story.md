# AshuOS: the project story (SOART)

Scenario, Obstacle, Action, Result, Troubleshooting. This is how AshuOS was planned and built, the decisions behind it, and what went wrong along the way. The detailed reasoning for each decision is in the [ADRs](adr/).

**Status:** in progress. The project and its documentation were set up on 2026-11-12, and the visual design is settled (the Emerald edition). Phase A, the design foundation, is next.

---

## S: Scenario

**Big ambitions stay vague when nothing connects them to what I do each day.**

I want one place that turns the person I want to become into what I actually do: a vision board for inspiration, goals and milestones I can measure, systems and habits I can repeat, and a weekly review to see what's working. It covers my five hobbies (swimming, geopolitics and reading, writing and poetry, public speaking, trekking), plus fitness, college, career, money and personal growth.

Two constraints shape it:

- **One codebase for every screen.** It has to work on a phone, a laptop and the web, with layouts designed for each, not a desktop squeezed onto a phone.
- **I'm new to programming and to Flutter.** I need to be able to explain every decision, so each non-obvious one gets an ADR.

## O: Obstacles

None recorded yet. They're added as they come up.

## A: Actions

### 1. Set up the documentation before the code

- Checked the toolchain: Flutter 3.50.0 and Dart 3.14.0.
- Created the repository with a README, this story, architecture diagrams, a folder for ADRs, a build log, a next-task file, a backlog and a pull request template, so every decision gets written down as it's made.

### 2. Settled the visual design and the build order

- Chose the Emerald edition: a deep green-black dark theme with emerald as the only accent, Inter for type, a 4 px spacing scale, a named component library and a cinematic, photo-led Vision Board.
- Reordered the build so every screen is made on sample data first (phases A–E: design foundation, app shell, core experience, hobbies, other modules), with the Supabase backend after that.

## R: Results

None yet.

## T: Troubleshooting

None yet. Every real error gets recorded here: the problem, the cause, the fix and the lesson.
