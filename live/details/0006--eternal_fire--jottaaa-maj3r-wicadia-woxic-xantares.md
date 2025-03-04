### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: jottAAA, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1837.6<br />
<br />
Final Rank Value (1837.6) = Starting Rank Value (1954.0) + Head To Head Adjustments (-116.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.869[<sup>1</sup>](#table2)
- Bounty Collected: 0.737[<sup>2</sup>](#table1)
- Opponent Network: 0.382[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.747<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1954.0
- 400 + ( ( 0.747 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1954.0


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
|           33 |        4 | 2025-03-02 | TYLOO           | L   | 1.000      | -            | -                | -                | -         |   -31.15 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |      282 | 2025-02-21 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -16.39 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |      414 | 2025-02-17 | 3DMAX           | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |     5.20 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |      475 | 2025-02-16 | BIG             | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     1.58 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |      518 | 2025-02-15 | FaZe Clan       | L   | 1.000      | -            | -                | -                | -         |   -19.98 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |      561 | 2025-02-14 | Imperial Female | W   | 1.000      | 1.000        | 0.160 (0.160)    | 0.213 (0.213)    | 1 (1.000) |     0.28 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |      869 | 2025-02-07 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |   -17.19 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1024 | 2025-02-04 | FaZe Clan       | W   | 1.000      | 1.000        | 0.475 (0.475)    | 0.399 (0.399)    | 1 (1.000) |    10.39 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1084 | 2025-02-03 | 3DMAX           | W   | 1.000      | 1.000        | 0.302 (0.302)    | 0.510 (0.510)    | 1 (1.000) |     4.42 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1105 | 2025-02-02 | Virtus.pro      | L   | 1.000      | -            | -                | -                | -         |   -24.90 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     1135 | 2025-02-01 | Team Falcons    | W   | 0.996      | 1.000        | 1.000 (0.996)    | 0.565 (0.562)    | 1 (0.996) |    14.06 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     1165 | 2025-01-30 | HEROIC          | W   | 0.984      | 1.000        | 0.154 (0.152)    | 0.412 (0.406)    | 1 (0.984) |     0.47 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     1175 | 2025-01-29 | Complexity      | W   | 0.977      | -            | -                | -                | 1 (0.977) |     0.19 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     1230 | 2025-01-26 | Team Spirit     | L   | 0.956      | -            | -                | -                | -         |   -12.94 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     1236 | 2025-01-25 | G2 Esports      | W   | 0.950      | 0.769        | 0.970 (0.708)    | 0.310 (0.226)    | 1 (0.950) |     7.95 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     1255 | 2025-01-24 | Team Vitality   | W   | 0.943      | 0.769        | 1.000 (0.725)    | 0.391 (0.284)    | 1 (0.943) |    15.09 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     1313 | 2025-01-19 | Team Falcons    | W   | 0.909      | 0.363        | 1.000 (0.330)    | 0.565 (0.186)    | -         |    14.46 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     1336 | 2025-01-16 | Fluxo           | W   | 0.889      | -            | -                | -                | -         |     0.25 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2905 | 2024-11-23 | Astralis        | L   | 0.528      | -            | -                | -                | -         |    -9.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           14 |     3000 | 2024-11-21 | Sashi Esport    | L   | 0.520      | -            | -                | -                | -         |   -16.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           13 |     3047 | 2024-11-21 | 3DMAX           | L   | 0.516      | -            | -                | -                | -         |   -14.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           12 |     3066 | 2024-11-20 | Aurora Gaming   | W   | 0.514      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           11 |     4437 | 2024-10-26 | B8              | L   | 0.343      | -            | -                | -                | -         |   -10.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|           10 |     4470 | 2024-10-26 | Team Falcons    | W   | 0.341      | -            | -                | -                | -         |     0.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            9 |     4531 | 2024-10-25 | B8              | L   | 0.335      | -            | -                | -                | -         |   -10.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            8 |     5264 | 2024-10-09 | The MongolZ     | L   | 0.229      | -            | -                | -                | -         |    -4.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            7 |     5336 | 2024-10-08 | G2 Esports      | W   | 0.223      | -            | -                | -                | -         |     1.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            6 |     5387 | 2024-10-07 | Astralis        | L   | 0.217      | -            | -                | -                | -         |    -4.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            5 |     6414 | 2024-09-22 | Natus Vincere   | L   | 0.116      | -            | -                | -                | -         |    -2.95 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            4 |     6481 | 2024-09-21 | MIBR            | W   | 0.109      | -            | -                | -                | -         |     0.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            3 |     6591 | 2024-09-19 | Team Vitality   | W   | 0.097      | -            | -                | -                | -         |     1.38 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            2 |     6671 | 2024-09-18 | The MongolZ     | W   | 0.088      | -            | -                | -                | -         |     1.12 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            1 |     7295 | 2024-09-07 | Natus Vincere   | L   | 0.017      | -            | -                | -                | -         |    -0.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($195,998.70)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.71) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-26 |      0.956 | $85,625.00     | $81,883.05      |
| 2024-10-27 |      0.350 | $3,000.00      | $1,051.12       |
| 2024-10-13 |      0.257 | $5,000.00      | $1,282.88       |
| 2024-09-22 |      0.116 | $80,000.00     | $9,281.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
