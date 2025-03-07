### Roster Details<br />
Team Name: ODDIK<br />
Roster: Ceruttera, matios, naitte, pancc, WOOD7<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  940.1<br />
<br />
Final Rank Value (940.1) = Starting Rank Value (898.1) + Head To Head Adjustments (42.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.1
- 400 + ( ( 0.226 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 898.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       56 | 2025-02-26 | Sharks Esports           | W   | 0.784      | 0.450        | 0.051 (0.022)    | 0.636 (0.269)    | 0 (0.000) |    16.00 | Ceruttera, matios, naitte, pancc, WOOD7 |
|           41 |       59 | 2025-02-26 | Sharks Esports           | W   | 0.784      | 0.450        | 0.051 (0.022)    | 0.636 (0.269)    | 0 (0.000) |    17.01 | Ceruttera, matios, naitte, pancc, WOOD7 |
|           40 |      221 | 2025-02-22 | Sharks Esports           | L   | 0.760      | -            | -                | -                | -         |    -7.26 | Ceruttera, matios, naitte, togs, WOOD7  |
|           39 |      278 | 2025-02-21 | Players (Brazilian team) | W   | 0.754      | 0.371        | 0.009 (0.003)    | 0.558 (0.187)    | 0 (0.000) |     7.84 | Ceruttera, matios, naitte, togs, WOOD7  |
|           38 |      352 | 2025-02-19 | 9z Team                  | W   | 0.744      | 0.371        | 0.004 (0.001)    | -                | 0 (0.000) |     4.43 | Ceruttera, matios, naitte, togs, WOOD7  |
|           37 |      385 | 2025-02-18 | AdalYamigos              | W   | 0.739      | 0.450        | -                | 0.484 (0.193)    | 0 (0.000) |     5.87 | Ceruttera, matios, naitte, WOOD7        |
|           36 |      388 | 2025-02-18 | AdalYamigos              | W   | 0.739      | 0.450        | -                | 0.484 (0.193)    | 0 (0.000) |     6.17 | Ceruttera, matios, naitte, WOOD7        |
|           35 |      560 | 2025-02-14 | UNO MILLE                | W   | 0.717      | 0.371        | 0.008 (0.002)    | 0.527 (0.168)    | 0 (0.000) |     7.83 | Ceruttera, matios, naitte, togs, WOOD7  |
|           34 |      628 | 2025-02-12 | MIBR Academy             | W   | 0.706      | 0.371        | -                | 0.361 (0.113)    | 0 (0.000) |     5.80 | Ceruttera, matios, naitte, togs, WOOD7  |
|           33 |      693 | 2025-02-10 | Players (Brazilian team) | W   | 0.693      | 0.371        | 0.009 (0.003)    | 0.558 (0.172)    | 0 (0.000) |     7.63 | Ceruttera, matios, naitte, togs, WOOD7  |
|           32 |      767 | 2025-02-08 | BESTIA                   | L   | 0.683      | -            | -                | -                | -         |   -10.38 | Ceruttera, matios, naitte, togs, WOOD7  |
|           31 |      837 | 2025-02-07 | Fake do Biru             | W   | 0.678      | -            | -                | -                | -         |     3.78 | Ceruttera, matios, naitte, togs, WOOD7  |
|           30 |      885 | 2025-02-07 | BESTIA                   | L   | 0.677      | -            | -                | -                | -         |   -10.79 | Ceruttera, matios, naitte, togs, WOOD7  |
|           29 |      963 | 2025-02-05 | Bounty Hunters Esports   | W   | 0.666      | -            | -                | -                | -         |     6.78 | Ceruttera, matios, naitte, togs, WOOD7  |
|           28 |      983 | 2025-02-05 | Swingers                 | W   | 0.666      | -            | -                | -                | -         |     6.49 | Ceruttera, matios, naitte, togs, WOOD7  |
|           27 |     1197 | 2025-01-29 | RED Canids               | L   | 0.628      | -            | -                | -                | -         |   -13.04 | Ceruttera, matios, naitte, WOOD7        |
|           26 |     1198 | 2025-01-29 | RED Canids               | L   | 0.628      | -            | -                | -                | -         |   -13.69 | Ceruttera, matios, naitte, WOOD7        |
|           25 |     1261 | 2025-01-27 | Team Solid               | L   | 0.617      | -            | -                | -                | -         |   -11.34 | Ceruttera, matios, naitte, WOOD7        |
|           24 |     1266 | 2025-01-27 | Team Solid               | W   | 0.617      | 0.450        | 0.023 (0.008)    | 0.624 (0.208)    | -         |     8.21 | Ceruttera, matios, naitte, WOOD7        |
|           23 |     2609 | 2024-11-30 | Fluxo                    | L   | 0.295      | -            | -                | -                | -         |    -3.88 | ksloks, matios, naitte, togs, WOOD7     |
|           22 |     2633 | 2024-11-30 | Sharks Esports           | W   | 0.294      | 0.371        | 0.051 (0.007)    | 0.636 (0.083)    | -         |     6.65 | ksloks, matios, naitte, togs, WOOD7     |
|           21 |     2698 | 2024-11-29 | Players (Brazilian team) | W   | 0.289      | 0.371        | 0.009 (0.001)    | -                | -         |     3.08 | ksloks, matios, naitte, togs, WOOD7     |
|           20 |     2731 | 2024-11-28 | VELOX Argentina          | W   | 0.283      | -            | -                | -                | -         |     0.92 | ksloks, matios, naitte, togs, WOOD7     |
|           19 |     3060 | 2024-11-22 | Team Solid               | L   | 0.250      | -            | -                | -                | -         |    -4.19 | ksloks, matios, naitte, togs, WOOD7     |
|           18 |     3777 | 2024-11-09 | Fluxo                    | L   | 0.177      | -            | -                | -                | -         |    -2.48 | ksloks, matios, naitte, togs, WOOD7     |
|           17 |     3833 | 2024-11-08 | Players (Brazilian team) | W   | 0.172      | -            | -                | -                | -         |     1.73 | ksloks, matios, naitte, togs, WOOD7     |
|           16 |     3894 | 2024-11-07 | UNO MILLE                | W   | 0.166      | -            | -                | -                | -         |     1.80 | ksloks, matios, naitte, togs, WOOD7     |
|           15 |     3975 | 2024-11-05 | AdalYamigos              | W   | 0.156      | -            | -                | -                | -         |     1.26 | ksloks, matios, naitte, togs, WOOD7     |
|           14 |     4026 | 2024-11-04 | Sharks Esports           | W   | 0.151      | 0.143        | 0.051 (0.001)    | -                | -         |     3.48 | ksloks, matios, naitte, togs, WOOD7     |
|           13 |     4093 | 2024-11-03 | UNO MILLE                | L   | 0.144      | -            | -                | -                | -         |    -3.01 | ksloks, matios, naitte, togs, WOOD7     |
|           12 |     4165 | 2024-11-02 | Intense Game             | W   | 0.139      | -            | -                | -                | -         |     0.96 | ksloks, matios, naitte, togs, WOOD7     |
|           11 |     4231 | 2024-11-01 | Galorys Academy          | W   | 0.133      | -            | -                | -                | -         |     0.77 | ksloks, matios, naitte, togs, WOOD7     |
|           10 |     4290 | 2024-10-31 | Team Solid               | W   | 0.128      | -            | -                | -                | -         |     1.87 | ksloks, matios, naitte, togs, WOOD7     |
|            9 |     4352 | 2024-10-30 | Bounty Hunters Esports   | L   | 0.122      | -            | -                | -                | -         |    -2.97 | ksloks, matios, naitte, togs, WOOD7     |
|            8 |     4406 | 2024-10-29 | Fluxo                    | L   | 0.117      | -            | -                | -                | -         |    -1.67 | ksloks, matios, naitte, togs, WOOD7     |
|            7 |     4473 | 2024-10-28 | América eSports          | W   | 0.111      | -            | -                | -                | -         |     0.63 | ksloks, matios, naitte, togs, WOOD7     |
|            6 |     4530 | 2024-10-27 | Sharks Esports           | L   | 0.105      | -            | -                | -                | -         |    -0.88 | ksloks, matios, naitte, togs, WOOD7     |
|            5 |     4585 | 2024-10-26 | AdalYamigos              | W   | 0.099      | -            | -                | -                | 1 (0.119) |     0.83 | ksloks, matios, naitte, togs, WOOD7     |
|            4 |     5084 | 2024-10-16 | BESTIA                   | L   | 0.044      | -            | -                | -                | -         |    -0.76 | ksloks, matios, naitte, togs, WOOD7     |
|            3 |     5168 | 2024-10-15 | KRÜ Esports              | W   | 0.039      | -            | -                | -                | -         |     0.33 | ksloks, matios, naitte, togs, WOOD7     |
|            2 |     5470 | 2024-10-09 | Dusty Roots              | W   | 0.005      | -            | -                | -                | -         |     0.06 | ksloks, matios, naitte, togs, WOOD7     |
|            1 |     5479 | 2024-10-09 | Dusty Roots              | W   | 0.005      | -            | -                | -                | -         |     0.06 | ksloks, matios, naitte, togs, WOOD7     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,049.87)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.914 | $1,500.00      | $1,371.32       |
| 2024-11-30 |      0.354 | $4,000.00      | $1,414.17       |
| 2024-11-24 |      0.313 | $3,878.61      | $1,212.52       |
| 2024-11-09 |      0.214 | $1,500.00      | $320.59         |
| 2024-10-27 |      0.126 | $4,555.41      | $573.22         |
| 2024-10-20 |      0.079 | $2,000.00      | $158.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
