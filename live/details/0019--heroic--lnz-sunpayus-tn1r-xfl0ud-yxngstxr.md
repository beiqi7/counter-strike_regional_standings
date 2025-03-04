### Roster Details<br />
Team Name: HEROIC<br />
Roster: LNZ, SunPayus, tN1R, xfl0ud, yxngstxr<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1214.4<br />
<br />
Final Rank Value (1214.4) = Starting Rank Value (1105.5) + Head To Head Adjustments (108.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.261[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1105.5
- 400 + ( ( 0.339 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1105.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      320 | 2025-02-20 | Astralis             | W   | 1.000      | 0.143        | 0.734 (0.105)    | 0.811 (0.116)    | 0 (0.000) |    29.75 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           30 |      636 | 2025-02-11 | Metizport            | W   | 1.000      | 0.143        | 0.087 (0.012)    | 0.517 (0.074)    | 0 (0.000) |    10.77 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           29 |      644 | 2025-02-11 | BIG                  | W   | 1.000      | 0.143        | 0.244 (0.035)    | 0.528 (0.075)    | 0 (0.000) |    23.66 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           28 |      664 | 2025-02-10 | 3DMAX                | L   | 1.000      | -            | -                | -                | -         |    -2.64 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           27 |      675 | 2025-02-10 | Zero Tenacity        | W   | 1.000      | 0.143        | -                | 0.843 (0.120)    | 0 (0.000) |     7.17 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           26 |      721 | 2025-02-09 | PARIVISION           | L   | 1.000      | -            | -                | -                | -         |   -25.48 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           25 |      796 | 2025-02-08 | Passion UA           | W   | 1.000      | 0.143        | -                | 0.495 (0.071)    | -         |     9.66 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           24 |     1160 | 2025-01-31 | BIG                  | L   | 0.990      | -            | -                | -                | -         |    -5.79 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           23 |     1163 | 2025-01-30 | Eternal Fire         | L   | 0.984      | -            | -                | -                | -         |    -0.47 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           22 |     1172 | 2025-01-29 | Team Liquid          | W   | 0.977      | 1.000        | 0.109 (0.107)    | 0.198 (0.194)    | 1 (0.977) |    18.23 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           21 |     1273 | 2025-01-23 | Team Spirit          | L   | 0.937      | -            | -                | -                | -         |    -0.32 | LNZ, maden, SunPayus, xfl0ud, yxngstxr |
|           20 |     1321 | 2025-01-18 | Team Liquid          | W   | 0.902      | 0.363        | 0.109 (0.036)    | -                | -         |    18.24 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           19 |     1342 | 2025-01-14 | 3DMAX                | W   | 0.876      | 0.363        | 0.302 (0.096)    | 0.510 (0.162)    | -         |    25.73 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           18 |     3176 | 2024-11-18 | Dynamo Eclot         | L   | 0.500      | -            | -                | -                | -         |    -7.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           17 |     3218 | 2024-11-17 | Cloud9               | L   | 0.494      | -            | -                | -                | -         |   -13.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           16 |     3255 | 2024-11-17 | MOUZ                 | L   | 0.489      | -            | -                | -                | -         |    -0.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           15 |     3275 | 2024-11-16 | Rebels Gaming        | W   | 0.488      | -            | -                | -                | 1 (0.488) |     2.42 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           14 |     4712 | 2024-10-20 | Nemiga Gaming        | W   | 0.303      | 0.500        | 0.204 (0.031)    | -                | -         |     5.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           13 |     4770 | 2024-10-19 | BC.Game Esports      | L   | 0.296      | -            | -                | -                | -         |    -5.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           12 |     4842 | 2024-10-17 | Nemiga Gaming        | W   | 0.284      | 0.500        | 0.204 (0.029)    | -                | -         |     4.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           11 |     4861 | 2024-10-17 | Fluxo                | W   | 0.282      | 0.624        | -                | 0.479 (0.084)    | 1 (0.282) |     3.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           10 |     4911 | 2024-10-16 | SAW                  | W   | 0.277      | 0.500        | 0.315 (0.044)    | -                | -         |     7.37 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            9 |     4933 | 2024-10-16 | Nemiga Gaming        | W   | 0.275      | 0.624        | 0.204 (0.035)    | 0.424 (0.073)    | 1 (0.275) |     4.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            8 |     4974 | 2024-10-15 | Sashi Esport         | W   | 0.270      | 0.500        | -                | 0.606 (0.082)    | -         |     3.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            7 |     6011 | 2024-09-27 | BetBoom Team         | L   | 0.151      | -            | -                | -                | -         |    -2.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            6 |     6117 | 2024-09-26 | Passion UA           | W   | 0.142      | -            | -                | -                | -         |     1.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            5 |     6168 | 2024-09-25 | Natus Vincere Junior | L   | 0.138      | -            | -                | -                | -         |    -2.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            4 |     7233 | 2024-09-08 | Team Falcons         | L   | 0.023      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            3 |     7335 | 2024-09-07 | FlyQuest             | W   | 0.015      | -            | -                | -                | 1 (0.015) |     0.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            2 |     7399 | 2024-09-06 | FaZe Clan            | L   | 0.010      | -            | -                | -                | -         |    -0.01 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            1 |     7465 | 2024-09-05 | Team Falcons         | W   | 0.004      | -            | -                | -                | 1 (0.004) |     0.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,712.14)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.957 | $25,000.00     | $23,916.78      |
| 2024-10-20 |      0.303 | $17,000.00     | $5,152.02       |
| 2024-10-19 |      0.297 | $25,000.00     | $7,432.40       |
| 2024-09-28 |      0.157 | $2,000.00      | $314.22         |
| 2024-09-22 |      0.116 | $12,000.00     | $1,396.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
