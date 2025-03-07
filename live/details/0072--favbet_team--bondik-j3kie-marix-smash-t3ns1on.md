### Roster Details<br />
Team Name: FAVBET Team<br />
Roster: bondik, j3kie, Marix, Smash, t3ns1on<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  891.9<br />
<br />
Final Rank Value (891.9) = Starting Rank Value (881.9) + Head To Head Adjustments (10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 881.9
- 400 + ( ( 0.218 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 881.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       13 | 2025-02-28 | RUSH B (Russian team)                     | W   | 0.794      | 0.143        | 0.026 (0.004)    | 0.901 (0.123)    | 0 (0.000) |    12.86 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           56 |       31 | 2025-02-27 | ECSTATIC                                  | L   | 0.788      | -            | -                | -                | -         |   -13.40 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           55 |       71 | 2025-02-26 | GUN5 Esports                              | W   | 0.783      | 0.500        | 0.105 (0.049)    | 0.562 (0.264)    | 0 (0.000) |    14.93 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           54 |       75 | 2025-02-26 | RUSH B (Russian team)                     | W   | 0.782      | 0.143        | 0.026 (0.003)    | 0.901 (0.121)    | 0 (0.000) |    13.24 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           53 |      115 | 2025-02-25 | Natus Vincere Junior                      | W   | 0.777      | 0.500        | 0.078 (0.036)    | 0.786 (0.366)    | 0 (0.000) |    15.98 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           52 |      357 | 2025-02-19 | Aurora Gaming                             | L   | 0.744      | -            | -                | -                | -         |   -12.37 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           51 |      810 | 2025-02-08 | Ex-Daystar                                | L   | 0.682      | -            | -                | -                | -         |   -18.33 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           50 |      868 | 2025-02-07 | Streaming5                                | W   | 0.677      | -            | -                | -                | 0 (0.000) |     1.37 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           49 |      880 | 2025-02-07 | Betclic Apogee Esports                    | L   | 0.677      | -            | -                | -                | -         |    -9.90 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           48 |      923 | 2025-02-06 | ALASKA                                    | L   | 0.671      | -            | -                | -                | -         |    -5.86 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           47 |     1047 | 2025-02-04 | ENRAGE                                    | L   | 0.659      | -            | -                | -                | -         |   -16.61 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           46 |     1057 | 2025-02-04 | Ex-Dragon Esports Club                    | W   | 0.659      | -            | -                | -                | 0 (0.000) |     1.13 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           45 |     1205 | 2025-01-29 | Betclic Apogee Esports                    | L   | 0.626      | -            | -                | -                | -         |   -10.47 | crush, j3kie, Marix, Smash, t3ns1on           |
|           44 |     1274 | 2025-01-27 | Aurora Gaming                             | W   | 0.615      | 0.143        | -                | 0.633 (0.067)    | 0 (0.000) |     7.45 | crush, j3kie, Marix, Smash, t3ns1on           |
|           43 |     1281 | 2025-01-26 | UNiTY esports                             | W   | 0.609      | 0.143        | 0.019 (0.002)    | -                | 0 (0.000) |     6.23 | crush, guthriee, j3kie, Marix, Smash, t3ns1on |
|           42 |     1321 | 2025-01-24 | GameAgents                                | W   | 0.599      | -            | -                | -                | 0 (0.000) |     4.95 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           41 |     1391 | 2025-01-22 | Rebels Gaming                             | W   | 0.588      | 0.500        | -                | 0.396 (0.140)    | 0 (0.000) |     6.08 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           40 |     1809 | 2024-12-17 | TEAM NEXT LEVEL                           | W   | 0.388      | 0.143        | 0.041 (0.003)    | -                | -         |     5.45 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           39 |     1858 | 2024-12-15 | Betera Esports                            | W   | 0.377      | -            | -                | -                | -         |     3.66 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           38 |     1917 | 2024-12-14 | Copenhagen Wolves (American organization) | L   | 0.372      | -            | -                | -                | -         |    -6.14 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           37 |     2006 | 2024-12-13 | Rebels Gaming                             | W   | 0.366      | -            | -                | -                | -         |     4.04 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           36 |     2056 | 2024-12-12 | FLuffy Gangsters                          | W   | 0.360      | -            | -                | -                | -         |     4.30 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           35 |     2100 | 2024-12-11 | JiJieHao                                  | L   | 0.355      | -            | -                | -                | -         |    -9.77 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           34 |     2141 | 2024-12-10 | Fire Flux Esports                         | W   | 0.349      | -            | -                | -                | -         |     5.95 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           33 |     2181 | 2024-12-09 | Fire Flux Esports                         | L   | 0.342      | -            | -                | -                | -         |    -5.05 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           32 |     2292 | 2024-12-07 | C.S.D.E                                   | W   | 0.332      | -            | -                | -                | -         |     2.69 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           31 |     2319 | 2024-12-07 | Iberian Soul                              | L   | 0.332      | -            | -                | -                | -         |    -5.51 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           30 |     2362 | 2024-12-06 | Leo Team                                  | W   | 0.326      | -            | -                | -                | -         |     4.64 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           29 |     2388 | 2024-12-05 | CYBERSHOKE Esports                        | W   | 0.319      | 0.435        | 0.014 (0.002)    | 1.000 (0.166)    | -         |     4.86 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           28 |     2462 | 2024-12-03 | AMKAL ESPORTS                             | L   | 0.310      | -            | -                | -                | -         |    -6.54 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           27 |     2470 | 2024-12-03 | ALTERNATE aTTaX                           | L   | 0.310      | -            | -                | -                | -         |    -4.78 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           26 |     2676 | 2024-11-30 | Copenhagen Wolves (American organization) | L   | 0.292      | -            | -                | -                | -         |    -4.89 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           25 |     2759 | 2024-11-28 | Nexus Gaming                              | W   | 0.282      | 0.372        | 0.161 (0.020)    | 0.539 (0.068)    | -         |     7.02 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           24 |     3011 | 2024-11-23 | Copenhagen Wolves (American organization) | W   | 0.253      | 0.372        | -                | 1.000 (0.113)    | -         |     3.78 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           23 |     3075 | 2024-11-22 | 500                                       | L   | 0.249      | -            | -                | -                | -         |    -2.33 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           22 |     3147 | 2024-11-21 | Team Spirit Academy                       | W   | 0.243      | 0.372        | 0.053 (0.006)    | 0.682 (0.074)    | -         |     4.52 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           21 |     3202 | 2024-11-20 | Haspers Team                              | W   | 0.238      | -            | -                | -                | -         |     1.98 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           20 |     3213 | 2024-11-20 | Ex-9INE Academy                           | W   | 0.238      | -            | -                | -                | -         |     0.64 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           19 |     3238 | 2024-11-20 | Fire Flux Esports                         | L   | 0.237      | -            | -                | -                | -         |    -3.50 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           18 |     3277 | 2024-11-19 | Leo Team                                  | W   | 0.232      | 0.372        | 0.020 (0.002)    | -                | -         |     3.11 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           17 |     3311 | 2024-11-18 | 1win                                      | W   | 0.227      | -            | -                | -                | -         |     2.12 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           16 |     3598 | 2024-11-13 | Anonymo Esports                           | W   | 0.199      | -            | -                | -                | -         |     0.70 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           15 |     3752 | 2024-11-10 | Monte                                     | L   | 0.182      | -            | -                | -                | -         |    -3.46 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           14 |     3957 | 2024-11-06 | Endpoint                                  | W   | 0.159      | -            | -                | -                | -         |     1.67 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           13 |     4058 | 2024-11-04 | Heimo Esports                             | W   | 0.149      | -            | -                | -                | -         |     1.49 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           12 |     4126 | 2024-11-03 | Natus Vincere Junior                      | W   | 0.143      | -            | -                | -                | -         |     2.94 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           11 |     4249 | 2024-11-01 | TEAM NEXT LEVEL                           | L   | 0.132      | -            | -                | -                | -         |    -2.30 | bondik, j3kie, Marix, Smash, t3ns1on          |
|           10 |     4431 | 2024-10-29 | Infinite Gaming                           | W   | 0.116      | -            | -                | -                | -         |     0.43 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            9 |     4826 | 2024-10-21 | The Suspect                               | W   | 0.071      | -            | -                | -                | -         |     0.64 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            8 |     4908 | 2024-10-20 | Tricked Esport                            | W   | 0.065      | -            | -                | -                | -         |     0.87 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            7 |     5047 | 2024-10-17 | Preasy Esport                             | L   | 0.048      | -            | -                | -                | -         |    -1.35 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            6 |     5270 | 2024-10-13 | Team Spirit Academy                       | L   | 0.026      | -            | -                | -                | -         |    -0.33 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            5 |     5282 | 2024-10-13 | Aurora Gaming                             | W   | 0.026      | -            | -                | -                | -         |     0.34 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            4 |     5294 | 2024-10-13 | RUSH B (Russian team)                     | W   | 0.025      | -            | -                | -                | -         |     0.46 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            3 |     5387 | 2024-10-12 | Passion UA                                | W   | 0.019      | -            | -                | -                | -         |     0.29 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            2 |     5410 | 2024-10-11 | BetBoom Team                              | W   | 0.014      | -            | -                | -                | -         |     0.29 | bondik, j3kie, Marix, Smash, t3ns1on          |
|            1 |     5445 | 2024-10-10 | Insilio                                   | L   | 0.008      | -            | -                | -                | -         |    -0.21 | bondik, j3kie, Marix, Smash, t3ns1on          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,771.72)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.465 | $9,581.38      | $4,456.67       |
| 2024-10-13 |      0.032 | $10,000.00     | $315.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
