```text
                 ,     \    /      ,
                / \    )\__/(     / \
               /   \  (_\  /_)   /   \
 _____________/_____\__\@  @/___/_____\______________
|                      |\../|                        |
|                       \VV/                         |
| THE LOST SYSTEMS — MISSION 2 — THE VANISHING BASKET|
|                                                    |
|____________________________________________________|
          |    /\ /      \\       \ /\    |
          |  /   V        ))       V   \  |
          |/     `       //        '     \|
          `              V                '
      __________________   __________________
  .-/|                  \ /                  |\-.
  ||||      CLASS        |      LOCATION     ||||
  ||||  Business Analyst |   Kester Digital  ||||
  ||||    --==*==--      |      --==*==--    ||||
  ||||                   |                   ||||
  ||||      STATUS       |     EST. TIME     ||||
  |||| Active Consultant |     10–15 min     ||||
  ||||    --==*==--      |                   ||||
  ||||                   |                   ||||
  ||||   THREAT LEVEL    |                   ||||
  ||||       Low         |                   ||||
  ||||__________________ | __________________||||
  ||/===================\|/===================\||
  `--------------------~___~-------------------''
```

11:27.

Three days after the logout incident.

You're halfway through lunch when Sanne appears beside your desk.

"Apparently you're becoming our problem magnet."

She drops another support ticket in front of you.

Customers are reporting that products sometimes disappear from their shopping basket.

Not individual products.

The **entire basket**.

Customer Service says:

> "People add products, come back later, and suddenly everything is gone."

Frontend says:

> "We just display whatever the Basket API gives us."

Backend says:

> "The endpoint works. We're returning valid responses."

Sanne looks at you.

"Before everyone starts blaming everyone else again, tell me what we actually know."

On your desktop is a new folder.

```text
> Basket API
```

Inside it is one endpoint.

**[+]** LOOT RECEIVED

```text
Basket API Endpoint
```

```http
GET /baskets/{basketId}
```

The documentation is short.

Possibly too short.

```text
GET /baskets/{basketId}

DESCRIPTION

Returns the current basket for the supplied basketId.


PATH PARAMETERS

basketId

Unique identifier of the customer's basket.


RESPONSE

200 OK

{
  "basketId": "BKT-18492",
  "items": [
    {
      "productId": "P-102",
      "quantity": 2
    }
  ],
  "expiresAt": "2026-08-11T15:30:00Z"
}


404 NOT FOUND

{
  "error": "basket_not_found"
}


NOTE

A basket is temporary.

After its expiration time,
the basket may no longer be available.
```

Sanne points at the documentation.

"Don't solve it yet."

"First tell me what this actually says."

---

# MISSION 2A — READ THE EVIDENCE

Before you investigate the incident, you need to separate **facts** from **assumptions**.

```text
MISSION DATA

DIFFICULTY      [*....]

SKILL FOCUS     API Literacy
                Investigation

MAXIMUM XP      100 XP

BASE REWARD     20 Gold

HINT COST       10 Gold
```

**[!]** CONSULTANT RULE

```text
You do not have enough information
to solve the incident yet.

That is intentional.
```

## THE TASK

Answer exactly these three questions.

### 1. Facts

What can you state with certainty based only on the API documentation?

```text
FACTS:

1.
2.
3.
...
```

### 2. Missing information

What information do you still need before you can explain why customers lose their basket?

```text
MISSING INFORMATION:

1.
2.
3.
...
```

### 3. Hypotheses

Give your **two strongest hypotheses** based on the evidence currently available.

Use this exact structure for both:

```text
HYPOTHESIS 1

Hypothesis:

Evidence supporting it:

What I need to verify:
```

```text
HYPOTHESIS 2

Hypothesis:

Evidence supporting it:

What I need to verify:
```

## MISSION RULES

**[!]** RULES

```text
- Separate facts from assumptions.
- Maximum two hypotheses.
- Do not blame a team yet.
- Use only the information currently available.
- No code required.
- Several hypotheses may be reasonable.
```

Your answer will be graded out of **10**.

```text
SCORING

10/10  = 100 XP
 9/10  =  90 XP
 8/10  =  80 XP
 7/10  =  70 XP
 6/10  =  60 XP
 5/10  =  50 XP
 4/10  =  40 XP
 3/10  =  30 XP
 2/10  =  20 XP
 1/10  =  10 XP
 0/10  =   0 XP
```

Gold is earned by completing the mission part.

Gold can be spent on hints during future mission parts.

**[?]** HINT AVAILABLE

```text
Cost: 10 Gold

Requesting a hint does NOT reduce your score.
It only costs Gold.
```

After your answer, you will receive:

```text
MISSION RESULT

Score:          ? / 10
XP earned:      ? / 100
Gold earned:    20

Coach feedback: LOCKED

Mission 2B:     LOCKED
```

Your investigation determines what happens next.

```text
MISSION PROGRESS

Mission 2A   [ ACTIVE ]
Mission 2B   [ LOCKED ]
Mission 2C   [ LOCKED ]
```

Complete Mission 2A to continue.

The basket may have vanished.

The evidence hasn't.
