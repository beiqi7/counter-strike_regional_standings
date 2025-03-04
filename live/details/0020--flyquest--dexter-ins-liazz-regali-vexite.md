### Roster Details<br />
Team Name: FlyQuest<br />
Roster: dexter, INS, Liazz, regali, Vexite<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1197.6<br />
<br />
Final Rank Value (1197.6) = Starting Rank Value (1206.0) + Head To Head Adjustments (-8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.499[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.536[<sup>2</sup>](#table1)

The average of these factors is 0.387<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1206.0
- 400 + ( ( 0.387 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1206.0


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
|           32 |        0 | 2025-03-03 | PaiN Gaming                      | W   | 1.000      | 0.889        | 0.333 (0.296)    | 0.406 (0.361)    | 1 (1.000) |    27.62 | dexter, INS, Liazz, regali, Vexite   |
|           31 |        2 | 2025-03-02 | Lynn Vision Gaming               | W   | 1.000      | 0.889        | 0.013 (0.011)    | 0.284 (0.252)    | 1 (1.000) |     5.79 | dexter, INS, Liazz, regali, Vexite   |
|           30 |        4 | 2025-03-01 | M80                              | L   | 1.000      | -            | -                | -                | -         |   -21.20 | dexter, INS, Liazz, regali, Vexite   |
|           29 |      450 | 2025-02-16 | SAW                              | L   | 1.000      | -            | -                | -                | -         |   -10.73 | dexter, INS, Liazz, regali, Vexite   |
|           28 |      522 | 2025-02-15 | BIG                              | L   | 1.000      | -            | -                | -                | -         |    -9.54 | dexter, INS, Liazz, regali, Vexite   |
|           27 |      571 | 2025-02-14 | Team Falcons                     | L   | 1.000      | -            | -                | -                | -         |    -0.82 | dexter, INS, Liazz, regali, Vexite   |
|           26 |     1168 | 2025-01-30 | Astralis                         | L   | 0.983      | -            | -                | -                | -         |    -1.08 | dexter, INS, Liazz, regali, Vexite   |
|           25 |     1182 | 2025-01-29 | 3DMAX                            | L   | 0.975      | -            | -                | -                | -         |    -3.57 | dexter, INS, Liazz, regali, Vexite   |
|           24 |     1313 | 2025-01-18 | Team Spirit                      | L   | 0.904      | -            | -                | -                | -         |    -0.44 | dexter, INS, Liazz, regali, Vexite   |
|           23 |     1343 | 2025-01-14 | MIBR                             | W   | 0.876      | 0.363        | 0.118 (0.037)    | 0.285 (0.091)    | -         |    10.40 | dexter, INS, Liazz, regali, Vexite   |
|           22 |     3489 | 2024-11-13 | Lynn Vision Gaming               | W   | 0.462      | 0.143        | 0.013 (0.001)    | 0.284 (0.019)    | 1 (0.462) |     1.90 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3496 | 2024-11-12 | Adventurers                      | W   | 0.460      | 0.143        | 0.019 (0.001)    | -                | 1 (0.460) |     1.84 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3530 | 2024-11-11 | Ex-GR Gaming                     | W   | 0.454      | 0.143        | 0.013 (0.001)    | -                | 1 (0.454) |     1.03 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3567 | 2024-11-11 | TALON                            | L   | 0.449      | -            | -                | -                | -         |   -13.76 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     4739 | 2024-10-19 | Mindfreak (Australian team)      | W   | 0.301      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     4823 | 2024-10-18 | Mindfreak (Australian team)      | W   | 0.288      | -            | -                | -                | -         |     0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     5279 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.228      | -            | -                | -                | -         |    -6.72 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     5282 | 2024-10-09 | Mindfreak (Australian team)      | L   | 0.228      | -            | -                | -                | -         |    -6.74 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     5420 | 2024-10-06 | BIG                              | W   | 0.211      | 0.500        | 0.244 (0.026)    | 0.528 (0.056)    | 1 (0.211) |     5.35 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     5444 | 2024-10-06 | Wildcard                         | W   | 0.209      | 0.500        | 0.161 (0.017)    | 0.279 (0.029)    | 1 (0.209) |     2.69 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     5561 | 2024-10-04 | SAW                              | W   | 0.198      | 0.500        | 0.315 (0.031)    | 0.333 (0.033)    | 1 (0.198) |     4.76 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     5580 | 2024-10-04 | BetBoom Team                     | W   | 0.196      | 0.500        | 0.122 (0.012)    | 0.387 (0.038)    | 1 (0.196) |     1.93 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     5831 | 2024-09-30 | Rooster                          | W   | 0.168      | 0.333        | -                | 0.376 (0.021)    | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     5832 | 2024-09-30 | Rooster                          | W   | 0.168      | 0.333        | -                | 0.376 (0.021)    | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     6051 | 2024-09-27 | Only One Word                    | W   | 0.148      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     6053 | 2024-09-27 | Only One Word                    | W   | 0.148      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     6123 | 2024-09-26 | Housebets                        | W   | 0.142      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     6128 | 2024-09-26 | Housebets                        | W   | 0.141      | -            | -                | -                | -         |     0.22 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     6215 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.135      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     6221 | 2024-09-25 | Arcade Esports (Australian team) | W   | 0.135      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     7335 | 2024-09-07 | HEROIC                           | L   | 0.015      | -            | -                | -                | -         |    -0.31 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     7400 | 2024-09-06 | Lynn Vision Gaming               | W   | 0.010      | -            | -                | -                | 1 (0.010) |     0.04 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,364.71)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-10-19 |      0.301 | $3,250.00      | $976.82         |
| 2024-10-06 |      0.211 | $50,000.00     | $10,573.14      |
| 2024-09-22 |      0.116 | $7,000.00      | $814.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
