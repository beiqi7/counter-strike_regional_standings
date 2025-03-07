### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: jottAAA, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1869.4<br />
<br />
Final Rank Value (1869.4) = Starting Rank Value (1940.9) + Head To Head Adjustments (-71.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.880[<sup>1</sup>](#table2)
- Bounty Collected: 0.664[<sup>2</sup>](#table1)
- Opponent Network: 0.251[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.699<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1940.9
- 400 + ( ( 0.699 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1940.9


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
|           27 |        2 | 2025-03-04 | FlyQuest        | W   | 0.815      | -            | -                | -                | 1 (0.978) |     0.42 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |        8 | 2025-03-02 | TYLOO           | L   | 0.807      | -            | -                | -                | -         |   -24.94 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |      288 | 2025-02-21 | Team Falcons    | L   | 0.754      | -            | -                | -                | -         |   -11.96 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |      437 | 2025-02-17 | 3DMAX           | W   | 0.732      | 1.000        | 0.261 (0.229)    | 0.383 (0.336)    | 1 (0.878) |     2.99 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |      498 | 2025-02-16 | BIG             | W   | 0.725      | 1.000        | 0.234 (0.203)    | 0.400 (0.348)    | 1 (0.869) |     0.93 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |      542 | 2025-02-15 | FaZe Clan       | L   | 0.720      | -            | -                | -                | -         |   -14.42 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |      585 | 2025-02-14 | Imperial Female | W   | 0.715      | 1.000        | 0.146 (0.125)    | 0.159 (0.136)    | 1 (0.859) |     0.14 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |      891 | 2025-02-07 | The MongolZ     | L   | 0.676      | -            | -                | -                | -         |   -12.59 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     1044 | 2025-02-04 | FaZe Clan       | W   | 0.659      | 1.000        | 0.498 (0.394)    | 0.354 (0.280)    | 1 (0.791) |     7.18 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     1106 | 2025-02-03 | 3DMAX           | W   | 0.655      | 1.000        | 0.261 (0.205)    | 0.383 (0.301)    | 1 (0.786) |     2.32 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     1128 | 2025-02-02 | Virtus.pro      | L   | 0.649      | -            | -                | -                | -         |   -16.89 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     1158 | 2025-02-01 | Team Falcons    | W   | 0.642      | 1.000        | 1.000 (0.771)    | 0.495 (0.381)    | 1 (0.771) |     9.70 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     1189 | 2025-01-30 | HEROIC          | W   | 0.632      | 1.000        | 0.120 (0.091)    | 0.372 (0.282)    | 1 (0.759) |     0.17 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     1201 | 2025-01-29 | Complexity      | W   | 0.627      | -            | -                | -                | 1 (0.752) |     0.08 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     1280 | 2025-01-26 | Team Spirit     | L   | 0.609      | -            | -                | -                | -         |    -8.58 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     1288 | 2025-01-25 | G2 Esports      | W   | 0.604      | 0.769        | 0.528 (0.294)    | 0.246 (0.137)    | 1 (0.725) |     1.47 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     1328 | 2025-01-24 | Team Vitality   | W   | 0.598      | 0.769        | 1.000 (0.552)    | 0.333 (0.184)    | -         |     7.86 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     1433 | 2025-01-19 | Team Falcons    | W   | 0.570      | 0.363        | 1.000 (0.248)    | 0.495 (0.123)    | -         |     9.11 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     1456 | 2025-01-16 | Fluxo           | W   | 0.554      | -            | -                | -                | -         |     0.09 | jottAAA, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3026 | 2024-11-23 | Astralis        | L   | 0.253      | -            | -                | -                | -         |    -4.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            7 |     3118 | 2024-11-21 | Sashi Esport    | L   | 0.246      | -            | -                | -                | -         |    -7.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            6 |     3166 | 2024-11-21 | 3DMAX           | L   | 0.242      | -            | -                | -                | -         |    -6.83 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            5 |     3185 | 2024-11-20 | Aurora Gaming   | W   | 0.241      | -            | -                | -                | -         |     0.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            4 |     4598 | 2024-10-26 | B8              | L   | 0.098      | -            | -                | -                | -         |    -3.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            3 |     4631 | 2024-10-26 | Team Falcons    | W   | 0.097      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            2 |     4697 | 2024-10-25 | B8              | L   | 0.091      | -            | -                | -                | -         |    -2.85 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |
|            1 |     5501 | 2024-10-09 | The MongolZ     | L   | 0.003      | -            | -                | -                | -         |    -0.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($153,587.56)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.73) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $62,500.00     | $57,427.66      |
| 2025-02-09 |      0.825 | $40,000.00     | $33,000.00      |
| 2025-01-26 |      0.731 | $85,625.00     | $62,625.17      |
| 2024-10-27 |      0.125 | $3,000.00      | $376.39         |
| 2024-10-13 |      0.032 | $5,000.00      | $158.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
