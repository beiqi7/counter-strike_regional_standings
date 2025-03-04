### Roster Details<br />
Team Name: Passion UA<br />
Roster: jackasmo, jambo, Kvem, Topa, zeRRoFIX<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  997.9<br />
<br />
Final Rank Value (997.9) = Starting Rank Value (948.5) + Head To Head Adjustments (49.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.199[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 948.5
- 400 + ( ( 0.264 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 948.5


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
|           64 |      275 | 2025-02-21 | GUN5 Esports                              | L   | 1.000      | -            | -                | -                | -         |   -16.97 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           63 |      549 | 2025-02-14 | ENCE                                      | L   | 1.000      | -            | -                | -                | -         |   -14.31 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           62 |      594 | 2025-02-13 | Betclic Apogee Esports                    | W   | 1.000      | 0.435        | 0.014 (0.006)    | 0.528 (0.230)    | 0 (0.000) |    13.21 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           61 |      796 | 2025-02-08 | HEROIC                                    | L   | 1.000      | -            | -                | -                | -         |    -9.66 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           60 |      872 | 2025-02-07 | BetBoom Team                              | W   | 1.000      | 0.143        | 0.122 (0.017)    | 0.387 (0.055)    | 0 (0.000) |    19.69 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           59 |      977 | 2025-02-05 | BetBoom Team                              | W   | 1.000      | 0.143        | 0.122 (0.017)    | 0.387 (0.055)    | 0 (0.000) |    21.22 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           58 |      987 | 2025-02-05 | Metizport                                 | W   | 1.000      | 0.143        | 0.087 (0.012)    | 0.517 (0.074)    | 0 (0.000) |    20.18 | jackasmo, jambo, Kvem, Topa, zeRRoFIX     |
|           57 |     2813 | 2024-11-23 | Astralis                                  | W   | 0.534      | 0.143        | 0.734 (0.056)    | 0.811 (0.062)    | 1 (0.534) |    16.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           56 |     2908 | 2024-11-22 | Team Falcons                              | L   | 0.528      | -            | -                | -                | -         |    -0.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           55 |     2996 | 2024-11-21 | BIG                                       | L   | 0.521      | -            | -                | -                | -         |    -0.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           54 |     3052 | 2024-11-21 | Team Spirit                               | W   | 0.515      | 0.143        | 1.000 (0.074)    | -                | 1 (0.515) |    16.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           53 |     3065 | 2024-11-20 | Virtus.pro                                | W   | 0.514      | 0.143        | 0.298 (0.022)    | -                | 1 (0.514) |    15.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           52 |     3094 | 2024-11-20 | Nexus Gaming                              | L   | 0.511      | -            | -                | -                | -         |    -3.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           51 |     3410 | 2024-11-14 | Permitta Esports                          | L   | 0.471      | -            | -                | -                | -         |    -9.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           50 |     3435 | 2024-11-14 | BC.Game Esports                           | L   | 0.470      | -            | -                | -                | -         |    -8.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           49 |     3457 | 2024-11-13 | Lilmix                                    | W   | 0.464      | -            | -                | -                | 0 (0.000) |     2.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           48 |     3801 | 2024-11-06 | Ex-Soul's Heart Esport                    | L   | 0.417      | -            | -                | -                | -         |   -11.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           47 |     3823 | 2024-11-06 | 500                                       | L   | 0.415      | -            | -                | -                | -         |    -4.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           46 |     3905 | 2024-11-04 | THE SPELLS                                | W   | 0.404      | -            | -                | -                | 0 (0.000) |     1.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           45 |     4213 | 2024-10-30 | XP Academy                                | L   | 0.371      | -            | -                | -                | -         |   -10.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           44 |     4395 | 2024-10-27 | Los kogutos                               | L   | 0.350      | -            | -                | -                | -         |    -5.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           43 |     4520 | 2024-10-25 | ALTERNATE aTTaX                           | W   | 0.336      | 0.372        | -                | 0.560 (0.070)    | 0 (0.000) |     5.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           42 |     4531 | 2024-10-25 | 9INE                                      | L   | 0.334      | -            | -                | -                | -         |    -7.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           41 |     4571 | 2024-10-23 | HOTU                                      | W   | 0.324      | 0.372        | -                | 0.785 (0.095)    | -         |     2.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           40 |     4646 | 2024-10-21 | FORZE Reload                              | W   | 0.311      | 0.372        | 0.031 (0.004)    | 0.563 (0.065)    | -         |     3.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           39 |     4662 | 2024-10-21 | Anonymo Esports                           | W   | 0.310      | -            | -                | -                | -         |     0.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           38 |     5041 | 2024-10-13 | Mission Possible                          | W   | 0.257      | -            | -                | -                | -         |     0.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           37 |     5052 | 2024-10-13 | Ex-ENTERPRISE esports                     | W   | 0.256      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           36 |     5110 | 2024-10-12 | Mission Possible                          | L   | 0.250      | -            | -                | -                | -         |    -7.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           35 |     5162 | 2024-10-12 | FAVBET Team                               | L   | 0.248      | -            | -                | -                | -         |    -4.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           34 |     5189 | 2024-10-11 | Cloud9                                    | W   | 0.241      | -            | -                | -                | -         |     2.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           33 |     5336 | 2024-10-08 | MOUZ NXT                                  | L   | 0.223      | -            | -                | -                | -         |    -6.39 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           32 |     5425 | 2024-10-06 | GamerLegion                               | L   | 0.211      | -            | -                | -                | -         |    -0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           31 |     5457 | 2024-10-06 | 3DMAX                                     | W   | 0.208      | 0.435        | 0.302 (0.027)    | -                | -         |     6.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           30 |     5496 | 2024-10-05 | ALTERNATE aTTaX                           | W   | 0.204      | -            | -                | -                | -         |     3.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           29 |     5522 | 2024-10-05 | Los kogutos                               | W   | 0.202      | -            | -                | -                | -         |     3.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           28 |     5540 | 2024-10-05 | TSM                                       | W   | 0.201      | -            | -                | -                | -         |     1.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           27 |     5586 | 2024-10-04 | Aurora Gaming                             | W   | 0.196      | 0.435        | -                | 0.671 (0.057)    | -         |     2.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           26 |     5633 | 2024-10-03 | GameAgents                                | W   | 0.189      | -            | -                | -                | -         |     1.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           25 |     5639 | 2024-10-03 | GUN5 Esports                              | W   | 0.188      | 0.435        | 0.123 (0.010)    | -                | -         |     3.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           24 |     5779 | 2024-10-01 | Wild Lotus                                | W   | 0.174      | -            | -                | -                | -         |     1.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           23 |     5829 | 2024-09-30 | ECSTATIC                                  | W   | 0.168      | 0.435        | -                | 0.809 (0.059)    | -         |     2.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           22 |     5981 | 2024-09-27 | Tricked Esport                            | W   | 0.154      | -            | -                | -                | -         |     1.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           21 |     6028 | 2024-09-27 | Copenhagen Wolves (American organization) | W   | 0.150      | -            | -                | -                | -         |     0.48 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           20 |     6117 | 2024-09-26 | HEROIC                                    | L   | 0.142      | -            | -                | -                | -         |    -1.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           19 |     6218 | 2024-09-25 | WW Team                                   | W   | 0.135      | -            | -                | -                | -         |     0.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           18 |     6285 | 2024-09-24 | Adventurers                               | L   | 0.130      | -            | -                | -                | -         |    -2.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           17 |     6365 | 2024-09-23 | Lynn Vision Gaming                        | W   | 0.123      | -            | -                | -                | -         |     1.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           16 |     6407 | 2024-09-22 | CYBERSHOKE Esports                        | L   | 0.117      | -            | -                | -                | -         |    -2.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           15 |     6427 | 2024-09-22 | 9INE                                      | W   | 0.115      | -            | -                | -                | -         |     1.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           14 |     6530 | 2024-09-20 | Monte                                     | L   | 0.103      | -            | -                | -                | -         |    -1.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     6666 | 2024-09-18 | FAVBET Team                               | W   | 0.089      | -            | -                | -                | -         |     1.31 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           12 |     6676 | 2024-09-18 | Illuminar Gaming                          | W   | 0.088      | -            | -                | -                | -         |     1.16 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           11 |     6793 | 2024-09-16 | EYEBALLERS                                | W   | 0.076      | -            | -                | -                | -         |     0.82 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           10 |     6816 | 2024-09-15 | Lazer Cats                                | W   | 0.070      | -            | -                | -                | -         |     0.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            9 |     6826 | 2024-09-15 | TEAM NEXT LEVEL                           | W   | 0.070      | -            | -                | -                | -         |     0.91 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            8 |     6879 | 2024-09-14 | Dragon Esports Club                       | W   | 0.064      | -            | -                | -                | -         |     0.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            7 |     6968 | 2024-09-13 | ECSTATIC                                  | L   | 0.057      | -            | -                | -                | -         |    -0.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            6 |     7077 | 2024-09-11 | HOTU                                      | L   | 0.043      | -            | -                | -                | -         |    -1.03 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     7187 | 2024-09-09 | Team PeeP                                 | W   | 0.030      | -            | -                | -                | -         |     0.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            4 |     7248 | 2024-09-08 | GamerLegion                               | L   | 0.022      | -            | -                | -                | -         |    -0.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            3 |     7321 | 2024-09-07 | GamerLegion Academy                       | W   | 0.016      | -            | -                | -                | -         |     0.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            2 |     7334 | 2024-09-07 | CYBERSHOKE Esports                        | W   | 0.015      | -            | -                | -                | -         |     0.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            1 |     7379 | 2024-09-06 | Tricked Esport                            | W   | 0.011      | -            | -                | -                | -         |     0.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,555.26)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-10-27 |      0.350 | $1,244.91      | $436.07         |
| 2024-10-13 |      0.257 | $2,000.00      | $513.57         |
| 2024-10-06 |      0.211 | $10,000.00     | $2,106.29       |
| 2024-10-05 |      0.201 | $11,000.00     | $2,212.27       |
| 2024-09-15 |      0.070 | $2,416.88      | $170.37         |
| 2024-09-08 |      0.023 | $5,000.00      | $116.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
