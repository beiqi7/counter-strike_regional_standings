### Roster Details<br />
Team Name: FlyQuest<br />
Roster: dexter, INS, Liazz, regali, Vexite<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1201.0<br />
<br />
Final Rank Value (1201.0) = Starting Rank Value (1208.2) + Head To Head Adjustments (-7.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.536[<sup>2</sup>](#table1)

The average of these factors is 0.389<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1208.2
- 400 + ( ( 0.389 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1208.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |        1 | 2025-03-03 | PaiN Gaming                      | W   | 1.000      | 0.889        | 0.333 (0.296)    | 0.406 (0.361)    | 1 (1.000) |    27.56 | dexter, INS, Liazz, regali, Vexite   |
|           31 |        3 | 2025-03-02 | Lynn Vision Gaming               | W   | 1.000      | 0.889        | 0.013 (0.011)    | 0.333 (0.296)    | 1 (1.000) |     6.96 | dexter, INS, Liazz, regali, Vexite   |
|           30 |        6 | 2025-03-01 | M80                              | L   | 1.000      | -            | -                | -                | -         |   -21.29 | dexter, INS, Liazz, regali, Vexite   |
|           29 |      452 | 2025-02-16 | SAW                              | L   | 1.000      | -            | -                | -                | -         |   -10.82 | dexter, INS, Liazz, regali, Vexite   |
|           28 |      524 | 2025-02-15 | BIG                              | L   | 1.000      | -            | -                | -                | -         |    -9.63 | dexter, INS, Liazz, regali, Vexite   |
|           27 |      573 | 2025-02-14 | Team Falcons                     | L   | 1.000      | -            | -                | -                | -         |    -0.83 | dexter, INS, Liazz, regali, Vexite   |
|           26 |     1170 | 2025-01-30 | Astralis                         | L   | 0.983      | -            | -                | -                | -         |    -1.08 | dexter, INS, Liazz, regali, Vexite   |
|           25 |     1184 | 2025-01-29 | 3DMAX                            | L   | 0.975      | -            | -                | -                | -         |    -3.62 | dexter, INS, Liazz, regali, Vexite   |
|           24 |     1315 | 2025-01-18 | Team Spirit                      | L   | 0.904      | -            | -                | -                | -         |    -0.44 | dexter, INS, Liazz, regali, Vexite   |
|           23 |     1345 | 2025-01-14 | MIBR                             | W   | 0.875      | 0.363        | 0.118 (0.037)    | 0.285 (0.091)    | -         |    10.30 | dexter, INS, Liazz, regali, Vexite   |
|           22 |     3491 | 2024-11-13 | Lynn Vision Gaming               | W   | 0.462      | 0.143        | 0.013 (0.001)    | 0.333 (0.022)    | 1 (0.462) |     2.54 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3498 | 2024-11-12 | Adventurers                      | W   | 0.460      | 0.143        | 0.019 (0.001)    | -                | 1 (0.460) |     1.83 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3532 | 2024-11-11 | Ex-GR Gaming                     | W   | 0.454      | 0.143        | 0.013 (0.001)    | -                | 1 (0.454) |     1.02 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3569 | 2024-11-11 | TALON                            | L   | 0.449      | -            | -                | -                | -         |   -13.75 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     4741 | 2024-10-19 | Mindfreak (Australian team)      | W   | 0.300      | -            | -                | -                | -         |     0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     4825 | 2024-10-18 | Mindfreak (Australian team)      | W   | 0.287      | -            | -                | -                | -         |     0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     5281 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.228      | -            | -                | -                | -         |    -6.71 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     5284 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.228      | -            | -                | -                | -         |    -6.74 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     5422 | 2024-10-06 | BIG                              | W   | 0.211      | 0.500        | 0.244 (0.026)    | 0.528 (0.056)    | 1 (0.211) |     5.33 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     5446 | 2024-10-06 | Wildcard                         | W   | 0.209      | 0.500        | 0.161 (0.017)    | 0.279 (0.029)    | 1 (0.209) |     2.66 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     5563 | 2024-10-04 | SAW                              | W   | 0.197      | 0.500        | 0.315 (0.031)    | 0.333 (0.033)    | 1 (0.197) |     4.74 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     5582 | 2024-10-04 | BetBoom Team                     | W   | 0.196      | 0.500        | 0.122 (0.012)    | 0.387 (0.038)    | 1 (0.196) |     1.92 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     5833 | 2024-09-30 | Rooster                          | W   | 0.168      | 0.333        | -                | 0.377 (0.021)    | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     5834 | 2024-09-30 | Rooster                          | W   | 0.168      | 0.333        | -                | 0.377 (0.021)    | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     6053 | 2024-09-27 | Only One Word                    | W   | 0.148      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     6055 | 2024-09-27 | Only One Word                    | W   | 0.148      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     6125 | 2024-09-26 | Housebets                        | W   | 0.141      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     6130 | 2024-09-26 | Housebets                        | W   | 0.141      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     6217 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.135      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     6223 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.134      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     7337 | 2024-09-07 | HEROIC                           | L   | 0.015      | -            | -                | -                | -         |    -0.30 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     7402 | 2024-09-06 | Lynn Vision Gaming               | W   | 0.009      | -            | -                | -                | 1 (0.009) |     0.05 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,342.26)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-10-19 |      0.300 | $3,250.00      | $975.61         |
| 2024-10-06 |      0.211 | $50,000.00     | $10,554.50      |
| 2024-09-22 |      0.116 | $7,000.00      | $812.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
