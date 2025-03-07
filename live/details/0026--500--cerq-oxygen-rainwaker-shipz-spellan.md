### Roster Details<br />
Team Name: 500<br />
Roster: CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN<br />
Global Rank: [26](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1075.9<br />
<br />
Final Rank Value (1075.9) = Starting Rank Value (1043.9) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.518[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1043.9
- 400 + ( ( 0.292 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1043.9


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
|           73 |       82 | 2025-02-26 | Partizan Esports                          | W   | 0.781      | 0.435        | 0.082 (0.033)    | 0.618 (0.252)    | 0 (0.000) |    11.19 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           72 |      112 | 2025-02-25 | Fire Flux Esports                         | L   | 0.777      | -            | -                | -                | -         |   -17.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           71 |      141 | 2025-02-24 | Betera Esports                            | W   | 0.771      | -            | -                | -                | 0 (0.000) |     2.24 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           70 |      482 | 2025-02-16 | CYBERSHOKE Esports                        | L   | 0.725      | -            | -                | -                | -         |   -18.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           69 |      523 | 2025-02-15 | Partizan Esports                          | W   | 0.721      | 0.435        | 0.082 (0.031)    | 0.618 (0.233)    | 0 (0.000) |     9.98 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           68 |      544 | 2025-02-15 | B8                                        | W   | 0.720      | 0.435        | 0.134 (0.050)    | 0.740 (0.278)    | 0 (0.000) |    11.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           67 |      583 | 2025-02-14 | BC.Game Esports                           | L   | 0.716      | -            | -                | -                | -         |   -10.70 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           66 |      591 | 2025-02-14 | Dynamo Eclot                              | W   | 0.715      | 0.435        | 0.114 (0.043)    | 0.468 (0.174)    | 0 (0.000) |     8.68 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           65 |      607 | 2025-02-13 | 9Pandas                                   | W   | 0.710      | 0.435        | 0.084 (0.031)    | 0.481 (0.178)    | 0 (0.000) |     8.96 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           64 |      616 | 2025-02-13 | Fnatic                                    | L   | 0.709      | -            | -                | -                | -         |   -12.62 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           63 |      664 | 2025-02-11 | ALASKA                                    | W   | 0.698      | 0.435        | 0.033 (0.012)    | 0.737 (0.268)    | 0 (0.000) |     9.92 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           62 |      741 | 2025-02-09 | Astralis                                  | L   | 0.687      | -            | -                | -                | -         |    -0.27 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           61 |      794 | 2025-02-08 | OG                                        | W   | 0.682      | 0.435        | 0.041 (0.015)    | 0.989 (0.352)    | 0 (0.000) |     6.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           60 |      817 | 2025-02-08 | BIG                                       | W   | 0.681      | 0.143        | 0.234 (0.027)    | -                | 0 (0.000) |    18.50 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           59 |      897 | 2025-02-07 | BC.Game Esports                           | W   | 0.675      | -            | -                | -                | 0 (0.000) |    10.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           58 |      940 | 2025-02-06 | SAW                                       | W   | 0.669      | 0.143        | 0.316 (0.036)    | -                | -         |    17.61 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           57 |      991 | 2025-02-05 | MoneyF                                    | W   | 0.665      | -            | -                | -                | -         |     1.59 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           56 |      997 | 2025-02-05 | BC.Game Esports                           | L   | 0.665      | -            | -                | -                | -         |    -9.88 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           55 |     1006 | 2025-02-05 | Eco Warriors                              | W   | 0.664      | -            | -                | -                | -         |     1.47 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           54 |     1034 | 2025-02-04 | TEAM NEXT LEVEL                           | W   | 0.660      | -            | -                | -                | -         |     3.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           53 |     1036 | 2025-02-04 | Fire Flux Esports                         | W   | 0.660      | -            | -                | -                | -         |     8.13 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           52 |     1040 | 2025-02-04 | Monte                                     | W   | 0.660      | -            | -                | -                | -         |     9.07 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           51 |     1066 | 2025-02-04 | Eternal Fire Academy                      | W   | 0.659      | -            | -                | -                | -         |     1.23 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           50 |     1118 | 2025-02-03 | 9INE                                      | W   | 0.653      | 0.435        | 0.039 (0.013)    | 0.876 (0.299)    | -         |     8.41 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           49 |     1131 | 2025-02-02 | Betclic Apogee Esports                    | L   | 0.648      | -            | -                | -                | -         |   -12.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           48 |     1270 | 2025-01-27 | CYBERSHOKE Esports                        | W   | 0.616      | 0.500        | -                | 1.000 (0.370)    | -         |     5.78 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           47 |     1320 | 2025-01-24 | Nemiga Gaming                             | L   | 0.599      | -            | -                | -                | -         |   -11.05 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           46 |     1360 | 2025-01-23 | Sashi Esport                              | L   | 0.594      | -            | -                | -                | -         |   -10.53 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           45 |     1687 | 2024-12-21 | Betclic Apogee Esports                    | L   | 0.410      | -            | -                | -                | -         |    -9.29 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           44 |     1748 | 2024-12-20 | 9INE                                      | L   | 0.404      | -            | -                | -                | -         |    -8.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           43 |     1754 | 2024-12-20 | Ex-GODSENT                                | W   | 0.404      | -            | -                | -                | -         |     0.74 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           42 |     1760 | 2024-12-20 | JANO Esports                              | L   | 0.403      | -            | -                | -                | -         |    -8.67 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           41 |     1785 | 2024-12-19 | Copenhagen Wolves (American organization) | L   | 0.397      | -            | -                | -                | -         |    -8.99 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           40 |     2226 | 2024-12-08 | Leo Team                                  | W   | 0.338      | -            | -                | -                | -         |     2.58 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           39 |     2307 | 2024-12-07 | Copenhagen Wolves (American organization) | W   | 0.332      | 0.372        | -                | 1.000 (0.148)    | -         |     2.91 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           38 |     2359 | 2024-12-06 | Fire Flux Esports                         | W   | 0.327      | -            | -                | -                | -         |     3.25 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           37 |     2382 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.321      | -            | -                | -                | -         |     2.73 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           36 |     2422 | 2024-12-04 | ALTERNATE aTTaX                           | W   | 0.316      | -            | -                | -                | -         |     3.15 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           35 |     2464 | 2024-12-03 | Partizan Esports                          | W   | 0.310      | -            | -                | -                | -         |     5.17 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           34 |     2588 | 2024-12-01 | Team Spirit Academy                       | L   | 0.298      | -            | -                | -                | -         |    -5.83 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           33 |     2756 | 2024-11-28 | BC.Game Esports                           | W   | 0.282      | -            | -                | -                | -         |     2.15 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           32 |     2899 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.260      | -            | -                | -                | -         |    -6.02 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           31 |     3075 | 2024-11-22 | FAVBET Team                               | W   | 0.249      | -            | -                | -                | -         |     2.33 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           30 |     3222 | 2024-11-20 | THE GENTLEMEN ESPORTS                     | W   | 0.238      | -            | -                | -                | -         |     0.44 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           29 |     3237 | 2024-11-20 | 1win                                      | L   | 0.237      | -            | -                | -                | -         |    -6.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           28 |     3281 | 2024-11-19 | Haspers Team                              | W   | 0.232      | -            | -                | -                | -         |     0.95 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           27 |     3289 | 2024-11-19 | K27                                       | W   | 0.231      | -            | -                | -                | -         |     2.85 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           26 |     3333 | 2024-11-18 | Endpoint                                  | W   | 0.226      | -            | -                | -                | -         |     1.20 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           25 |     3646 | 2024-11-12 | BetBoom Team                              | L   | 0.193      | -            | -                | -                | -         |    -3.45 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           24 |     3658 | 2024-11-12 | GUN5 Esports                              | W   | 0.191      | -            | -                | -                | -         |     2.56 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           23 |     3704 | 2024-11-11 | ENCE                                      | W   | 0.187      | -            | -                | -                | -         |     1.92 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           22 |     3760 | 2024-11-10 | 9Pandas                                   | W   | 0.181      | -            | -                | -                | -         |     2.57 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           21 |     3858 | 2024-11-08 | Nemiga Gaming                             | L   | 0.170      | -            | -                | -                | -         |    -3.21 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           20 |     3867 | 2024-11-08 | Sashi Esport                              | W   | 0.169      | -            | -                | -                | -         |     2.13 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           19 |     3908 | 2024-11-07 | Monte                                     | W   | 0.165      | -            | -                | -                | -         |     1.11 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           18 |     3916 | 2024-11-07 | SINNERS Esports                           | L   | 0.164      | -            | -                | -                | -         |    -3.36 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           17 |     3962 | 2024-11-06 | Passion UA                                | W   | 0.158      | -            | -                | -                | -         |     1.36 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           16 |     4007 | 2024-11-05 | Lilmix                                    | W   | 0.154      | -            | -                | -                | -         |     0.48 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           15 |     4080 | 2024-11-04 | Zero Tenacity                             | W   | 0.148      | -            | -                | -                | -         |     1.42 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           14 |     4188 | 2024-11-02 | Wild Lotus                                | L   | 0.138      | -            | -                | -                | -         |    -4.00 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           13 |     4306 | 2024-10-31 | GUN5 Esports                              | L   | 0.127      | -            | -                | -                | -         |    -2.35 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           12 |     4454 | 2024-10-29 | AMKAL ESPORTS                             | W   | 0.115      | -            | -                | -                | -         |     0.68 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           11 |     4502 | 2024-10-28 | Zero Tenacity                             | W   | 0.110      | -            | -                | -                | -         |     1.04 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|           10 |     4517 | 2024-10-28 | OG                                        | W   | 0.109      | -            | -                | -                | -         |     1.03 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            9 |     4685 | 2024-10-25 | Kubix Esports                             | W   | 0.092      | -            | -                | -                | -         |     0.98 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            8 |     4716 | 2024-10-24 | Lazer Cats                                | W   | 0.087      | -            | -                | -                | -         |     0.36 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            7 |     4920 | 2024-10-20 | ECSTATIC                                  | W   | 0.064      | -            | -                | -                | -         |     0.55 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            6 |     5042 | 2024-10-17 | Leo Team                                  | W   | 0.048      | -            | -                | -                | -         |     0.32 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            5 |     5199 | 2024-10-15 | The Suspect                               | W   | 0.037      | -            | -                | -                | -         |     0.16 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            4 |     5252 | 2024-10-14 | UNiTY esports                             | W   | 0.031      | -            | -                | -                | -         |     0.19 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            3 |     5336 | 2024-10-12 | CYBERSHOKE Esports                        | W   | 0.021      | -            | -                | -                | -         |     0.18 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            2 |     5407 | 2024-10-11 | UNiTY esports                             | W   | 0.015      | -            | -                | -                | -         |     0.09 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |
|            1 |     5527 | 2024-10-09 | HOTU                                      | W   | 0.002      | -            | -                | -                | -         |     0.01 | CeRq, Oxygen, Rainwaker, SHiPZ, SPELLAN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,695.10)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      0.939 | $1,000.00      | $939.17         |
| 2025-02-15 |      0.866 | $22,000.00     | $19,046.30      |
| 2024-12-08 |      0.405 | $7,000.00      | $2,836.94       |
| 2024-11-12 |      0.232 | $3,500.00      | $810.27         |
| 2024-11-09 |      0.211 | $5,030.36      | $1,062.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
