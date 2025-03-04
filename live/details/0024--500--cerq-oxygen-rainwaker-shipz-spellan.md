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
|           87 |       76 | 2025-02-26 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.819 (0.356)    | 0 (0.000) |    13.77 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           86 |      104 | 2025-02-25 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -22.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           85 |      133 | 2025-02-24 | Betera Esports                            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           84 |      457 | 2025-02-16 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -26.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           83 |      498 | 2025-02-15 | Partizan Esports                          | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.819 (0.356)    | 0 (0.000) |    12.89 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           82 |      518 | 2025-02-15 | B8                                        | W   | 1.000      | 0.435        | 0.148 (0.064)    | 0.790 (0.343)    | 0 (0.000) |    17.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           81 |      557 | 2025-02-14 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -13.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           80 |      567 | 2025-02-14 | Dynamo Eclot                              | W   | 1.000      | 0.435        | 0.150 (0.065)    | 0.705 (0.306)    | 0 (0.000) |    13.04 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           79 |      588 | 2025-02-13 | 9Pandas                                   | W   | 1.000      | 0.435        | 0.104 (0.045)    | 0.628 (0.273)    | 0 (0.000) |    13.40 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           78 |      597 | 2025-02-13 | Fnatic                                    | L   | 1.000      | -            | -                | -                | -         |   -15.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           77 |      643 | 2025-02-11 | ALASKA                                    | W   | 1.000      | 0.435        | -                | 0.888 (0.386)    | 0 (0.000) |     8.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           76 |      717 | 2025-02-09 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           75 |      770 | 2025-02-08 | OG                                        | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.984 (0.428)    | 0 (0.000) |    10.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           74 |      793 | 2025-02-08 | BIG                                       | W   | 1.000      | 0.143        | 0.244 (0.035)    | -                | 0 (0.000) |    26.52 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           73 |      873 | 2025-02-07 | BC.Game Esports                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           72 |      916 | 2025-02-06 | SAW                                       | W   | 1.000      | 0.143        | 0.315 (0.045)    | -                | -         |    25.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           71 |      968 | 2025-02-05 | MoneyF                                    | W   | 1.000      | -            | -                | -                | -         |     2.19 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           70 |      974 | 2025-02-05 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |   -12.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           69 |      983 | 2025-02-05 | Eco Warriors                              | W   | 1.000      | -            | -                | -                | -         |     2.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           68 |     1012 | 2025-02-04 | TEAM NEXT LEVEL                           | W   | 1.000      | -            | -                | -                | -         |     4.54 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           67 |     1014 | 2025-02-04 | Fire Flux Esports                         | W   | 1.000      | -            | -                | -                | -         |    13.57 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           66 |     1018 | 2025-02-04 | Monte                                     | W   | 1.000      | -            | -                | -                | -         |    14.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           65 |     1044 | 2025-02-04 | Eternal Fire Academy                      | W   | 1.000      | -            | -                | -                | -         |     1.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           64 |     1093 | 2025-02-03 | 9INE                                      | W   | 1.000      | 0.435        | -                | 0.862 (0.375)    | -         |    13.90 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           63 |     1106 | 2025-02-02 | Betclic Apogee Esports                    | L   | 1.000      | -            | -                | -                | -         |   -18.82 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           62 |     1219 | 2025-01-27 | CYBERSHOKE Esports                        | W   | 0.964      | 0.500        | -                | 1.000 (0.482)    | -         |     8.86 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           61 |     1245 | 2025-01-24 | Nemiga Gaming                             | L   | 0.944      | -            | -                | -                | -         |   -12.54 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           60 |     1269 | 2025-01-23 | Sashi Esport                              | L   | 0.938      | -            | -                | -                | -         |   -15.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           59 |     1566 | 2024-12-21 | Betclic Apogee Esports                    | L   | 0.717      | -            | -                | -                | -         |   -15.96 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           58 |     1626 | 2024-12-20 | 9INE                                      | L   | 0.711      | -            | -                | -                | -         |   -14.40 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           57 |     1632 | 2024-12-20 | Ex-GODSENT                                | W   | 0.710      | -            | -                | -                | -         |     1.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           56 |     1638 | 2024-12-20 | JANO Esports                              | L   | 0.708      | -            | -                | -                | -         |   -16.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           55 |     1663 | 2024-12-19 | Copenhagen Wolves (American organization) | L   | 0.702      | -            | -                | -                | -         |   -16.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           54 |     2098 | 2024-12-08 | Leo Team                                  | W   | 0.631      | -            | -                | -                | -         |     5.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           53 |     2172 | 2024-12-07 | Copenhagen Wolves (American organization) | W   | 0.624      | 0.372        | -                | 1.000 (0.232)    | -         |     5.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           52 |     2222 | 2024-12-06 | Fire Flux Esports                         | W   | 0.617      | -            | -                | -                | -         |     6.75 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           51 |     2245 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.610      | -            | -                | -                | -         |     4.67 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           50 |     2285 | 2024-12-04 | ALTERNATE aTTaX                           | W   | 0.604      | -            | -                | -                | -         |     6.80 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           49 |     2327 | 2024-12-03 | Partizan Esports                          | W   | 0.598      | 0.372        | 0.097 (0.022)    | -                | -         |    10.46 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           48 |     2468 | 2024-12-01 | Team Spirit Academy                       | L   | 0.583      | -            | -                | -                | -         |   -10.51 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           47 |     2638 | 2024-11-28 | BC.Game Esports                           | W   | 0.564      | -            | -                | -                | -         |     4.71 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           46 |     2778 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.537      | -            | -                | -                | -         |   -12.77 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           45 |     2955 | 2024-11-22 | FAVBET Team                               | W   | 0.524      | -            | -                | -                | -         |     5.21 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           44 |     3099 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | W   | 0.511      | -            | -                | -                | -         |     1.84 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           43 |     3114 | 2024-11-20 | 1win                                      | L   | 0.510      | -            | -                | -                | -         |   -13.79 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           42 |     3154 | 2024-11-19 | Haspers Team                              | W   | 0.504      | -            | -                | -                | -         |     1.82 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           41 |     3161 | 2024-11-19 | K27                                       | W   | 0.503      | -            | -                | -                | -         |     4.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           40 |     3201 | 2024-11-18 | Endpoint                                  | W   | 0.497      | -            | -                | -                | -         |     2.67 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           39 |     3511 | 2024-11-12 | BetBoom Team                              | L   | 0.457      | -            | -                | -                | -         |    -7.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           38 |     3523 | 2024-11-12 | GUN5 Esports                              | W   | 0.455      | -            | -                | -                | -         |     5.68 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           37 |     3569 | 2024-11-11 | ENCE                                      | W   | 0.449      | 0.384        | 0.158 (0.027)    | -                | -         |     6.57 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           36 |     3625 | 2024-11-10 | 9Pandas                                   | W   | 0.443      | -            | -                | -                | -         |     7.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           35 |     3723 | 2024-11-08 | Nemiga Gaming                             | L   | 0.429      | -            | -                | -                | -         |    -5.60 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           34 |     3732 | 2024-11-08 | Sashi Esport                              | W   | 0.428      | -            | -                | -                | -         |     5.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           33 |     3772 | 2024-11-07 | Monte                                     | W   | 0.423      | -            | -                | -                | -         |     3.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           32 |     3780 | 2024-11-07 | SINNERS Esports                           | L   | 0.422      | -            | -                | -                | -         |    -8.13 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           31 |     3823 | 2024-11-06 | Passion UA                                | W   | 0.415      | -            | -                | -                | -         |     4.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           30 |     3937 | 2024-11-04 | Zero Tenacity                             | W   | 0.403      | -            | -                | -                | -         |     4.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           29 |     4047 | 2024-11-02 | Wild Lotus                                | L   | 0.390      | -            | -                | -                | -         |   -10.04 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           28 |     4165 | 2024-10-31 | GUN5 Esports                              | L   | 0.378      | -            | -                | -                | -         |    -7.49 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           27 |     4299 | 2024-10-29 | AMKAL ESPORTS                             | W   | 0.363      | -            | -                | -                | -         |     2.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           26 |     4344 | 2024-10-28 | Zero Tenacity                             | W   | 0.358      | -            | -                | -                | -         |     3.43 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           25 |     4358 | 2024-10-28 | OG                                        | W   | 0.357      | -            | -                | -                | -         |     3.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           24 |     4519 | 2024-10-25 | Kubix Esports                             | W   | 0.336      | -            | -                | -                | -         |     3.89 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           23 |     4546 | 2024-10-24 | Lazer Cats                                | W   | 0.329      | -            | -                | -                | -         |     1.32 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           22 |     4731 | 2024-10-20 | ECSTATIC                                  | W   | 0.302      | -            | -                | -                | -         |     2.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           21 |     4847 | 2024-10-17 | Leo Team                                  | W   | 0.283      | -            | -                | -                | -         |     2.14 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           20 |     4981 | 2024-10-15 | The Suspect                               | W   | 0.270      | -            | -                | -                | -         |     1.18 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           19 |     5031 | 2024-10-14 | UNiTY esports                             | W   | 0.262      | -            | -                | -                | -         |     2.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           18 |     5113 | 2024-10-12 | CYBERSHOKE Esports                        | W   | 0.250      | -            | -                | -                | -         |     2.26 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           17 |     5180 | 2024-10-11 | UNiTY esports                             | W   | 0.243      | -            | -                | -                | -         |     2.06 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           16 |     5286 | 2024-10-09 | HOTU                                      | W   | 0.228      | -            | -                | -                | -         |     1.06 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           15 |     5387 | 2024-10-07 | Daystar                                   | W   | 0.217      | -            | -                | -                | -         |     0.64 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           14 |     5494 | 2024-10-05 | Los kogutos                               | W   | 0.204      | -            | -                | -                | -         |     2.91 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           13 |     5574 | 2024-10-04 | ENCE Academy                              | L   | 0.197      | -            | -                | -                | -         |    -4.81 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           12 |     5632 | 2024-10-03 | Dynamo Eclot                              | W   | 0.189      | -            | -                | -                | -         |     3.57 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           11 |     5675 | 2024-10-02 | CYBERSHOKE Esports                        | W   | 0.183      | -            | -                | -                | -         |     1.72 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           10 |     5827 | 2024-09-30 | ALTERNATE aTTaX                           | W   | 0.169      | -            | -                | -                | -         |     2.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            9 |     5876 | 2024-09-29 | Insilio                                   | L   | 0.162      | -            | -                | -                | -         |    -4.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            8 |     5914 | 2024-09-28 | WinX                                      | L   | 0.157      | -            | -                | -                | -         |    -4.73 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            7 |     5929 | 2024-09-28 | FORZE Reload                              | W   | 0.157      | -            | -                | -                | -         |     1.27 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            6 |     6095 | 2024-09-26 | ARCRED                                    | L   | 0.143      | -            | -                | -                | -         |    -3.59 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            5 |     6173 | 2024-09-25 | TEAM NEXT LEVEL                           | W   | 0.138      | -            | -                | -                | -         |     0.53 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            4 |     7064 | 2024-09-11 | Daystar                                   | L   | 0.044      | -            | -                | -                | -         |    -1.26 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            3 |     7221 | 2024-09-08 | GameAgents                                | L   | 0.024      | -            | -                | -                | -         |    -0.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            2 |     7285 | 2024-09-07 | Natus Vincere Junior                      | L   | 0.017      | -            | -                | -                | -         |    -0.30 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            1 |     7397 | 2024-09-06 | K27                                       | W   | 0.010      | -            | -                | -                | -         |     0.12 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,461.14)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $1,000.00      | $1,000.00       |
| 2025-02-15 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-12-08 |      0.631 | $7,000.00      | $4,413.92       |
| 2024-11-12 |      0.457 | $3,500.00      | $1,598.75       |
| 2024-11-09 |      0.436 | $5,030.36      | $2,195.68       |
| 2024-10-05 |      0.202 | $1,250.00      | $252.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
