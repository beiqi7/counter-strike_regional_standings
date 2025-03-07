### Roster Details<br />
Team Name: FORZE Reload<br />
Roster: KusMe, rexxie, shady, Something, spirit<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  853.6<br />
<br />
Final Rank Value (853.6) = Starting Rank Value (832.9) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.072[<sup>2</sup>](#table1)

The average of these factors is 0.196<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.9
- 400 + ( ( 0.196 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 832.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      798 | 2025-02-08 | Zero Tenacity              | L   | 0.682      | -            | -                | -                | -         |   -10.45 | KusMe, rexxie, shady, Something, spirit   |
|           49 |      870 | 2025-02-07 | Divergent                  | W   | 0.677      | -            | -                | -                | 0 (0.000) |     1.48 | KusMe, rexxie, shady, Something, spirit   |
|           48 |     1755 | 2024-12-20 | AMKAL ESPORTS              | L   | 0.404      | -            | -                | -                | -         |    -7.24 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           47 |     1777 | 2024-12-19 | K27                        | W   | 0.398      | 0.333        | 0.009 (0.001)    | 0.652 (0.104)    | 0 (0.000) |     7.58 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           46 |     1866 | 2024-12-15 | RUSH B (Russian team)      | L   | 0.376      | -            | -                | -                | -         |    -4.55 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           45 |     1915 | 2024-12-14 | G2 Ares                    | W   | 0.372      | 0.333        | -                | 0.182 (0.027)    | 0 (0.000) |     3.17 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           44 |     1966 | 2024-12-13 | LEON Esports               | W   | 0.369      | 0.143        | 0.010 (0.001)    | -                | 1 (0.443) |     4.57 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           43 |     2014 | 2024-12-13 | NEVERMORE (Ukrainian team) | L   | 0.366      | -            | -                | -                | -         |    -6.80 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           42 |     2026 | 2024-12-13 | LEON Esports               | W   | 0.365      | 0.143        | 0.010 (0.001)    | -                | 0 (0.000) |     4.46 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           41 |     2063 | 2024-12-12 | JANO Esports               | W   | 0.360      | 0.333        | 0.019 (0.003)    | 0.430 (0.062)    | 0 (0.000) |     6.77 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           40 |     2121 | 2024-12-11 | Dark Cloud Esports         | W   | 0.353      | 0.333        | 0.035 (0.005)    | 0.667 (0.094)    | 0 (0.000) |     5.20 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           39 |     2182 | 2024-12-09 | GenOne                     | L   | 0.342      | -            | -                | -                | -         |    -5.70 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           38 |     2423 | 2024-12-04 | Monte                      | L   | 0.315      | -            | -                | -                | -         |    -3.76 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           37 |     2473 | 2024-12-03 | Viperio                    | W   | 0.309      | 0.333        | -                | 0.325 (0.040)    | 0 (0.000) |     3.50 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           36 |     2527 | 2024-12-02 | BC.Game Esports            | W   | 0.303      | 0.333        | 0.021 (0.003)    | 0.432 (0.052)    | 0 (0.000) |     4.84 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           35 |     2552 | 2024-12-01 | Zero Tenacity              | L   | 0.299      | -            | -                | -                | -         |    -4.02 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           34 |     2559 | 2024-12-01 | MASONIC                    | W   | 0.299      | -            | -                | -                | 0 (0.000) |     2.45 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           33 |     2576 | 2024-12-01 | Lilmix                     | W   | 0.299      | -            | -                | -                | -         |     1.97 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           32 |     2878 | 2024-11-25 | Dark Cloud Esports         | W   | 0.264      | 0.333        | 0.035 (0.004)    | 0.667 (0.070)    | -         |     4.10 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           31 |     2990 | 2024-11-23 | JANO Esports               | W   | 0.254      | 0.333        | 0.019 (0.002)    | 0.430 (0.044)    | -         |     5.16 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           30 |     3015 | 2024-11-23 | Hyuga                      | W   | 0.253      | -            | -                | -                | -         |     1.12 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           29 |     3138 | 2024-11-21 | Underrated                 | W   | 0.243      | -            | -                | -                | -         |     2.49 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           28 |     3171 | 2024-11-21 | BC.Game Esports            | W   | 0.242      | 0.333        | 0.021 (0.002)    | 0.432 (0.042)    | -         |     3.63 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           27 |     3207 | 2024-11-20 | Soul's Heart Esport        | W   | 0.238      | -            | -                | -                | -         |     1.21 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           26 |     3317 | 2024-11-18 | Lilmix                     | W   | 0.227      | -            | -                | -                | -         |     1.79 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           25 |     3458 | 2024-11-16 | K27                        | W   | 0.214      | 0.143        | -                | 0.652 (0.024)    | -         |     4.67 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           24 |     3467 | 2024-11-16 | XGOD ARENA                 | W   | 0.214      | -            | -                | -                | -         |     1.56 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           23 |     3492 | 2024-11-15 | XP Academy                 | L   | 0.210      | -            | -                | -                | -         |    -5.46 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           22 |     3538 | 2024-11-14 | FLuffy Gangsters           | L   | 0.205      | -            | -                | -                | -         |    -3.81 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           21 |     3580 | 2024-11-14 | FORTIS (Russian team)      | W   | 0.203      | -            | -                | -                | -         |     1.06 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           20 |     3675 | 2024-11-11 | THE SPELLS                 | L   | 0.188      | -            | -                | -                | -         |    -5.03 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           19 |     4255 | 2024-11-01 | Lausanne-Sport Esports     | W   | 0.132      | -            | -                | -                | -         |     0.69 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           18 |     4297 | 2024-10-31 | Grindas                    | L   | 0.127      | -            | -                | -                | -         |    -3.36 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           17 |     4430 | 2024-10-29 | ROUNDS                     | W   | 0.116      | -            | -                | -                | -         |     0.53 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           16 |     4447 | 2024-10-29 | MOUZ NXT                   | W   | 0.115      | -            | -                | -                | -         |     0.56 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           15 |     4710 | 2024-10-24 | Nexus Gaming               | W   | 0.087      | 0.333        | 0.161 (0.006)    | -                | -         |     2.33 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           14 |     4747 | 2024-10-23 | Dynamo Eclot               | W   | 0.082      | -            | -                | -                | -         |     0.21 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           13 |     4772 | 2024-10-23 | FLuffy Gangsters           | W   | 0.081      | -            | -                | -                | -         |     1.05 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           12 |     4831 | 2024-10-21 | Passion UA                 | L   | 0.071      | -            | -                | -                | -         |    -1.00 | dwushka, KusMe, shady, spirit, xdENiSZERA |
|           11 |     4949 | 2024-10-19 | FLuffy Gangsters           | W   | 0.059      | -            | -                | -                | -         |     0.77 | KusMe, shady, spirit, xdENiSZERA          |
|           10 |     4970 | 2024-10-19 | Viperio                    | W   | 0.058      | -            | -                | -                | -         |     0.69 | KusMe, shady, spirit, xdENiSZERA          |
|            9 |     5014 | 2024-10-18 | K27                        | W   | 0.052      | -            | -                | -                | -         |     1.16 | KusMe, shady, spirit, xdENiSZERA          |
|            8 |     5065 | 2024-10-17 | BC.Game Esports            | W   | 0.047      | -            | -                | -                | -         |     0.71 | KusMe, shady, spirit, xdENiSZERA          |
|            7 |     5103 | 2024-10-16 | Ex-ENTERPRISE esports      | W   | 0.043      | -            | -                | -                | -         |     0.11 | KusMe, shady, spirit, xdENiSZERA          |
|            6 |     5133 | 2024-10-16 | Kay Team                   | W   | 0.043      | -            | -                | -                | -         |     0.18 | KusMe, shady, spirit, xdENiSZERA          |
|            5 |     5183 | 2024-10-15 | Nexus Gaming               | L   | 0.038      | -            | -                | -                | -         |    -0.18 | KusMe, shady, spirit, xdENiSZERA          |
|            4 |     5240 | 2024-10-14 | RUSTEC                     | W   | 0.032      | -            | -                | -                | -         |     0.16 | KusMe, shady, spirit, xdENiSZERA          |
|            3 |     5368 | 2024-10-12 | Eternal prem               | W   | 0.020      | -            | -                | -                | -         |     0.07 | KusMe, malinov, shady, spirit, xdENiSZERA |
|            2 |     5374 | 2024-10-12 | RUSTEC                     | W   | 0.019      | -            | -                | -                | -         |     0.18 | KusMe, malinov, shady, spirit, xdENiSZERA |
|            1 |     5490 | 2024-10-09 | Lazer Cats                 | L   | 0.004      | -            | -                | -                | -         |    -0.09 | KusMe, shady, spirit, xdENiSZERA          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,742.45)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-21 |      0.491 | $1,000.00      | $490.97         |
| 2024-12-15 |      0.452 | $3,873.73      | $1,749.82       |
| 2024-12-04 |      0.378 | $3,000.00      | $1,135.42       |
| 2024-11-14 |      0.246 | $3,000.00      | $737.08         |
| 2024-10-24 |      0.105 | $6,000.00      | $629.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
