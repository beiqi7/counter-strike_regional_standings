### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, ropz, ZywOo<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1902.2<br />
<br />
Final Rank Value (1902.2) = Starting Rank Value (1864.3) + Head To Head Adjustments (37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.642[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.829[<sup>2</sup>](#table1)

The average of these factors is 0.664<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1864.3
- 400 + ( ( 0.664 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1864.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      736 | 2025-02-09 | Team Spirit  | W   | 0.688      | 1.000        | 1.000 (0.825)    | 0.503 (0.415)    | 1 (0.825) |    13.08 | apEX, flameZ, mezii, ropz, ZywOo  |
|           16 |      814 | 2025-02-08 | The MongolZ  | W   | 0.682      | 1.000        | 1.000 (0.818)    | 0.374 (0.306)    | 1 (0.818) |    10.18 | apEX, flameZ, mezii, ropz, ZywOo  |
|           15 |     1045 | 2025-02-04 | Virtus.pro   | W   | 0.659      | 1.000        | 0.320 (0.253)    | 0.352 (0.278)    | 1 (0.791) |     4.82 | apEX, flameZ, mezii, ropz, ZywOo  |
|           14 |     1124 | 2025-02-02 | FaZe Clan    | W   | 0.649      | 1.000        | 0.498 (0.388)    | 0.354 (0.276)    | 1 (0.779) |     8.72 | apEX, flameZ, mezii, ropz, ZywOo  |
|           13 |     1157 | 2025-02-01 | 3DMAX        | W   | 0.642      | 1.000        | 0.261 (0.201)    | 0.383 (0.295)    | 1 (0.771) |     2.95 | apEX, flameZ, mezii, ropz, ZywOo  |
|           12 |     1328 | 2025-01-24 | Eternal Fire | L   | 0.598      | -            | -                | -                | -         |    -7.86 | apEX, flameZ, mezii, ropz, ZywOo  |
|           11 |     1426 | 2025-01-19 | Virtus.pro   | W   | 0.571      | 0.363        | 0.320 (0.080)    | 0.352 (0.087)    | -         |     4.08 | apEX, flameZ, mezii, ropz, ZywOo  |
|           10 |     1458 | 2025-01-15 | Metizport    | W   | 0.549      | 0.363        | 0.062 (0.015)    | 0.367 (0.088)    | -         |     0.14 | apEX, flameZ, mezii, ropz, ZywOo  |
|            9 |     3343 | 2024-11-18 | FaZe Clan    | W   | 0.225      | 0.143        | 0.498 (0.019)    | -                | 1 (0.270) |     3.23 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     3395 | 2024-11-17 | BetBoom Team | W   | 0.220      | -            | -                | -                | 1 (0.263) |     0.06 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     3413 | 2024-11-16 | GamerLegion  | W   | 0.218      | 0.143        | -                | 0.415 (0.016)    | 1 (0.262) |     1.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     4219 | 2024-11-02 | G2 Esports   | L   | 0.136      | -            | -                | -                | -         |    -3.86 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|            5 |     4275 | 2024-11-01 | MOUZ         | W   | 0.130      | 1.000        | 1.000 (0.156)    | 0.384 (0.060)    | 1 (0.156) |     2.79 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|            4 |     4322 | 2024-10-31 | Team Liquid  | W   | 0.125      | 1.000        | 0.075 (0.011)    | 0.180 (0.027)    | 1 (0.150) |     0.08 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|            3 |     4393 | 2024-10-30 | Team Spirit  | L   | 0.120      | -            | -                | -                | -         |    -1.28 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|            2 |     5389 | 2024-10-11 | MOUZ         | L   | 0.016      | -            | -                | -                | -         |    -0.16 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     5498 | 2024-10-09 | Team Falcons | L   | 0.004      | -            | -                | -                | -         |    -0.05 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($347,485.76)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $400,000.00    | $330,000.00     |
| 2025-01-26 |      0.731 | $3,750.00      | $2,742.71       |
| 2024-11-03 |      0.170 | $85,000.00     | $14,426.39      |
| 2024-10-13 |      0.032 | $10,000.00     | $316.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
