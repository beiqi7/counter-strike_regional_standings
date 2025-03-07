### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, Spinx, torzsi, xertioN<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1942.4<br />
<br />
Final Rank Value (1942.4) = Starting Rank Value (2000.0) + Head To Head Adjustments (-57.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.642[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.725<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.725 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 2000.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      174 | 2025-02-23 | Team Falcons  | W   | 0.766      | 1.000        | 1.000 (0.919)    | 0.495 (0.455)    | 1 (0.919) |    11.24 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           20 |      231 | 2025-02-22 | Astralis      | W   | 0.759      | 1.000        | 0.788 (0.719)    | 0.807 (0.736)    | 1 (0.911) |     7.74 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           19 |      294 | 2025-02-21 | PaiN Gaming   | W   | 0.752      | 1.000        | 0.357 (0.322)    | 0.371 (0.335)    | 1 (0.903) |     4.34 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           18 |      399 | 2025-02-18 | Virtus.pro    | W   | 0.737      | 1.000        | 0.320 (0.283)    | 0.352 (0.311)    | 1 (0.884) |     3.89 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           17 |      440 | 2025-02-17 | Team Falcons  | L   | 0.731      | -            | -                | -                | -         |   -12.70 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           16 |      476 | 2025-02-16 | FaZe Clan     | L   | 0.726      | -            | -                | -                | -         |   -14.88 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           15 |      549 | 2025-02-15 | 3DMAX         | W   | 0.719      | 1.000        | 0.261 (0.225)    | 0.383 (0.331)    | 1 (0.863) |     2.45 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           14 |      600 | 2025-02-14 | BIG           | W   | 0.713      | 1.000        | 0.234 (0.200)    | 0.400 (0.343)    | 1 (0.856) |     0.72 | Brollan, Jimpphat, Spinx, torzsi, xertioN |
|           13 |     1120 | 2025-02-03 | Team Liquid   | L   | 0.653      | -            | -                | -                | -         |   -20.32 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           12 |     1147 | 2025-02-01 | GamerLegion   | L   | 0.643      | -            | -                | -                | -         |   -18.45 | Brollan, Jimpphat, torzsi, xelex, xertioN |
|           11 |     1447 | 2025-01-17 | BetBoom Team  | L   | 0.560      | -            | -                | -                | -         |   -17.57 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3347 | 2024-11-17 | Natus Vincere | W   | 0.224      | 0.143        | 0.420 (0.016)    | 0.321 (0.012)    | 1 (0.269) |     0.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3387 | 2024-11-17 | HEROIC        | W   | 0.220      | 0.143        | 0.120 (0.005)    | 0.372 (0.014)    | 1 (0.264) |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3412 | 2024-11-16 | Nemiga Gaming | W   | 0.218      | 0.143        | -                | 0.313 (0.012)    | 1 (0.262) |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     4275 | 2024-11-01 | Team Vitality | L   | 0.130      | -            | -                | -                | -         |    -2.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     4325 | 2024-10-31 | Astralis      | L   | 0.125      | -            | -                | -                | -         |    -2.39 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4404 | 2024-10-30 | FaZe Clan     | W   | 0.119      | 1.000        | 0.498 (0.071)    | 0.354 (0.051)    | 1 (0.143) |     1.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     5267 | 2024-10-13 | Natus Vincere | L   | 0.026      | -            | -                | -                | -         |    -0.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     5325 | 2024-10-12 | FURIA         | W   | 0.021      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     5389 | 2024-10-11 | Team Vitality | W   | 0.016      | 0.624        | 1.000 (0.012)    | -                | -         |     0.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     5481 | 2024-10-09 | FaZe Clan     | W   | 0.005      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($381,360.09)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $400,000.00    | $367,537.04     |
| 2025-02-09 |      0.825 | $10,000.00     | $8,250.00       |
| 2024-11-03 |      0.170 | $25,000.00     | $4,243.06       |
| 2024-10-13 |      0.032 | $42,000.00     | $1,330.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
