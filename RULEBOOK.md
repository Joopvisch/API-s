```
                                                 ___====-_  _-====___
                                           _--^^^#####//      \\#####^^^--_
                                        _-^##########// (    ) \\##########^_
                                       -############//  |\^^/|  \\############-
                                     _/############//   (@::@)   \\############\_
                                    /#############((     \\//     ))#############\
                                   -###############\\    (oo)    //###############-
                                  -#################\\  / VV \  //#################-
                                 -###################\\/      \//###################-
                                 ####################@#\  ^^  /#@####################
                                 |################/   \|  |  |/   \#################|
                                  \###############|    |  |  |    |#################/
                                    \##############\   |  |  |   /################/
                                       \############\  |  |  |  /##############/
                                          \##########\ |  |  | /###########/
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
                                 ______ _   _ _      ___________  _____  _____ _   __
                                 | ___ \ | | | |    |  ___| ___ \|  _  ||  _  | | / /
                                 | |_/ / | | | |    | |__ | |_/ /| | | || | | | |/ /
                                 |    /| | | | |    |  __|| ___ \| | | || | | |    \
                                 | |\ \| |_| | |____| |___| |_/ /\ \_/ /\ \_/ / |\  \
                                 \_| \_|\___/\_____/\____/\____/  \___/  \___/\_| \_/
                           based on real API cases                     RULEBOOK v2.9, locked
```

# THE LOST SYSTEMS — Mission Format (v2.9, locked)

This is the locked format for every mission. It only changes when the Dungeon Master explicitly asks for a revision, versioned in the changelog below.

Players cannot modify the rules. They play missions, make decisions, request coaching or hints, and track their own progress.

Every mission is one episode in a season. A season is a storyline at one fictional company; each episode is one investigation inside it.

An episode may be divided into short **sub-missions** such as `2A`, `2B`, and `2C`. Sub-missions should be bite-sized and may branch based on player decisions.

## The skeleton

Every mission keeps the same visual identity and uses these core sections in this order.

```
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
   T H E   L O S T   S Y S T E M S
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
Season [N] — Mission [N] — [Episode Title]

CLASS: Business Analyst
STATUS: Active Consultant
Location: [Company Name]
Threat Level: [Low / Medium / High]
Estimated Mission Time: [XX–XX min]

▓▓▓ INTRO ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[Short scene-setting, stakeholder problem, conflicting or incomplete
accounts, urgency, and a direct question]

▓▓▓ LOOT ONTVANGEN ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[The artifact: API documentation, logs, stakeholder notes, etc.]

▓▓▓ YOUR FIRST TASK ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[The immediate objective and sub-mission data]

▓▓▓ THE TASK ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[One small, clearly structured assignment]

▓▓▓ MISSION RULES ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
[Only mission-specific constraints]

[Closing line or decision that leads to the next sub-mission]
```

Global rules, scoring rules, hint rules and progression rules belong in this Rulebook and are **not repeated in full inside every mission**.

## Rules of engagement

- **Only the Dungeon Master controls scope and rules.** They decide when a new season or episode starts and are the only one who can request a Rulebook revision.
- **The AI acts as coach and game master.** It stays in character during missions but prioritises useful BA coaching over roleplay.
- **No emoji, ever.** Use ASCII or the banner style shown above.
- **No production code is required from the player.**
- **English throughout.**
- **Tasks must be answerable through reasoning and the evidence provided.**
- **Facts, assumptions and hypotheses must remain distinguishable.**
- **The format is locked.** Changes require the Dungeon Master's explicit request, a version bump and a changelog entry.

## Beginner calibration

The campaign is designed to be accessible to junior Business Analysts.

- No task may require prior knowledge of a concept that has not been introduced in plain language.
- New technical concepts should be introduced through evidence, context or a short explanation before the player is expected to use them.
- Difficult scenarios are allowed. The **decision itself should stay small and clear**.
- Prefer one focused task over several broad questions.
- When a structured answer improves learning, provide the answer format.
- Missions should become more demanding through reasoning, not through hidden technical trivia.

## Sub-missions

Episodes may be split into smaller parts.

Example:

```
Mission 2
|
+-- 2A  Observe
|
+-- 2B  Investigate
|
+-- 2C  Analyse / Communicate
```

A sub-mission should normally take around **5–15 minutes**.

Each sub-mission must show, before the player starts:

```
DIFFICULTY      [*....]
SKILL FOCUS     [skill]
MAXIMUM XP      [number]
BASE REWARD     [number] Gold
```

The player should always know the maximum reward before answering.

## Branching decisions

Some sub-missions may end with a decision.

Example:

```
What do you investigate next?

[A] Backend logs
[B] Frontend request
[C] Customer Support
```

On GitHub, each choice may link to a different Markdown file.

Different paths may reveal different evidence. Branches may reconnect later. The goal is meaningful choice without requiring every decision to create an entirely separate storyline.

Branching is used for **decisions**. Core BA work should still require the player to reason, write, prioritise or analyse rather than only selecting multiple-choice answers.

