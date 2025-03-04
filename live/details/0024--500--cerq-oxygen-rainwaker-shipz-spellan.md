### Roster Details<br />
Team Name: 500<br />
Roster: CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1135.6<br />
<br />
Final Rank Value (1135.6) = Starting Rank Value (1070.0) + Head To Head Adjustments (65.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.514[<sup>1</sup>](#table2)
- Bounty Collected: 0.421[<sup>2</sup>](#table1)
- Opponent Network: 0.354[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.322<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1070.0
- 400 + ( ( 0.322 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1070.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           87 |       78 | 2025-02-26 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.819 (0.356)    | 0 (0.000) |    13.77 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           86 |      106 | 2025-02-25 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -22.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           85 |      135 | 2025-02-24 | Betera Esports                            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.82 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           84 |      459 | 2025-02-16 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -26.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           83 |      500 | 2025-02-15 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.819 (0.356)    | 0 (0.000) |    12.89 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           82 |      520 | 2025-02-15 | B8                                        | W   | 1.000      | 0.435        | 0.147 (0.064)    | 0.790 (0.343)    | 0 (0.000) |    17.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           81 |      559 | 2025-02-14 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -13.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           80 |      569 | 2025-02-14 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.150 (0.065)    | 0.705 (0.306)    | 0 (0.000) |    13.03 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           79 |      590 | 2025-02-13 | 9Pandas                                   | W   | 1.000      | 0.435        | 0.104 (0.045)    | 0.628 (0.273)    | 0 (0.000) |    13.40 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           78 |      599 | 2025-02-13 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |   -15.03 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           77 |      645 | 2025-02-11 | ALASKA                                    | W   | 1.000      | 0.435        | -                | 0.888 (0.386)    | 0 (0.000) |     8.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           76 |      719 | 2025-02-09 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.82 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           75 |      772 | 2025-02-08 | OG                                        | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.985 (0.428)    | 0 (0.000) |    10.69 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           74 |      795 | 2025-02-08 | BIG                                       | W   | 1.000      | 0.143        | 0.244 (0.035)    | -                | 0 (0.000) |    26.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           73 |      875 | 2025-02-07 | BC.Game Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           72 |      918 | 2025-02-06 | SAW                                       | W   | 1.000      | 0.143        | 0.315 (0.045)    | -                | -         |    25.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           71 |      970 | 2025-02-05 | MoneyF                                    | W   | 1.000      | -            | -                | -                | -         |     2.19 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           70 |      976 | 2025-02-05 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -12.96 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           69 |      985 | 2025-02-05 | Eco Warriors                              | W   | 1.000      | -            | -                | -                | -         |     2.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           68 |     1014 | 2025-02-04 | TEAM NEXT LEVEL                           | W   | 1.000      | -            | -                | -                | -         |     4.54 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           67 |     1016 | 2025-02-04 | Fire Flux Esports                         | W   | 1.000      | -            | -                | -                | -         |    13.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           66 |     1020 | 2025-02-04 | Monte                                     | W   | 1.000      | -            | -                | -                | -         |    14.41 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           65 |     1046 | 2025-02-04 | Eternal Fire Academy                      | W   | 1.000      | -            | -                | -                | -         |     1.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           64 |     1095 | 2025-02-03 | 9INE                                      | W   | 1.000      | 0.435        | -                | 0.863 (0.375)    | -         |    13.89 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           63 |     1108 | 2025-02-02 | Betclic Apogee Esports                    | L   | 1.000      | -            | -                | -                | -         |   -18.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           62 |     1221 | 2025-01-27 | CYBERSHOKE Esports                        | W   | 0.964      | 0.500        | -                | 1.000 (0.482)    | -         |     8.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           61 |     1247 | 2025-01-24 | Nemiga Gaming                             | L   | 0.944      | -            | -                | -                | -         |   -12.43 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           60 |     1271 | 2025-01-23 | Sashi Esport                              | L   | 0.937      | -            | -                | -                | -         |   -15.32 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           59 |     1568 | 2024-12-21 | Betclic Apogee Esports                    | L   | 0.717      | -            | -                | -                | -         |   -15.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           58 |     1628 | 2024-12-20 | 9INE                                      | L   | 0.710      | -            | -                | -                | -         |   -14.39 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           57 |     1634 | 2024-12-20 | Ex-GODSENT                                | W   | 0.709      | -            | -                | -                | -         |     1.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           56 |     1640 | 2024-12-20 | JANO Esports                              | L   | 0.708      | -            | -                | -                | -         |   -16.87 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           55 |     1665 | 2024-12-19 | Copenhagen Wolves (American organization) | L   | 0.701      | -            | -                | -                | -         |   -15.99 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           54 |     2100 | 2024-12-08 | Leo Team                                  | W   | 0.630      | -            | -                | -                | -         |     5.45 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           53 |     2174 | 2024-12-07 | Copenhagen Wolves (American organization) | W   | 0.624      | 0.372        | -                | 1.000 (0.232)    | -         |     5.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           52 |     2224 | 2024-12-06 | Fire Flux Esports                         | W   | 0.617      | -            | -                | -                | -         |     6.74 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           51 |     2247 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.610      | -            | -                | -                | -         |     4.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           50 |     2287 | 2024-12-04 | ALTERNATE aTTaX                           | W   | 0.604      | -            | -                | -                | -         |     6.80 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           49 |     2329 | 2024-12-03 | Partizan Esports                          | W   | 0.597      | 0.372        | 0.097 (0.022)    | -                | -         |    10.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           48 |     2470 | 2024-12-01 | Team Spirit Academy                       | L   | 0.583      | -            | -                | -                | -         |   -10.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           47 |     2640 | 2024-11-28 | BC.Game Esports                           | W   | 0.564      | -            | -                | -                | -         |     4.71 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           46 |     2780 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.537      | -            | -                | -                | -         |   -12.76 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           45 |     2957 | 2024-11-22 | FAVBET Team                               | W   | 0.524      | -            | -                | -                | -         |     5.21 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           44 |     3101 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | W   | 0.510      | -            | -                | -                | -         |     1.84 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           43 |     3116 | 2024-11-20 | 1win                                      | L   | 0.510      | -            | -                | -                | -         |   -13.79 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           42 |     3156 | 2024-11-19 | Haspers Team                              | W   | 0.503      | -            | -                | -                | -         |     1.82 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           41 |     3163 | 2024-11-19 | K27                                       | W   | 0.503      | -            | -                | -                | -         |     4.55 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           40 |     3203 | 2024-11-18 | Endpoint                                  | W   | 0.497      | -            | -                | -                | -         |     2.66 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           39 |     3513 | 2024-11-12 | BetBoom Team                              | L   | 0.456      | -            | -                | -                | -         |    -7.76 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           38 |     3525 | 2024-11-12 | GUN5 Esports                              | W   | 0.455      | -            | -                | -                | -         |     5.67 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           37 |     3571 | 2024-11-11 | ENCE                                      | W   | 0.449      | 0.384        | 0.158 (0.027)    | -                | -         |     6.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           36 |     3627 | 2024-11-10 | 9Pandas                                   | W   | 0.442      | -            | -                | -                | -         |     7.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           35 |     3725 | 2024-11-08 | Nemiga Gaming                             | L   | 0.429      | -            | -                | -                | -         |    -5.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           34 |     3734 | 2024-11-08 | Sashi Esport                              | W   | 0.428      | -            | -                | -                | -         |     5.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           33 |     3774 | 2024-11-07 | Monte                                     | W   | 0.422      | -            | -                | -                | -         |     3.77 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           32 |     3782 | 2024-11-07 | SINNERS Esports                           | L   | 0.421      | -            | -                | -                | -         |    -8.12 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           31 |     3825 | 2024-11-06 | Passion UA                                | W   | 0.415      | -            | -                | -                | -         |     4.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           30 |     3939 | 2024-11-04 | Zero Tenacity                             | W   | 0.402      | -            | -                | -                | -         |     4.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           29 |     4049 | 2024-11-02 | Wild Lotus                                | L   | 0.390      | -            | -                | -                | -         |   -10.04 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           28 |     4167 | 2024-10-31 | GUN5 Esports                              | L   | 0.377      | -            | -                | -                | -         |    -7.48 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           27 |     4301 | 2024-10-29 | AMKAL ESPORTS                             | W   | 0.363      | -            | -                | -                | -         |     2.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           26 |     4346 | 2024-10-28 | Zero Tenacity                             | W   | 0.357      | -            | -                | -                | -         |     3.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           25 |     4360 | 2024-10-28 | OG                                        | W   | 0.356      | -            | -                | -                | -         |     3.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           24 |     4521 | 2024-10-25 | Kubix Esports                             | W   | 0.336      | -            | -                | -                | -         |     3.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           23 |     4548 | 2024-10-24 | Lazer Cats                                | W   | 0.329      | -            | -                | -                | -         |     1.32 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           22 |     4733 | 2024-10-20 | ECSTATIC                                  | W   | 0.301      | -            | -                | -                | -         |     2.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           21 |     4849 | 2024-10-17 | Leo Team                                  | W   | 0.283      | -            | -                | -                | -         |     2.13 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           20 |     4983 | 2024-10-15 | The Suspect                               | W   | 0.270      | -            | -                | -                | -         |     1.18 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           19 |     5033 | 2024-10-14 | UNiTY esports                             | W   | 0.262      | -            | -                | -                | -         |     2.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           18 |     5115 | 2024-10-12 | CYBERSHOKE Esports                        | W   | 0.250      | -            | -                | -                | -         |     2.26 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           17 |     5182 | 2024-10-11 | UNiTY esports                             | W   | 0.242      | -            | -                | -                | -         |     2.06 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           16 |     5288 | 2024-10-09 | HOTU                                      | W   | 0.227      | -            | -                | -                | -         |     1.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           15 |     5389 | 2024-10-07 | Daystar                                   | W   | 0.217      | -            | -                | -                | -         |     0.64 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           14 |     5496 | 2024-10-05 | Los kogutos                               | W   | 0.203      | -            | -                | -                | -         |     2.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           13 |     5576 | 2024-10-04 | ENCE Academy                              | L   | 0.197      | -            | -                | -                | -         |    -4.80 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           12 |     5634 | 2024-10-03 | Dynamo Eclot                              | W   | 0.188      | -            | -                | -                | -         |     3.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           11 |     5677 | 2024-10-02 | CYBERSHOKE Esports                        | W   | 0.182      | -            | -                | -                | -         |     1.71 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           10 |     5829 | 2024-09-30 | ALTERNATE aTTaX                           | W   | 0.168      | -            | -                | -                | -         |     2.01 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            9 |     5878 | 2024-09-29 | Insilio                                   | L   | 0.161      | -            | -                | -                | -         |    -4.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            8 |     5916 | 2024-09-28 | WinX                                      | L   | 0.157      | -            | -                | -                | -         |    -4.72 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            7 |     5931 | 2024-09-28 | FORZE Reload                              | W   | 0.156      | -            | -                | -                | -         |     1.27 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            6 |     6097 | 2024-09-26 | ARCRED                                    | L   | 0.143      | -            | -                | -                | -         |    -3.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            5 |     6175 | 2024-09-25 | TEAM NEXT LEVEL                           | W   | 0.137      | -            | -                | -                | -         |     0.53 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            4 |     7066 | 2024-09-11 | Daystar                                   | L   | 0.044      | -            | -                | -                | -         |    -1.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            3 |     7223 | 2024-09-08 | GameAgents                                | L   | 0.024      | -            | -                | -                | -         |    -0.69 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            2 |     7287 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.017      | -            | -                | -                | -         |    -0.30 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            1 |     7399 | 2024-09-06 | K27                                       | W   | 0.010      | -            | -                | -                | -         |     0.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,454.88)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $1,000.00      | $1,000.00       |
| 2025-02-15 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-12-08 |      0.630 | $7,000.00      | $4,411.31       |
| 2024-11-12 |      0.456 | $3,500.00      | $1,597.45       |
| 2024-11-09 |      0.436 | $5,030.36      | $2,193.81       |
| 2024-10-05 |      0.202 | $1,250.00      | $252.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
