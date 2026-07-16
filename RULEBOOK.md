# 🎲 THE LOST SYSTEMS — Mission Format (v2.2, locked)

This replaces the previous v1.0 ruleset (the "quest/realm/XP" version), which missed the mark. This is the format Joep actually wants, based on the mission ChatGPT wrote for him. It is locked as of this version: the skeleton below does not change unless Joep explicitly asks for a revision, and any change gets a version bump and a changelog entry.

Every mission is one episode in a season. A season is a storyline at one fictional company; each episode is one investigation inside it.

## The fixed skeleton — every mission uses exactly this structure, in this order

```
🎲 THE LOST SYSTEMS
Season [N] — [Episode Title]

CLASS
Business Analyst

STATUS
Active Consultant

Location
[Company Name]

Threat Level
[Low / Medium / High]

Estimated Mission Time
[XX–XX min]

📖 Intro
[Timestamp]
[2-5 short lines of scene-setting, second person, present tense]
[A message from a named stakeholder: role + name]
[The message itself: describes a real problem, includes at least two
 conflicting or incomplete accounts from different parties (e.g. dev
 vs. front-end vs. ops), states urgency/deadline, ends asking a direct question]
[One line noting an artifact is available, e.g. a folder/file on the desktop]

📦 Loot ontvangen
[The artifact itself: real-looking API documentation, a log excerpt,
 an error message, a config snippet, etc. — technically accurate]

Your First Task
[Explicit constraint reminders: no code, you are the consultant, you'll
 get one shot to ask the developers the right questions later]
[One line on what happens after this step]

The Task
[Task, usually 3-5 numbered questions or asks. Must be answerable from
 reasoning alone, with the given artifact, not by looking things up.]
[One line instruction on register/tone to answer in, e.g. "write as
 someone who just got hired and isn't sure of anything yet"]

Mission Rules
* [3-5 short bullet constraints, e.g. "no guessing", "state your
  assumptions explicitly", "think like a consultant, not a developer"]

[Closing line: sign-off in character, plus what happens next — see the
 Feedback Loop below for how the answer actually gets evaluated]
```

## Rules of engagement

- **Joep is the Dungeon Master of scope.** Only he decides when a new season or episode starts, and when a season is considered finished.
- **I draft, in character, inside the skeleton.** I write the mission content (story + a technically accurate artifact) in the structure above. I do not add new sections, rename them, drop the stat block, or change the tone/format between episodes.
- **The task must be answerable by reasoning, not lookup.** Every "Opdracht" is something Joep can genuinely think through as a BA, using only what's in the artifact and the message: no trick requires outside research.
- **No code, ever.** Joep is the consultant, not the developer. Every mission is solvable through analysis, questions, and documentation reading.
- **This skeleton is locked.** If Joep wants to change a section, add one, or alter the tone, he says so explicitly. That triggers a version bump and a changelog entry below. Nothing changes silently between episodes.
- **English throughout.** All mission text, artifacts, teacher's notes, hints, and grading are written in English.

### Beginner calibration

- Joep is not a technical specialist. He can't ask about a concept he doesn't know exists, so a mission can't quietly assume prior knowledge it never gave him.
- Any concept a question depends on must already be visible somewhere in the Intro or the artifact (in plain language), or explained inline via a "📘 Teacher's note." New jargon is introduced before it's required, never after.
- When in doubt about whether something assumes too much, default to explaining more, not less.

### Feedback loop (replaces one-shot grading)

Grading is no longer instant. It's a back-and-forth:

1. Joep submits an initial answer.
2. I respond in character as the stakeholder, giving a **hint**, not a grade: I point at one or two things that are thin, missing, or worth pushing on, without revealing the mechanism or the answer itself.
3. Joep revises or extends his answer in light of the hint.
4. Repeat step 2-3 for at most one more round if there's clearly more to draw out.
5. Only once Joep says he's ready, or the hint rounds are used up, do I give the full in-character grade and reveal the truth.

The reveal itself may introduce a brand-new concept Joep didn't know before (that's the point, it's the payoff), but everything asked of him *before* the reveal must stay inside what Beginner Calibration allows.

## Changelog

- v2.2 (2026-07-16) — Switched all mission content and feedback from Dutch to English, per Joep's request.
- v2.1 (2026-07-16) — Added Beginner Calibration and the Feedback Loop, replacing one-shot grading with hint-then-revise. Requested by Joep after Episode 1.
- v2.0 (2026-07-14) — Replaced the quest/realm/XP ruleset with the locked "Lost Systems" mission format, based on Joep's ChatGPT example (Novaris Solutions, Season I — The First Contract).
- v1.0 (2026-07-14) — Deprecated. Original RPG quest/realm/XP ruleset, superseded before first use.
