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

```
CLASS
Business Analyst

STATUS
Active Consultant

Location
Kester Digital

Threat Level
Low

Estimated Mission Time
45–60 min
```

📖 Intro

09:14.
Tweede week bij Kester Digital.
Je koffie is nog warm als je Slack-melding binnenkomt.

From: Sanne de Groot — Product Owner

"Hoi, sorry dat ik je er meteen inschiet.
Sinds gisteravond loggen klanten willekeurig uit, midden in hun sessie.
Support krijgt tientallen tickets binnen.
Ik heb drie versies van het verhaal gehoord.
Backend zegt: 'de tokens zijn geldig, wij zien niks geks.'
Mobile team zegt: 'de app doet exact wat hij moet doen, hij vraagt gewoon een nieuw token op wanneer dat nodig is.'
Klantenservice zegt: 'het gebeurt willekeurig, niet bij iedereen, en niet op een vast moment.'
Ik heb morgenvroeg 09:00 een call met de klant.
Ik wil vanmiddag nog weten: waar moet ik dit zoeken?
Er staat een map op je bureaublad."

Op je bureaublad ligt één map.

```
Auth API
```

Daarin zit één bestand.

📦 Loot ontvangen

📜 API Endpoint

```
POST /auth/refresh
```

Documentatie:

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

Je eerste opdracht

Je mag geen code schrijven.
Je bent de consultant.
Je krijgt straks maar één kans om de developers de juiste vragen te stellen.
Voordat je dat doet, wil Sanne weten hoe jij naar dit probleem kijkt.

Opdracht

Beantwoord alleen deze vier vragen:

1. Welke informatie ontbreekt nog om te bepalen waar het probleem zit?
2. Welke stakeholders zou jij willen spreken?
3. Welke hypotheses heb je op basis van alleen deze documentatie?
4. Welke drie onderzoeksvragen stel jij als eerste?

Schrijf alsof je net bent ingehuurd en nog niets zeker weet.

Mission Rules

* Geen gokken.
* Benoem aannames expliciet.
* Denk als een consultant, niet als een developer.
* Er is geen perfect antwoord. Wel een sterke aanpak.

Succes, consultant.
Wanneer je jouw analyse hebt ingeleverd, beoordeel ik deze alsof ik Sanne ben. Pas daarna ontdek je wat er écht aan de hand is.
