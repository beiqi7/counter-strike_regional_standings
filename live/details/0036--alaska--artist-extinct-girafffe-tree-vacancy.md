### Roster Details<br />
Team Name: ALASKA<br />
Roster: arTisT, Extinct, Girafffe, Tree, Vacancy<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.2<br />
<br />
Final Rank Value (993.2) = Starting Rank Value (1226.0) + Head To Head Adjustments (-232.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.737[<sup>2</sup>](#table1)

The average of these factors is 0.375<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1226.0
- 400 + ( ( 0.375 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1226.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           79 |       35 | 2025-02-27 | RUSH B (Russian team)                     | L   | 0.787      | -            | -                | -                | -         |   -16.20 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           78 |       64 | 2025-02-26 | ECSTATIC                                  | L   | 0.783      | -            | -                | -                | -         |   -18.02 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           77 |      190 | 2025-02-23 | 8Sins                                     | W   | 0.765      | 0.143        | 0.006 (0.001)    | -                | 1 (0.918) |    10.78 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           76 |      195 | 2025-02-23 | Ctrl Alt Defeat                           | W   | 0.764      | -            | -                | -                | 1 (0.916) |    11.50 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           75 |      226 | 2025-02-22 | 8Sins                                     | L   | 0.760      | -            | -                | -                | -         |   -13.11 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           74 |      234 | 2025-02-22 | Belfast Storm                             | W   | 0.759      | -            | -                | -                | 1 (0.911) |     4.46 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           73 |      260 | 2025-02-21 | Ctrl Alt Defeat                           | W   | 0.755      | -            | -                | -                | 1 (0.906) |    11.20 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           72 |      598 | 2025-02-14 | CYBERSHOKE Esports                        | L   | 0.714      | -            | -                | -                | -         |   -16.51 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           71 |      635 | 2025-02-12 | SINNERS Esports                           | L   | 0.704      | -            | -                | -                | -         |   -14.75 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           70 |      664 | 2025-02-11 | 500                                       | L   | 0.698      | -            | -                | -                | -         |    -9.92 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           69 |      747 | 2025-02-09 | Aurora Gaming                             | W   | 0.686      | 0.143        | 0.007 (0.001)    | 0.633 (0.074)    | 0 (0.000) |     5.19 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           68 |      793 | 2025-02-08 | Betclic Apogee Esports                    | W   | 0.682      | 0.143        | 0.012 (0.001)    | 0.528 (0.062)    | -         |     7.73 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           67 |      871 | 2025-02-07 | Little Red Door                           | L   | 0.677      | -            | -                | -                | -         |   -20.06 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           66 |      894 | 2025-02-07 | Copenhagen Wolves (American organization) | L   | 0.675      | -            | -                | -                | -         |   -15.70 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           65 |      923 | 2025-02-06 | FAVBET Team                               | W   | 0.671      | 0.143        | 0.023 (0.003)    | 0.790 (0.091)    | -         |     5.86 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           64 |     1240 | 2025-01-28 | Betclic Apogee Esports                    | L   | 0.620      | -            | -                | -                | -         |   -14.54 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           63 |     1292 | 2025-01-25 | Fire Flux Esports                         | L   | 0.603      | -            | -                | -                | -         |   -13.51 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           62 |     1326 | 2025-01-24 | Chimera Esports                           | W   | 0.599      | 0.143        | 0.023 (0.002)    | 0.430 (0.044)    | -         |     4.68 | arTisT, Extinct, Girafffe, Tree, Vacancy    |
|           61 |     1591 | 2024-12-27 | NEVERMORE (Ukrainian team)                | L   | 0.443      | -            | -                | -                | -         |   -11.84 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           60 |     1616 | 2024-12-24 | WOPA Esport                               | W   | 0.425      | 0.333        | 0.031 (0.005)    | 0.611 (0.104)    | -         |     2.85 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           59 |     1652 | 2024-12-22 | Heimo Esports                             | W   | 0.414      | 0.333        | -                | 0.528 (0.088)    | -         |     1.50 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           58 |     1697 | 2024-12-21 | WOPA Esport                               | L   | 0.409      | -            | -                | -                | -         |   -10.47 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           57 |     1761 | 2024-12-20 | Dark Cloud Esports                        | W   | 0.403      | 0.333        | 0.035 (0.006)    | 0.667 (0.107)    | -         |     2.53 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           56 |     1782 | 2024-12-19 | XI Esport                                 | L   | 0.397      | -            | -                | -                | -         |   -11.43 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           55 |     1796 | 2024-12-18 | ENCE Academy                              | L   | 0.392      | -            | -                | -                | -         |   -10.38 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           54 |     1814 | 2024-12-17 | Preasy Esport                             | W   | 0.387      | 0.333        | 0.010 (0.002)    | 0.647 (0.100)    | -         |     1.50 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           53 |     1817 | 2024-12-17 | Illuminar Gaming                          | W   | 0.386      | 0.333        | -                | 0.334 (0.052)    | -         |     1.58 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           52 |     1859 | 2024-12-15 | G2 Ares                                   | W   | 0.377      | -            | -                | -                | -         |     0.96 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           51 |     1932 | 2024-12-14 | Viperio                                   | L   | 0.371      | -            | -                | -                | -         |   -10.29 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           50 |     1950 | 2024-12-14 | TEAM NEXT LEVEL                           | W   | 0.370      | 0.333        | 0.041 (0.006)    | 0.335 (0.050)    | -         |     2.06 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           49 |     2143 | 2024-12-10 | ESC Gaming                                | W   | 0.349      | -            | -                | -                | -         |     0.44 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           48 |     2159 | 2024-12-10 | Illuminar Gaming                          | L   | 0.347      | -            | -                | -                | -         |    -9.59 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           47 |     2323 | 2024-12-07 | Belfast Storm                             | W   | 0.332      | -            | -                | -                | 1 (0.398) |     1.15 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           46 |     2858 | 2024-11-26 | BC.Game Esports                           | L   | 0.269      | -            | -                | -                | -         |    -7.25 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           45 |     2862 | 2024-11-25 | TRAXXXMANIA                               | W   | 0.266      | -            | -                | -                | -         |     0.49 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           44 |     3111 | 2024-11-22 | Astralis Talent                           | L   | 0.247      | -            | -                | -                | -         |    -6.89 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           43 |     3125 | 2024-11-21 | Grindas                                   | W   | 0.244      | -            | -                | -                | -         |     0.27 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           42 |     3135 | 2024-11-21 | Illuminar Gaming                          | W   | 0.244      | -            | -                | -                | -         |     0.88 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           41 |     3150 | 2024-11-21 | Viperio                                   | L   | 0.243      | -            | -                | -                | -         |    -6.93 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           40 |     3200 | 2024-11-20 | XP Academy                                | L   | 0.238      | -            | -                | -                | -         |    -7.25 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           39 |     3232 | 2024-11-20 | Permitta Esports                          | L   | 0.238      | -            | -                | -                | -         |    -6.61 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           38 |     3283 | 2024-11-19 | GenOne                                    | L   | 0.232      | -            | -                | -                | -         |    -6.44 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           37 |     3325 | 2024-11-18 | Al-Ittihad                                | L   | 0.227      | -            | -                | -                | -         |    -6.73 | arTisT, Extinct, Girafffe, leaf, Vacancy    |
|           36 |     3340 | 2024-11-18 | Lilmix                                    | W   | 0.225      | -            | -                | -                | -         |     0.33 | arTisT, Diviiii, dobbo, Extinct, Girafffe   |
|           35 |     3579 | 2024-11-14 | Alliance                                  | L   | 0.203      | -            | -                | -                | -         |    -5.40 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           34 |     3594 | 2024-11-13 | Fire Flux Esports                         | L   | 0.199      | -            | -                | -                | -         |    -5.24 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           33 |     3641 | 2024-11-12 | ROYALS                                    | W   | 0.193      | -            | -                | -                | -         |     0.28 | arTisT, Diviiii, Extinct, Girafffe, leaf    |
|           32 |     3729 | 2024-11-10 | Annex Esports                             | W   | 0.183      | -            | -                | -                | -         |     0.23 | arTisT, Diviiii, Extinct, Girafffe, leaf    |
|           31 |     3744 | 2024-11-10 | Robins Esports                            | W   | 0.182      | -            | -                | -                | -         |     0.07 | arTisT, Diviiii, Extinct, Girafffe, leaf    |
|           30 |     3878 | 2024-11-07 | Annex Esports                             | L   | 0.166      | -            | -                | -                | -         |    -5.04 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           29 |     3887 | 2024-11-07 | Glitchtech Esports                        | W   | 0.166      | -            | -                | -                | -         |     0.14 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           28 |     3909 | 2024-11-07 | Case Esports                              | L   | 0.164      | -            | -                | -                | -         |    -4.93 | arTisT, Diviiii, Extinct, Girafffe, leaf    |
|           27 |     3983 | 2024-11-05 | The Last Resort                           | W   | 0.155      | -            | -                | -                | -         |     0.34 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           26 |     4239 | 2024-11-01 | Tutel                                     | L   | 0.133      | -            | -                | -                | -         |    -4.09 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           25 |     4258 | 2024-11-01 | HyperSpirit                               | W   | 0.132      | -            | -                | -                | -         |     0.20 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           24 |     4273 | 2024-11-01 | ECSTATIC                                  | L   | 0.130      | -            | -                | -                | -         |    -3.55 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           23 |     4305 | 2024-10-31 | ROYALS                                    | W   | 0.127      | -            | -                | -                | -         |     0.17 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           22 |     4321 | 2024-10-31 | Case Esports                              | L   | 0.125      | -            | -                | -                | -         |    -3.78 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           21 |     4346 | 2024-10-30 | Belfast Storm                             | L   | 0.122      | -            | -                | -                | -         |    -3.58 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           20 |     4353 | 2024-10-30 | TRAXXXMANIA                               | W   | 0.122      | -            | -                | -                | -         |     0.15 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           19 |     4369 | 2024-10-30 | 8Sins                                     | L   | 0.121      | -            | -                | -                | -         |    -3.00 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           18 |     4424 | 2024-10-29 | Dreams To Legends                         | W   | 0.116      | -            | -                | -                | -         |     0.06 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           17 |     4522 | 2024-10-28 | 9Pandas                                   | L   | 0.109      | -            | -                | -                | -         |    -2.67 | arTisT, bevve, Extinct, Girafffe, Vacancy   |
|           16 |     4552 | 2024-10-27 | Verdant fe                                | W   | 0.104      | -            | -                | -                | 1 (0.125) |     0.14 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           15 |     4595 | 2024-10-26 | Verdant fe                                | W   | 0.098      | -            | -                | -                | 1 (0.118) |     0.13 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           14 |     4622 | 2024-10-26 | 8Sins                                     | W   | 0.097      | -            | -                | -                | 1 (0.117) |     0.66 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           13 |     4667 | 2024-10-25 | Belfast Storm                             | W   | 0.093      | -            | -                | -                | 1 (0.112) |     0.20 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           12 |     4742 | 2024-10-23 | Lilmix                                    | W   | 0.082      | -            | -                | -                | -         |     0.10 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           11 |     4771 | 2024-10-23 | ALTERNATE aTTaX                           | L   | 0.081      | -            | -                | -                | -         |    -2.22 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           10 |     4818 | 2024-10-22 | Heimo Esports                             | L   | 0.074      | -            | -                | -                | -         |    -2.19 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            9 |     4918 | 2024-10-20 | WOPA Esport                               | L   | 0.064      | -            | -                | -                | -         |    -1.79 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            8 |     5053 | 2024-10-17 | Lausanne-Sport Esports                    | W   | 0.048      | -            | -                | -                | -         |     0.03 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            7 |     5219 | 2024-10-15 | Dynamo Eclot                              | W   | 0.035      | 0.333        | 0.114 (0.002)    | -                | -         |     0.27 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            6 |     5230 | 2024-10-14 | KONO.ECF                                  | L   | 0.032      | -            | -                | -                | -         |    -0.85 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            5 |     5255 | 2024-10-14 | Anonymo Esports                           | L   | 0.030      | -            | -                | -                | -         |    -0.92 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            4 |     5416 | 2024-10-11 | Viperio                                   | W   | 0.013      | -            | -                | -                | -         |     0.03 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            3 |     5441 | 2024-10-10 | Viperio                                   | L   | 0.008      | -            | -                | -                | -         |    -0.24 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            2 |     5487 | 2024-10-09 | THE SPELLS                                | W   | 0.004      | -            | -                | -                | -         |     0.00 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|            1 |     5499 | 2024-10-09 | ROUNDS                                    | W   | 0.004      | -            | -                | -                | -         |     0.00 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,864.72)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.918 | $2,715.56      | $2,491.71       |
| 2024-12-24 |      0.510 | $6,000.00      | $3,058.33       |
| 2024-12-07 |      0.398 | $2,166.28      | $862.30         |
| 2024-10-27 |      0.125 | $3,629.08      | $452.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
