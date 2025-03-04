### Roster Details<br />
Team Name: SINNERS Esports<br />
Roster: beastik, MoriiSko, Pepo, SHOCK, ZEDKO<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  917.3<br />
<br />
Final Rank Value (917.3) = Starting Rank Value (1020.4) + Head To Head Adjustments (-103.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.279[<sup>2</sup>](#table1)
- LAN Wins: 0.153[<sup>2</sup>](#table1)

The average of these factors is 0.298<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1020.4
- 400 + ( ( 0.298 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1020.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           63 |       10 | 2025-02-28 | Fire Flux Esports                         | W   | 1.000      | 0.435        | 0.009 (0.004)    | 1.000 (0.435)    | 0 (0.000) |    17.58 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           62 |       24 | 2025-02-27 | Iberian Soul                              | L   | 1.000      | -            | -                | -                | -         |   -16.93 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           61 |      103 | 2025-02-25 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -16.90 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           60 |      345 | 2025-02-19 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -10.88 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           59 |      369 | 2025-02-18 | JiJieHao                                  | W   | 1.000      | 0.500        | -                | 0.262 (0.131)    | 0 (0.000) |     5.16 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           58 |      446 | 2025-02-16 | ECSTATIC                                  | L   | 1.000      | -            | -                | -                | -         |   -16.93 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           57 |      523 | 2025-02-15 | Sashi Esport                              | L   | 1.000      | -            | -                | -                | -         |   -14.93 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           56 |      617 | 2025-02-12 | ALASKA                                    | W   | 1.000      | 0.435        | 0.036 (0.016)    | 0.888 (0.386)    | 0 (0.000) |    14.35 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           55 |      710 | 2025-02-09 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -15.29 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           54 |      778 | 2025-02-08 | Little Red Door                           | L   | 1.000      | -            | -                | -                | -         |   -28.41 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           53 |      828 | 2025-02-07 | Soul's Heart Esport                       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.09 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           52 |      873 | 2025-02-07 | Monte                                     | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.866 (0.376)    | 0 (0.000) |    14.93 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           51 |      945 | 2025-02-05 | OG                                        | L   | 1.000      | -            | -                | -                | -         |   -16.71 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           50 |     1017 | 2025-02-04 | Alliance                                  | L   | 1.000      | -            | -                | -                | -         |   -19.21 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           49 |     1120 | 2025-02-01 | GTZ.ESPORTS                               | W   | 0.998      | 0.435        | 0.094 (0.041)    | 0.619 (0.268)    | 0 (0.000) |    23.00 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           48 |     1266 | 2025-01-23 | Monte                                     | W   | 0.937      | 0.500        | 0.052 (0.025)    | 0.866 (0.406)    | -         |    15.47 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           47 |     1302 | 2025-01-21 | PARIVISION                                | W   | 0.924      | 0.500        | -                | 0.870 (0.402)    | -         |     5.10 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           46 |     1350 | 2025-01-11 | Wildcard                                  | L   | 0.857      | -            | -                | -                | -         |    -8.50 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           45 |     1359 | 2025-01-10 | KONO.ECF                                  | W   | 0.848      | 0.417        | -                | 0.445 (0.157)    | -         |     3.86 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           44 |     1886 | 2024-12-13 | ECSTATIC                                  | L   | 0.664      | -            | -                | -                | -         |   -11.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1919 | 2024-12-13 | Team Spirit Academy                       | L   | 0.661      | -            | -                | -                | -         |    -9.85 | beastik, majky, MoriiSko, oskar, SHOCK |
|           42 |     1938 | 2024-12-12 | Natus Vincere Junior                      | L   | 0.657      | -            | -                | -                | -         |    -8.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           41 |     3129 | 2024-11-20 | GamerLegion                               | L   | 0.508      | -            | -                | -                | -         |    -0.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           40 |     3179 | 2024-11-18 | Cloud9                                    | L   | 0.499      | -            | -                | -                | -         |   -11.95 | beastik, majky, MoriiSko, oskar, SHOCK |
|           39 |     3221 | 2024-11-17 | Dynamo Eclot                              | W   | 0.493      | 0.143        | 0.150 (0.011)    | -                | 1 (0.493) |     9.85 | beastik, majky, MoriiSko, oskar, SHOCK |
|           38 |     3267 | 2024-11-17 | Natus Vincere                             | L   | 0.488      | -            | -                | -                | -         |    -0.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           37 |     3279 | 2024-11-16 | SAW                                       | W   | 0.487      | 0.143        | 0.315 (0.022)    | -                | 1 (0.487) |    13.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           36 |     3622 | 2024-11-10 | Dynamo Eclot                              | L   | 0.443      | -            | -                | -                | -         |    -4.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           35 |     3782 | 2024-11-07 | 500                                       | W   | 0.421      | 0.384        | 0.114 (0.018)    | 1.000 (0.162)    | -         |     8.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|           34 |     3812 | 2024-11-06 | PARIVISION                                | L   | 0.417      | -            | -                | -                | -         |   -10.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           33 |     3826 | 2024-11-06 | Los kogutos                               | L   | 0.415      | -            | -                | -                | -         |    -7.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           32 |     3870 | 2024-11-05 | 9INE                                      | W   | 0.410      | -            | -                | -                | -         |     3.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           31 |     3881 | 2024-11-05 | Dynamo Eclot                              | L   | 0.408      | -            | -                | -                | -         |    -4.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           30 |     3974 | 2024-11-03 | ECSTATIC                                  | W   | 0.397      | -            | -                | -                | -         |     5.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           29 |     4001 | 2024-11-03 | ARCRED                                    | W   | 0.395      | -            | -                | -                | -         |     3.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           28 |     4126 | 2024-11-01 | Endpoint                                  | W   | 0.383      | -            | -                | -                | -         |     3.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           27 |     4174 | 2024-10-31 | Rebels Gaming                             | W   | 0.376      | -            | -                | -                | -         |     3.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           26 |     4307 | 2024-10-29 | HOTU                                      | L   | 0.362      | -            | -                | -                | -         |    -9.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           25 |     4407 | 2024-10-27 | Insilio                                   | W   | 0.348      | 0.371        | -                | 0.513 (0.066)    | -         |     1.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           24 |     5076 | 2024-10-13 | Team Spirit Academy                       | L   | 0.254      | -            | -                | -                | -         |    -3.87 | beastik, majky, MoriiSko, oskar, SHOCK |
|           23 |     5108 | 2024-10-12 | GUN5 Esports                              | W   | 0.250      | 0.435        | 0.123 (0.013)    | -                | -         |     3.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           22 |     5169 | 2024-10-11 | Monte                                     | W   | 0.243      | 0.435        | 0.034 (0.004)    | -                | -         |     2.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           21 |     5620 | 2024-10-03 | Los kogutos                               | L   | 0.190      | -            | -                | -                | -         |    -2.81 | beastik, majky, MoriiSko, oskar, SHOCK |
|           20 |     6226 | 2024-09-25 | CYBERSHOKE Esports                        | L   | 0.134      | -            | -                | -                | -         |    -2.69 | beastik, majky, MoriiSko, oskar, SHOCK |
|           19 |     6364 | 2024-09-23 | Zero Tenacity                             | L   | 0.123      | -            | -                | -                | -         |    -2.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           18 |     6410 | 2024-09-22 | UNiTY esports                             | L   | 0.116      | -            | -                | -                | -         |    -2.56 | beastik, majky, MoriiSko, oskar, SHOCK |
|           17 |     6421 | 2024-09-22 | Team Sampi                                | W   | 0.115      | -            | -                | -                | 1 (0.115) |     0.95 | beastik, majky, MoriiSko, oskar, SHOCK |
|           16 |     6475 | 2024-09-21 | UNiTY esports                             | L   | 0.110      | -            | -                | -                | -         |    -2.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           15 |     6529 | 2024-09-20 | Dynamo Eclot                              | W   | 0.103      | -            | -                | -                | 1 (0.103) |     2.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           14 |     6599 | 2024-09-19 | 9INE                                      | W   | 0.096      | -            | -                | -                | -         |     0.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           13 |     6608 | 2024-09-19 | ARCRED                                    | L   | 0.095      | -            | -                | -                | -         |    -2.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           12 |     6663 | 2024-09-18 | Nemiga Gaming                             | L   | 0.089      | -            | -                | -                | -         |    -1.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           11 |     6824 | 2024-09-15 | GamerLegion                               | W   | 0.070      | -            | -                | -                | -         |     0.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|           10 |     6837 | 2024-09-15 | Insilio                                   | W   | 0.069      | -            | -                | -                | -         |     0.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|            9 |     6894 | 2024-09-14 | Revenant Esports                          | L   | 0.063      | -            | -                | -                | -         |    -1.87 | beastik, majky, MoriiSko, oskar, SHOCK |
|            8 |     6925 | 2024-09-14 | GUN5 Esports                              | W   | 0.062      | -            | -                | -                | -         |     0.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|            7 |     7046 | 2024-09-12 | FAVBET Team                               | W   | 0.047      | -            | -                | -                | -         |     0.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|            6 |     7191 | 2024-09-09 | Team Sampi                                | W   | 0.029      | -            | -                | -                | -         |     0.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|            5 |     7249 | 2024-09-08 | Insilio                                   | L   | 0.021      | -            | -                | -                | -         |    -0.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|            4 |     7407 | 2024-09-06 | UNiTY esports                             | W   | 0.009      | -            | -                | -                | -         |     0.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|            3 |     7459 | 2024-09-05 | B8                                        | L   | 0.004      | -            | -                | -                | -         |    -0.03 | beastik, majky, MoriiSko, oskar, SHOCK |
|            2 |     7494 | 2024-09-05 | AVEZ                                      | W   | 0.002      | -            | -                | -                | -         |     0.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|            1 |     7508 | 2024-09-05 | Monte                                     | L   | 0.001      | -            | -                | -                | -         |    -0.02 | beastik, majky, MoriiSko, oskar, SHOCK |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,546.10)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-12 |      0.863 | $5,000.00      | $4,313.44       |
| 2024-11-12 |      0.456 | $500.00        | $228.21         |
| 2024-10-20 |      0.303 | $2,500.00      | $756.72         |
| 2024-10-13 |      0.256 | $5,000.00      | $1,282.07       |
| 2024-09-26 |      0.143 | $500.00        | $71.39          |
| 2024-09-22 |      0.116 | $3,117.85      | $362.89         |
| 2024-09-15 |      0.070 | $22,000.00     | $1,531.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
