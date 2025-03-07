### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno4K<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1848.8<br />
<br />
Final Rank Value (1848.8) = Starting Rank Value (1866.3) + Head To Head Adjustments (-17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.545[<sup>2</sup>](#table1)
- Opponent Network: 0.176[<sup>2</sup>](#table1)
- LAN Wins: 0.938[<sup>2</sup>](#table1)

The average of these factors is 0.665<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1866.3
- 400 + ( ( 0.665 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1866.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      291 | 2025-02-21 | Astralis         | L   | 0.753      | -            | -                | -                | -         |   -14.11 | 910, bLitz, mzinho, Senzu, Techno4K |
|           20 |      470 | 2025-02-16 | PaiN Gaming      | W   | 0.726      | 1.000        | 0.357 (0.311)    | 0.371 (0.323)    | 1 (0.872) |     5.35 | 910, bLitz, mzinho, Senzu, Techno4K |
|           19 |      546 | 2025-02-15 | Wildcard         | W   | 0.720      | 1.000        | 0.162 (0.140)    | 0.216 (0.187)    | 1 (0.863) |     0.40 | 910, bLitz, mzinho, Senzu, Techno4K |
|           18 |      592 | 2025-02-14 | Complexity       | W   | 0.714      | 1.000        | 0.092 (0.079)    | 0.102 (0.088)    | 1 (0.857) |     0.12 | 910, bLitz, mzinho, Senzu, Techno4K |
|           17 |      814 | 2025-02-08 | Team Vitality    | L   | 0.682      | -            | -                | -                | -         |   -10.18 | 910, bLitz, mzinho, Senzu, Techno4K |
|           16 |      891 | 2025-02-07 | Eternal Fire     | W   | 0.676      | 1.000        | 0.731 (0.593)    | 0.557 (0.452)    | 1 (0.811) |    12.59 | 910, bLitz, mzinho, Senzu, Techno4K |
|           15 |     1033 | 2025-02-04 | Natus Vincere    | L   | 0.660      | -            | -                | -                | -         |   -16.80 | 910, bLitz, mzinho, Senzu, Techno4K |
|           14 |     1119 | 2025-02-03 | GamerLegion      | W   | 0.653      | 1.000        | 0.094 (0.074)    | 0.415 (0.325)    | 1 (0.784) |     3.25 | 910, bLitz, mzinho, Senzu, Techno4K |
|           13 |     1132 | 2025-02-02 | Team Liquid      | W   | 0.648      | 1.000        | 0.075 (0.058)    | 0.180 (0.140)    | 1 (0.777) |     0.41 | 910, bLitz, mzinho, Senzu, Techno4K |
|           12 |     3664 | 2024-11-12 | Adventurers      | W   | 0.191      | -            | -                | -                | 1 (0.229) |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K |
|           11 |     3721 | 2024-11-11 | Alter Ego        | W   | 0.186      | -            | -                | -                | 1 (0.223) |     0.00 | 910, bLitz, mzinho, Senzu, Techno4K |
|           10 |     4113 | 2024-11-03 | Team Falcons     | W   | 0.143      | 0.934        | 1.000 (0.160)    | 0.495 (0.079)    | 1 (0.172) |     2.70 | 910, bLitz, mzinho, Senzu, Techno4K |
|            9 |     4174 | 2024-11-02 | 3DMAX            | W   | 0.138      | 0.934        | 0.261 (0.040)    | 0.383 (0.059)    | 1 (0.166) |     0.64 | 910, bLitz, mzinho, Senzu, Techno4K |
|            8 |     4594 | 2024-10-26 | Imperial Esports | W   | 0.098      | 0.934        | 0.061 (0.007)    | 0.576 (0.063)    | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K |
|            7 |     4789 | 2024-10-22 | Fnatic           | W   | 0.077      | 0.934        | -                | 0.471 (0.041)    | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno4K |
|            6 |     4815 | 2024-10-22 | Cloud9           | W   | 0.075      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno4K |
|            5 |     4957 | 2024-10-19 | ENCE             | L   | 0.059      | -            | -                | -                | -         |    -1.85 | 910, bLitz, mzinho, Senzu, Techno4K |
|            4 |     5140 | 2024-10-16 | B8               | W   | 0.042      | 0.589        | 0.134 (0.004)    | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno4K |
|            3 |     5152 | 2024-10-16 | JANO Esports     | W   | 0.041      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K |
|            2 |     5482 | 2024-10-09 | Virtus.pro       | L   | 0.005      | -            | -                | -                | -         |    -0.11 | 910, bLitz, mzinho, Senzu, Techno4K |
|            1 |     5501 | 2024-10-09 | Eternal Fire     | W   | 0.003      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno4K |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,686.06)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $62,500.00     | $57,427.66      |
| 2025-02-09 |      0.825 | $80,000.00     | $66,000.00      |
| 2024-11-03 |      0.172 | $500,000.00    | $85,902.78      |
| 2024-10-20 |      0.078 | $15,000.00     | $1,165.63       |
| 2024-10-13 |      0.032 | $6,000.00      | $190.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