## Scoring & XP

Every scored sub-mission receives a score from **0 to 10**.

The score reflects the quality of the player's reasoning, not effort or participation alone.

```
10/10  Exceptional
 9/10  Very strong
 8/10  Strong
 7/10  Solid
 6/10  Adequate, meaningful gaps
 5/10  Partly correct, important gaps
 4/10  Weak
 3/10  Mostly off-track
 2/10  Very limited
 1/10  Minimal useful reasoning
 0/10  No assessable answer
```

XP is calculated predictably:

```
XP earned = Maximum XP x (Score / 10)
```

Example:

```
Maximum XP: 100
Score:      8/10
XP earned:  80 XP
```

If a sub-mission uses a different Maximum XP, the same formula applies. Round to the nearest whole XP when necessary.

## Gold

Gold is the campaign currency.

- Gold is earned for **completing a sub-mission**.
- The Base Reward is shown before the player starts.
- Gold is awarded once per sub-mission.
- A retry cannot earn the same Gold twice.
- Gold can be spent on optional hints.

Suggested Base Reward by difficulty:

```
[*....]   20 Gold
[**...]   30 Gold
[***..]   40 Gold
[****.]   50 Gold
[*****]   60 Gold
```

A mission may deviate from this only when there is a clear reason.

## Hints

Hints are optional and must be requested by the player.

Using a hint **does not reduce the score or XP directly**. It costs Gold instead.

```
[?] NUDGE        10 Gold
    Points toward the area that deserves another look.

[?] CLUE         20 Gold
    Narrows the investigation or explains a relevant concept.

[?] RESCUE       30 Gold
    Gives strong guidance, but never writes the final answer for the player.
```

The player chooses whether the additional help is worth the Gold.

The coach must never silently charge Gold or provide a paid hint without the player requesting one.

## Coaching & retry loop

Coaching is not the same as a paid hint.

1. The player submits an answer.
2. The coach gives a **score out of 10**, XP earned, and concise feedback.
3. Feedback identifies what was strong and what is missing without immediately giving the ideal answer.
4. The player may make **one coached retry**.
5. If the retry improves the answer, the higher score replaces the original score and only the additional XP is added.
6. No additional Gold is awarded for the retry.
7. After the retry, or when the player accepts the result, the coach may give the full learning reveal.

This keeps scoring honest while making the campaign a coaching experience rather than an exam.

## Skill focus

Every sub-mission identifies one or two BA skills being practised.

Examples:

- Investigation
- API Literacy
- Requirements
- Testing
- Communication
- Modelling
- Stakeholder Management

Skill Focus is currently descriptive. It does not create a second point system.

## Loot

Loot represents useful knowledge or reusable BA tools.

Examples:

```
[+] LOOT UNLOCKED

HTTP Status Codex
Quick reference for common HTTP status codes.
```

Loot should teach or support future missions. Avoid decorative inventory that has no learning purpose.

## Mission results

At the end of a scored sub-mission, use a compact result block:

```
MISSION RESULT

Score:          8 / 10
XP earned:      80 / 100
Gold earned:    20
Gold spent:      0

Coach feedback: COMPLETE
Next mission:   UNLOCKED
```

## Progress tracking

XP is tracked in `LEADERBOARD.md` at the repo root.

Recommended player fields:

- Alias
- Total XP
- Gold
- Sub-missions Completed

Players with write access update their own progress after completing a scored sub-mission.

## Delivery, adapted per player

- Mission content should use short sections, clear labels and small tasks.
- Explanations outside the mission should be concise and stepwise.
- Avoid unnecessary information before the player needs it.
- When the player is learning a tool such as GitHub, introduce one concrete action at a time.

## Changelog

- **v2.9 (2026-08-11)** — Added bite-sized sub-missions, branching decisions, fixed `/10` scoring, upfront Maximum XP, predictable XP calculation, Gold rewards, purchasable hints, one coached retry, Skill Focus and functional Loot. Global mechanics now live in the Rulebook instead of being repeated in every mission.
- **v2.8 (2026-08-06)** — Replaced emoji section markers with ASCII banner headers for every mission section and added an explicit "no emoji, ever" rule.
- **v2.7 (2026-07-16)** — Split player and Dungeon Master into distinct roles.
- **v2.6 (2026-07-16)** — Genericized the document for public/shared use.
- **v2.5 (2026-07-16)** — Replaced fixed per-mission XP with scored XP.
- **v2.4 (2026-07-16)** — Added XP and Leaderboard rules.
- **v2.3 (2026-07-16)** — Added adaptive delivery pacing.
- **v2.2 (2026-07-16)** — Switched all mission content and feedback to English.
- **v2.1 (2026-07-16)** — Added Beginner Calibration and the original feedback loop.
- **v2.0 (2026-07-14)** — Introduced the locked Lost Systems mission format.
- **v1.0 (2026-07-14)** — Deprecated original ruleset.
