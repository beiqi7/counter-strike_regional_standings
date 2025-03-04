### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: aNdu, b1elany, Jackinho, szejn, Tapewaare<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  907.6<br />
<br />
Final Rank Value (907.6) = Starting Rank Value (913.9) + Head To Head Adjustments (-6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.245[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.9
- 400 + ( ( 0.247 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 913.9


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
|           79 |      101 | 2025-02-25 | SINNERS Esports            | W   | 1.000      | 0.500        | 0.031 (0.015)    | 0.597 (0.298)    | 0 (0.000) |    16.90 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           78 |      171 | 2025-02-23 | ARCRED                     | L   | 1.000      | -            | -                | -                | -         |   -18.75 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           77 |      174 | 2025-02-23 | Wolves eSports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.98 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           76 |      216 | 2025-02-22 | Dark Cloud Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.65 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           75 |      277 | 2025-02-21 | Tricked Esport             | L   | 1.000      | -            | -                | -                | -         |   -15.97 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           74 |      306 | 2025-02-20 | HyperSpirit                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.73 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           73 |      366 | 2025-02-18 | 9Pandas                    | W   | 1.000      | 0.500        | 0.104 (0.052)    | 0.628 (0.314)    | 0 (0.000) |    22.55 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           72 |      374 | 2025-02-18 | BC.Game Esports            | L   | 1.000      | -            | -                | -                | -         |    -4.64 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           71 |      411 | 2025-02-17 | GTZ.ESPORTS                | W   | 1.000      | 0.435        | 0.094 (0.041)    | 0.619 (0.269)    | 0 (0.000) |    24.62 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           70 |      428 | 2025-02-16 | Bad News Eagles            | L   | 1.000      | -            | -                | -                | -         |   -25.61 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           69 |      543 | 2025-02-14 | THE GENTLEMEN ESPORTS      | L   | 1.000      | -            | -                | -                | -         |   -23.27 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           68 |      572 | 2025-02-14 | Chimera Esports            | W   | 1.000      | 0.435        | 0.030 (0.013)    | 0.597 (0.259)    | 0 (0.000) |    15.96 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           67 |      618 | 2025-02-12 | Sashi Esport               | L   | 1.000      | -            | -                | -                | -         |   -12.34 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           66 |      638 | 2025-02-11 | 9INE                       | L   | 1.000      | -            | -                | -                | -         |   -13.11 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           65 |      719 | 2025-02-09 | Iberian Soul               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.99 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           64 |      836 | 2025-02-07 | NEVERMORE (Ukrainian team) | L   | 1.000      | -            | -                | -                | -         |   -19.72 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           63 |      870 | 2025-02-07 | ALASKA                     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.17 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           62 |      910 | 2025-02-06 | Betclic Apogee Esports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.32 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           61 |     1174 | 2025-01-29 | Wild Lotus                 | L   | 0.977      | -            | -                | -                | -         |   -17.69 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           60 |     1200 | 2025-01-28 | JiJieHao                   | W   | 0.971      | -            | -                | -                | -         |     6.24 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           59 |     1218 | 2025-01-27 | Monte                      | L   | 0.964      | -            | -                | -                | -         |   -11.31 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           58 |     1232 | 2025-01-25 | KONO.ECF                   | W   | 0.951      | -            | -                | -                | -         |     6.49 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           57 |     1255 | 2025-01-24 | ECSTATIC                   | W   | 0.942      | -            | -                | -                | -         |    15.50 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           56 |     1266 | 2025-01-23 | PARIVISION                 | L   | 0.938      | -            | -                | -                | -         |   -22.15 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           55 |     1393 | 2024-12-30 | SemperFi Esports           | L   | 0.777      | -            | -                | -                | -         |   -21.64 | aNdu, b1elany, Jackinho, szejn, Tapewaare |
|           54 |     1409 | 2024-12-29 | Dark Cloud Esports         | L   | 0.770      | -            | -                | -                | -         |   -13.60 | aNdu, kory, shield, szejn, Tapewaare      |
|           53 |     1424 | 2024-12-28 | NEVERMORE (Ukrainian team) | W   | 0.765      | 0.333        | -                | 0.928 (0.237)    | -         |     8.02 | aNdu, kory, shield, szejn, Tapewaare      |
|           52 |     1436 | 2024-12-28 | NEVERMORE (Ukrainian team) | W   | 0.764      | 0.303        | -                | 0.928 (0.215)    | -         |     8.51 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           51 |     1445 | 2024-12-28 | Preasy Esport              | W   | 0.763      | -            | -                | -                | -         |     7.26 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           50 |     1568 | 2024-12-21 | Lazer Cats                 | W   | 0.717      | -            | -                | -                | -         |     6.48 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           49 |     1574 | 2024-12-21 | 0to100                     | L   | 0.717      | -            | -                | -                | -         |   -15.14 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           48 |     1596 | 2024-12-21 | Nexus Gaming               | L   | 0.716      | -            | -                | -                | -         |    -6.60 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           47 |     1602 | 2024-12-21 | Lazer Cats                 | W   | 0.715      | -            | -                | -                | -         |     6.00 | aNdu, Jackinho, kory, szejn, Tapewaare    |
|           46 |     1634 | 2024-12-20 | Monte                      | L   | 0.709      | -            | -                | -                | -         |    -8.61 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           45 |     1663 | 2024-12-19 | 500                        | W   | 0.702      | 0.371        | 0.114 (0.030)    | 1.000 (0.260)    | -         |    16.00 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           44 |     1694 | 2024-12-17 | Dragon Esports Club        | W   | 0.688      | -            | -                | -                | -         |     5.11 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           43 |     1697 | 2024-12-16 | TEAM NEXT LEVEL            | W   | 0.685      | 0.371        | 0.047 (0.012)    | -                | -         |     9.89 | AMSALEM, aNdu, JBOEN, szejn, Tapewaare    |
|           42 |     1789 | 2024-12-14 | FAVBET Team                | W   | 0.671      | -            | -                | -                | -         |    11.70 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           41 |     1879 | 2024-12-13 | CYBERSHOKE Esports         | W   | 0.664      | -            | -                | -                | -         |    10.39 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           40 |     1904 | 2024-12-13 | ENCE Academy               | L   | 0.663      | -            | -                | -                | -         |   -12.56 | aNdu, Flierax, MAGILA, szejn, Tapewaare   |
|           39 |     2049 | 2024-12-09 | Heimo Esports              | L   | 0.637      | -            | -                | -                | -         |   -14.92 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           38 |     2172 | 2024-12-07 | 500                        | L   | 0.624      | -            | -                | -                | -         |    -5.25 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           37 |     2288 | 2024-12-04 | Leo Team                   | L   | 0.603      | -            | -                | -                | -         |    -9.27 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           36 |     2396 | 2024-12-02 | Team Spirit Academy        | W   | 0.591      | 0.372        | 0.080 (0.017)    | -                | -         |    12.01 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           35 |     2555 | 2024-11-30 | FAVBET Team                | W   | 0.576      | 0.372        | 0.037 (0.008)    | 0.952 (0.204)    | -         |    10.31 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           34 |     2652 | 2024-11-28 | 1win                       | W   | 0.563      | -            | -                | -                | -         |     6.37 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           33 |     2772 | 2024-11-24 | KONO.ECF                   | W   | 0.538      | 0.372        | 0.054 (0.011)    | -                | -         |     8.58 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           32 |     2778 | 2024-11-24 | 500                        | W   | 0.537      | 0.372        | 0.114 (0.023)    | 1.000 (0.200)    | -         |    12.77 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           31 |     2782 | 2024-11-24 | Ex-RUBY                    | L   | 0.537      | -            | -                | -                | -         |   -14.60 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           30 |     2806 | 2024-11-24 | Natus Vincere Junior       | L   | 0.535      | -            | -                | -                | -         |    -4.88 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           29 |     2828 | 2024-11-23 | Hawks (Argentinian team)   | W   | 0.531      | -            | -                | -                | -         |     1.76 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           28 |     2882 | 2024-11-23 | CYBERSHOKE Esports         | W   | 0.530      | 0.372        | -                | 1.000 (0.197)    | -         |     8.37 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           27 |     2889 | 2024-11-23 | FAVBET Team                | L   | 0.529      | -            | -                | -                | -         |    -7.20 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           26 |     3027 | 2024-11-21 | Illuminar Gaming           | L   | 0.517      | -            | -                | -                | -         |    -9.54 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           25 |     3033 | 2024-11-21 | Fire Flux Esports          | W   | 0.517      | -            | -                | -                | -         |    10.59 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           24 |     3044 | 2024-11-21 | Fire Flux Esports          | L   | 0.516      | -            | -                | -                | -         |    -5.74 | aNdu, MAGILA, mwlky, szejn, Tapewaare     |
|           23 |     3163 | 2024-11-19 | Lazer Cats                 | W   | 0.503      | -            | -                | -                | -         |     5.43 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           22 |     3575 | 2024-11-11 | Case Esports               | W   | 0.449      | -            | -                | -                | -         |     3.71 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           21 |     3624 | 2024-11-10 | Leo Team                   | L   | 0.443      | -            | -                | -                | -         |    -7.67 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           20 |     3777 | 2024-11-07 | ENCE Academy               | W   | 0.422      | -            | -                | -                | -         |     5.53 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           19 |     3862 | 2024-11-05 | Viperio                    | W   | 0.411      | -            | -                | -                | -         |     4.20 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           18 |     4006 | 2024-11-03 | Dark Cloud Esports         | L   | 0.395      | -            | -                | -                | -         |    -7.00 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           17 |     4181 | 2024-10-31 | Fire Flux Esports          | L   | 0.376      | -            | -                | -                | -         |    -5.04 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           16 |     4251 | 2024-10-30 | ENCE Academy               | W   | 0.368      | -            | -                | -                | -         |     4.81 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           15 |     4526 | 2024-10-25 | P0RTUGAL                   | L   | 0.335      | -            | -                | -                | -         |    -6.78 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           14 |     4576 | 2024-10-23 | GenOne                     | L   | 0.324      | -            | -                | -                | -         |    -5.86 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           13 |     4593 | 2024-10-23 | HyperSpirit                | W   | 0.323      | -            | -                | -                | -         |     2.15 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           12 |     4632 | 2024-10-22 | Chimera Esports            | L   | 0.314      | -            | -                | -                | -         |    -5.61 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           11 |     4669 | 2024-10-21 | Viperio                    | W   | 0.308      | -            | -                | -                | -         |     2.91 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|           10 |     4736 | 2024-10-20 | KONO.ECF                   | L   | 0.301      | -            | -                | -                | -         |    -4.31 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            9 |     4813 | 2024-10-18 | Chimera Esports            | W   | 0.289      | -            | -                | -                | -         |     3.97 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            8 |     4870 | 2024-10-17 | Leo Team                   | W   | 0.281      | -            | -                | -                | -         |     3.90 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            7 |     4899 | 2024-10-16 | GODSENT                    | W   | 0.277      | -            | -                | -                | -         |     1.88 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            6 |     4905 | 2024-10-16 | Permitta Esports           | W   | 0.277      | -            | -                | -                | -         |     3.33 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            5 |     4977 | 2024-10-15 | THE SPELLS                 | W   | 0.270      | -            | -                | -                | -         |     1.02 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            4 |     4988 | 2024-10-15 | ROUNDS                     | W   | 0.269      | -            | -                | -                | -         |     0.94 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            3 |     4996 | 2024-10-15 | Anonymo Esports            | W   | 0.268      | -            | -                | -                | -         |     1.02 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            2 |     5028 | 2024-10-14 | Viperio                    | L   | 0.263      | -            | -                | -                | -         |    -5.56 | aNdu, eraa, MAGILA, szejn, Tapewaare      |
|            1 |     5054 | 2024-10-13 | 9INE                       | L   | 0.256      | -            | -                | -                | -         |    -5.40 | aNdu, eraa, MAGILA, szejn, Tapewaare      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,155.15)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.778 | $500.00        | $388.90         |
| 2024-12-30 |      0.776 | $1,000.00      | $775.84         |
| 2024-12-28 |      0.764 | $2,500.00      | $1,909.56       |
| 2024-12-08 |      0.631 | $3,300.00      | $2,080.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
