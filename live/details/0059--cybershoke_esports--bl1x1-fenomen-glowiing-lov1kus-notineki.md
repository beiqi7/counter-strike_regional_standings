### Roster Details<br />
Team Name: CYBERSHOKE Esports<br />
Roster: bl1x1, FenomeN, glowiing, lov1kus, notineki<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  917.1<br />
<br />
Final Rank Value (917.1) = Starting Rank Value (878.7) + Head To Head Adjustments (38.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 878.7
- 400 + ( ( 0.217 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 878.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      117 | 2025-02-25 | Nemiga Gaming                             | W   | 0.776      | 0.500        | 0.074 (0.035)    | 0.313 (0.145)    | 0 (0.000) |    13.37 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           63 |      232 | 2025-02-22 | B8                                        | L   | 0.759      | -            | -                | -                | -         |    -5.95 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           62 |      252 | 2025-02-21 | BASEMENT BOYS                             | W   | 0.756      | -            | -                | -                | 0 (0.000) |     1.79 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           61 |      256 | 2025-02-21 | Tricked Esport                            | W   | 0.755      | 0.143        | 0.030 (0.004)    | 0.549 (0.071)    | 0 (0.000) |    10.33 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           60 |      273 | 2025-02-21 | Wild Lotus                                | W   | 0.754      | -            | -                | -                | 0 (0.000) |     5.04 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           59 |      279 | 2025-02-21 | AMKAL ESPORTS                             | W   | 0.754      | 0.143        | -                | 0.588 (0.076)    | 0 (0.000) |     7.44 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           58 |      290 | 2025-02-21 | Nemiga Gaming                             | W   | 0.753      | 0.435        | 0.074 (0.029)    | 0.313 (0.123)    | 0 (0.000) |    14.09 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           57 |      307 | 2025-02-20 | THE GENTLEMEN ESPORTS                     | W   | 0.749      | -            | -                | -                | 0 (0.000) |     3.88 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           56 |      394 | 2025-02-18 | Sashi Esport                              | L   | 0.738      | -            | -                | -                | -         |    -8.78 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           55 |      400 | 2025-02-18 | ECSTATIC                                  | W   | 0.736      | 0.435        | 0.027 (0.010)    | 0.659 (0.253)    | 0 (0.000) |    11.54 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           54 |      414 | 2025-02-17 | OG                                        | L   | 0.733      | -            | -                | -                | -         |   -10.01 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           53 |      425 | 2025-02-17 | PLUSH                                     | W   | 0.732      | -            | -                | -                | 0 (0.000) |     1.78 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           52 |      429 | 2025-02-17 | Little Red Door                           | W   | 0.732      | -            | -                | -                | 0 (0.000) |     3.98 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           51 |      449 | 2025-02-16 | FLuffy Gangsters                          | W   | 0.728      | 0.143        | 0.011 (0.001)    | 0.635 (0.079)    | -         |     7.96 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           50 |      482 | 2025-02-16 | 500                                       | W   | 0.725      | 0.435        | 0.118 (0.044)    | 1.000 (0.378)    | -         |    18.17 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           49 |      598 | 2025-02-14 | ALASKA                                    | W   | 0.714      | 0.435        | 0.033 (0.012)    | 0.737 (0.274)    | -         |    16.51 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           48 |      641 | 2025-02-12 | BC.Game Esports                           | L   | 0.703      | -            | -                | -                | -         |    -4.07 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           47 |      669 | 2025-02-11 | Monte                                     | L   | 0.697      | -            | -                | -                | -         |    -7.96 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           46 |      728 | 2025-02-09 | KONO.ECF                                  | W   | 0.688      | -            | -                | -                | -         |     5.75 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           45 |      787 | 2025-02-08 | TEAM NEXT LEVEL                           | L   | 0.682      | -            | -                | -                | -         |   -13.32 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           44 |      807 | 2025-02-08 | Inner Circle Esports                      | W   | 0.682      | -            | -                | -                | -         |     3.15 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           43 |      813 | 2025-02-08 | AMKAL ESPORTS                             | W   | 0.682      | -            | -                | -                | -         |     8.65 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           42 |      861 | 2025-02-07 | XP Academy                                | W   | 0.678      | -            | -                | -                | -         |     3.90 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           41 |      899 | 2025-02-07 | Alliance                                  | W   | 0.675      | 0.143        | 0.013 (0.001)    | -                | -         |    12.28 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           40 |      936 | 2025-02-06 | AMKAL ESPORTS                             | L   | 0.670      | -            | -                | -                | -         |   -11.83 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           39 |     1095 | 2025-02-04 | Bad News Eagles                           | L   | 0.659      | -            | -                | -                | -         |   -17.28 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           38 |     1270 | 2025-01-27 | 500                                       | L   | 0.616      | -            | -                | -                | -         |    -5.78 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           37 |     1358 | 2025-01-23 | Fire Flux Esports                         | L   | 0.594      | -            | -                | -                | -         |    -8.42 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           36 |     1423 | 2025-01-21 | Betera Esports                            | L   | 0.583      | -            | -                | -                | -         |   -14.50 | bl1x1, FenomeN, glowiing, lov1kus, notineki    |
|           35 |     1857 | 2024-12-15 | Fire Flux Esports                         | W   | 0.377      | -            | -                | -                | -         |     6.56 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           34 |     1918 | 2024-12-14 | Rebels Gaming                             | W   | 0.372      | -            | -                | -                | -         |     4.39 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           33 |     2007 | 2024-12-13 | Copenhagen Wolves (American organization) | L   | 0.366      | -            | -                | -                | -         |    -5.80 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           32 |     2105 | 2024-12-11 | Insilio                                   | W   | 0.355      | -            | -                | -                | -         |     1.39 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           31 |     2140 | 2024-12-10 | Leo Team                                  | W   | 0.349      | -            | -                | -                | -         |     5.27 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           30 |     2175 | 2024-12-09 | Endpoint                                  | L   | 0.343      | -            | -                | -                | -         |    -7.41 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           29 |     2327 | 2024-12-07 | Team Sampi                                | W   | 0.331      | -            | -                | -                | -         |     3.25 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           28 |     2382 | 2024-12-05 | 500                                       | L   | 0.321      | -            | -                | -                | -         |    -2.73 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           27 |     2388 | 2024-12-05 | FAVBET Team                               | L   | 0.319      | -            | -                | -                | -         |    -4.86 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           26 |     2472 | 2024-12-03 | ECSTATIC                                  | L   | 0.309      | -            | -                | -                | -         |    -4.96 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           25 |     2515 | 2024-12-02 | Leo Team                                  | L   | 0.304      | -            | -                | -                | -         |    -5.29 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           24 |     2657 | 2024-11-30 | Fire Flux Esports                         | W   | 0.293      | 0.372        | -                | 1.000 (0.131)    | -         |     5.04 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           23 |     2715 | 2024-11-29 | Partizan Esports                          | W   | 0.287      | 0.372        | 0.082 (0.010)    | 0.618 (0.079)    | -         |     6.71 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           22 |     3004 | 2024-11-23 | Copenhagen Wolves (American organization) | L   | 0.254      | -            | -                | -                | -         |    -4.08 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           21 |     3132 | 2024-11-21 | RUSTEC                                    | W   | 0.244      | -            | -                | -                | -         |     1.76 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           20 |     3242 | 2024-11-20 | FLuffy Gangsters                          | L   | 0.237      | -            | -                | -                | -         |    -4.70 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           19 |     3287 | 2024-11-19 | Flame Sharks                              | W   | 0.232      | -            | -                | -                | -         |     1.06 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           18 |     3313 | 2024-11-18 | Endpoint                                  | W   | 0.227      | -            | -                | -                | -         |     2.44 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           17 |     3550 | 2024-11-14 | Lilmix                                    | W   | 0.204      | -            | -                | -                | -         |     1.36 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           16 |     3608 | 2024-11-13 | 1win                                      | W   | 0.198      | -            | -                | -                | -         |     1.98 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           15 |     3928 | 2024-11-06 | GameAgents                                | W   | 0.160      | -            | -                | -                | -         |     1.18 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           14 |     3951 | 2024-11-06 | Illuminar Gaming                          | W   | 0.159      | -            | -                | -                | -         |     2.02 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           13 |     4250 | 2024-11-01 | Nexus Gaming                              | W   | 0.132      | 0.372        | 0.161 (0.010)    | -                | -         |     3.38 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           12 |     4324 | 2024-10-31 | Rare Atom                                 | L   | 0.125      | -            | -                | -                | -         |    -2.24 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           11 |     4394 | 2024-10-30 | Natus Vincere Junior                      | L   | 0.120      | -            | -                | -                | -         |    -1.27 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|           10 |     4441 | 2024-10-29 | KONO.ECF                                  | L   | 0.116      | -            | -                | -                | -         |    -1.56 | FenomeN, levantino, lov1kus, notineki, TruNiQ  |
|            9 |     4663 | 2024-10-25 | Team PeeP                                 | L   | 0.093      | -            | -                | -                | -         |    -2.33 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            8 |     4708 | 2024-10-24 | GenOne                                    | W   | 0.088      | -            | -                | -                | -         |     1.13 | FenomeN, levantino, lov1kus, notineki          |
|            7 |     4717 | 2024-10-24 | Viperio                                   | L   | 0.087      | -            | -                | -                | -         |    -1.85 | FenomeN, levantino, lov1kus, notineki          |
|            6 |     4823 | 2024-10-21 | QUAZAR                                    | L   | 0.071      | -            | -                | -                | -         |    -1.63 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            5 |     4958 | 2024-10-19 | Natus Vincere Junior                      | L   | 0.059      | -            | -                | -                | -         |    -0.65 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            4 |     5156 | 2024-10-16 | Monte                                     | L   | 0.041      | -            | -                | -                | -         |    -0.52 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            3 |     5336 | 2024-10-12 | 500                                       | L   | 0.021      | -            | -                | -                | -         |    -0.18 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            2 |     5422 | 2024-10-10 | 3DMAX                                     | L   | 0.010      | -            | -                | -                | -         |    -0.01 | FenomeN, levantino, lov1kus, notineki, sstiNiX |
|            1 |     5438 | 2024-10-10 | Tricked Esport                            | L   | 0.008      | -            | -                | -                | -         |    -0.15 | FenomeN, levantino, lov1kus, notineki, sstiNiX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,936.76)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      0.939 | $500.00        | $469.58         |
| 2025-02-23 |      0.919 | $2,000.00      | $1,837.41       |
| 2024-12-08 |      0.405 | $1,250.00      | $506.60         |
| 2024-11-03 |      0.172 | $715.22        | $123.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
