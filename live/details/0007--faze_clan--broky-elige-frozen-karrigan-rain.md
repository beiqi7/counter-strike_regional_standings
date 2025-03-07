### Roster Details<br />
Team Name: FaZe Clan<br />
Roster: broky, EliGE, frozen, karrigan, rain<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [6]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1814.7<br />
<br />
Final Rank Value (1814.7) = Starting Rank Value (1834.2) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.768[<sup>1</sup>](#table2)
- Bounty Collected: 0.639[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.650<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1834.2
- 400 + ( ( 0.650 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1834.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      191 | 2025-02-23 | Astralis      | L   | 0.765      | -            | -                | -                | -         |   -12.98 | broky, EliGE, frozen, karrigan, rain |
|           20 |      213 | 2025-02-22 | Team Falcons  | L   | 0.760      | -            | -                | -                | -         |    -9.46 | broky, EliGE, frozen, karrigan, rain |
|           19 |      271 | 2025-02-21 | SAW           | W   | 0.755      | 1.000        | 0.316 (0.286)    | 0.260 (0.235)    | 1 (0.905) |     1.29 | broky, EliGE, frozen, karrigan, rain |
|           18 |      476 | 2025-02-16 | MOUZ          | W   | 0.726      | 1.000        | 1.000 (0.871)    | 0.384 (0.335)    | 1 (0.871) |    14.88 | broky, EliGE, frozen, karrigan, rain |
|           17 |      542 | 2025-02-15 | Eternal Fire  | W   | 0.720      | 1.000        | 0.731 (0.632)    | 0.557 (0.482)    | 1 (0.864) |    14.42 | broky, EliGE, frozen, karrigan, rain |
|           16 |      595 | 2025-02-14 | SAW           | W   | 0.714      | 1.000        | 0.316 (0.271)    | 0.260 (0.222)    | 1 (0.857) |     1.26 | broky, EliGE, frozen, karrigan, rain |
|           15 |     1044 | 2025-02-04 | Eternal Fire  | L   | 0.659      | -            | -                | -                | -         |    -7.18 | broky, EliGE, frozen, karrigan, rain |
|           14 |     1105 | 2025-02-03 | G2 Esports    | W   | 0.655      | 1.000        | 0.528 (0.415)    | 0.246 (0.193)    | 1 (0.786) |     3.11 | broky, EliGE, frozen, karrigan, rain |
|           13 |     1124 | 2025-02-02 | Team Vitality | L   | 0.649      | -            | -                | -                | -         |    -8.72 | broky, EliGE, frozen, karrigan, rain |
|           12 |     1153 | 2025-02-01 | BIG           | W   | 0.643      | 1.000        | 0.234 (0.180)    | 0.400 (0.309)    | 1 (0.771) |     1.72 | broky, EliGE, frozen, karrigan, rain |
|           11 |     1442 | 2025-01-18 | PaiN Gaming   | L   | 0.565      | -            | -                | -                | -         |   -13.06 | broky, EliGE, frozen, karrigan, rain |
|           10 |     1455 | 2025-01-16 | M80           | W   | 0.554      | 0.363        | 0.010 (0.002)    | 0.423 (0.102)    | -         |     0.08 | broky, EliGE, frozen, karrigan, rain |
|            9 |     3293 | 2024-11-19 | Cloud9        | W   | 0.231      | 0.143        | -                | 0.055 (0.002)    | 1 (0.277) |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            8 |     3299 | 2024-11-19 | Fnatic        | W   | 0.230      | 0.143        | 0.025 (0.001)    | 0.471 (0.019)    | 1 (0.276) |     0.07 | broky, frozen, karrigan, rain, ropz  |
|            7 |     3343 | 2024-11-18 | Team Vitality | L   | 0.225      | -            | -                | -                | -         |    -3.23 | broky, frozen, karrigan, rain, ropz  |
|            6 |     3385 | 2024-11-17 | Team Falcons  | W   | 0.220      | 0.143        | 0.001 (0.000)    | -                | 1 (0.264) |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            5 |     3411 | 2024-11-16 | Cloud9        | W   | 0.218      | -            | -                | -                | 1 (0.262) |     0.01 | broky, frozen, karrigan, rain, ropz  |
|            4 |     4269 | 2024-11-01 | Team Spirit   | L   | 0.131      | -            | -                | -                | -         |    -1.25 | broky, frozen, karrigan, rain, ropz  |
|            3 |     4329 | 2024-10-30 | Natus Vincere | W   | 0.124      | 1.000        | 0.420 (0.062)    | 0.321 (0.048)    | -         |     0.69 | broky, frozen, karrigan, rain, ropz  |
|            2 |     4404 | 2024-10-30 | MOUZ          | L   | 0.119      | -            | -                | -                | -         |    -1.06 | broky, frozen, karrigan, rain, ropz  |
|            1 |     5481 | 2024-10-09 | MOUZ          | L   | 0.005      | -            | -                | -                | -         |    -0.04 | broky, frozen, karrigan, rain, ropz  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,631.78)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $87,500.00     | $80,398.73      |
| 2025-02-09 |      0.825 | $24,000.00     | $19,800.00      |
| 2024-11-03 |      0.170 | $25,000.00     | $4,243.06       |
| 2024-10-13 |      0.032 | $6,000.00      | $190.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
