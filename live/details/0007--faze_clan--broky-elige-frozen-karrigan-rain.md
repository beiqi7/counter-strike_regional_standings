### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, EliGE, frozen, karrigan, rain<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1788.4<br />
<br />
Final Rank Value (1788.4) = Starting Rank Value (1828.6) + Head To Head Adjustments (-40.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.755[<sup>1</sup>](#table2)
- Bounty Collected: 0.707[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.687<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1828.6
- 400 + ( ( 0.687 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1828.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      185 | 2025-02-23 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -19.41 | broky, EliGE, frozen, karrigan, rain |
|           30 |      207 | 2025-02-22 | Team Falcons      | L   | 1.000      | -            | -                | -                | -         |   -13.01 | broky, EliGE, frozen, karrigan, rain |
|           29 |      265 | 2025-02-21 | SAW               | W   | 1.000      | 1.000        | 0.315 (0.315)    | 0.333 (0.333)    | 1 (1.000) |     2.04 | broky, EliGE, frozen, karrigan, rain |
|           28 |      453 | 2025-02-16 | MOUZ              | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.420 (0.420)    | 1 (1.000) |    18.39 | broky, EliGE, frozen, karrigan, rain |
|           27 |      518 | 2025-02-15 | Eternal Fire      | W   | 1.000      | 1.000        | 0.708 (0.708)    | 0.524 (0.524)    | 1 (1.000) |    19.98 | broky, EliGE, frozen, karrigan, rain |
|           26 |      577 | 2025-02-14 | SAW               | W   | 1.000      | 1.000        | 0.315 (0.315)    | 0.333 (0.333)    | 1 (1.000) |     2.09 | broky, EliGE, frozen, karrigan, rain |
|           25 |     1024 | 2025-02-04 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |   -10.39 | broky, EliGE, frozen, karrigan, rain |
|           24 |     1083 | 2025-02-03 | G2 Esports        | W   | 1.000      | 1.000        | 0.970 (0.970)    | 0.310 (0.310)    | 1 (1.000) |    13.47 | broky, EliGE, frozen, karrigan, rain |
|           23 |     1101 | 2025-02-02 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -10.08 | broky, EliGE, frozen, karrigan, rain |
|           22 |     1130 | 2025-02-01 | BIG               | W   | 0.996      | 1.000        | 0.244 (0.243)    | 0.528 (0.526)    | 1 (0.996) |     3.80 | broky, EliGE, frozen, karrigan, rain |
|           21 |     1322 | 2025-01-18 | PaiN Gaming       | L   | 0.903      | -            | -                | -                | -         |   -23.77 | broky, EliGE, frozen, karrigan, rain |
|           20 |     1335 | 2025-01-16 | M80               | W   | 0.890      | 0.363        | 0.043 (0.014)    | 0.460 (0.149)    | -         |     0.27 | broky, EliGE, frozen, karrigan, rain |
|           19 |     3166 | 2024-11-19 | Cloud9            | W   | 0.502      | -            | -                | -                | 1 (0.502) |     0.07 | broky, frozen, karrigan, rain, ropz  |
|           18 |     3171 | 2024-11-19 | Fnatic            | W   | 0.501      | 0.143        | -                | 0.508 (0.036)    | 1 (0.501) |     0.35 | broky, frozen, karrigan, rain, ropz  |
|           17 |     3213 | 2024-11-18 | Team Vitality     | L   | 0.495      | -            | -                | -                | -         |    -5.63 | broky, frozen, karrigan, rain, ropz  |
|           16 |     3255 | 2024-11-17 | Team Falcons      | W   | 0.489      | -            | -                | -                | 1 (0.489) |     0.04 | broky, frozen, karrigan, rain, ropz  |
|           15 |     3281 | 2024-11-16 | Cloud9            | W   | 0.487      | -            | -                | -                | 1 (0.487) |     0.05 | broky, frozen, karrigan, rain, ropz  |
|           14 |     4132 | 2024-11-01 | Team Spirit       | L   | 0.382      | -            | -                | -                | -         |    -3.31 | broky, frozen, karrigan, rain, ropz  |
|           13 |     4189 | 2024-10-30 | Natus Vincere     | W   | 0.374      | 1.000        | 0.602 (0.225)    | 0.434 (0.162)    | -         |     4.31 | broky, frozen, karrigan, rain, ropz  |
|           12 |     4256 | 2024-10-30 | MOUZ              | L   | 0.368      | -            | -                | -                | -         |    -3.44 | broky, frozen, karrigan, rain, ropz  |
|           11 |     5249 | 2024-10-09 | MOUZ              | L   | 0.230      | -            | -                | -                | -         |    -2.17 | broky, frozen, karrigan, rain, ropz  |
|           10 |     5329 | 2024-10-08 | Team Liquid       | W   | 0.224      | 0.624        | 0.109 (0.015)    | -                | -         |     0.28 | broky, frozen, karrigan, rain, ropz  |
|            9 |     5378 | 2024-10-07 | PaiN Gaming       | W   | 0.217      | 0.624        | 0.333 (0.045)    | 0.406 (0.055)    | -         |     1.02 | broky, frozen, karrigan, rain, ropz  |
|            8 |     5407 | 2024-10-07 | FURIA             | L   | 0.216      | -            | -                | -                | -         |    -6.60 | broky, frozen, karrigan, rain, ropz  |
|            7 |     5906 | 2024-09-28 | Natus Vincere     | L   | 0.157      | -            | -                | -                | -         |    -3.26 | broky, frozen, karrigan, rain, ropz  |
|            6 |     6021 | 2024-09-27 | Team Liquid       | W   | 0.150      | -            | -                | -                | -         |     0.18 | broky, frozen, karrigan, rain, ropz  |
|            5 |     6126 | 2024-09-26 | Team Falcons      | W   | 0.141      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            4 |     6208 | 2024-09-25 | G2 Esports        | L   | 0.135      | -            | -                | -                | -         |    -2.88 | broky, frozen, karrigan, rain, ropz  |
|            3 |     6729 | 2024-09-17 | Complexity        | L   | 0.083      | -            | -                | -                | -         |    -2.60 | broky, frozen, karrigan, rain, ropz  |
|            2 |     7401 | 2024-09-06 | HEROIC            | W   | 0.009      | -            | -                | -                | -         |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            1 |     7458 | 2024-09-05 | Ninjas in Pyjamas | W   | 0.004      | -            | -                | -                | -         |     0.00 | broky, frozen, karrigan, rain, ropz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($131,431.99)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.47) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $87,500.00     | $87,500.00      |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-11-03 |      0.395 | $25,000.00     | $9,865.79       |
| 2024-10-13 |      0.257 | $6,000.00      | $1,539.46       |
| 2024-09-29 |      0.162 | $40,000.00     | $6,496.38       |
| 2024-09-22 |      0.116 | $17,500.00     | $2,030.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
