### Roster Details<br />
Team Name: Leo Team<br />
Roster: kL1o, kr1vda, Malkiss, marat2k, OneUn1que<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.6<br />
<br />
Final Rank Value (835.6) = Starting Rank Value (809.0) + Head To Head Adjustments (26.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 809.0
- 400 + ( ( 0.185 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 809.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |      411 | 2025-02-17 | OG                                        | L   | 0.733      | -            | -                | -                | -         |    -8.79 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           57 |      415 | 2025-02-17 | Hesta                                     | W   | 0.733      | 0.143        | -                | 0.665 (0.084)    | 0 (0.000) |    10.77 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           56 |      426 | 2025-02-17 | Mercenaires                               | W   | 0.732      | -            | -                | -                | 0 (0.000) |     3.93 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           55 |      434 | 2025-02-17 | Mission Possible                          | W   | 0.732      | -            | -                | -                | 0 (0.000) |     4.06 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           54 |      454 | 2025-02-16 | Sabrina                                   | W   | 0.728      | -            | -                | -                | 0 (0.000) |     1.94 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           53 |     1065 | 2025-02-04 | Insilio                                   | L   | 0.659      | -            | -                | -                | -         |   -14.80 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           52 |     2101 | 2024-12-11 | FLuffy Gangsters                          | L   | 0.355      | -            | -                | -                | -         |    -6.41 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           51 |     2140 | 2024-12-10 | CYBERSHOKE Esports                        | L   | 0.349      | -            | -                | -                | -         |    -5.27 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           50 |     2226 | 2024-12-08 | 500                                       | L   | 0.338      | -            | -                | -                | -         |    -2.58 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           49 |     2362 | 2024-12-06 | FAVBET Team                               | L   | 0.326      | -            | -                | -                | -         |    -4.64 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           48 |     2425 | 2024-12-04 | Copenhagen Wolves (American organization) | W   | 0.315      | 0.372        | 0.017 (0.002)    | 1.000 (0.141)    | 0 (0.000) |     5.45 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           47 |     2515 | 2024-12-02 | CYBERSHOKE Esports                        | W   | 0.304      | 0.372        | 0.014 (0.002)    | 1.000 (0.136)    | 0 (0.000) |     5.29 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           46 |     2634 | 2024-11-30 | Nuclear TigeRES                           | W   | 0.294      | 0.372        | -                | 0.431 (0.057)    | 0 (0.000) |     4.71 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           45 |     2758 | 2024-11-28 | ALTERNATE aTTaX                           | W   | 0.282      | 0.372        | 0.018 (0.002)    | -                | 0 (0.000) |     5.24 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           44 |     2859 | 2024-11-26 | Tricked Esport                            | L   | 0.269      | -            | -                | -                | -         |    -4.22 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           43 |     2876 | 2024-11-25 | GenOne                                    | L   | 0.264      | -            | -                | -                | -         |    -4.64 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           42 |     2880 | 2024-11-25 | BC.Game Esports                           | L   | 0.264      | -            | -                | -                | -         |    -4.51 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           41 |     3065 | 2024-11-22 | Viperio                                   | W   | 0.249      | -            | -                | -                | 0 (0.000) |     2.89 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           40 |     3070 | 2024-11-22 | Partizan Esports                          | W   | 0.249      | 0.372        | 0.082 (0.009)    | 0.618 (0.069)    | 0 (0.000) |     6.12 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           39 |     3096 | 2024-11-22 | Astralis Talent                           | W   | 0.248      | -            | -                | -                | -         |     3.35 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           38 |     3134 | 2024-11-21 | KONO.ECF                                  | W   | 0.244      | 0.372        | 0.047 (0.005)    | 0.597 (0.065)    | -         |     4.69 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           37 |     3139 | 2024-11-21 | GenOne                                    | W   | 0.243      | 0.372        | -                | 0.644 (0.070)    | -         |     3.69 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           36 |     3157 | 2024-11-21 | Illuminar Gaming                          | W   | 0.243      | -            | -                | -                | -         |     3.31 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           35 |     3175 | 2024-11-21 | Preasy Esport                             | L   | 0.241      | -            | -                | -                | -         |    -4.46 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           34 |     3277 | 2024-11-19 | FAVBET Team                               | L   | 0.232      | -            | -                | -                | -         |    -3.11 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           33 |     3341 | 2024-11-18 | Chimera Esports                           | W   | 0.225      | 0.333        | 0.023 (0.002)    | -                | -         |     3.63 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           32 |     3383 | 2024-11-17 | Dark Cloud Esports                        | W   | 0.220      | 0.333        | 0.035 (0.003)    | 0.667 (0.059)    | -         |     3.59 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           31 |     3428 | 2024-11-16 | THE GENTLEMEN ESPORTS                     | W   | 0.216      | -            | -                | -                | -         |     1.22 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           30 |     3496 | 2024-11-15 | K27                                       | L   | 0.210      | -            | -                | -                | -         |    -2.01 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           29 |     3517 | 2024-11-15 | GenOne                                    | W   | 0.209      | -            | -                | -                | -         |     3.21 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           28 |     3578 | 2024-11-14 | ENCE Academy                              | W   | 0.203      | -            | -                | -                | -         |     3.29 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           27 |     3584 | 2024-11-14 | Dark Cloud Esports                        | L   | 0.203      | -            | -                | -                | -         |    -3.04 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           26 |     3602 | 2024-11-13 | Team Spirit Academy                       | W   | 0.199      | 0.372        | 0.053 (0.005)    | 0.682 (0.061)    | -         |     4.23 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           25 |     3653 | 2024-11-12 | Viperio                                   | W   | 0.192      | -            | -                | -                | -         |     2.45 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           24 |     3674 | 2024-11-11 | TEAM NEXT LEVEL                           | W   | 0.188      | 0.372        | 0.041 (0.003)    | -                | -         |     3.17 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           23 |     3759 | 2024-11-10 | Copenhagen Wolves (American organization) | W   | 0.181      | 0.333        | -                | 1.000 (0.072)    | -         |     3.37 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           22 |     3791 | 2024-11-09 | Betera Esports                            | L   | 0.177      | -            | -                | -                | -         |    -3.45 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           21 |     3843 | 2024-11-08 | Lazer Cats                                | W   | 0.171      | -            | -                | -                | -         |     2.02 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           20 |     3944 | 2024-11-06 | UNiTY esports                             | W   | 0.160      | 0.372        | 0.019 (0.001)    | -                | -         |     2.35 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           19 |     3961 | 2024-11-06 | GenOne                                    | W   | 0.158      | -            | -                | -                | -         |     2.46 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           18 |     4217 | 2024-11-02 | Devils.one                                | W   | 0.136      | -            | -                | -                | -         |     0.58 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           17 |     4451 | 2024-10-29 | BC.Game Esports                           | L   | 0.115      | -            | -                | -                | -         |    -1.76 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           16 |     4614 | 2024-10-26 | Adventurers                               | L   | 0.098      | -            | -                | -                | -         |    -1.87 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           15 |     4700 | 2024-10-25 | GenOne                                    | W   | 0.091      | -            | -                | -                | -         |     1.42 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           14 |     4724 | 2024-10-24 | WOPA Esport                               | W   | 0.086      | -            | -                | -                | -         |     1.50 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           13 |     4814 | 2024-10-22 | Anonymo Esports                           | W   | 0.075      | -            | -                | -                | -         |     0.38 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           12 |     4851 | 2024-10-21 | Adventurers                               | L   | 0.070      | -            | -                | -                | -         |    -1.35 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           11 |     4971 | 2024-10-19 | Illuminar Gaming                          | L   | 0.058      | -            | -                | -                | -         |    -0.93 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|           10 |     5012 | 2024-10-18 | Dynamo Eclot                              | W   | 0.053      | -            | -                | -                | -         |     0.56 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            9 |     5042 | 2024-10-17 | 500                                       | L   | 0.048      | -            | -                | -                | -         |    -0.32 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            8 |     5067 | 2024-10-17 | Copenhagen Wolves (American organization) | L   | 0.047      | -            | -                | -                | -         |    -0.59 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            7 |     5104 | 2024-10-16 | Ex-ENTERPRISE esports                     | W   | 0.043      | -            | -                | -                | -         |     0.13 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            6 |     5215 | 2024-10-15 | Viperio                                   | W   | 0.036      | -            | -                | -                | -         |     0.47 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            5 |     5251 | 2024-10-14 | TEAM NEXT LEVEL                           | L   | 0.031      | -            | -                | -                | -         |    -0.43 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            4 |     5259 | 2024-10-13 | Astralis Talent                           | W   | 0.027      | -            | -                | -                | -         |     0.37 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            3 |     5379 | 2024-10-12 | Dynamo Eclot                              | L   | 0.019      | -            | -                | -                | -         |    -0.14 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            2 |     5412 | 2024-10-11 | Natus Vincere Junior                      | W   | 0.014      | -            | -                | -                | -         |     0.32 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |
|            1 |     5420 | 2024-10-10 | MOUZ NXT                                  | L   | 0.010      | -            | -                | -                | -         |    -0.26 | kL1o, kr1vda, Malkiss, marat2k, OneUn1que |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,225.61)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.465 | $1,197.67      | $557.08         |
| 2024-12-08 |      0.405 | $4,300.00      | $1,742.69       |
| 2024-11-17 |      0.264 | $6,000.00      | $1,584.17       |
| 2024-11-10 |      0.219 | $1,000.00      | $218.61         |
| 2024-10-27 |      0.123 | $1,000.00      | $123.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
