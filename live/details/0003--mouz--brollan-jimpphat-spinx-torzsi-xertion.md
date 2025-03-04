### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, Spinx, torzsi, xertioN<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1882.0<br />
<br />
Final Rank Value (1882.0) = Starting Rank Value (1977.6) + Head To Head Adjustments (-95.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.678[<sup>2</sup>](#table1)
- Opponent Network: 0.356[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1977.6
- 400 + ( ( 0.758 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1977.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      168 | 2025-02-23 | Team Falcons     | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.565 (0.565)    | 1 (1.000) |    15.82 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           28 |      225 | 2025-02-22 | Astralis         | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |     9.39 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           27 |      288 | 2025-02-21 | PaiN Gaming      | W   | 1.000      | 1.000        | 0.333 (0.333)    | 0.406 (0.406)    | 1 (1.000) |     4.83 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           26 |      377 | 2025-02-18 | Virtus.pro       | W   | 1.000      | 1.000        | 0.299 (0.299)    | 0.419 (0.419)    | 1 (1.000) |     7.37 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           25 |      417 | 2025-02-17 | Team Falcons     | L   | 1.000      | -            | -                | -                | -         |   -16.04 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           24 |      453 | 2025-02-16 | FaZe Clan        | L   | 1.000      | -            | -                | -                | -         |   -18.39 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           23 |      525 | 2025-02-15 | 3DMAX            | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |     5.43 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           22 |      583 | 2025-02-14 | BIG              | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     1.56 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           21 |     1097 | 2025-02-03 | Team Liquid      | L   | 1.000      | -            | -                | -                | -         |   -30.65 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           20 |     1124 | 2025-02-01 | GamerLegion      | L   | 0.997      | -            | -                | -                | -         |   -27.40 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           19 |     1327 | 2025-01-17 | BetBoom Team     | L   | 0.897      | -            | -                | -                | -         |   -28.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     3217 | 2024-11-17 | Natus Vincere    | W   | 0.494      | -            | -                | -                | 1 (0.494) |     3.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     3257 | 2024-11-17 | HEROIC           | W   | 0.489      | -            | -                | -                | 1 (0.489) |     0.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     3282 | 2024-11-16 | Nemiga Gaming    | W   | 0.487      | -            | -                | -                | 1 (0.487) |     0.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     4138 | 2024-11-01 | Team Vitality    | L   | 0.381      | -            | -                | -                | -         |    -6.83 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     4185 | 2024-10-31 | Astralis         | L   | 0.375      | -            | -                | -                | -         |    -7.19 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     4256 | 2024-10-30 | FaZe Clan        | W   | 0.368      | 1.000        | 0.475 (0.175)    | 0.399 (0.147)    | 1 (0.368) |     3.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     5048 | 2024-10-13 | Natus Vincere    | L   | 0.257      | -            | -                | -                | -         |    -6.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     5104 | 2024-10-12 | FURIA            | W   | 0.250      | -            | -                | -                | -         |     0.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     5166 | 2024-10-11 | Team Vitality    | W   | 0.244      | 0.624        | 1.000 (0.152)    | 0.391 (0.059)    | -         |     3.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     5249 | 2024-10-09 | FaZe Clan        | W   | 0.230      | 0.624        | 0.475 (0.068)    | 0.399 (0.057)    | -         |     2.17 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     5323 | 2024-10-08 | Complexity       | W   | 0.224      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     5381 | 2024-10-07 | FURIA            | L   | 0.217      | -            | -                | -                | -         |    -6.74 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     5406 | 2024-10-07 | PaiN Gaming      | W   | 0.216      | 0.624        | 0.333 (0.045)    | 0.406 (0.055)    | -         |     0.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     6840 | 2024-09-15 | Complexity       | L   | 0.068      | -            | -                | -                | -         |    -2.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     6924 | 2024-09-14 | Fnatic           | W   | 0.062      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     7021 | 2024-09-12 | Complexity       | L   | 0.050      | -            | -                | -                | -         |    -1.57 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     7070 | 2024-09-11 | Imperial Esports | L   | 0.043      | -            | -                | -                | -         |    -1.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     7144 | 2024-09-10 | Rooster          | W   | 0.035      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($432,034.24)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-11-03 |      0.395 | $25,000.00     | $9,865.79       |
| 2024-10-13 |      0.257 | $42,000.00     | $10,776.20      |
| 2024-09-22 |      0.116 | $12,000.00     | $1,392.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
