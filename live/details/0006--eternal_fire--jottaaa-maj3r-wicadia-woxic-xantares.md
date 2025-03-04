### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: jottAAA, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1837.5<br />
<br />
Final Rank Value (1837.5) = Starting Rank Value (1954.1) + Head To Head Adjustments (-116.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.869[<sup>1</sup>](#table2)
- Bounty Collected: 0.737[<sup>2</sup>](#table1)
- Opponent Network: 0.382[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.747<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1954.1
- 400 + ( ( 0.747 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1954.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |        3 | 2025-03-02 | TYLOO           | L   | 1.000      | -            | -                | -                | -         |   -31.16 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |      280 | 2025-02-21 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -16.40 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |      412 | 2025-02-17 | 3DMAX           | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |     5.20 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |      473 | 2025-02-16 | BIG             | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     1.58 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |      516 | 2025-02-15 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |   -19.98 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |      559 | 2025-02-14 | Imperial Female | W   | 1.000      | 1.000        | 0.160 (0.160)    | 0.213 (0.213)    | 1 (1.000) |     0.28 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |      867 | 2025-02-07 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |   -17.19 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1022 | 2025-02-04 | FaZe Clan       | W   | 1.000      | 1.000        | 0.475 (0.475)    | 0.398 (0.398)    | 1 (1.000) |    10.38 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1082 | 2025-02-03 | 3DMAX           | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |     4.42 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1103 | 2025-02-02 | Virtus.pro      | L   | 1.000      | -            | -                | -                | -         |   -24.90 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     1133 | 2025-02-01 | Team Falcons    | W   | 0.996      | 1.000        | 1.000 (0.996)    | 0.565 (0.562)    | 1 (0.996) |    14.07 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     1163 | 2025-01-30 | HEROIC          | W   | 0.984      | 1.000        | 0.154 (0.152)    | 0.412 (0.406)    | 1 (0.984) |     0.47 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     1173 | 2025-01-29 | Complexity      | W   | 0.977      | -            | -                | -                | 1 (0.977) |     0.19 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     1228 | 2025-01-26 | Team Spirit     | L   | 0.957      | -            | -                | -                | -         |   -12.95 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     1234 | 2025-01-25 | G2 Esports      | W   | 0.950      | 0.769        | 0.971 (0.709)    | 0.310 (0.226)    | 1 (0.950) |     7.97 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     1253 | 2025-01-24 | Team Vitality   | W   | 0.943      | 0.769        | 1.000 (0.725)    | 0.391 (0.284)    | 1 (0.943) |    15.11 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     1311 | 2025-01-19 | Team Falcons    | W   | 0.909      | 0.363        | 1.000 (0.330)    | 0.565 (0.186)    | -         |    14.46 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     1334 | 2025-01-16 | Fluxo           | W   | 0.890      | -            | -                | -                | -         |     0.25 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2903 | 2024-11-23 | Astralis        | L   | 0.529      | -            | -                | -                | -         |    -9.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           14 |     2998 | 2024-11-21 | Sashi Esport    | L   | 0.521      | -            | -                | -                | -         |   -16.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           13 |     3045 | 2024-11-21 | 3DMAX           | L   | 0.516      | -            | -                | -                | -         |   -14.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           12 |     3064 | 2024-11-20 | Aurora Gaming   | W   | 0.514      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           11 |     4435 | 2024-10-26 | B8              | L   | 0.343      | -            | -                | -                | -         |   -10.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           10 |     4468 | 2024-10-26 | Team Falcons    | W   | 0.342      | -            | -                | -                | -         |     0.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            9 |     4529 | 2024-10-25 | B8              | L   | 0.335      | -            | -                | -                | -         |   -10.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            8 |     5262 | 2024-10-09 | The MongolZ     | L   | 0.229      | -            | -                | -                | -         |    -4.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            7 |     5334 | 2024-10-08 | G2 Esports      | W   | 0.224      | -            | -                | -                | -         |     1.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            6 |     5385 | 2024-10-07 | Astralis        | L   | 0.217      | -            | -                | -                | -         |    -4.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            5 |     6412 | 2024-09-22 | Natus Vincere   | L   | 0.116      | -            | -                | -                | -         |    -2.97 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            4 |     6479 | 2024-09-21 | MIBR            | W   | 0.110      | -            | -                | -                | -         |     0.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            3 |     6589 | 2024-09-19 | Team Vitality   | W   | 0.097      | -            | -                | -                | -         |     1.38 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            2 |     6669 | 2024-09-18 | The MongolZ     | W   | 0.089      | -            | -                | -                | -         |     1.12 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            1 |     7293 | 2024-09-07 | Natus Vincere   | L   | 0.017      | -            | -                | -                | -         |    -0.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($196,063.40)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.71) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-26 |      0.957 | $85,625.00     | $81,914.96      |
| 2024-10-27 |      0.351 | $3,000.00      | $1,052.24       |
| 2024-10-13 |      0.257 | $5,000.00      | $1,284.74       |
| 2024-09-22 |      0.116 | $80,000.00     | $9,311.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
