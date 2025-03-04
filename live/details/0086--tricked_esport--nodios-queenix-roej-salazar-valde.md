### Roster Details<br />
Team Name: Tricked Esport<br />
Roster: Nodios, Queenix, roeJ, salazar, valde<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  910.3<br />
<br />
Final Rank Value (910.3) = Starting Rank Value (859.6) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.6
- 400 + ( ( 0.221 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 859.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       16 | 2025-02-28 | ESC Gaming                                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.87 | Nodios, Queenix, roeJ, salazar, valde    |
|           69 |      119 | 2025-02-25 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.29 | Nodios, Queenix, roeJ, salazar, valde    |
|           68 |      142 | 2025-02-24 | OG                                        | L   | 1.000      | -            | -                | -                | -         |    -9.81 | Nodios, Queenix, roeJ, salazar, valde    |
|           67 |      250 | 2025-02-21 | CYBERSHOKE Esports                        | L   | 1.000      | -            | -                | -                | -         |   -13.61 | Leakz, niko, Queenix, salazar, valde     |
|           66 |      268 | 2025-02-21 | Dark Cloud Esports                        | W   | 1.000      | 0.143        | 0.045 (0.006)    | 0.837 (0.120)    | 0 (0.000) |    14.81 | Leakz, niko, Queenix, salazar, valde     |
|           65 |      279 | 2025-02-21 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    15.97 | Leakz, niko, Queenix, salazar, valde     |
|           64 |      300 | 2025-02-20 | Viperio                                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.90 | Leakz, niko, Queenix, salazar, valde     |
|           63 |     1070 | 2025-02-04 | Wildcard Academy                          | L   | 1.000      | -            | -                | -                | -         |   -27.65 | Leakz, Nodios, Queenix, salazar, valde   |
|           62 |     2061 | 2024-12-09 | Betclic Apogee Esports                    | L   | 0.635      | -            | -                | -                | -         |    -9.97 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           61 |     2196 | 2024-12-07 | Fire Flux Esports                         | L   | 0.621      | -            | -                | -                | -         |    -8.13 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           60 |     2245 | 2024-12-05 | Chimera Esports                           | L   | 0.610      | -            | -                | -                | -         |   -10.14 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           59 |     2254 | 2024-12-05 | Team Sampi                                | W   | 0.608      | -            | -                | -                | 0 (0.000) |     6.56 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           58 |     2293 | 2024-12-04 | Iberian Soul                              | L   | 0.602      | -            | -                | -                | -         |   -10.28 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           57 |     2472 | 2024-12-01 | Iberian Soul                              | L   | 0.582      | -            | -                | -                | -         |   -10.46 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           56 |     2540 | 2024-11-30 | Betclic Apogee Esports                    | W   | 0.577      | -            | -                | -                | 0 (0.000) |     8.79 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           55 |     2599 | 2024-11-29 | Natus Vincere Junior                      | W   | 0.570      | 0.354        | 0.106 (0.021)    | 1.000 (0.202)    | 0 (0.000) |    12.00 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           54 |     2611 | 2024-11-29 | BC.Game Esports                           | L   | 0.568      | -            | -                | -                | -         |    -9.86 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           53 |     2634 | 2024-11-28 | GUN5 Esports                              | W   | 0.564      | 0.354        | 0.123 (0.024)    | 0.576 (0.115)    | 0 (0.000) |    10.74 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           52 |     2660 | 2024-11-28 | Chimera Esports                           | W   | 0.561      | 0.333        | 0.030 (0.006)    | 0.597 (0.112)    | 0 (0.000) |     8.39 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           51 |     2671 | 2024-11-27 | Betclic Apogee Esports                    | L   | 0.557      | -            | -                | -                | -         |    -8.85 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           50 |     2676 | 2024-11-27 | Iberian Soul                              | W   | 0.557      | 0.354        | 0.020 (0.004)    | 0.615 (0.121)    | -         |     8.34 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           49 |     2689 | 2024-11-27 | Betclic Apogee Esports                    | W   | 0.555      | -            | -                | -                | -         |     8.78 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           48 |     2725 | 2024-11-26 | Iberian Soul                              | L   | 0.551      | -            | -                | -                | -         |    -9.31 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           47 |     2741 | 2024-11-26 | Leo Team                                  | W   | 0.548      | 0.333        | 0.030 (0.006)    | 0.763 (0.139)    | -         |     8.75 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           46 |     2749 | 2024-11-25 | Fire Flux Esports                         | W   | 0.544      | 0.333        | -                | 1.000 (0.181)    | -         |    10.66 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           45 |     2812 | 2024-11-24 | Viperio                                   | W   | 0.535      | -            | -                | -                | -         |     5.22 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           44 |     2995 | 2024-11-22 | Betclic Apogee Esports                    | L   | 0.521      | -            | -                | -                | -         |    -8.11 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           43 |     3205 | 2024-11-18 | GenOne                                    | W   | 0.496      | 0.333        | -                | 0.853 (0.141)    | -         |     7.37 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           42 |     3521 | 2024-11-12 | G2 Ares                                   | W   | 0.455      | -            | -                | -                | -         |     3.73 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           41 |     3600 | 2024-11-10 | Zero Tenacity                             | L   | 0.444      | -            | -                | -                | -         |    -5.89 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           40 |     3670 | 2024-11-09 | 9Pandas                                   | L   | 0.436      | -            | -                | -                | -         |    -3.49 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           39 |     3770 | 2024-11-07 | AMKAL ESPORTS                             | W   | 0.423      | 0.384        | 0.020 (0.003)    | -                | -         |     5.50 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           38 |     3777 | 2024-11-07 | 9INE                                      | W   | 0.422      | -            | -                | -                | -         |     5.25 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           37 |     3996 | 2024-11-03 | 9Pandas                                   | L   | 0.395      | -            | -                | -                | -         |    -3.29 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           36 |     4129 | 2024-11-01 | HOTU                                      | W   | 0.382      | 0.384        | -                | 0.785 (0.115)    | -         |     3.35 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           35 |     4172 | 2024-10-31 | ECSTATIC                                  | L   | 0.377      | -            | -                | -                | -         |    -5.32 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           34 |     4285 | 2024-10-29 | Johnny Speeds                             | W   | 0.364      | 0.333        | 0.046 (0.006)    | -                | -         |     6.70 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           33 |     4296 | 2024-10-29 | Endpoint                                  | W   | 0.363      | -            | -                | -                | -         |     4.64 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           32 |     4368 | 2024-10-28 | Rebels Gaming                             | W   | 0.355      | -            | -                | -                | -         |     4.62 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           31 |     4395 | 2024-10-27 | AMKAL ESPORTS                             | W   | 0.349      | -            | -                | -                | -         |     4.55 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           30 |     4469 | 2024-10-26 | Natus Vincere Junior                      | L   | 0.341      | -            | -                | -                | -         |    -3.05 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           29 |     4599 | 2024-10-23 | Dynamo Eclot                              | W   | 0.322      | -            | -                | -                | -         |     2.73 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           28 |     4721 | 2024-10-20 | FAVBET Team                               | L   | 0.302      | -            | -                | -                | -         |    -4.20 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           27 |     4766 | 2024-10-19 | 9INE                                      | W   | 0.296      | -            | -                | -                | -         |     3.60 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           26 |     5001 | 2024-10-15 | GUN5 Esports                              | W   | 0.267      | 0.384        | 0.123 (0.013)    | -                | -         |     5.72 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           25 |     5128 | 2024-10-12 | GTZ.ESPORTS                               | W   | 0.249      | 0.143        | 0.094 (0.003)    | -                | -         |     7.24 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           24 |     5186 | 2024-10-11 | HOTU                                      | W   | 0.242      | -            | -                | -                | -         |     2.60 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           23 |     5211 | 2024-10-10 | CYBERSHOKE Esports                        | W   | 0.235      | -            | -                | -                | -         |     4.24 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           22 |     5539 | 2024-10-05 | Team Sampi                                | W   | 0.201      | -            | -                | -                | -         |     2.99 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           21 |     5680 | 2024-10-02 | ENCE Academy                              | L   | 0.182      | -            | -                | -                | -         |    -3.04 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           20 |     5701 | 2024-10-02 | HOTU                                      | L   | 0.181      | -            | -                | -                | -         |    -3.70 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           19 |     5705 | 2024-10-02 | TSM                                       | L   | 0.181      | -            | -                | -                | -         |    -3.51 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           18 |     5830 | 2024-09-30 | Johnny Speeds                             | W   | 0.168      | -            | -                | -                | -         |     3.10 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           17 |     5970 | 2024-09-28 | Nexus Gaming                              | L   | 0.155      | -            | -                | -                | -         |    -0.53 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           16 |     5983 | 2024-09-27 | Passion UA                                | L   | 0.154      | -            | -                | -                | -         |    -1.86 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           15 |     6096 | 2024-09-26 | GameAgents                                | L   | 0.143      | -            | -                | -                | -         |    -2.92 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           14 |     6124 | 2024-09-26 | Los kogutos                               | W   | 0.141      | -            | -                | -                | -         |     3.27 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           13 |     6178 | 2024-09-25 | Zero Tenacity                             | W   | 0.137      | -            | -                | -                | -         |     2.68 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           12 |     6212 | 2024-09-25 | TSM                                       | L   | 0.135      | -            | -                | -                | -         |    -2.66 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           11 |     6491 | 2024-09-21 | KONO.ECF                                  | W   | 0.108      | -            | -                | -                | -         |     2.15 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|           10 |     6849 | 2024-09-15 | GamerLegion                               | L   | 0.068      | -            | -                | -                | -         |    -1.48 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            9 |     6944 | 2024-09-14 | ECSTATIC                                  | W   | 0.061      | -            | -                | -                | -         |     1.12 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            8 |     6994 | 2024-09-13 | Cloud9                                    | W   | 0.055      | -            | -                | -                | -         |     0.69 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            7 |     7150 | 2024-09-10 | Chimera Esports                           | W   | 0.034      | -            | -                | -                | -         |     0.56 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            6 |     7196 | 2024-09-09 | FAVBET Team                               | L   | 0.029      | -            | -                | -                | -         |    -0.37 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            5 |     7297 | 2024-09-07 | Team Spirit Academy                       | L   | 0.017      | -            | -                | -                | -         |    -0.16 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            4 |     7381 | 2024-09-06 | Passion UA                                | L   | 0.010      | -            | -                | -                | -         |    -0.12 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            3 |     7493 | 2024-09-05 | BetBoom Team                              | L   | 0.002      | -            | -                | -                | -         |    -0.02 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            2 |     7507 | 2024-09-05 | Team Sampi                                | L   | 0.001      | -            | -                | -                | -         |    -0.02 | kraghen, nicoodoz, Nodios, Queenix, roeJ |
|            1 |     7510 | 2024-09-05 | Revenant Esports                          | W   | 0.001      | -            | -                | -                | -         |     0.00 | kraghen, nicoodoz, Nodios, Queenix, roeJ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,867.77)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.577 | $12,000.00     | $6,922.25       |
| 2024-11-29 |      0.568 | $3,000.00      | $1,703.90       |
| 2024-11-27 |      0.556 | $1,000.00      | $555.88         |
| 2024-11-12 |      0.456 | $500.00        | $228.21         |
| 2024-11-10 |      0.444 | $2,500.00      | $1,109.50       |
| 2024-09-15 |      0.070 | $5,000.00      | $348.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
