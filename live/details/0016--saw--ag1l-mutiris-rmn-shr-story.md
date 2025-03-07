### Roster Details<br />
Team Name: SAW<br />
Roster: Ag1l, MUTiRiS, rmn, shr, story<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1325.4<br />
<br />
Final Rank Value (1325.4) = Starting Rank Value (1366.5) + Head To Head Adjustments (-41.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.667[<sup>1</sup>](#table2)
- Bounty Collected: 0.420[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.593[<sup>2</sup>](#table1)

The average of these factors is 0.438<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1366.5
- 400 + ( ( 0.438 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1366.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      271 | 2025-02-21 | FaZe Clan       | L   | 0.755      | -            | -                | -                | -         |    -1.29 | Ag1l, MUTiRiS, rmn, shr, story     |
|           23 |      401 | 2025-02-18 | 3DMAX           | W   | 0.736      | 1.000        | 0.261 (0.230)    | 0.383 (0.339)    | 1 (0.883) |    18.41 | Ag1l, MUTiRiS, rmn, shr, story     |
|           22 |      419 | 2025-02-17 | Complexity      | W   | 0.733      | 1.000        | 0.092 (0.081)    | 0.102 (0.090)    | 1 (0.879) |     2.60 | Ag1l, MUTiRiS, rmn, shr, story     |
|           21 |      475 | 2025-02-16 | FlyQuest        | W   | 0.726      | 1.000        | 0.096 (0.084)    | 0.190 (0.166)    | 1 (0.871) |     6.29 | Ag1l, MUTiRiS, rmn, shr, story     |
|           20 |      531 | 2025-02-15 | Astralis        | L   | 0.721      | -            | -                | -                | -         |    -1.22 | Ag1l, MUTiRiS, rmn, shr, story     |
|           19 |      595 | 2025-02-14 | FaZe Clan       | L   | 0.714      | -            | -                | -                | -         |    -1.26 | Ag1l, MUTiRiS, rmn, shr, story     |
|           18 |      940 | 2025-02-06 | 500             | L   | 0.669      | -            | -                | -                | -         |   -17.61 | Ag1l, MUTiRiS, rmn, shr, story     |
|           17 |      998 | 2025-02-05 | Eco Warriors    | W   | 0.665      | 0.143        | -                | 0.198 (0.023)    | 0 (0.000) |     0.30 | Ag1l, MUTiRiS, rmn, shr, story     |
|           16 |     1007 | 2025-02-05 | BC.Game Esports | L   | 0.664      | -            | -                | -                | -         |   -17.68 | Ag1l, MUTiRiS, rmn, shr, story     |
|           15 |     1196 | 2025-01-30 | Virtus.pro      | L   | 0.631      | -            | -                | -                | -         |    -3.16 | Ag1l, MUTiRiS, rmn, shr, story     |
|           14 |     1206 | 2025-01-29 | GamerLegion     | L   | 0.625      | -            | -                | -                | -         |    -4.98 | Ag1l, MUTiRiS, rmn, shr, story     |
|           13 |     1460 | 2025-01-15 | BIG             | L   | 0.548      | -            | -                | -                | -         |    -7.30 | Ag1l, MUTiRiS, rmn, shr, story     |
|           12 |     3260 | 2024-11-19 | BetBoom Team    | L   | 0.234      | -            | -                | -                | -         |    -6.48 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|           11 |     3303 | 2024-11-18 | Natus Vincere   | L   | 0.229      | -            | -                | -                | -         |    -1.80 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|           10 |     3349 | 2024-11-17 | Team Falcons    | W   | 0.224      | 0.143        | 0.001 (0.000)    | -                | 1 (0.269) |     0.17 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            9 |     3384 | 2024-11-17 | UNiTY esports   | W   | 0.220      | 0.143        | 0.019 (0.001)    | 0.213 (0.008)    | 1 (0.264) |     0.27 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            8 |     3409 | 2024-11-16 | SINNERS Esports | L   | 0.219      | -            | -                | -                | -         |    -6.31 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            7 |     4538 | 2024-10-27 | B8              | W   | 0.105      | 0.500        | 0.134 (0.008)    | 0.740 (0.046)    | 1 (0.125) |     0.68 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            6 |     4560 | 2024-10-27 | Monte           | W   | 0.103      | 0.500        | 0.023 (0.001)    | 0.108 (0.007)    | 1 (0.124) |     0.14 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            5 |     4681 | 2024-10-25 | B8              | W   | 0.093      | 0.500        | 0.134 (0.007)    | 0.740 (0.041)    | 1 (0.111) |     0.59 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            4 |     4693 | 2024-10-25 | Team Falcons    | W   | 0.092      | 0.500        | 0.001 (0.000)    | 0.016 (0.001)    | 1 (0.110) |     0.07 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            3 |     4997 | 2024-10-18 | 3DMAX           | L   | 0.054      | -            | -                | -                | -         |    -0.44 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            2 |     5038 | 2024-10-17 | 9Pandas         | W   | 0.049      | 0.500        | 0.084 (0.002)    | 0.481 (0.014)    | -         |     0.17 | Ag1l, ewjerkz, MUTiRiS, rmn, story |
|            1 |     5122 | 2024-10-16 | HEROIC          | L   | 0.043      | -            | -                | -                | -         |    -1.17 | Ag1l, ewjerkz, MUTiRiS, rmn, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,424.42)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $62,500.00     | $57,427.66      |
| 2025-02-09 |      0.825 | $2,500.00      | $2,062.50       |
| 2024-10-27 |      0.125 | $50,000.00     | $6,273.15       |
| 2024-10-20 |      0.078 | $8,500.00      | $661.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
