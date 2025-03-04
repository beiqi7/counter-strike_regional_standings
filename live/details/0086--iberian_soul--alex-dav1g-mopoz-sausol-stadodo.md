### Roster Details<br />
Team Name: Iberian Soul<br />
Roster: alex, dav1g, mopoz, sausol, stadodo<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.8<br />
<br />
Final Rank Value (908.8) = Starting Rank Value (878.5) + Head To Head Adjustments (30.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.164[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 878.5
- 400 + ( ( 0.230 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 878.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |       11 | 2025-02-28 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    18.76 | alex, dav1g, mopoz, sausol, stadodo   |
|           45 |       22 | 2025-02-27 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | 0 (0.000) |    16.93 | alex, dav1g, mopoz, sausol, stadodo   |
|           44 |       60 | 2025-02-26 | Team Spirit Academy                       | L   | 1.000      | -            | -                | -                | -         |    -8.63 | alex, dav1g, mopoz, sausol, stadodo   |
|           43 |      106 | 2025-02-25 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.78 | alex, dav1g, mopoz, sausol, stadodo   |
|           42 |      130 | 2025-02-24 | OG                                        | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.984 (0.141)    | 0 (0.000) |    21.99 | alex, dav1g, mopoz, sausol, stadodo   |
|           41 |      134 | 2025-02-24 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    20.41 | alex, dav1g, mopoz, sausol, stadodo   |
|           40 |      184 | 2025-02-23 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.88 | alex, dav1g, mopoz, sausol, stadodo   |
|           39 |      319 | 2025-02-20 | ECSTATIC                                  | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    18.49 | alex, dav1g, mopoz, sausol, stadodo   |
|           38 |      341 | 2025-02-19 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -3.70 | alex, dav1g, mopoz, sausol, stadodo   |
|           37 |      347 | 2025-02-19 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |    -8.28 | alex, dav1g, mopoz, sausol, stadodo   |
|           36 |      542 | 2025-02-14 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -16.88 | alex, dav1g, mopoz, sausol, stadodo   |
|           35 |      719 | 2025-02-09 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -12.99 | alex, dav1g, mopoz, sausol, stadodo   |
|           34 |      799 | 2025-02-08 | UNiTY esports                             | W   | 1.000      | 0.143        | 0.030 (0.004)    | -                | 0 (0.000) |    14.35 | alex, dav1g, mopoz, sausol, stadodo   |
|           33 |      850 | 2025-02-07 | Team Novaq                                | L   | 1.000      | -            | -                | -                | -         |    -4.41 | alex, dav1g, mopoz, sausol, stadodo   |
|           32 |      990 | 2025-02-05 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | alex, dav1g, mopoz, sausol, stadodo   |
|           31 |     1071 | 2025-02-04 | UNiTY esports                             | L   | 1.000      | -            | -                | -                | -         |   -16.43 | alex, dav1g, mopoz, sausol, stadodo   |
|           30 |     1236 | 2025-01-25 | ECSTATIC                                  | L   | 0.949      | -            | -                | -                | -         |   -12.78 | alex, dav1g, mopoz, sausol, stadodo   |
|           29 |     1254 | 2025-01-24 | KONO.ECF                                  | L   | 0.943      | -            | -                | -                | -         |   -22.61 | alex, dav1g, mopoz, sausol, stadodo   |
|           28 |     1824 | 2024-12-14 | Chimera Esports                           | L   | 0.669      | -            | -                | -                | -         |    -8.55 | adamS, dav1g, mopoz, sausol, stadodo  |
|           27 |     1921 | 2024-12-13 | GUN5 Esports                              | L   | 0.662      | -            | -                | -                | -         |    -7.29 | adamS, dav1g, mopoz, sausol, stadodo  |
|           26 |     1983 | 2024-12-11 | Endpoint                                  | L   | 0.650      | -            | -                | -                | -         |   -14.45 | adamS, dav1g, mopoz, sausol, stadodo  |
|           25 |     2025 | 2024-12-10 | Team Spirit Academy                       | L   | 0.644      | -            | -                | -                | -         |    -7.81 | adamS, dav1g, mopoz, sausol, stadodo  |
|           24 |     2031 | 2024-12-10 | TSM                                       | W   | 0.642      | -            | -                | -                | 0 (0.000) |     6.40 | adamS, dav1g, mopoz, sausol, stadodo  |
|           23 |     2182 | 2024-12-07 | FAVBET Team                               | W   | 0.623      | 0.435        | 0.037 (0.010)    | 0.952 (0.258)    | -         |    10.77 | adamS, dav1g, mopoz, sausol, stadodo  |
|           22 |     2227 | 2024-12-06 | 9INE                                      | L   | 0.616      | -            | -                | -                | -         |    -9.13 | adamS, dav1g, mopoz, sausol, stadodo  |
|           21 |     2247 | 2024-12-05 | Betclic Apogee Esports                    | W   | 0.609      | 0.371        | -                | 0.528 (0.119)    | -         |     9.66 | adamS, dav1g, mopoz, sausol, stadodo  |
|           20 |     2291 | 2024-12-04 | Tricked Esport                            | W   | 0.603      | 0.435        | 0.039 (0.010)    | 0.702 (0.184)    | -         |    10.28 | adamS, dav1g, mopoz, sausol, stadodo  |
|           19 |     2470 | 2024-12-01 | Tricked Esport                            | W   | 0.582      | 0.371        | 0.039 (0.008)    | 0.702 (0.151)    | -         |    10.47 | adamS, dav1g, mopoz, sausol, stadodo  |
|           18 |     2643 | 2024-11-28 | GUN5 Esports                              | L   | 0.564      | -            | -                | -                | -         |    -6.27 | adamS, dav1g, mopoz, sausol, stadodo  |
|           17 |     2674 | 2024-11-27 | Tricked Esport                            | L   | 0.557      | -            | -                | -                | -         |    -8.35 | adamS, dav1g, mopoz, sausol, stadodo  |
|           16 |     2681 | 2024-11-27 | TEAM NEXT LEVEL                           | W   | 0.556      | 0.333        | 0.047 (0.009)    | -                | -         |     8.62 | adamS, dav1g, mopoz, sausol, stadodo  |
|           15 |     2723 | 2024-11-26 | Tricked Esport                            | W   | 0.551      | 0.333        | 0.039 (0.007)    | 0.702 (0.129)    | -         |     9.31 | adamS, dav1g, mopoz, sausol, stadodo  |
|           14 |     2755 | 2024-11-25 | 9INE                                      | W   | 0.543      | -            | -                | -                | -         |     6.90 | adamS, dav1g, mopoz, sausol, stadodo  |
|           13 |     2866 | 2024-11-23 | ENCE Academy                              | W   | 0.531      | 0.333        | -                | 0.665 (0.118)    | -         |     7.24 | adamS, dav1g, mopoz, sausol, stadodo  |
|           12 |     2967 | 2024-11-22 | JANO Esports                              | W   | 0.524      | 0.333        | 0.026 (0.005)    | -                | -         |    10.32 | adamS, dav1g, mopoz, sausol, stadodo  |
|           11 |     3117 | 2024-11-20 | ENCE Academy                              | L   | 0.510      | -            | -                | -                | -         |    -8.93 | adamS, dav1g, mopoz, sausol, stadodo  |
|           10 |     3245 | 2024-11-17 | Rhyno Esports                             | L   | 0.490      | -            | -                | -                | -         |    -7.13 | adamS, dav1g, deLonge, mopoz, stadodo |
|            9 |     3305 | 2024-11-16 | GOOFYBOYZ                                 | W   | 0.484      | -            | -                | -                | 1 (0.484) |     6.01 | adamS, dav1g, deLonge, mopoz, stadodo |
|            8 |     4201 | 2024-10-30 | ECSTATIC                                  | L   | 0.372      | -            | -                | -                | -         |    -5.06 | adamS, dav1g, JUST, mopoz, stadodo    |
|            7 |     4224 | 2024-10-30 | Illuminar Gaming                          | W   | 0.371      | -            | -                | -                | -         |     6.00 | adamS, dav1g, JUST, mopoz, stadodo    |
|            6 |     4238 | 2024-10-30 | Metizport                                 | L   | 0.370      | -            | -                | -                | -         |    -2.20 | adamS, dav1g, JUST, mopoz, stadodo    |
|            5 |     5529 | 2024-10-05 | Rhyno Esports                             | L   | 0.202      | -            | -                | -                | -         |    -4.60 | adamS, dav1g, JUST, mopoz, stadodo    |
|            4 |     5669 | 2024-10-02 | Natus Vincere Junior                      | L   | 0.184      | -            | -                | -                | -         |    -1.72 | adamS, dav1g, JUST, mopoz, stadodo    |
|            3 |     5741 | 2024-10-01 | Preasy Esport                             | W   | 0.177      | -            | -                | -                | -         |     2.48 | adamS, dav1g, JUST, mopoz, stadodo    |
|            2 |     7377 | 2024-09-06 | Wildcard                                  | L   | 0.011      | -            | -                | -                | -         |    -0.06 | adamS, dav1g, JUST, mopoz, stadodo    |
|            1 |     7500 | 2024-09-05 | The MongolZ                               | L   | 0.002      | -            | -                | -                | -         |     0.00 | adamS, dav1g, JUST, mopoz, stadodo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,467.55)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $500.00        | $500.00         |
| 2024-11-27 |      0.556 | $5,000.00      | $2,781.27       |
| 2024-11-17 |      0.490 | $3,163.39      | $1,549.20       |
| 2024-10-06 |      0.209 | $1,098.17      | $229.71         |
| 2024-09-22 |      0.116 | $3,500.00      | $407.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
