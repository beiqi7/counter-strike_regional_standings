### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, byr9, kensizor, nifee, s4ltovsk1yy<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.2<br />
<br />
Final Rank Value (946.2) = Starting Rank Value (924.6) + Head To Head Adjustments (21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.429[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.6
- 400 + ( ( 0.238 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 924.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |     1515 | 2024-12-30 | Dark Cloud Esports                        | W   | 0.459      | 0.333        | 0.035 (0.006)    | 0.667 (0.122)    | 0 (0.000) |     5.64 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           59 |     1530 | 2024-12-29 | Los kogutos                               | W   | 0.453      | 0.333        | 0.022 (0.004)    | -                | 0 (0.000) |     5.69 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           58 |     1568 | 2024-12-28 | Kubix Esports                             | W   | 0.448      | 0.333        | 0.039 (0.007)    | -                | 0 (0.000) |     6.60 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           57 |     1610 | 2024-12-25 | WOPA Esport                               | W   | 0.431      | 0.333        | 0.031 (0.005)    | 0.611 (0.105)    | 0 (0.000) |     5.65 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           56 |     1620 | 2024-12-23 | TEAM NEXT LEVEL                           | L   | 0.420      | -            | -                | -                | -         |    -7.71 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           55 |     1623 | 2024-12-23 | ENCE Academy                              | W   | 0.419      | 0.333        | -                | 0.566 (0.095)    | 0 (0.000) |     4.90 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           54 |     1628 | 2024-12-22 | Monte                                     | W   | 0.416      | 0.371        | 0.036 (0.007)    | 0.766 (0.142)    | 0 (0.000) |     7.30 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           53 |     1640 | 2024-12-22 | TEAM NEXT LEVEL                           | W   | 0.415      | 0.143        | 0.041 (0.003)    | -                | 0 (0.000) |     5.79 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           52 |     1650 | 2024-12-22 | Nexus Gaming                              | W   | 0.414      | 0.371        | 0.161 (0.030)    | 0.539 (0.099)    | 0 (0.000) |     9.39 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           51 |     1686 | 2024-12-21 | JANO Esports                              | W   | 0.410      | 0.371        | 0.019 (0.003)    | -                | -         |     6.67 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           50 |     1709 | 2024-12-21 | ADEPTS                                    | W   | 0.409      | -            | -                | -                | -         |     1.91 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           49 |     1726 | 2024-12-21 | WOPA Esport                               | L   | 0.408      | -            | -                | -                | -         |    -7.67 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           48 |     1744 | 2024-12-20 | TEAM NEXT LEVEL                           | L   | 0.405      | -            | -                | -                | -         |    -7.24 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           47 |     1767 | 2024-12-19 | Nexus Gaming                              | W   | 0.399      | 0.371        | 0.161 (0.029)    | 0.539 (0.096)    | -         |     9.28 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           46 |     1773 | 2024-12-19 | Astralis Talent                           | W   | 0.398      | 0.333        | -                | 0.564 (0.090)    | -         |     4.18 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           45 |     1786 | 2024-12-19 | Preasy Esport                             | W   | 0.397      | 0.333        | -                | 0.647 (0.103)    | -         |     4.09 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           44 |     1805 | 2024-12-17 | Lazer Cats                                | W   | 0.388      | -            | -                | -                | -         |     3.55 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           43 |     1808 | 2024-12-17 | Dark Cloud Esports                        | L   | 0.388      | -            | -                | -                | -         |    -7.06 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           42 |     1827 | 2024-12-16 | Monte                                     | W   | 0.382      | 0.371        | 0.036 (0.006)    | 0.766 (0.130)    | -         |     7.22 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           41 |     1839 | 2024-12-16 | GenOne                                    | W   | 0.380      | 0.333        | -                | 0.644 (0.098)    | -         |     4.81 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           40 |     2062 | 2024-12-12 | Astralis Talent                           | W   | 0.360      | -            | -                | -                | -         |     4.13 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           39 |     2072 | 2024-12-12 | Lilmix                                    | W   | 0.359      | -            | -                | -                | -         |     2.10 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           38 |     2234 | 2024-12-08 | GODSENT                                   | W   | 0.337      | -            | -                | -                | -         |     2.38 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           37 |     2251 | 2024-12-08 | GenOne                                    | L   | 0.336      | -            | -                | -                | -         |    -5.97 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           36 |     2583 | 2024-12-01 | BC.Game Esports                           | L   | 0.298      | -            | -                | -                | -         |    -5.13 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           35 |     2680 | 2024-11-30 | Betclic Apogee Esports                    | L   | 0.292      | -            | -                | -                | -         |    -4.77 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |     2724 | 2024-11-29 | BC.Game Esports                           | L   | 0.287      | -            | -                | -                | -         |    -5.18 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |     2836 | 2024-11-26 | ALTERNATE aTTaX                           | L   | 0.272      | -            | -                | -                | -         |    -4.28 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           32 |     2879 | 2024-11-25 | Preasy Esport                             | W   | 0.264      | -            | -                | -                | -         |     2.75 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           31 |     2893 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.260      | -            | -                | -                | -         |    -4.44 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           30 |     2963 | 2024-11-23 | RUSTEC                                    | L   | 0.255      | -            | -                | -                | -         |    -6.43 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           29 |     2998 | 2024-11-23 | GenOne                                    | W   | 0.254      | -            | -                | -                | -         |     2.96 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |     3094 | 2024-11-22 | FLuffy Gangsters                          | L   | 0.248      | -            | -                | -                | -         |    -5.12 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           27 |     3134 | 2024-11-21 | Leo Team                                  | L   | 0.244      | -            | -                | -                | -         |    -4.69 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           26 |     3152 | 2024-11-21 | RUSTEC                                    | W   | 0.243      | -            | -                | -                | -         |     0.86 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           25 |     3291 | 2024-11-19 | Flame Sharks                              | W   | 0.231      | -            | -                | -                | -         |     0.91 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           24 |     3497 | 2024-11-15 | Team Novaq                                | L   | 0.210      | -            | -                | -                | -         |    -2.98 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     3505 | 2024-11-15 | Team USA                                  | W   | 0.209      | -            | -                | -                | 1 (0.251) |     0.35 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     3543 | 2024-11-14 | Team Latvia                               | L   | 0.205      | -            | -                | -                | -         |    -5.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     3553 | 2024-11-14 | Nexus Gaming                              | L   | 0.204      | -            | -                | -                | -         |    -1.62 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     3564 | 2024-11-14 | GnG x Amazigh                             | W   | 0.204      | -            | -                | -                | 1 (0.245) |     0.37 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     3927 | 2024-11-06 | Heimo Esports                             | W   | 0.160      | -            | -                | -                | -         |     1.36 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           18 |     3942 | 2024-11-06 | QUAZAR                                    | W   | 0.160      | -            | -                | -                | -         |     1.15 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           17 |     4097 | 2024-11-03 | Preasy Esport                             | L   | 0.144      | -            | -                | -                | -         |    -3.05 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     4375 | 2024-10-30 | Fire Flux Esports                         | L   | 0.121      | -            | -                | -                | -         |    -2.07 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           15 |     4441 | 2024-10-29 | CYBERSHOKE Esports                        | W   | 0.116      | -            | -                | -                | -         |     1.56 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           14 |     4543 | 2024-10-27 | MOUZ NXT                                  | W   | 0.104      | -            | -                | -                | -         |     0.34 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           13 |     4727 | 2024-10-24 | Chimera Esports                           | L   | 0.085      | -            | -                | -                | -         |    -1.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           12 |     4813 | 2024-10-22 | Natus Vincere Junior                      | W   | 0.075      | -            | -                | -                | -         |     1.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           11 |     4838 | 2024-10-21 | Endpoint                                  | L   | 0.071      | -            | -                | -                | -         |    -1.61 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           10 |     4925 | 2024-10-20 | Copenhagen Wolves (American organization) | W   | 0.063      | -            | -                | -                | -         |     0.87 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            9 |     5016 | 2024-10-18 | GenOne                                    | L   | 0.052      | -            | -                | -                | -         |    -1.09 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            8 |     5058 | 2024-10-17 | Illuminar Gaming                          | W   | 0.047      | -            | -                | -                | -         |     0.49 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            7 |     5218 | 2024-10-15 | Heimo Esports                             | W   | 0.035      | -            | -                | -                | -         |     0.30 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            6 |     5230 | 2024-10-14 | ALASKA                                    | W   | 0.032      | -            | -                | -                | -         |     0.85 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|            5 |     5256 | 2024-10-14 | Natus Vincere Junior                      | L   | 0.030      | -            | -                | -                | -         |    -0.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            4 |     5295 | 2024-10-13 | ADEPTS                                    | L   | 0.025      | -            | -                | -                | -         |    -0.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            3 |     5442 | 2024-10-10 | ENCE Academy                              | W   | 0.008      | -            | -                | -                | -         |     0.10 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            2 |     5488 | 2024-10-09 | Soul's Heart Esport (former roster)       | W   | 0.004      | -            | -                | -                | -         |     0.01 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|            1 |     5528 | 2024-10-09 | Heimo Esports                             | W   | 0.002      | -            | -                | -                | -         |     0.02 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,830.39)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.551 | $6,000.00      | $3,303.33       |
| 2024-12-25 |      0.517 | $6,000.00      | $3,102.92       |
| 2024-12-23 |      0.504 | $5,000.00      | $2,520.14       |
| 2024-12-22 |      0.498 | $1,196.99      | $596.50         |
| 2024-10-24 |      0.102 | $3,000.00      | $307.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
