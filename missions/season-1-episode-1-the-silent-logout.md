```
                 ,     \    /      ,        
                / \    )\__/(     / \       
               /   \  (_\  /_)   /   \      
 _____________/_____\__\@  @/___/_____\______________
|                      |\../|                        |
|                       \VV/                         |
|  THE LOST SYSTEMS — MISSION 1 — THE SILENT LOGOUT  |
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
  |||| Active Consultant |     45–60 min     ||||
  ||||    --==*==--      |                   ||||
  ||||                   |                   ||||
  ||||   THREAT LEVEL    |                   ||||
  ||||       Low         |                   ||||
  ||||__________________ | __________________||||
  ||/===================\|/===================\||
  `--------------------~___~-------------------''

```

09:14. 
Second week at Kester Digital. Your coffee is still warm when a Slack notification comes in.

From: Sanne de Groot — Product Owner
"Hey, sorry to hit you with this right away. Since last night, customers have been getting logged out at random, mid-session. Support is getting dozens of tickets. I've heard three different versions of the story. Backend says: 'the tokens are valid, we're not seeing anything wrong.' Mobile team says: 'the app is doing exactly what it's supposed to do, it just requests a new token whenever it needs one.' Customer service says: 'it happens randomly, not to everyone, and not at a fixed time.' I have a call with the client tomorrow morning at 09:00. I want to know by this afternoon: where should I even start looking? There's a folder on your desktop."

On your desktop is a single folder.

```
Auth API
```

Inside it is one file.

📦 Loot received: 📜 API Endpoint

```
POST /auth/refresh
```

Documentation:

```
Refreshes an expired access token.

Request Headers
Authorization: Bearer <refresh_token>

Response

200 OK
{
  "accessToken": "string",
  "expiresIn": 3600
}

401 Unauthorized
{
  "error": "invalid_refresh_token"
}
```

Your First Task

You may not write code. You're the consultant. In a moment, you'll get exactly one shot at asking the dev team the right questions. Before you do, Sanne wants to know how you're reading this problem.
The Task

Answer only these four questions:

1. What information is still missing to determine where the problem lies?
2. Which stakeholders would you want to talk to?
3. What hypotheses do you have based on this documentation alone?
4. What are the first three research questions you'd ask?

Write as if you were just hired and don't know anything for certain yet.
Mission Rules

* No guessing.
* State your assumptions explicitly.
* Think like a consultant, not a developer.
* There's no perfect answer. Just a strong approach.

Good luck, consultant. Once you submit your analysis, I'll grade it as if I were Sanne. Only then will you find out what's really going on.
