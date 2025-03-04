### Roster Details<br />
Team Name: Team Vitality<br />
Roster: apEX, flameZ, mezii, ropz, ZywOo<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1956.2<br />
<br />
Final Rank Value (1956.2) = Starting Rank Value (1920.2) + Head To Head Adjustments (36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.704[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.921[<sup>2</sup>](#table1)

The average of these factors is 0.731<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1920.2
- 400 + ( ( 0.731 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1920.2


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
|           26 |      715 | 2025-02-09 | Team Spirit  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.569 (0.569)    | 1 (1.000) |    16.63 | apEX, flameZ, mezii, ropz, ZywOo  |
|           25 |      792 | 2025-02-08 | The MongolZ  | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.463 (0.463)    | 1 (1.000) |    13.25 | apEX, flameZ, mezii, ropz, ZywOo  |
|           24 |     1025 | 2025-02-04 | Virtus.pro   | W   | 1.000      | 1.000        | 0.299 (0.299)    | 0.419 (0.419)    | 1 (1.000) |     6.60 | apEX, flameZ, mezii, ropz, ZywOo  |
|           23 |     1101 | 2025-02-02 | FaZe Clan    | W   | 1.000      | 1.000        | 0.475 (0.475)    | 0.399 (0.399)    | 1 (1.000) |    10.08 | apEX, flameZ, mezii, ropz, ZywOo  |
|           22 |     1134 | 2025-02-01 | 3DMAX        | W   | 0.996      | 1.000        | 0.302 (0.301)    | 0.510 (0.508)    | 1 (0.996) |     4.19 | apEX, flameZ, mezii, ropz, ZywOo  |
|           21 |     1255 | 2025-01-24 | Eternal Fire | L   | 0.943      | -            | -                | -                | -         |   -15.09 | apEX, flameZ, mezii, ropz, ZywOo  |
|           20 |     1306 | 2025-01-19 | Virtus.pro   | W   | 0.910      | 0.363        | 0.299 (0.099)    | 0.419 (0.138)    | -         |     5.54 | apEX, flameZ, mezii, ropz, ZywOo  |
|           19 |     1338 | 2025-01-15 | Metizport    | W   | 0.884      | 0.363        | -                | 0.517 (0.166)    | -         |     0.27 | apEX, flameZ, mezii, ropz, ZywOo  |
|           18 |     3213 | 2024-11-18 | FaZe Clan    | W   | 0.495      | -            | -                | -                | 1 (0.495) |     5.63 | apEX, flameZ, mezii, Spinx, ZywOo |
|           17 |     3265 | 2024-11-17 | BetBoom Team | W   | 0.488      | -            | -                | -                | 1 (0.488) |     0.14 | apEX, flameZ, mezii, Spinx, ZywOo |
|           16 |     3283 | 2024-11-16 | GamerLegion  | W   | 0.487      | -            | -                | -                | 1 (0.487) |     2.00 | apEX, flameZ, mezii, Spinx, ZywOo |
|           15 |     4081 | 2024-11-02 | G2 Esports   | L   | 0.388      | -            | -                | -                | -         |    -9.21 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           14 |     4138 | 2024-11-01 | MOUZ         | W   | 0.381      | 1.000        | 1.000 (0.381)    | 0.420 (0.160)    | 1 (0.381) |     6.83 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           13 |     4182 | 2024-10-31 | Team Liquid  | W   | 0.375      | 1.000        | 0.109 (0.041)    | 0.198 (0.074)    | 1 (0.375) |     0.28 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           12 |     4245 | 2024-10-30 | Team Spirit  | L   | 0.369      | -            | -                | -                | -         |    -4.55 | apEX, flameZ, JACKZ, Spinx, ZywOo |
|           11 |     5166 | 2024-10-11 | MOUZ         | L   | 0.244      | -            | -                | -                | -         |    -3.28 | apEX, flameZ, mezii, Spinx, ZywOo |
|           10 |     5261 | 2024-10-09 | Team Falcons | L   | 0.230      | -            | -                | -                | -         |    -3.45 | apEX, flameZ, mezii, Spinx, ZywOo |
|            9 |     5343 | 2024-10-08 | The MongolZ  | W   | 0.222      | 0.624        | 1.000 (0.139)    | -                | -         |     3.17 | apEX, flameZ, mezii, Spinx, ZywOo |
|            8 |     5396 | 2024-10-07 | 9z Team      | W   | 0.216      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |
|            7 |     5946 | 2024-09-28 | G2 Esports   | L   | 0.156      | -            | -                | -                | -         |    -3.81 | apEX, flameZ, mezii, Spinx, ZywOo |
|            6 |     6080 | 2024-09-26 | Team Liquid  | W   | 0.144      | -            | -                | -                | -         |     0.10 | apEX, flameZ, mezii, Spinx, ZywOo |
|            5 |     6193 | 2024-09-25 | Astralis     | W   | 0.136      | 0.729        | 0.734 (0.073)    | 0.811 (0.081)    | -         |     1.98 | apEX, flameZ, mezii, Spinx, ZywOo |
|            4 |     6591 | 2024-09-19 | Eternal Fire | L   | 0.097      | -            | -                | -                | -         |    -1.38 | apEX, flameZ, mezii, Spinx, ZywOo |
|            3 |     6820 | 2024-09-15 | Team Liquid  | W   | 0.070      | -            | -                | -                | -         |     0.05 | apEX, flameZ, mezii, Spinx, ZywOo |
|            2 |     7029 | 2024-09-12 | FURIA        | W   | 0.049      | -            | -                | -                | -         |     0.03 | apEX, flameZ, mezii, Spinx, ZywOo |
|            1 |     7090 | 2024-09-11 | ATOX Esports | W   | 0.042      | -            | -                | -                | -         |     0.01 | apEX, flameZ, mezii, Spinx, ZywOo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($449,904.61)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $400,000.00    | $400,000.00     |
| 2025-01-26 |      0.956 | $3,750.00      | $3,586.12       |
| 2024-11-03 |      0.395 | $85,000.00     | $33,543.70      |
| 2024-10-13 |      0.257 | $10,000.00     | $2,565.76       |
| 2024-09-29 |      0.162 | $40,000.00     | $6,496.38       |
| 2024-09-22 |      0.116 | $32,000.00     | $3,712.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
