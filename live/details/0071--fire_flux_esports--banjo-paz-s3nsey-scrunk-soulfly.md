### Roster Details<br />
Team Name: Fire Flux Esports<br />
Roster: Banjo, paz, S3NSEY, ScrunK, soulfly<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  893.6<br />
<br />
Final Rank Value (893.6) = Starting Rank Value (891.9) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.320[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.222[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.9
- 400 + ( ( 0.223 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 891.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           74 |       14 | 2025-02-28 | SINNERS Esports                           | L   | 0.793      | -            | -                | -                | -         |   -13.76 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           73 |       17 | 2025-02-28 | Iberian Soul                              | L   | 0.792      | -            | -                | -                | -         |   -14.71 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           72 |       32 | 2025-02-27 | GUN5 Esports                              | L   | 0.787      | -            | -                | -                | -         |   -11.49 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           71 |      112 | 2025-02-25 | 500                                       | W   | 0.777      | 0.500        | 0.118 (0.055)    | 1.000 (0.466)    | 0 (0.000) |    17.16 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           70 |      120 | 2025-02-25 | Wild Lotus                                | W   | 0.775      | -            | -                | -                | 0 (0.000) |     4.41 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           69 |      142 | 2025-02-24 | Iberian Soul                              | L   | 0.771      | -            | -                | -                | -         |   -15.28 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           68 |      146 | 2025-02-24 | Ninjas in Pyjamas                         | W   | 0.770      | -            | -                | -                | 0 (0.000) |     5.60 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           67 |      214 | 2025-02-22 | ESC Gaming                                | W   | 0.760      | -            | -                | -                | 0 (0.000) |     3.38 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           66 |      255 | 2025-02-21 | RUSH B (Russian team)                     | W   | 0.755      | 0.143        | -                | 0.901 (0.117)    | 0 (0.000) |    11.90 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           65 |      393 | 2025-02-18 | Nemiga Gaming                             | L   | 0.738      | -            | -                | -                | -         |   -10.67 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           64 |      617 | 2025-02-13 | Nexus Gaming                              | L   | 0.709      | -            | -                | -                | -         |    -8.65 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           63 |      731 | 2025-02-09 | SINNERS Esports                           | W   | 0.688      | 0.435        | 0.016 (0.006)    | 0.494 (0.177)    | 0 (0.000) |    10.78 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           62 |      853 | 2025-02-07 | Ex-Daystar                                | L   | 0.678      | -            | -                | -                | -         |   -19.16 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           61 |      892 | 2025-02-07 | Natus Vincere Junior                      | W   | 0.676      | 0.435        | 0.078 (0.027)    | 0.786 (0.277)    | 0 (0.000) |    12.39 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           60 |      935 | 2025-02-06 | GTZ.ESPORTS                               | L   | 0.670      | -            | -                | -                | -         |    -4.42 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           59 |     1030 | 2025-02-04 | B8                                        | L   | 0.660      | -            | -                | -                | -         |    -5.51 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           58 |     1036 | 2025-02-04 | 500                                       | L   | 0.660      | -            | -                | -                | -         |    -8.13 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           57 |     1046 | 2025-02-04 | ARCRED                                    | W   | 0.659      | -            | -                | -                | 0 (0.000) |     7.66 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           56 |     1059 | 2025-02-04 | Sangal Esports                            | W   | 0.659      | -            | -                | -                | 0 (0.000) |     1.01 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           55 |     1127 | 2025-02-02 | 9INE                                      | W   | 0.649      | 0.435        | 0.039 (0.013)    | 0.876 (0.296)    | 0 (0.000) |    10.72 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           54 |     1199 | 2025-01-29 | Ninjas in Pyjamas                         | W   | 0.627      | -            | -                | -                | -         |     2.89 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           53 |     1271 | 2025-01-27 | Betera Esports                            | L   | 0.616      | -            | -                | -                | -         |   -15.78 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           52 |     1292 | 2025-01-25 | ALASKA                                    | W   | 0.603      | -            | -                | -                | -         |    13.51 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           51 |     1324 | 2025-01-24 | Betclic Apogee Esports                    | W   | 0.599      | -            | -                | -                | -         |     8.33 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           50 |     1327 | 2025-01-24 | Sashi Esport                              | W   | 0.598      | 0.500        | -                | 0.535 (0.192)    | -         |    11.39 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           49 |     1358 | 2025-01-23 | CYBERSHOKE Esports                        | W   | 0.594      | 0.500        | 0.014 (0.005)    | 1.000 (0.356)    | -         |     8.42 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           48 |     1749 | 2024-12-20 | Nexus Gaming                              | L   | 0.404      | -            | -                | -                | -         |    -3.33 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           47 |     1772 | 2024-12-19 | TEAM NEXT LEVEL                           | L   | 0.399      | -            | -                | -                | -         |    -7.12 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           46 |     1857 | 2024-12-15 | CYBERSHOKE Esports                        | L   | 0.377      | -            | -                | -                | -         |    -6.56 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           45 |     1942 | 2024-12-14 | Team Spirit Academy                       | L   | 0.371      | -            | -                | -                | -         |    -5.03 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           44 |     2009 | 2024-12-13 | Betera Esports                            | W   | 0.366      | -            | -                | -                | -         |     3.12 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           43 |     2066 | 2024-12-12 | Insilio                                   | W   | 0.360      | -            | -                | -                | -         |     1.14 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           42 |     2098 | 2024-12-11 | Endpoint                                  | W   | 0.355      | -            | -                | -                | -         |     3.10 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           41 |     2110 | 2024-12-11 | ECSTATIC                                  | L   | 0.354      | -            | -                | -                | -         |    -6.20 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           40 |     2141 | 2024-12-10 | FAVBET Team                               | L   | 0.349      | -            | -                | -                | -         |    -5.95 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           39 |     2181 | 2024-12-09 | FAVBET Team                               | W   | 0.342      | 0.435        | 0.023 (0.004)    | 0.790 (0.141)    | -         |     5.05 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           38 |     2331 | 2024-12-07 | Tricked Esport                            | W   | 0.330      | 0.435        | 0.030 (0.005)    | -                | -         |     4.37 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           37 |     2359 | 2024-12-06 | 500                                       | L   | 0.327      | -            | -                | -                | -         |    -3.25 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           36 |     2379 | 2024-12-05 | Team Spirit Academy                       | W   | 0.321      | 0.372        | 0.053 (0.008)    | 0.682 (0.098)    | -         |     5.73 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           35 |     2383 | 2024-12-05 | Metizport                                 | L   | 0.320      | -            | -                | -                | -         |    -3.66 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           34 |     2409 | 2024-12-04 | GenOne                                    | W   | 0.316      | -            | -                | -                | -         |     4.07 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           33 |     2424 | 2024-12-04 | Endpoint                                  | L   | 0.315      | -            | -                | -                | -         |    -7.17 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           32 |     2461 | 2024-12-03 | FLuffy Gangsters                          | W   | 0.311      | -            | -                | -                | -         |     3.51 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           31 |     2657 | 2024-11-30 | CYBERSHOKE Esports                        | L   | 0.293      | -            | -                | -                | -         |    -5.04 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           30 |     2763 | 2024-11-28 | Kubix Esports                             | W   | 0.282      | 0.372        | 0.039 (0.005)    | -                | -         |     4.57 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           29 |     2867 | 2024-11-25 | Tricked Esport                            | L   | 0.266      | -            | -                | -                | -         |    -5.08 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           28 |     2906 | 2024-11-24 | Endpoint                                  | L   | 0.259      | -            | -                | -                | -         |    -5.99 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           27 |     2958 | 2024-11-23 | Al-Ittihad                                | W   | 0.255      | -            | -                | -                | -         |     1.74 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           26 |     3154 | 2024-11-21 | Copenhagen Wolves (American organization) | L   | 0.243      | -            | -                | -                | -         |    -4.35 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           25 |     3165 | 2024-11-21 | Copenhagen Wolves (American organization) | W   | 0.242      | 0.333        | -                | 1.000 (0.097)    | -         |     3.34 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           24 |     3198 | 2024-11-20 | Hawks (Argentinian team)                  | W   | 0.238      | -            | -                | -                | -         |     0.66 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           23 |     3223 | 2024-11-20 | K27                                       | W   | 0.238      | -            | -                | -                | -         |     4.27 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           22 |     3238 | 2024-11-20 | FAVBET Team                               | W   | 0.237      | -            | -                | -                | -         |     3.50 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           21 |     3284 | 2024-11-19 | Haspers Team                              | W   | 0.232      | -            | -                | -                | -         |     1.82 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           20 |     3337 | 2024-11-18 | Sissi State Punks                         | W   | 0.226      | -            | -                | -                | -         |     1.05 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           19 |     3439 | 2024-11-16 | Astralis Talent                           | W   | 0.215      | -            | -                | -                | -         |     2.22 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           18 |     3545 | 2024-11-14 | GenOne                                    | W   | 0.205      | -            | -                | -                | -         |     2.46 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           17 |     3594 | 2024-11-13 | ALASKA                                    | W   | 0.199      | -            | -                | -                | -         |     5.24 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           16 |     3697 | 2024-11-11 | Ex-RUBY                                   | W   | 0.188      | -            | -                | -                | -         |     0.68 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           15 |     3862 | 2024-11-08 | 9Pandas                                   | L   | 0.170      | -            | -                | -                | -         |    -1.93 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           14 |     4065 | 2024-11-04 | Nexus Gaming                              | W   | 0.149      | 0.372        | 0.161 (0.011)    | -                | -         |     3.66 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           13 |     4107 | 2024-11-03 | P0RTUGAL                                  | W   | 0.143      | -            | -                | -                | -         |     1.64 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           12 |     4323 | 2024-10-31 | Copenhagen Wolves (American organization) | W   | 0.125      | -            | -                | -                | -         |     1.88 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           11 |     4354 | 2024-10-30 | 1win                                      | L   | 0.122      | -            | -                | -                | -         |    -2.77 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|           10 |     4375 | 2024-10-30 | KONO.ECF                                  | W   | 0.121      | -            | -                | -                | -         |     2.07 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            9 |     4688 | 2024-10-25 | 9Pandas                                   | L   | 0.092      | -            | -                | -                | -         |    -1.07 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            8 |     4757 | 2024-10-23 | Ex-9INE Academy                           | W   | 0.082      | -            | -                | -                | -         |     0.23 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            7 |     4824 | 2024-10-21 | GenOne                                    | W   | 0.071      | -            | -                | -                | -         |     0.85 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            6 |     4840 | 2024-10-21 | Illuminar Gaming                          | W   | 0.071      | -            | -                | -                | -         |     0.82 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            5 |     5048 | 2024-10-17 | ARCRED                                    | W   | 0.048      | -            | -                | -                | -         |     0.60 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            4 |     5128 | 2024-10-16 | ROUNDS                                    | W   | 0.043      | -            | -                | -                | -         |     0.15 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            3 |     5197 | 2024-10-15 | Partizan Esports                          | W   | 0.037      | -            | -                | -                | -         |     0.86 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            2 |     5375 | 2024-10-12 | Sashi Esport                              | L   | 0.019      | -            | -                | -                | -         |    -0.23 | Banjo, paz, S3NSEY, ScrunK, soulfly |
|            1 |     5489 | 2024-10-09 | ALTERNATE aTTaX                           | W   | 0.004      | -            | -                | -                | -         |     0.07 | Banjo, paz, S3NSEY, ScrunK, soulfly |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,589.03)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.405 | $2,000.00      | $810.56         |
| 2024-11-24 |      0.311 | $2,500.00      | $778.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
