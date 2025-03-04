### Roster Details<br />
Team Name: SAW<br />
Roster: Ag1l, MUTiRiS, rmn, shr, story<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1341.6<br />
<br />
Final Rank Value (1341.6) = Starting Rank Value (1420.8) + Head To Head Adjustments (-79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.709[<sup>2</sup>](#table1)

The average of these factors is 0.491<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.8
- 400 + ( ( 0.491 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1420.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      265 | 2025-02-21 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -2.04 | Ag1l, MUTiRiS, rmn, shr, story          |
|           34 |      379 | 2025-02-18 | 3DMAX           | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |    25.21 | Ag1l, MUTiRiS, rmn, shr, story          |
|           33 |      397 | 2025-02-17 | Complexity      | W   | 1.000      | 1.000        | 0.091 (0.091)    | 0.118 (0.118)    | 1 (1.000) |     4.30 | Ag1l, MUTiRiS, rmn, shr, story          |
|           32 |      452 | 2025-02-16 | FlyQuest        | W   | 1.000      | 1.000        | 0.099 (0.099)    | 0.267 (0.267)    | 1 (1.000) |    10.82 | Ag1l, MUTiRiS, rmn, shr, story          |
|           31 |      508 | 2025-02-15 | Astralis        | L   | 1.000      | -            | -                | -                | -         |    -2.73 | Ag1l, MUTiRiS, rmn, shr, story          |
|           30 |      577 | 2025-02-14 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |    -2.09 | Ag1l, MUTiRiS, rmn, shr, story          |
|           29 |      918 | 2025-02-06 | 500             | L   | 1.000      | -            | -                | -                | -         |   -25.47 | Ag1l, MUTiRiS, rmn, shr, story          |
|           28 |      977 | 2025-02-05 | Eco Warriors    | W   | 1.000      | -            | -                | -                | -         |     0.46 | Ag1l, MUTiRiS, rmn, shr, story          |
|           27 |      986 | 2025-02-05 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -25.15 | Ag1l, MUTiRiS, rmn, shr, story          |
|           26 |     1172 | 2025-01-30 | Virtus.pro      | L   | 0.982      | -            | -                | -                | -         |    -5.33 | Ag1l, MUTiRiS, rmn, shr, story          |
|           25 |     1180 | 2025-01-29 | GamerLegion     | L   | 0.975      | -            | -                | -                | -         |    -8.39 | Ag1l, MUTiRiS, rmn, shr, story          |
|           24 |     1340 | 2025-01-15 | BIG             | L   | 0.883      | -            | -                | -                | -         |   -11.32 | Ag1l, MUTiRiS, rmn, shr, story          |
|           23 |     3136 | 2024-11-19 | BetBoom Team    | L   | 0.506      | -            | -                | -                | -         |   -13.57 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           22 |     3175 | 2024-11-18 | Natus Vincere   | L   | 0.500      | -            | -                | -                | -         |    -2.38 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           21 |     3219 | 2024-11-17 | Team Falcons    | W   | 0.494      | -            | -                | -                | 1 (0.494) |     0.43 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           20 |     3254 | 2024-11-17 | UNiTY esports   | W   | 0.489      | 0.143        | -                | 0.408 (0.028)    | 1 (0.489) |     0.76 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           19 |     3279 | 2024-11-16 | SINNERS Esports | L   | 0.487      | -            | -                | -                | -         |   -13.90 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           18 |     4380 | 2024-10-27 | B8              | W   | 0.350      | 0.500        | 0.147 (0.026)    | 0.790 (0.138)    | 1 (0.350) |     3.17 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           17 |     4401 | 2024-10-27 | Monte           | W   | 0.349      | 0.500        | 0.034 (0.006)    | 0.236 (0.041)    | 1 (0.349) |     0.61 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           16 |     4519 | 2024-10-25 | B8              | W   | 0.336      | 0.500        | 0.147 (0.025)    | 0.790 (0.133)    | 1 (0.336) |     2.88 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           15 |     4527 | 2024-10-25 | Team Falcons    | W   | 0.335      | -            | -                | -                | 1 (0.335) |     0.26 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           14 |     4807 | 2024-10-18 | 3DMAX           | L   | 0.290      | -            | -                | -                | -         |    -2.54 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           13 |     4845 | 2024-10-17 | 9Pandas         | W   | 0.283      | 0.500        | 0.104 (0.015)    | 0.628 (0.089)    | -         |     1.09 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           12 |     4913 | 2024-10-16 | HEROIC          | L   | 0.277      | -            | -                | -                | -         |    -7.36 | Ag1l, ewjerkz, MUTiRiS, rmn, story      |
|           11 |     5430 | 2024-10-06 | BIG             | L   | 0.210      | -            | -                | -                | -         |    -2.85 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|           10 |     5478 | 2024-10-05 | BetBoom Team    | W   | 0.204      | 0.500        | 0.122 (0.012)    | 0.387 (0.040)    | 1 (0.204) |     0.80 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            9 |     5563 | 2024-10-04 | FlyQuest        | L   | 0.197      | -            | -                | -                | -         |    -4.74 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            8 |     5579 | 2024-10-04 | Rooster         | W   | 0.196      | 0.500        | -                | 0.377 (0.037)    | -         |     0.12 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            7 |     5867 | 2024-09-29 | 3DMAX           | W   | 0.162      | 0.143        | 0.302 (0.007)    | -                | -         |     3.77 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            6 |     5920 | 2024-09-28 | 9z Team         | W   | 0.157      | -            | -                | -                | -         |     0.10 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            5 |     5951 | 2024-09-28 | Nemiga Gaming   | W   | 0.156      | 0.143        | 0.204 (0.005)    | -                | -         |     0.80 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            4 |     6014 | 2024-09-27 | B8              | L   | 0.150      | -            | -                | -                | -         |    -3.62 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            3 |     6040 | 2024-09-27 | GameAgents      | W   | 0.149      | -            | -                | -                | -         |     0.12 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            2 |     7040 | 2024-09-12 | Insilio         | L   | 0.048      | -            | -                | -                | -         |    -1.49 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |
|            1 |     7145 | 2024-09-10 | TSM             | W   | 0.035      | -            | -                | -                | -         |     0.03 | arrozdoce, ewjerkz, MUTiRiS, rmn, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($87,202.36)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-10-27 |      0.350 | $50,000.00     | $17,518.62      |
| 2024-10-20 |      0.303 | $8,500.00      | $2,572.84       |
| 2024-10-06 |      0.211 | $10,000.00     | $2,110.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
