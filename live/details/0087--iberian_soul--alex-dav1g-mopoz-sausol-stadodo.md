### Roster Details<br />
Team Name: Iberian Soul<br />
Roster: alex, dav1g, mopoz, sausol, stadodo<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.7<br />
<br />
Final Rank Value (908.7) = Starting Rank Value (878.4) + Head To Head Adjustments (30.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.164[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 878.4
- 400 + ( ( 0.230 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 878.4


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
|           46 |       13 | 2025-02-28 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    18.76 | alex, dav1g, mopoz, sausol, stadodo   |
|           45 |       24 | 2025-02-27 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | 0 (0.000) |    16.93 | alex, dav1g, mopoz, sausol, stadodo   |
|           44 |       62 | 2025-02-26 | Team Spirit Academy                       | L   | 1.000      | -            | -                | -                | -         |    -8.63 | alex, dav1g, mopoz, sausol, stadodo   |
|           43 |      108 | 2025-02-25 | Aurora Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -14.78 | alex, dav1g, mopoz, sausol, stadodo   |
|           42 |      132 | 2025-02-24 | OG                                        | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.985 (0.141)    | 0 (0.000) |    21.99 | alex, dav1g, mopoz, sausol, stadodo   |
|           41 |      136 | 2025-02-24 | Fire Flux Esports                         | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    20.42 | alex, dav1g, mopoz, sausol, stadodo   |
|           40 |      186 | 2025-02-23 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.88 | alex, dav1g, mopoz, sausol, stadodo   |
|           39 |      321 | 2025-02-20 | ECSTATIC                                  | W   | 1.000      | 0.143        | 0.038 (0.005)    | -                | 0 (0.000) |    18.49 | alex, dav1g, mopoz, sausol, stadodo   |
|           38 |      343 | 2025-02-19 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -3.70 | alex, dav1g, mopoz, sausol, stadodo   |
|           37 |      349 | 2025-02-19 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |    -8.28 | alex, dav1g, mopoz, sausol, stadodo   |
|           36 |      544 | 2025-02-14 | Rebels Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -16.88 | alex, dav1g, mopoz, sausol, stadodo   |
|           35 |      721 | 2025-02-09 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -12.99 | alex, dav1g, mopoz, sausol, stadodo   |
|           34 |      801 | 2025-02-08 | UNiTY esports                             | W   | 1.000      | 0.143        | 0.030 (0.004)    | -                | 0 (0.000) |    14.35 | alex, dav1g, mopoz, sausol, stadodo   |
|           33 |      852 | 2025-02-07 | Team Novaq                                | L   | 1.000      | -            | -                | -                | -         |    -4.41 | alex, dav1g, mopoz, sausol, stadodo   |
|           32 |      992 | 2025-02-05 | Ninjas in Pyjamas                         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | alex, dav1g, mopoz, sausol, stadodo   |
|           31 |     1073 | 2025-02-04 | UNiTY esports                             | L   | 1.000      | -            | -                | -                | -         |   -16.43 | alex, dav1g, mopoz, sausol, stadodo   |
|           30 |     1238 | 2025-01-25 | ECSTATIC                                  | L   | 0.949      | -            | -                | -                | -         |   -12.77 | alex, dav1g, mopoz, sausol, stadodo   |
|           29 |     1256 | 2025-01-24 | KONO.ECF                                  | L   | 0.942      | -            | -                | -                | -         |   -22.60 | alex, dav1g, mopoz, sausol, stadodo   |
|           28 |     1826 | 2024-12-14 | Chimera Esports                           | L   | 0.669      | -            | -                | -                | -         |    -8.55 | adamS, dav1g, mopoz, sausol, stadodo  |
|           27 |     1923 | 2024-12-13 | GUN5 Esports                              | L   | 0.661      | -            | -                | -                | -         |    -7.28 | adamS, dav1g, mopoz, sausol, stadodo  |
|           26 |     1985 | 2024-12-11 | Endpoint                                  | L   | 0.650      | -            | -                | -                | -         |   -14.44 | adamS, dav1g, mopoz, sausol, stadodo  |
|           25 |     2027 | 2024-12-10 | Team Spirit Academy                       | L   | 0.643      | -            | -                | -                | -         |    -7.81 | adamS, dav1g, mopoz, sausol, stadodo  |
|           24 |     2033 | 2024-12-10 | TSM                                       | W   | 0.642      | -            | -                | -                | 0 (0.000) |     6.39 | adamS, dav1g, mopoz, sausol, stadodo  |
|           23 |     2184 | 2024-12-07 | FAVBET Team                               | W   | 0.623      | 0.435        | 0.037 (0.010)    | 0.952 (0.258)    | -         |    10.77 | adamS, dav1g, mopoz, sausol, stadodo  |
|           22 |     2229 | 2024-12-06 | 9INE                                      | L   | 0.615      | -            | -                | -                | -         |    -9.13 | adamS, dav1g, mopoz, sausol, stadodo  |
|           21 |     2249 | 2024-12-05 | Betclic Apogee Esports                    | W   | 0.609      | 0.371        | -                | 0.528 (0.119)    | -         |     9.65 | adamS, dav1g, mopoz, sausol, stadodo  |
|           20 |     2293 | 2024-12-04 | Tricked Esport                            | W   | 0.602      | 0.435        | 0.039 (0.010)    | 0.702 (0.184)    | -         |    10.28 | adamS, dav1g, mopoz, sausol, stadodo  |
|           19 |     2472 | 2024-12-01 | Tricked Esport                            | W   | 0.582      | 0.371        | 0.039 (0.008)    | 0.702 (0.151)    | -         |    10.46 | adamS, dav1g, mopoz, sausol, stadodo  |
|           18 |     2645 | 2024-11-28 | GUN5 Esports                              | L   | 0.563      | -            | -                | -                | -         |    -6.26 | adamS, dav1g, mopoz, sausol, stadodo  |
|           17 |     2676 | 2024-11-27 | Tricked Esport                            | L   | 0.557      | -            | -                | -                | -         |    -8.34 | adamS, dav1g, mopoz, sausol, stadodo  |
|           16 |     2683 | 2024-11-27 | TEAM NEXT LEVEL                           | W   | 0.556      | 0.333        | 0.047 (0.009)    | -                | -         |     8.62 | adamS, dav1g, mopoz, sausol, stadodo  |
|           15 |     2725 | 2024-11-26 | Tricked Esport                            | W   | 0.551      | 0.333        | 0.039 (0.007)    | 0.702 (0.129)    | -         |     9.31 | adamS, dav1g, mopoz, sausol, stadodo  |
|           14 |     2757 | 2024-11-25 | 9INE                                      | W   | 0.543      | -            | -                | -                | -         |     6.89 | adamS, dav1g, mopoz, sausol, stadodo  |
|           13 |     2868 | 2024-11-23 | ENCE Academy                              | W   | 0.530      | 0.333        | -                | 0.665 (0.117)    | -         |     7.24 | adamS, dav1g, mopoz, sausol, stadodo  |
|           12 |     2969 | 2024-11-22 | JANO Esports                              | W   | 0.523      | 0.333        | 0.026 (0.005)    | -                | -         |    10.31 | adamS, dav1g, mopoz, sausol, stadodo  |
|           11 |     3119 | 2024-11-20 | ENCE Academy                              | L   | 0.510      | -            | -                | -                | -         |    -8.92 | adamS, dav1g, mopoz, sausol, stadodo  |
|           10 |     3247 | 2024-11-17 | Rhyno Esports                             | L   | 0.489      | -            | -                | -                | -         |    -7.13 | adamS, dav1g, deLonge, mopoz, stadodo |
|            9 |     3307 | 2024-11-16 | GOOFYBOYZ                                 | W   | 0.483      | -            | -                | -                | 1 (0.483) |     6.01 | adamS, dav1g, deLonge, mopoz, stadodo |
|            8 |     4203 | 2024-10-30 | ECSTATIC                                  | L   | 0.371      | -            | -                | -                | -         |    -5.05 | adamS, dav1g, JUST, mopoz, stadodo    |
|            7 |     4226 | 2024-10-30 | Illuminar Gaming                          | W   | 0.370      | -            | -                | -                | -         |     5.99 | adamS, dav1g, JUST, mopoz, stadodo    |
|            6 |     4240 | 2024-10-30 | Metizport                                 | L   | 0.370      | -            | -                | -                | -         |    -2.20 | adamS, dav1g, JUST, mopoz, stadodo    |
|            5 |     5531 | 2024-10-05 | Rhyno Esports                             | L   | 0.201      | -            | -                | -                | -         |    -4.59 | adamS, dav1g, JUST, mopoz, stadodo    |
|            4 |     5671 | 2024-10-02 | Natus Vincere Junior                      | L   | 0.183      | -            | -                | -                | -         |    -1.72 | adamS, dav1g, JUST, mopoz, stadodo    |
|            3 |     5743 | 2024-10-01 | Preasy Esport                             | W   | 0.177      | -            | -                | -                | -         |     2.47 | adamS, dav1g, JUST, mopoz, stadodo    |
|            2 |     7379 | 2024-09-06 | Wildcard                                  | L   | 0.010      | -            | -                | -                | -         |    -0.06 | adamS, dav1g, JUST, mopoz, stadodo    |
|            1 |     7502 | 2024-09-05 | The MongolZ                               | L   | 0.002      | -            | -                | -                | -         |     0.00 | adamS, dav1g, JUST, mopoz, stadodo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,462.79)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $500.00        | $500.00         |
| 2024-11-27 |      0.556 | $5,000.00      | $2,779.41       |
| 2024-11-17 |      0.489 | $3,163.39      | $1,548.02       |
| 2024-10-06 |      0.209 | $1,098.17      | $229.30         |
| 2024-09-22 |      0.116 | $3,500.00      | $406.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
