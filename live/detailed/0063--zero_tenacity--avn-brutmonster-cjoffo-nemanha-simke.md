### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.4<br />
<br />
Final Rank Value (944.4) = Starting Rank Value (946.4) + Head To Head Adjustments (-2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.124[<sup>2</sup>](#table1)

The average of these factors is 0.263<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 946.4
- 400 + ( ( 0.263 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 946.4


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
|           73 |       10 | 2025-02-28 | Sashi Esport                              | W   | 1.000      | 0.435        | 0.015 (0.007)    | 0.606 (0.263)    | 0 (0.000) |    16.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |       28 | 2025-02-27 | Team Spirit Academy                       | L   | 1.000      | -            | -                | -                | -         |   -10.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |       61 | 2025-02-26 | ARCRED                                    | W   | 1.000      | 0.500        | 0.025 (0.012)    | 0.541 (0.270)    | 0 (0.000) |    12.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |      342 | 2025-02-19 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -13.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |      642 | 2025-02-11 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |      665 | 2025-02-10 | NEVERMORE (Ukrainian team)                | W   | 1.000      | 0.143        | -                | 0.928 (0.133)    | 0 (0.000) |    12.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |      675 | 2025-02-10 | HEROIC                                    | L   | 1.000      | -            | -                | -                | -         |    -7.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |      741 | 2025-02-08 | Little Red Door                           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |      757 | 2025-02-08 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -7.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |      762 | 2025-02-08 | ENCE                                      | W   | 1.000      | 0.143        | 0.158 (0.023)    | -                | 0 (0.000) |    20.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |      774 | 2025-02-08 | FORZE Reload                              | W   | 1.000      | 0.143        | -                | 0.563 (0.080)    | 0 (0.000) |    15.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |      794 | 2025-02-08 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -12.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |      822 | 2025-02-07 | Arch Esports                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.71 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |      945 | 2025-02-05 | KONO.ECF                                  | L   | 1.000      | -            | -                | -                | -         |   -24.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1009 | 2025-02-04 | RUSH B (Russian team)                     | W   | 1.000      | 0.143        | -                | 0.984 (0.141)    | 0 (0.000) |    17.80 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1070 | 2025-02-04 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -23.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1078 | 2025-02-04 | Superior Esports                          | W   | 1.000      | -            | -                | -                | -         |     1.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1199 | 2025-01-28 | B8                                        | L   | 0.971      | -            | -                | -                | -         |    -6.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1203 | 2025-01-28 | Wild Lotus                                | L   | 0.971      | -            | -                | -                | -         |   -20.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1225 | 2025-01-27 | Adventurers                               | W   | 0.963      | -            | -                | -                | -         |    10.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1227 | 2025-01-26 | AMKAL ESPORTS                             | L   | 0.957      | -            | -                | -                | -         |   -19.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1244 | 2025-01-24 | Team Spirit Academy                       | W   | 0.944      | 0.500        | 0.080 (0.038)    | 0.863 (0.407)    | -         |    19.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1506 | 2024-12-22 | RUSH B (Russian team)                     | L   | 0.725      | -            | -                | -                | -         |   -10.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1510 | 2024-12-22 | Metizport                                 | L   | 0.724      | -            | -                | -                | -         |    -7.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1561 | 2024-12-21 | Alliance                                  | W   | 0.717      | -            | -                | -                | -         |     9.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     1823 | 2024-12-14 | ECSTATIC                                  | L   | 0.669      | -            | -                | -                | -         |   -10.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     1939 | 2024-12-12 | AMKAL ESPORTS                             | W   | 0.658      | 0.435        | -                | 0.689 (0.197)    | -         |     7.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2432 | 2024-12-01 | FORZE Reload                              | W   | 0.584      | -            | -                | -                | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2443 | 2024-12-01 | RUSH B (Russian team)                     | W   | 0.584      | 0.143        | -                | 0.984 (0.082)    | -         |     9.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2457 | 2024-12-01 | Los kogutos                               | W   | 0.584      | -            | -                | -                | -         |     0.81 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2869 | 2024-11-23 | ENCE                                      | L   | 0.530      | -            | -                | -                | -         |    -6.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     3226 | 2024-11-17 | 0to100                                    | W   | 0.491      | -            | -                | -                | 1 (0.491) |     4.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     3331 | 2024-11-16 | Juggernauts                               | W   | 0.482      | -            | -                | -                | 1 (0.482) |     2.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     3547 | 2024-11-11 | Ninjas in Pyjamas                         | L   | 0.451      | -            | -                | -                | -         |    -8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     3598 | 2024-11-10 | Tricked Esport                            | W   | 0.444      | 0.384        | 0.039 (0.007)    | 0.702 (0.120)    | -         |     5.90 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     3658 | 2024-11-09 | GUN5 Esports                              | W   | 0.437      | 0.143        | 0.123 (0.008)    | -                | -         |     8.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     3726 | 2024-11-08 | Johnny Speeds                             | W   | 0.429      | 0.384        | 0.046 (0.008)    | -                | -         |     7.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     3820 | 2024-11-06 | HOTU                                      | W   | 0.416      | 0.384        | -                | 0.785 (0.125)    | -         |     2.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     3937 | 2024-11-04 | 500                                       | L   | 0.403      | -            | -                | -                | -         |    -4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     4055 | 2024-11-02 | Los kogutos                               | W   | 0.390      | 0.384        | 0.037 (0.006)    | -                | -         |     6.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     4301 | 2024-10-29 | OG                                        | L   | 0.363      | -            | -                | -                | -         |    -5.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     4344 | 2024-10-28 | 500                                       | L   | 0.358      | -            | -                | -                | -         |    -3.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     4360 | 2024-10-28 | Dynamo Eclot                              | L   | 0.357      | -            | -                | -                | -         |    -3.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     4364 | 2024-10-28 | Wu-Tang Clan                              | W   | 0.356      | -            | -                | -                | -         |     1.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     4975 | 2024-10-15 | 9Pandas                                   | L   | 0.270      | -            | -                | -                | -         |    -3.03 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     5216 | 2024-10-10 | Aurora Gaming                             | L   | 0.234      | -            | -                | -                | -         |    -4.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     5407 | 2024-10-07 | ECSTATIC                                  | W   | 0.216      | -            | -                | -                | -         |     3.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     5440 | 2024-10-06 | MADNESS (Kosovar team)                    | W   | 0.210      | -            | -                | -                | -         |     0.64 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     5516 | 2024-10-05 | Team Spirit Academy                       | L   | 0.203      | -            | -                | -                | -         |    -2.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     5766 | 2024-10-01 | FAVBET Team                               | W   | 0.175      | -            | -                | -                | -         |     2.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     6176 | 2024-09-25 | Tricked Esport                            | L   | 0.138      | -            | -                | -                | -         |    -2.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     6208 | 2024-09-25 | 3DMAX                                     | L   | 0.135      | -            | -                | -                | -         |    -0.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     6314 | 2024-09-24 | 3DMAX                                     | L   | 0.128      | -            | -                | -                | -         |    -0.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     6362 | 2024-09-23 | SINNERS Esports                           | W   | 0.124      | -            | -                | -                | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     6376 | 2024-09-23 | Nexus Gaming                              | W   | 0.123      | 0.435        | 0.219 (0.012)    | -                | -         |     3.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     6426 | 2024-09-22 | Copenhagen Wolves (American organization) | L   | 0.115      | -            | -                | -                | -         |    -3.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     6598 | 2024-09-19 | FAVBET Team                               | W   | 0.096      | -            | -                | -                | -         |     1.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     6674 | 2024-09-18 | Monte                                     | L   | 0.088      | -            | -                | -                | -         |    -1.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     6712 | 2024-09-17 | Sampi NEXT                                | L   | 0.084      | -            | -                | -                | -         |    -2.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     6777 | 2024-09-16 | ECSTATIC                                  | W   | 0.077      | -            | -                | -                | -         |     1.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     6891 | 2024-09-14 | GamerLegion                               | L   | 0.063      | -            | -                | -                | -         |    -1.56 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     6935 | 2024-09-14 | Rebels Gaming                             | L   | 0.062      | -            | -                | -                | -         |    -1.29 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     6985 | 2024-09-13 | 3DMAX                                     | W   | 0.056      | 0.384        | 0.302 (0.006)    | -                | -         |     1.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     7029 | 2024-09-12 | EYEBALLERS                                | W   | 0.049      | -            | -                | -                | -         |     0.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     7084 | 2024-09-11 | Metizport                                 | W   | 0.043      | -            | -                | -                | -         |     1.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     7113 | 2024-09-10 | Devils.one                                | L   | 0.038      | -            | -                | -                | -         |    -0.99 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     7122 | 2024-09-10 | Ins (Polish team)                         | W   | 0.037      | -            | -                | -                | -         |     0.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     7196 | 2024-09-09 | Metizport                                 | W   | 0.029      | -            | -                | -                | -         |     0.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     7238 | 2024-09-08 | B8                                        | L   | 0.023      | -            | -                | -                | -         |    -0.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     7288 | 2024-09-07 | Nemiga Gaming                             | W   | 0.017      | -            | -                | -                | -         |     0.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     7331 | 2024-09-07 | Cloud9                                    | L   | 0.016      | -            | -                | -                | -         |    -0.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     7416 | 2024-09-06 | Young Ninjas                              | W   | 0.008      | -            | -                | -                | -         |     0.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     7478 | 2024-09-05 | Alliance                                  | W   | 0.003      | -            | -                | -                | -         |     0.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,814.43)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.677 | $2,000.00      | $1,354.18       |
| 2024-11-24 |      0.536 | $1,864.89      | $1,000.31       |
| 2024-11-17 |      0.491 | $7,908.47      | $3,882.33       |
| 2024-11-12 |      0.457 | $1,000.00      | $456.79         |
| 2024-10-20 |      0.303 | $5,000.00      | $1,515.30       |
| 2024-09-26 |      0.143 | $1,000.00      | $143.15         |
| 2024-09-15 |      0.070 | $2,000.00      | $139.96         |
| 2024-09-14 |      0.064 | $2,000.00      | $127.23         |
| 2024-09-08 |      0.023 | $5,000.00      | $116.69         |
| 2024-09-07 |      0.016 | $5,000.00      | $78.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
