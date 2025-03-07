### Roster Details<br />
Team Name: Iberian Soul<br />
Roster: alex, dav1g, mopoz, sausol, stadodo<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
<br />
Final Rank Value:  860.6<br />
<br />
Final Rank Value (860.6) = Starting Rank Value (859.1) + Head To Head Adjustments (1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.042[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.1
- 400 + ( ( 0.208 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 859.1


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
|           44 |       17 | 2025-02-28 | Fire Flux Esports                         | W   | 0.792      | 0.143        | -                | 1.000 (0.136)    | 0 (0.000) |    14.71 | alex, dav1g, mopoz, sausol, stadodo   |
|           43 |       28 | 2025-02-27 | SINNERS Esports                           | W   | 0.788      | 0.435        | 0.016 (0.007)    | 0.494 (0.203)    | 0 (0.000) |    13.47 | alex, dav1g, mopoz, sausol, stadodo   |
|           42 |       66 | 2025-02-26 | Team Spirit Academy                       | L   | 0.783      | -            | -                | -                | -         |    -7.94 | alex, dav1g, mopoz, sausol, stadodo   |
|           41 |      114 | 2025-02-25 | Aurora Gaming                             | L   | 0.777      | -            | -                | -                | -         |   -12.14 | alex, dav1g, mopoz, sausol, stadodo   |
|           40 |      138 | 2025-02-24 | OG                                        | W   | 0.772      | 0.143        | 0.041 (0.005)    | 0.989 (0.131)    | 0 (0.000) |    16.06 | alex, dav1g, mopoz, sausol, stadodo   |
|           39 |      142 | 2025-02-24 | Fire Flux Esports                         | W   | 0.771      | 0.143        | -                | 1.000 (0.132)    | 0 (0.000) |    15.28 | alex, dav1g, mopoz, sausol, stadodo   |
|           38 |      192 | 2025-02-23 | Alliance                                  | W   | 0.765      | -            | -                | -                | 0 (0.000) |    14.05 | alex, dav1g, mopoz, sausol, stadodo   |
|           37 |      328 | 2025-02-20 | ECSTATIC                                  | W   | 0.748      | 0.143        | 0.027 (0.004)    | 0.659 (0.084)    | 0 (0.000) |    13.25 | alex, dav1g, mopoz, sausol, stadodo   |
|           36 |      354 | 2025-02-19 | B8                                        | L   | 0.744      | -            | -                | -                | -         |    -3.73 | alex, dav1g, mopoz, sausol, stadodo   |
|           35 |      360 | 2025-02-19 | 9INE                                      | L   | 0.743      | -            | -                | -                | -         |    -6.75 | alex, dav1g, mopoz, sausol, stadodo   |
|           34 |      568 | 2025-02-14 | Rebels Gaming                             | L   | 0.716      | -            | -                | -                | -         |   -12.49 | alex, dav1g, mopoz, sausol, stadodo   |
|           33 |      743 | 2025-02-09 | Copenhagen Wolves (American organization) | L   | 0.687      | -            | -                | -                | -         |    -9.19 | alex, dav1g, mopoz, sausol, stadodo   |
|           32 |      823 | 2025-02-08 | UNiTY esports                             | W   | 0.680      | 0.143        | 0.019 (0.002)    | -                | 0 (0.000) |     8.88 | alex, dav1g, mopoz, sausol, stadodo   |
|           31 |      874 | 2025-02-07 | Team Novaq                                | L   | 0.677      | -            | -                | -                | -         |    -6.97 | alex, dav1g, mopoz, sausol, stadodo   |
|           30 |     1012 | 2025-02-05 | Ninjas in Pyjamas                         | W   | 0.664      | 0.143        | -                | 0.649 (0.074)    | 0 (0.000) |     5.56 | alex, dav1g, mopoz, sausol, stadodo   |
|           29 |     1093 | 2025-02-04 | UNiTY esports                             | L   | 0.659      | -            | -                | -                | -         |   -12.23 | alex, dav1g, mopoz, sausol, stadodo   |
|           28 |     1234 | 2025-01-28 | ARCRED                                    | L   | 0.622      | -            | -                | -                | -         |   -10.10 | dav1g, mopoz, sausol, stadodo         |
|           27 |     1290 | 2025-01-25 | ECSTATIC                                  | L   | 0.603      | -            | -                | -                | -         |    -9.13 | alex, dav1g, mopoz, sausol, stadodo   |
|           26 |     1317 | 2025-01-24 | RUSH B (Russian team)                     | W   | 0.599      | 0.500        | 0.026 (0.009)    | 0.901 (0.324)    | 0 (0.000) |    12.45 | dav1g, mopoz, sausol, stadodo         |
|           25 |     1329 | 2025-01-24 | KONO.ECF                                  | L   | 0.598      | -            | -                | -                | -         |   -14.68 | alex, dav1g, mopoz, sausol, stadodo   |
|           24 |     1389 | 2025-01-22 | Zero Tenacity                             | L   | 0.588      | -            | -                | -                | -         |    -8.05 | dav1g, mopoz, sausol, stadodo         |
|           23 |     1952 | 2024-12-14 | Chimera Esports                           | L   | 0.370      | -            | -                | -                | -         |    -5.63 | adamS, dav1g, mopoz, sausol, stadodo  |
|           22 |     2044 | 2024-12-13 | GUN5 Esports                              | L   | 0.364      | -            | -                | -                | -         |    -3.91 | adamS, dav1g, mopoz, sausol, stadodo  |
|           21 |     2106 | 2024-12-11 | Endpoint                                  | L   | 0.354      | -            | -                | -                | -         |    -7.75 | adamS, dav1g, mopoz, sausol, stadodo  |
|           20 |     2149 | 2024-12-10 | Team Spirit Academy                       | L   | 0.349      | -            | -                | -                | -         |    -4.50 | adamS, dav1g, mopoz, sausol, stadodo  |
|           19 |     2156 | 2024-12-10 | TSM                                       | W   | 0.348      | -            | -                | -                | -         |     3.01 | adamS, dav1g, mopoz, sausol, stadodo  |
|           18 |     2319 | 2024-12-07 | FAVBET Team                               | W   | 0.332      | 0.435        | 0.023 (0.004)    | 0.790 (0.137)    | -         |     5.51 | adamS, dav1g, mopoz, sausol, stadodo  |
|           17 |     2364 | 2024-12-06 | 9INE                                      | L   | 0.325      | -            | -                | -                | -         |    -4.59 | adamS, dav1g, mopoz, sausol, stadodo  |
|           16 |     2384 | 2024-12-05 | Betclic Apogee Esports                    | W   | 0.320      | 0.371        | -                | 0.528 (0.075)    | -         |     5.02 | adamS, dav1g, mopoz, sausol, stadodo  |
|           15 |     2428 | 2024-12-04 | Tricked Esport                            | W   | 0.314      | 0.435        | 0.030 (0.005)    | 0.549 (0.090)    | -         |     4.80 | adamS, dav1g, mopoz, sausol, stadodo  |
|           14 |     2590 | 2024-12-01 | Tricked Esport                            | W   | 0.298      | 0.371        | 0.030 (0.004)    | -                | -         |     4.67 | adamS, dav1g, mopoz, sausol, stadodo  |
|           13 |     2760 | 2024-11-28 | GUN5 Esports                              | L   | 0.282      | -            | -                | -                | -         |    -3.01 | adamS, dav1g, mopoz, sausol, stadodo  |
|           12 |     2792 | 2024-11-27 | Tricked Esport                            | L   | 0.277      | -            | -                | -                | -         |    -4.64 | adamS, dav1g, mopoz, sausol, stadodo  |
|           11 |     2799 | 2024-11-27 | TEAM NEXT LEVEL                           | W   | 0.276      | 0.333        | 0.041 (0.004)    | -                | -         |     4.23 | adamS, dav1g, mopoz, sausol, stadodo  |
|           10 |     2842 | 2024-11-26 | Tricked Esport                            | W   | 0.271      | 0.333        | 0.030 (0.003)    | -                | -         |     4.06 | adamS, dav1g, mopoz, sausol, stadodo  |
|            9 |     2875 | 2024-11-25 | 9INE                                      | W   | 0.265      | -            | -                | -                | -         |     2.26 | adamS, dav1g, mopoz, sausol, stadodo  |
|            8 |     2988 | 2024-11-23 | ENCE Academy                              | W   | 0.254      | -            | -                | -                | -         |     3.66 | adamS, dav1g, mopoz, sausol, stadodo  |
|            7 |     3087 | 2024-11-22 | JANO Esports                              | W   | 0.249      | -            | -                | -                | -         |     4.98 | adamS, dav1g, mopoz, sausol, stadodo  |
|            6 |     3240 | 2024-11-20 | ENCE Academy                              | L   | 0.237      | -            | -                | -                | -         |    -4.04 | adamS, dav1g, mopoz, sausol, stadodo  |
|            5 |     3377 | 2024-11-17 | Rhyno Esports                             | L   | 0.220      | -            | -                | -                | -         |    -3.93 | adamS, dav1g, deLonge, mopoz, stadodo |
|            4 |     3436 | 2024-11-16 | GOOFYBOYZ                                 | W   | 0.215      | -            | -                | -                | 1 (0.258) |     2.43 | adamS, dav1g, deLonge, mopoz, stadodo |
|            3 |     4345 | 2024-10-30 | ECSTATIC                                  | L   | 0.122      | -            | -                | -                | -         |    -1.86 | adamS, dav1g, JUST, mopoz, stadodo    |
|            2 |     4372 | 2024-10-30 | Illuminar Gaming                          | W   | 0.121      | -            | -                | -                | -         |     1.57 | adamS, dav1g, JUST, mopoz, stadodo    |
|            1 |     4388 | 2024-10-30 | Metizport                                 | L   | 0.121      | -            | -                | -                | -         |    -1.10 | adamS, dav1g, JUST, mopoz, stadodo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,960.99)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      0.939 | $500.00        | $469.58         |
| 2024-11-27 |      0.331 | $5,000.00      | $1,654.86       |
| 2024-11-17 |      0.264 | $3,163.39      | $836.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
