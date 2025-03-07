### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: aNdu, b1elany, Jackinho, szejn, Tapewaare<br />
Global Rank: [84](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  867.8<br />
<br />
Final Rank Value (867.8) = Starting Rank Value (878.6) + Head To Head Adjustments (-10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 878.6
- 400 + ( ( 0.217 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 878.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           79 |      109 | 2025-02-25 | SINNERS Esports            | W   | 0.777      | 0.500        | 0.016 (0.008)    | 0.494 (0.230)    | 0 (0.000) |    12.98 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           78 |      179 | 2025-02-23 | ARCRED                     | L   | 0.765      | -            | -                | -                | -         |   -13.61 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           77 |      182 | 2025-02-23 | Wolves eSports             | W   | 0.765      | -            | -                | -                | 0 (0.000) |     1.85 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           76 |      224 | 2025-02-22 | Dark Cloud Esports         | W   | 0.760      | 0.143        | 0.035 (0.005)    | -                | 0 (0.000) |    10.91 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           75 |      285 | 2025-02-21 | Tricked Esport             | L   | 0.754      | -            | -                | -                | -         |   -12.70 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           74 |      314 | 2025-02-20 | HyperSpirit                | W   | 0.749      | -            | -                | -                | 0 (0.000) |     1.60 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           73 |      390 | 2025-02-18 | 9Pandas                    | W   | 0.738      | 0.500        | 0.084 (0.037)    | 0.481 (0.213)    | 0 (0.000) |    15.73 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           72 |      398 | 2025-02-18 | BC.Game Esports            | L   | 0.737      | -            | -                | -                | -         |    -4.80 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           71 |      436 | 2025-02-17 | GTZ.ESPORTS                | W   | 0.732      | 0.435        | 0.068 (0.026)    | 0.498 (0.190)    | 0 (0.000) |    18.61 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           70 |      453 | 2025-02-16 | Bad News Eagles            | L   | 0.728      | -            | -                | -                | -         |   -18.61 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           69 |      569 | 2025-02-14 | THE GENTLEMEN ESPORTS      | L   | 0.716      | -            | -                | -                | -         |   -19.23 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           68 |      594 | 2025-02-14 | Chimera Esports            | W   | 0.714      | 0.435        | 0.023 (0.009)    | 0.430 (0.160)    | 0 (0.000) |    10.46 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           67 |      638 | 2025-02-12 | Sashi Esport               | L   | 0.703      | -            | -                | -                | -         |    -8.90 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           66 |      659 | 2025-02-11 | 9INE                       | L   | 0.698      | -            | -                | -                | -         |    -9.60 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           65 |      743 | 2025-02-09 | Iberian Soul               | W   | 0.687      | -            | -                | -                | 0 (0.000) |     9.19 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           64 |      860 | 2025-02-07 | NEVERMORE (Ukrainian team) | L   | 0.678      | -            | -                | -                | -         |   -13.25 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           63 |      894 | 2025-02-07 | ALASKA                     | W   | 0.675      | -            | -                | -                | 0 (0.000) |    15.70 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           62 |      934 | 2025-02-06 | Betclic Apogee Esports     | W   | 0.671      | -            | -                | -                | 0 (0.000) |    12.06 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           61 |     1202 | 2025-01-29 | Wild Lotus                 | L   | 0.627      | -            | -                | -                | -         |   -15.44 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           60 |     1235 | 2025-01-28 | JiJieHao                   | W   | 0.622      | -            | -                | -                | -         |     2.64 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           59 |     1269 | 2025-01-27 | Monte                      | L   | 0.616      | -            | -                | -                | -         |    -7.57 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           58 |     1285 | 2025-01-25 | KONO.ECF                   | W   | 0.605      | -            | -                | -                | -         |     3.85 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           57 |     1330 | 2025-01-24 | ECSTATIC                   | W   | 0.597      | -            | -                | -                | -         |     9.29 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           56 |     1357 | 2025-01-23 | PARIVISION                 | L   | 0.594      | -            | -                | -                | -         |   -13.92 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           55 |     1514 | 2024-12-30 | SemperFi Esports           | L   | 0.460      | -            | -                | -                | -         |   -12.63 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           54 |     1527 | 2024-12-29 | Dark Cloud Esports         | L   | 0.454      | -            | -                | -                | -         |    -7.98 | aNdu, kory, shield, szejn, Tapewaare      |
|           53 |     1542 | 2024-12-28 | NEVERMORE (Ukrainian team) | W   | 0.450      | 0.333        | -                | 0.803 (0.144)    | -         |     5.09 | aNdu, kory, shield, szejn, Tapewaare      |
|           52 |     1556 | 2024-12-28 | NEVERMORE (Ukrainian team) | W   | 0.449      | 0.303        | -                | 0.803 (0.131)    | -         |     5.27 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           51 |     1565 | 2024-12-28 | Preasy Esport              | W   | 0.448      | -            | -                | -                | -         |     4.65 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           50 |     1690 | 2024-12-21 | Lazer Cats                 | W   | 0.410      | -            | -                | -                | -         |     3.77 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           49 |     1696 | 2024-12-21 | 0to100                     | L   | 0.409      | -            | -                | -                | -         |    -8.52 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           48 |     1718 | 2024-12-21 | Nexus Gaming               | L   | 0.409      | -            | -                | -                | -         |    -3.31 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           47 |     1724 | 2024-12-21 | Lazer Cats                 | W   | 0.408      | -            | -                | -                | -         |     3.60 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           46 |     1756 | 2024-12-20 | Monte                      | L   | 0.403      | -            | -                | -                | -         |    -5.02 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           45 |     1785 | 2024-12-19 | 500                        | W   | 0.397      | 0.371        | 0.118 (0.021)    | 1.000 (0.177)    | -         |     8.99 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           44 |     1819 | 2024-12-17 | Dragon Esports Club        | W   | 0.386      | -            | -                | -                | -         |     3.31 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           43 |     1822 | 2024-12-16 | TEAM NEXT LEVEL            | W   | 0.383      | 0.371        | 0.041 (0.007)    | -                | -         |     5.58 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           42 |     1917 | 2024-12-14 | FAVBET Team                | W   | 0.372      | -            | -                | -                | -         |     6.14 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           41 |     2007 | 2024-12-13 | CYBERSHOKE Esports         | W   | 0.366      | -            | -                | -                | -         |     5.80 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           40 |     2031 | 2024-12-13 | ENCE Academy               | L   | 0.365      | -            | -                | -                | -         |    -6.55 | aNdu, Flierax, MAGILA, szejn, Tapewaare   |
|           39 |     2174 | 2024-12-09 | Heimo Esports              | L   | 0.343      | -            | -                | -                | -         |    -7.87 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           38 |     2307 | 2024-12-07 | 500                        | L   | 0.332      | -            | -                | -                | -         |    -2.91 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           37 |     2425 | 2024-12-04 | Leo Team                   | L   | 0.315      | -            | -                | -                | -         |    -5.45 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           36 |     2516 | 2024-12-02 | Team Spirit Academy        | W   | 0.304      | 0.372        | 0.053 (0.007)    | -                | -         |     5.80 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           35 |     2676 | 2024-11-30 | FAVBET Team                | W   | 0.292      | -            | -                | -                | -         |     4.89 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           34 |     2769 | 2024-11-28 | 1win                       | W   | 0.281      | -            | -                | -                | -         |     2.90 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           33 |     2893 | 2024-11-24 | KONO.ECF                   | W   | 0.260      | 0.372        | 0.047 (0.005)    | -                | -         |     4.44 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           32 |     2899 | 2024-11-24 | 500                        | W   | 0.260      | 0.372        | 0.118 (0.014)    | 1.000 (0.116)    | -         |     6.02 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           31 |     2903 | 2024-11-24 | Ex-RUBY                    | L   | 0.260      | -            | -                | -                | -         |    -7.08 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           30 |     2928 | 2024-11-24 | Natus Vincere Junior       | L   | 0.258      | -            | -                | -                | -         |    -2.73 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           29 |     2950 | 2024-11-23 | Hawks (Argentinian team)   | W   | 0.255      | -            | -                | -                | -         |     0.92 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           28 |     3004 | 2024-11-23 | CYBERSHOKE Esports         | W   | 0.254      | 0.372        | -                | 1.000 (0.113)    | -         |     4.08 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           27 |     3011 | 2024-11-23 | FAVBET Team                | L   | 0.253      | -            | -                | -                | -         |    -3.78 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           26 |     3148 | 2024-11-21 | Illuminar Gaming           | L   | 0.243      | -            | -                | -                | -         |    -4.89 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           25 |     3154 | 2024-11-21 | Fire Flux Esports          | W   | 0.243      | 0.372        | -                | 1.000 (0.108)    | -         |     4.35 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           24 |     3165 | 2024-11-21 | Fire Flux Esports          | L   | 0.242      | -            | -                | -                | -         |    -3.34 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           23 |     3292 | 2024-11-19 | Lazer Cats                 | W   | 0.231      | -            | -                | -                | -         |     2.23 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           22 |     3710 | 2024-11-11 | Case Esports               | W   | 0.186      | -            | -                | -                | -         |     1.39 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           21 |     3759 | 2024-11-10 | Leo Team                   | L   | 0.181      | -            | -                | -                | -         |    -3.37 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           20 |     3913 | 2024-11-07 | ENCE Academy               | W   | 0.164      | -            | -                | -                | -         |     2.28 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           19 |     4002 | 2024-11-05 | Viperio                    | W   | 0.154      | -            | -                | -                | -         |     1.61 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           18 |     4149 | 2024-11-03 | Dark Cloud Esports         | L   | 0.141      | -            | -                | -                | -         |    -2.50 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           17 |     4323 | 2024-10-31 | Fire Flux Esports          | L   | 0.125      | -            | -                | -                | -         |    -1.88 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           16 |     4401 | 2024-10-30 | ENCE Academy               | W   | 0.119      | -            | -                | -                | -         |     1.66 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           15 |     4694 | 2024-10-25 | P0RTUGAL                   | L   | 0.092      | -            | -                | -                | -         |    -1.78 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           14 |     4751 | 2024-10-23 | GenOne                     | L   | 0.082      | -            | -                | -                | -         |    -1.56 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           13 |     4770 | 2024-10-23 | HyperSpirit                | W   | 0.081      | -            | -                | -                | -         |     0.60 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           12 |     4817 | 2024-10-22 | Chimera Esports            | L   | 0.074      | -            | -                | -                | -         |    -1.34 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           11 |     4858 | 2024-10-21 | Viperio                    | W   | 0.069      | -            | -                | -                | -         |     0.70 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           10 |     4925 | 2024-10-20 | KONO.ECF                   | L   | 0.063      | -            | -                | -                | -         |    -0.87 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            9 |     5005 | 2024-10-18 | Chimera Esports            | W   | 0.053      | -            | -                | -                | -         |     0.72 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            8 |     5067 | 2024-10-17 | Leo Team                   | W   | 0.047      | -            | -                | -                | -         |     0.59 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            7 |     5109 | 2024-10-16 | GODSENT                    | W   | 0.043      | -            | -                | -                | -         |     0.30 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            6 |     5116 | 2024-10-16 | Permitta Esports           | W   | 0.043      | -            | -                | -                | -         |     0.53 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            5 |     5195 | 2024-10-15 | THE SPELLS                 | W   | 0.037      | -            | -                | -                | -         |     0.14 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            4 |     5206 | 2024-10-15 | ROUNDS                     | W   | 0.037      | -            | -                | -                | -         |     0.14 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            3 |     5214 | 2024-10-15 | Anonymo Esports            | W   | 0.036      | -            | -                | -                | -         |     0.13 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            2 |     5249 | 2024-10-14 | Viperio                    | L   | 0.031      | -            | -                | -                | -         |    -0.66 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            1 |     5277 | 2024-10-13 | 9INE                       | L   | 0.026      | -            | -                | -                | -         |    -0.62 | aNdu, eraa, MAGILA, szejn, Tapewaare      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,510.59)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.553 | $500.00        | $276.26         |
| 2024-12-30 |      0.551 | $1,000.00      | $550.56         |
| 2024-12-28 |      0.539 | $2,500.00      | $1,346.35       |
| 2024-12-08 |      0.405 | $3,300.00      | $1,337.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
