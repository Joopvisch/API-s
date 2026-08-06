```
                                  ...a rulebook only the Dungeon Master may touch

 _____ _   _  _____   _     _____ _____ _____ 
|_   _| | | ||  ___| | |   |  _  /  ___|_   _|
  | | | |_| || |__   | |   | | | \ `--.  | |  
  | | |  _  ||  __|  | |   | | | |`--. \ | |  
  | | | | | || |___  | |___\ \_/ /\__/ / | |  
  \_/ \_| |_/\____/  \_____/\___/\____/  \_/  

 _______   _______ _____ ________  ___ _____ 
/  ___\ \ / /  ___|_   _|  ___|  \/  |/  ___|
\ `--. \ V /\ `--.  | | | |__ | .  . |\ `--. 
 `--. \ \ /  `--. \ | | |  __|| |\/| | `--. \
/\__/ / | | /\__/ / | | | |___| |  | |/\__/ /
\____/  \_/ \____/  \_/ \____/\_|  |_/\____/ 

 based on real Heeyoo API cases                     RULEBOOK v2.8, locked
```

# THE LOST SYSTEMS — Mission Format (v2.8, locked)

This is the locked format for every mission. It only changes when the Dungeon Master explicitly asks for a revision, versioned in the changelog below. Players cannot modify this document, only play missions and track their own XP.

Every mission is one episode in a season. A season is a storyline at one fictional company; each episode is one investigation inside it.

## The fixed skeleton — every mission uses exactly this structure, in this order

```
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
   T H E   L O S T   S Y S T E M S
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
Season [N] — [Episode Title]

CLASS: Business Analyst
STATUS: Active Consultant
Location: [Company Name]
Threat Level: [Low / Medium / High]
Estimated Mission Time: [XX–XX min]

▓▓▓ INTRO ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[Short scene-setting, a message from a named stakeholder describing a
 real problem, with conflicting or incomplete accounts, urgency, and
 a direct question]

▓▓▓ LOOT ONTVANGEN ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[The artifact: real-looking API documentation, a log excerpt, etc.]

▓▓▓ YOUR FIRST TASK ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[No code, you're the consultant, one shot to ask the dev team later]

▓▓▓ THE TASK ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[3-5 numbered questions, answerable by reasoning + the artifact alone]

▓▓▓ MISSION RULES ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
* [3-5 short constraints, e.g. "no guessing", "state assumptions"]

[Closing line: what happens next]
```

## Rules of engagement

- **Only the Dungeon Master controls scope and rules.** They decide when a new season or episode starts, and they're the only one who can request a change to this Rulebook. Players cannot.
- **Claude drafts, in character, inside the skeleton.** No new sections, no renamed sections, same tone every episode.
- **No emoji, ever.** Section headers use the banner format shown above (`▓▓▓ LABEL ▓▓▓▓...`), never emoji.
- **The task must be answerable by reasoning, not lookup.**
- **No code, ever.**
- **English throughout.**
- **This skeleton is locked.** Changes require the Dungeon Master's explicit request, a version bump, and a changelog entry.

### Beginner calibration

- No question can depend on a concept that wasn't already shown, in plain language, somewhere in the Intro, the artifact, or a Teacher's note.
- When in doubt, explain more, not less.

### Feedback loop (replaces one-shot grading)

1. The player submits an initial answer.
2. Claude gives a **hint**, not a grade: pointing at what's thin or missing, without revealing the answer.
3. The player revises.
4. At most one more hint round if needed.
5. Only then does Claude give the full grade and reveal.

### Delivery, adapted per player

- The mission skeleton itself is delivered whole, in one message, its short lines, labeled sections, and code blocks already make it digestible.
- Everything outside the mission skeleton, explanations, instructions, admin/tooling steps, is adapted to what works for the player. If a player finds long or unstructured messages hard to follow, those get broken into single, concrete steps, one per message, waiting for confirmation before the next.

### XP & Leaderboard

- Every mission scores 10-100 XP, not a fixed number, so two people doing the same mission can land differently based on how they answered.
- Scoring bands, judged when the full grade is given:
  - 90-100: sharp and structured, catches the real shape of the problem, no hints needed
  - 70-89: solid reasoning, minor gaps, at most one hint used
  - 50-69: on the right track but vague, needed both hint rounds
  - 10-49: attempted, but mostly guessing or off-track
- XP is only awarded at the full grade + reveal, not for hints alone.
- XP is tracked in `LEADERBOARD.md` at the repo root: alias, Total XP, Missions Completed.
- Anyone with write access edits their own row directly on GitHub after finishing a mission.
- Other Heeyoo BAs join by being added as Collaborators on the repo (Settings → Collaborators), then they can add themselves to the leaderboard and run missions themselves.

## Changelog

- v2.8 (2026-08-06) — Replaced emoji section markers with ASCII banner headers (Office-memo × D&D-plaque style: `▓▓▓ LABEL ▓▓▓...`) for every mission section, plus a single top banner on this document. Added an explicit "no emoji, ever" rule.
- v2.7 (2026-07-16) — Split "player" and "Dungeon Master" into distinct roles: only the Dungeon Master can change this Rulebook, players can only play missions and track XP.
- v2.6 (2026-07-16) — Genericized the whole document: no personal names, since this repo is public/shared with other Heeyoo BAs. "The player" replaces any individual's name throughout.
- v2.5 (2026-07-16) — Replaced fixed per-mission XP with a 10-100 scored range and scoring bands, so quality of the answer determines XP, not just completion.
- v2.4 (2026-07-16) — Added XP & Leaderboard rules, tracked in LEADERBOARD.md, opening the door to other Heeyoo BAs joining via the same repo.
- v2.3 (2026-07-16) — Added delivery pacing adapted per player: missions stay whole (one message, the structured skeleton); everything else (explanations, setup steps) can be broken into short, one-at-a-time steps if that works better for the player.
- v2.2 (2026-07-16) — Switched all mission content and feedback to English.
- v2.1 (2026-07-16) — Added Beginner Calibration and the Feedback Loop, replacing one-shot grading with hint-then-revise.
- v2.0 (2026-07-14) — Replaced the quest/realm/XP ruleset with the locked "Lost Systems" mission format.
- v1.0 (2026-07-14) — Deprecated. Original RPG quest/realm/XP ruleset, superseded before first use.
