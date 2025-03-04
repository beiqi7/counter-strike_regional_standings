### Roster Details<br />
Team Name: Passion UA<br />
Roster: jackasmo, jambo, Kvem, Topa, zeRRoFIX<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  998.2<br />
<br />
Final Rank Value (998.2) = Starting Rank Value (948.3) + Head To Head Adjustments (49.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 948.3
- 400 + ( ( 0.264 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 948.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      277 | 2025-02-21 | GUN5 Esports                              | L   | 1.000      | -            | -                | -                | -         |   -16.98 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           63 |      551 | 2025-02-14 | ENCE                                      | L   | 1.000      | -            | -                | -                | -         |   -14.34 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           62 |      596 | 2025-02-13 | Betclic Apogee Esports                    | W   | 1.000      | 0.435        | 0.014 (0.006)    | 0.528 (0.230)    | 0 (0.000) |    13.19 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           61 |      798 | 2025-02-08 | HEROIC                                    | L   | 1.000      | -            | -                | -                | -         |    -9.69 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           60 |      874 | 2025-02-07 | BetBoom Team                              | W   | 1.000      | 0.143        | 0.122 (0.017)    | 0.387 (0.055)    | 0 (0.000) |    19.80 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           59 |      979 | 2025-02-05 | BetBoom Team                              | W   | 1.000      | 0.143        | 0.122 (0.017)    | 0.387 (0.055)    | 0 (0.000) |    21.34 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           58 |      989 | 2025-02-05 | Metizport                                 | W   | 1.000      | 0.143        | 0.087 (0.012)    | 0.517 (0.074)    | 0 (0.000) |    20.16 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           57 |     2815 | 2024-11-23 | Astralis                                  | W   | 0.534      | 0.143        | 0.734 (0.056)    | 0.811 (0.062)    | 1 (0.534) |    16.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           56 |     2910 | 2024-11-22 | Team Falcons                              | L   | 0.527      | -            | -                | -                | -         |    -0.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           55 |     2998 | 2024-11-21 | BIG                                       | L   | 0.520      | -            | -                | -                | -         |    -0.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           54 |     3054 | 2024-11-21 | Team Spirit                               | W   | 0.515      | 0.143        | 1.000 (0.074)    | -                | 1 (0.515) |    16.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           53 |     3067 | 2024-11-20 | Virtus.pro                                | W   | 0.514      | 0.143        | 0.299 (0.022)    | -                | 1 (0.514) |    15.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           52 |     3096 | 2024-11-20 | Nexus Gaming                              | L   | 0.511      | -            | -                | -                | -         |    -3.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           51 |     3412 | 2024-11-14 | Permitta Esports                          | L   | 0.470      | -            | -                | -                | -         |    -9.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           50 |     3437 | 2024-11-14 | BC.Game Esports                           | L   | 0.469      | -            | -                | -                | -         |    -8.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           49 |     3459 | 2024-11-13 | Lilmix                                    | W   | 0.464      | -            | -                | -                | 0 (0.000) |     2.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           48 |     3803 | 2024-11-06 | Ex-Soul's Heart Esport                    | L   | 0.417      | -            | -                | -                | -         |   -11.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           47 |     3825 | 2024-11-06 | 500                                       | L   | 0.415      | -            | -                | -                | -         |    -4.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           46 |     3907 | 2024-11-04 | THE SPELLS                                | W   | 0.404      | -            | -                | -                | 0 (0.000) |     1.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           45 |     4215 | 2024-10-30 | XP Academy                                | L   | 0.371      | -            | -                | -                | -         |   -10.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           44 |     4397 | 2024-10-27 | Los kogutos                               | L   | 0.349      | -            | -                | -                | -         |    -5.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           43 |     4522 | 2024-10-25 | ALTERNATE aTTaX                           | W   | 0.336      | 0.372        | -                | 0.559 (0.070)    | 0 (0.000) |     5.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           42 |     4533 | 2024-10-25 | 9INE                                      | L   | 0.334      | -            | -                | -                | -         |    -7.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           41 |     4573 | 2024-10-23 | HOTU                                      | W   | 0.324      | 0.372        | -                | 0.785 (0.095)    | -         |     2.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           40 |     4648 | 2024-10-21 | FORZE Reload                              | W   | 0.310      | 0.372        | 0.031 (0.004)    | 0.563 (0.065)    | -         |     3.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           39 |     4664 | 2024-10-21 | Anonymo Esports                           | W   | 0.309      | -            | -                | -                | -         |     0.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           38 |     5043 | 2024-10-13 | Mission Possible                          | W   | 0.257      | -            | -                | -                | -         |     0.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           37 |     5054 | 2024-10-13 | Ex-ENTERPRISE esports                     | W   | 0.256      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           36 |     5112 | 2024-10-12 | Mission Possible                          | L   | 0.250      | -            | -                | -                | -         |    -7.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           35 |     5164 | 2024-10-12 | FAVBET Team                               | L   | 0.247      | -            | -                | -                | -         |    -4.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           34 |     5191 | 2024-10-11 | Cloud9                                    | W   | 0.241      | -            | -                | -                | -         |     2.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           33 |     5338 | 2024-10-08 | MOUZ NXT                                  | L   | 0.223      | -            | -                | -                | -         |    -6.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           32 |     5427 | 2024-10-06 | GamerLegion                               | L   | 0.210      | -            | -                | -                | -         |    -0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           31 |     5459 | 2024-10-06 | 3DMAX                                     | W   | 0.208      | 0.435        | 0.302 (0.027)    | -                | -         |     6.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           30 |     5498 | 2024-10-05 | ALTERNATE aTTaX                           | W   | 0.203      | -            | -                | -                | -         |     3.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           29 |     5524 | 2024-10-05 | Los kogutos                               | W   | 0.202      | -            | -                | -                | -         |     3.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           28 |     5542 | 2024-10-05 | TSM                                       | W   | 0.201      | -            | -                | -                | -         |     1.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           27 |     5588 | 2024-10-04 | Aurora Gaming                             | W   | 0.195      | 0.435        | -                | 0.671 (0.057)    | -         |     2.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           26 |     5635 | 2024-10-03 | GameAgents                                | W   | 0.188      | -            | -                | -                | -         |     1.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           25 |     5641 | 2024-10-03 | GUN5 Esports                              | W   | 0.187      | 0.435        | 0.123 (0.010)    | -                | -         |     3.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           24 |     5781 | 2024-10-01 | Wild Lotus                                | W   | 0.174      | -            | -                | -                | -         |     1.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           23 |     5831 | 2024-09-30 | ECSTATIC                                  | W   | 0.168      | 0.435        | -                | 0.809 (0.059)    | -         |     2.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           22 |     5983 | 2024-09-27 | Tricked Esport                            | W   | 0.154      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           21 |     6030 | 2024-09-27 | Copenhagen Wolves (American organization) | W   | 0.149      | -            | -                | -                | -         |     0.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           20 |     6119 | 2024-09-26 | HEROIC                                    | L   | 0.142      | -            | -                | -                | -         |    -1.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           19 |     6220 | 2024-09-25 | WW Team                                   | W   | 0.135      | -            | -                | -                | -         |     0.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           18 |     6287 | 2024-09-24 | Adventurers                               | L   | 0.129      | -            | -                | -                | -         |    -2.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           17 |     6367 | 2024-09-23 | Lynn Vision Gaming                        | W   | 0.123      | -            | -                | -                | -         |     1.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           16 |     6409 | 2024-09-22 | CYBERSHOKE Esports                        | L   | 0.116      | -            | -                | -                | -         |    -2.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           15 |     6429 | 2024-09-22 | 9INE                                      | W   | 0.115      | -            | -                | -                | -         |     1.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           14 |     6532 | 2024-09-20 | Monte                                     | L   | 0.103      | -            | -                | -                | -         |    -1.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     6668 | 2024-09-18 | FAVBET Team                               | W   | 0.088      | -            | -                | -                | -         |     1.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           12 |     6678 | 2024-09-18 | Illuminar Gaming                          | W   | 0.087      | -            | -                | -                | -         |     1.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           11 |     6795 | 2024-09-16 | EYEBALLERS                                | W   | 0.075      | -            | -                | -                | -         |     0.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           10 |     6818 | 2024-09-15 | Lazer Cats                                | W   | 0.070      | -            | -                | -                | -         |     0.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            9 |     6828 | 2024-09-15 | TEAM NEXT LEVEL                           | W   | 0.069      | -            | -                | -                | -         |     0.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            8 |     6881 | 2024-09-14 | Dragon Esports Club                       | W   | 0.063      | -            | -                | -                | -         |     0.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            7 |     6970 | 2024-09-13 | ECSTATIC                                  | L   | 0.057      | -            | -                | -                | -         |    -0.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            6 |     7079 | 2024-09-11 | HOTU                                      | L   | 0.043      | -            | -                | -                | -         |    -1.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     7189 | 2024-09-09 | Team PeeP                                 | W   | 0.029      | -            | -                | -                | -         |     0.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            4 |     7250 | 2024-09-08 | GamerLegion                               | L   | 0.021      | -            | -                | -                | -         |    -0.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            3 |     7323 | 2024-09-07 | GamerLegion Academy                       | W   | 0.016      | -            | -                | -                | -         |     0.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            2 |     7336 | 2024-09-07 | CYBERSHOKE Esports                        | W   | 0.015      | -            | -                | -                | -         |     0.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            1 |     7381 | 2024-09-06 | Tricked Esport                            | W   | 0.010      | -            | -                | -                | -         |     0.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,543.46)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-10-27 |      0.350 | $1,244.91      | $435.61         |
| 2024-10-13 |      0.256 | $2,000.00      | $512.83         |
| 2024-10-06 |      0.210 | $10,000.00     | $2,102.57       |
| 2024-10-05 |      0.201 | $11,000.00     | $2,208.17       |
| 2024-09-15 |      0.070 | $2,416.88      | $169.47         |
| 2024-09-08 |      0.023 | $5,000.00      | $114.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
