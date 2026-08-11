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
                                       ______ _____  ___ _________  ___ _____
                                       | ___ \  ___|/ _ \|  _  \  \/  ||  ___|
                                       | |_/ / |__ / /_\ \ | | | .  . || |__
                                       |    /|  __||  _  | | | | |\/| ||  __|
                                       | |\ \| |___| | | | |/ /| |  | || |___
                                       \_| \_\____/\_| |_/___/ \_|  |_/\____/
                           based on real API cases                     README v2.9
```

# The Lost Systems — an API Investigation Campaign

A narrative learning campaign for Business Analysts.
You play a consultant investigating broken systems through stakeholder conversations, API documentation, logs and other technical evidence.
You do **not** need to be a developer and you do **not** need to write production code.
The goal is to become better at understanding APIs, investigating integration problems, asking useful questions and translating technical behaviour into solid BA work.

See [`RULEBOOK.md`](RULEBOOK.md) for the complete mission format and game rules.

## Who this is for

The campaign is designed to be accessible to **junior Business Analysts and consultants**.
It assumes curiosity and analytical thinking, not deep technical knowledge.
New concepts are introduced during the missions before the player is expected to use them.

## How it plays

A mission is an investigation.
Instead of one large assignment, episodes may be split into short sub-missions:

```
MISSION 2

2A  Observe
 |
2B  Investigate
 |
2C  Analyse / Communicate
```

Most sub-missions should take around **5–15 minutes**.

You may receive:

- stakeholder messages;
- API documentation;
- request/response examples;
- logs;
- requirements;
- support tickets;
- conflicting explanations.

Your job is to reason from the evidence as a Business Analyst.

## Decisions

Some missions contain choices.

Example:

```
What do you investigate next?

[A] Backend logs
[B] Frontend request
[C] Customer Support
```

On GitHub, these choices can link to different mission files, similar to an old choose-your-own-adventure book.
Different choices may reveal different evidence before the paths reconnect.
Choosing a path is only part of the game. The important BA work still happens when you analyse what you find.

## Coaching

This is a learning campaign, not a pass/fail exam.
After a submitted answer, the coach gives:

```
Score
XP earned
Gold earned
What worked
What needs improvement
```

The player may make one coached retry.
Hints are optional and can be purchased with Gold before answering.

## XP & Gold

Each sub-mission tells you its maximum XP and Gold reward **before you start**.
Scores are always out of 10.

```
Maximum XP: 100
Score:       8/10
XP earned:   80 XP
```

Gold is earned by completing sub-missions and can be spent on hints.
Full scoring and hint rules are defined in [`RULEBOOK.md`](RULEBOOK.md).

## Skills

Missions develop practical BA skills such as:

- Investigation
- API Literacy
- Requirements
- Testing
- Communication
- Modelling
- Stakeholder Management

The technical subjects build gradually toward topics such as REST APIs, requests and responses, status codes, authentication, token flows, webhooks, polling and integration behaviour.

## Campaign log

| Season | Mission | Title | Company | Status |
|--------|---------|-------|---------|--------|
| I | 1 | [The Silent Logout](missions/season-1-episode-1-the-silent-logout.md) | Kester Digital | Available |
| I | 2 | The Vanishing Basket | Kester Digital | In development |

## Repository structure

```
API-s/
|
|-- README.md
|-- RULEBOOK.md
|-- LEADERBOARD.md
|
|-- missions/
|   |-- season-1-episode-1-the-silent-logout.md
|   `-- ...
|
`-- artifacts/
    `-- polished BA deliverables from completed missions
```

## Start playing

1. Open the first available mission.
2. Read only the evidence provided.
3. Complete the task.
4. Submit your answer to the campaign coach.
5. Receive your score, XP, Gold and coaching.
6. Continue to the next unlocked sub-mission or decision.

The system is deliberately small.

Learn one thing. Make one decision. Investigate what happens next.
