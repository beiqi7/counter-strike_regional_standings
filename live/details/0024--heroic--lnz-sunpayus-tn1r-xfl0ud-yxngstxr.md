### Roster Details<br />
Team Name: HEROIC<br />
Roster: LNZ, SunPayus, tN1R, xfl0ud, yxngstxr<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1113.4<br />
<br />
Final Rank Value (1113.4) = Starting Rank Value (1038.8) + Head To Head Adjustments (74.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.520[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.183[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1038.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1038.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      329 | 2025-02-20 | Astralis        | W   | 0.748      | 0.143        | 0.788 (0.101)    | 0.807 (0.103)    | 0 (0.000) |    23.10 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           23 |      657 | 2025-02-11 | Metizport       | W   | 0.699      | 0.143        | 0.062 (0.007)    | 0.367 (0.044)    | 0 (0.000) |     8.08 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           22 |      665 | 2025-02-11 | BIG             | W   | 0.697      | 0.143        | 0.234 (0.028)    | 0.400 (0.048)    | 0 (0.000) |    18.07 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           21 |      685 | 2025-02-10 | 3DMAX           | L   | 0.694      | -            | -                | -                | -         |    -1.35 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           20 |      698 | 2025-02-10 | Zero Tenacity   | W   | 0.692      | 0.143        | 0.020 (0.002)    | 0.778 (0.092)    | 0 (0.000) |     5.92 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           19 |      745 | 2025-02-09 | PARIVISION      | L   | 0.686      | -            | -                | -                | -         |   -17.49 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           18 |      820 | 2025-02-08 | Passion UA      | W   | 0.681      | 0.143        | -                | 0.262 (0.031)    | 0 (0.000) |     6.37 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           17 |     1186 | 2025-01-31 | BIG             | L   | 0.637      | -            | -                | -                | -         |    -2.88 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           16 |     1189 | 2025-01-30 | Eternal Fire    | L   | 0.632      | -            | -                | -                | -         |    -0.17 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           15 |     1200 | 2025-01-29 | Team Liquid     | W   | 0.627      | 1.000        | 0.075 (0.056)    | 0.180 (0.136)    | 1 (0.752) |    12.63 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           14 |     1364 | 2025-01-23 | Team Spirit     | L   | 0.593      | -            | -                | -                | -         |    -0.12 | LNZ, maden, SunPayus, xfl0ud, yxngstxr |
|           13 |     1443 | 2025-01-18 | Team Liquid     | W   | 0.564      | 0.363        | 0.075 (0.018)    | 0.180 (0.044)    | 0 (0.000) |    11.93 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           12 |     1464 | 2025-01-14 | 3DMAX           | W   | 0.542      | 0.363        | 0.261 (0.062)    | 0.383 (0.090)    | -         |    16.20 | LNZ, SunPayus, tN1R, xfl0ud, yxngstxr  |
|           11 |     3306 | 2024-11-18 | Dynamo Eclot    | L   | 0.229      | -            | -                | -                | -         |    -3.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|           10 |     3350 | 2024-11-17 | Cloud9          | L   | 0.224      | -            | -                | -                | -         |    -6.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            9 |     3387 | 2024-11-17 | MOUZ            | L   | 0.220      | -            | -                | -                | -         |    -0.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            8 |     3407 | 2024-11-16 | Rebels Gaming   | W   | 0.219      | 0.143        | -                | 0.396 (0.015)    | 1 (0.263) |     1.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            7 |     4901 | 2024-10-20 | Nemiga Gaming   | W   | 0.065      | 0.500        | 0.074 (0.003)    | -                | -         |     0.83 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            6 |     4960 | 2024-10-19 | BC.Game Esports | L   | 0.059      | -            | -                | -                | -         |    -0.99 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            5 |     5037 | 2024-10-17 | Nemiga Gaming   | W   | 0.049      | -            | -                | -                | -         |     0.61 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            4 |     5057 | 2024-10-17 | Fluxo           | W   | 0.047      | 0.624        | -                | 0.411 (0.015)    | 1 (0.057) |     0.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            3 |     5122 | 2024-10-16 | SAW             | W   | 0.043      | 0.500        | 0.316 (0.008)    | -                | -         |     1.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            2 |     5148 | 2024-10-16 | Nemiga Gaming   | W   | 0.042      | 0.624        | 0.074 (0.002)    | -                | 1 (0.050) |     0.53 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |
|            1 |     5192 | 2024-10-15 | Sashi Esport    | W   | 0.037      | -            | -                | -                | -         |     0.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,119.79)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $4,500.00      | $3,712.50       |
| 2025-01-26 |      0.731 | $25,000.00     | $18,284.72      |
| 2024-10-20 |      0.078 | $17,000.00     | $1,322.22       |
| 2024-10-19 |      0.072 | $25,000.00     | $1,800.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
