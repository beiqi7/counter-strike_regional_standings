### Roster Details<br />
Team Name: RUSH B (Russian team)<br />
Roster: executor, kinqie, KIRO, tex1y, z1Nny<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  925.2<br />
<br />
Final Rank Value (925.2) = Starting Rank Value (969.1) + Head To Head Adjustments (-43.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.402[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.172[<sup>2</sup>](#table1)

The average of these factors is 0.274<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 969.1
- 400 + ( ( 0.274 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 969.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           65 |        9 | 2025-02-28 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -16.48 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           64 |       31 | 2025-02-27 | ALASKA                          | W   | 1.000      | 0.143        | 0.036 (0.005)    | 0.888 (0.127)    | 0 (0.000) |    15.19 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           63 |       64 | 2025-02-26 | B8                              | L   | 1.000      | -            | -                | -                | -         |    -5.07 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           62 |       71 | 2025-02-26 | FAVBET Team                     | L   | 1.000      | -            | -                | -                | -         |   -17.60 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           61 |      137 | 2025-02-24 | PARIVISION                      | L   | 1.000      | -            | -                | -                | -         |   -16.06 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           60 |      174 | 2025-02-23 | ESC Gaming                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.23 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           59 |      231 | 2025-02-22 | Rebels Gaming                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.68 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           58 |      249 | 2025-02-21 | Fire Flux Esports               | L   | 1.000      | -            | -                | -                | -         |   -15.51 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           57 |      274 | 2025-02-21 | Astralis Talent                 | L   | 1.000      | -            | -                | -                | -         |   -24.03 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           56 |      309 | 2025-02-20 | Benched                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.04 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           55 |      344 | 2025-02-19 | Zero Tenacity                   | W   | 1.000      | 0.500        | 0.032 (0.016)    | 0.843 (0.422)    | 0 (0.000) |    13.70 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           54 |      373 | 2025-02-18 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -14.66 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           53 |      374 | 2025-02-18 | Team Spirit Academy             | L   | 1.000      | -            | -                | -                | -         |   -12.02 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           52 |      418 | 2025-02-17 | Fnatic                          | L   | 1.000      | -            | -                | -                | -         |   -10.10 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           51 |      513 | 2025-02-15 | KONO.ECF                        | L   | 1.000      | -            | -                | -                | -         |   -26.31 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           50 |      549 | 2025-02-14 | QUAZAR                          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           49 |      565 | 2025-02-14 | GTZ.ESPORTS                     | W   | 1.000      | 0.435        | 0.094 (0.041)    | 0.619 (0.269)    | 0 (0.000) |    20.21 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           48 |      668 | 2025-02-10 | Sashi Esport                    | W   | 1.000      | 0.435        | 0.015 (0.007)    | 0.606 (0.263)    | 0 (0.000) |    14.82 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           47 |      717 | 2025-02-09 | OG                              | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.985 (0.141)    | -         |    15.74 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           46 |      786 | 2025-02-08 | Natus Vincere Junior            | L   | 1.000      | -            | -                | -                | -         |   -13.48 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           45 |      796 | 2025-02-08 | Zero Tenacity                   | W   | 1.000      | 0.143        | 0.032 (0.005)    | 0.843 (0.120)    | -         |    12.26 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           44 |      840 | 2025-02-07 | Heimo Esports                   | W   | 1.000      | 0.143        | -                | 0.667 (0.095)    | -         |     7.39 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           43 |      981 | 2025-02-05 | Adventurers                     | W   | 1.000      | -            | -                | -                | -         |     9.38 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           42 |     1011 | 2025-02-04 | Zero Tenacity                   | L   | 1.000      | -            | -                | -                | -         |   -17.80 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           41 |     1036 | 2025-02-04 | Monte                           | L   | 1.000      | -            | -                | -                | -         |   -15.11 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           40 |     1290 | 2025-01-22 | ARCRED                          | W   | 0.930      | 0.500        | 0.025 (0.012)    | 0.541 (0.252)    | -         |     9.33 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           39 |     1508 | 2024-12-22 | Zero Tenacity                   | W   | 0.724      | 0.143        | 0.032 (0.003)    | 0.843 (0.087)    | -         |    10.81 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           38 |     1526 | 2024-12-22 | P0RTUGAL                        | L   | 0.723      | -            | -                | -                | -         |   -15.24 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           37 |     1582 | 2024-12-21 | JANO Esports                    | W   | 0.716      | -            | -                | -                | -         |     8.46 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           36 |     1741 | 2024-12-15 | FORZE Reload                    | W   | 0.677      | 0.143        | 0.031 (0.003)    | -                | 1 (0.677) |     8.96 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           35 |     1828 | 2024-12-14 | K27                             | W   | 0.668      | 0.143        | -                | 0.787 (0.075)    | 1 (0.668) |     8.79 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           34 |     2074 | 2024-12-08 | 0to100                          | W   | 0.631      | -            | -                | -                | -         |     5.56 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           33 |     2081 | 2024-12-08 | Preasy Esport                   | W   | 0.631      | -            | -                | -                | -         |     5.67 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           32 |     2098 | 2024-12-08 | Aimclub                         | W   | 0.630      | -            | -                | -                | -         |     0.85 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           31 |     2445 | 2024-12-01 | Zero Tenacity                   | L   | 0.584      | -            | -                | -                | -         |    -9.39 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           30 |     2456 | 2024-12-01 | EYEBALLERS                      | W   | 0.583      | -            | -                | -                | -         |     5.84 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           29 |     2797 | 2024-11-24 | Premdesant                      | W   | 0.535      | -            | -                | -                | -         |     3.17 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           28 |     3251 | 2024-11-17 | INDINDA                         | W   | 0.489      | -            | -                | -                | -         |     1.32 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           27 |     3263 | 2024-11-17 | LEON Esports                    | L   | 0.489      | -            | -                | -                | -         |   -11.47 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           26 |     3272 | 2024-11-17 | XP Academy                      | W   | 0.488      | -            | -                | -                | -         |     1.79 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           25 |     3687 | 2024-11-09 | Nuclear TigeRES                 | W   | 0.435      | -            | -                | -                | -         |     5.29 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           24 |     3693 | 2024-11-09 | VOID GAMING (Russian team)      | W   | 0.435      | -            | -                | -                | -         |     0.80 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           23 |     3961 | 2024-11-03 | ARCRED                          | L   | 0.397      | -            | -                | -                | -         |    -8.31 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           22 |     4038 | 2024-11-02 | 1win                            | W   | 0.390      | -            | -                | -                | -         |     3.21 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           21 |     4107 | 2024-11-01 | Nuclear TigeRES                 | W   | 0.384      | -            | -                | -                | -         |     4.60 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           20 |     4391 | 2024-10-27 | K27                             | W   | 0.350      | -            | -                | -                | -         |     5.37 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           19 |     4430 | 2024-10-26 | ECSTATIC                        | L   | 0.343      | -            | -                | -                | -         |    -5.95 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           18 |     4547 | 2024-10-24 | NewBALLS                        | W   | 0.329      | -            | -                | -                | -         |     1.79 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           17 |     4663 | 2024-10-21 | ARCRED                          | L   | 0.309      | -            | -                | -                | -         |    -6.73 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           16 |     4686 | 2024-10-20 | Wu-Tang Clan                    | L   | 0.304      | -            | -                | -                | -         |    -8.87 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           15 |     4700 | 2024-10-20 | GenOne                          | W   | 0.303      | -            | -                | -                | -         |     3.40 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           14 |     4776 | 2024-10-19 | GTZ.ESPORTS                     | W   | 0.295      | 0.143        | 0.094 (0.004)    | -                | -         |     7.98 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           13 |     5073 | 2024-10-13 | FAVBET Team                     | L   | 0.255      | -            | -                | -                | -         |    -4.47 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           12 |     6164 | 2024-09-25 | Fire Flux Esports               | L   | 0.138      | -            | -                | -                | -         |    -2.37 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           11 |     6345 | 2024-09-23 | Asian fetish                    | W   | 0.124      | -            | -                | -                | -         |     0.45 | executor, kinqie, KIRO, tex1y, z1Nny      |
|           10 |     6455 | 2024-09-21 | Freesunshine                    | W   | 0.111      | -            | -                | -                | -         |     0.34 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            9 |     6462 | 2024-09-21 | Cerberus eSports (Russian team) | W   | 0.110      | -            | -                | -                | -         |     0.41 | executor, kinqie, KIRO, tex1y, z1Nny      |
|            8 |     6904 | 2024-09-14 | ARCRED                          | L   | 0.062      | -            | -                | -                | -         |    -1.36 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            7 |     6936 | 2024-09-14 | Devils.one                      | L   | 0.061      | -            | -                | -                | -         |    -1.64 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            6 |     7027 | 2024-09-12 | Nexus Gaming                    | L   | 0.049      | -            | -                | -                | -         |    -0.26 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            5 |     7306 | 2024-09-07 | FLuffy Gangsters                | W   | 0.016      | -            | -                | -                | -         |     0.15 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            4 |     7324 | 2024-09-07 | Partizan Esports                | W   | 0.016      | -            | -                | -                | -         |     0.37 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            3 |     7372 | 2024-09-06 | Asian fetish                    | W   | 0.011      | -            | -                | -                | -         |     0.02 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            2 |     7382 | 2024-09-06 | ZEROvariant                     | W   | 0.010      | -            | -                | -                | -         |     0.01 | executor, Gospadarov, kinqie, KIRO, tex1y |
|            1 |     7485 | 2024-09-05 | HOTU                            | L   | 0.003      | -            | -                | -                | -         |    -0.06 | executor, Gospadarov, kinqie, KIRO, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,996.27)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.724 | $2,607.56      | $1,888.80       |
| 2024-12-15 |      0.677 | $7,263.25      | $4,914.48       |
| 2024-11-03 |      0.397 | $5,108.69      | $2,028.82       |
| 2024-09-23 |      0.124 | $1,300.00      | $160.94         |
| 2024-09-07 |      0.016 | $200.00        | $3.23           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
