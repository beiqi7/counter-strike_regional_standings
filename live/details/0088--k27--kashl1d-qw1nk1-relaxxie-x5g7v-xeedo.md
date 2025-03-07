### Roster Details<br />
Team Name: K27<br />
Roster: kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.2<br />
<br />
Final Rank Value (861.2) = Starting Rank Value (986.8) + Head To Head Adjustments (-125.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.329[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.426[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.8
- 400 + ( ( 0.266 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 986.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |      178 | 2025-02-23 | Inner Circle Esports  | L   | 0.765      | -            | -                | -                | -         |   -20.67 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           58 |      188 | 2025-02-23 | MASONIC               | W   | 0.765      | -            | -                | -                | 0 (0.000) |     5.58 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           57 |      220 | 2025-02-22 | RUBY                  | W   | 0.760      | -            | -                | -                | 0 (0.000) |     3.32 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           56 |      322 | 2025-02-20 | AMKAL ESPORTS         | L   | 0.749      | -            | -                | -                | -         |   -16.28 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           55 |      463 | 2025-02-16 | Nuclear TigeRES       | W   | 0.727      | 0.143        | 0.004 (0.001)    | 0.431 (0.054)    | 1 (0.873) |     9.35 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           54 |      468 | 2025-02-16 | Underrated            | W   | 0.727      | 0.143        | 0.002 (0.000)    | 0.219 (0.027)    | 1 (0.872) |     6.58 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           53 |      480 | 2025-02-16 | NewBALLS              | W   | 0.725      | -            | -                | -                | 1 (0.870) |     5.89 | kashl1d, qw1nk1, relaxxie, X5G7V, XeeDo   |
|           52 |      726 | 2025-02-09 | Flame Sharks          | L   | 0.688      | -            | -                | -                | -         |   -18.12 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           51 |      730 | 2025-02-09 | Duxes                 | W   | 0.688      | -            | -                | -                | 0 (0.000) |     1.34 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           50 |      857 | 2025-02-07 | Aurora Gaming         | L   | 0.678      | -            | -                | -                | -         |   -12.42 | aliot, kashl1d, qw1nk1, xdENiSZERA, XeeDo |
|           49 |      972 | 2025-02-05 | NewBALLS              | L   | 0.666      | -            | -                | -                | -         |   -16.63 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           48 |     1083 | 2025-02-04 | Bad News Eagles       | L   | 0.659      | -            | -                | -                | -         |   -18.24 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           47 |     1099 | 2025-02-04 | Chimera Esports       | W   | 0.659      | 0.143        | 0.023 (0.003)    | 0.430 (0.049)    | 0 (0.000) |     8.81 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           46 |     1734 | 2024-12-20 | Mission Possible      | L   | 0.405      | -            | -                | -                | -         |   -11.58 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           45 |     1742 | 2024-12-20 | Minsk House           | W   | 0.405      | -            | -                | -                | 0 (0.000) |     1.05 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           44 |     1777 | 2024-12-19 | FORZE Reload          | L   | 0.398      | -            | -                | -                | -         |    -7.58 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           43 |     1912 | 2024-12-14 | Viperio               | W   | 0.372      | 0.333        | 0.002 (0.000)    | 0.325 (0.048)    | 0 (0.000) |     3.40 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           42 |     1946 | 2024-12-14 | LEON Esports          | L   | 0.370      | -            | -                | -                | -         |    -8.34 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           41 |     1954 | 2024-12-14 | RUSH B (Russian team) | L   | 0.370      | -            | -                | -                | -         |    -5.91 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           40 |     2073 | 2024-12-12 | AMKAL ESPORTS         | L   | 0.358      | -            | -                | -                | -         |    -7.99 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           39 |     2150 | 2024-12-10 | JANO Esports          | W   | 0.349      | 0.333        | 0.019 (0.003)    | 0.430 (0.060)    | 0 (0.000) |     5.13 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           38 |     2187 | 2024-12-09 | BC.Game Esports       | W   | 0.342      | 0.333        | 0.021 (0.003)    | 0.432 (0.059)    | -         |     3.83 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           37 |     2612 | 2024-11-30 | ARCRED                | L   | 0.294      | -            | -                | -                | -         |    -6.23 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           36 |     2618 | 2024-11-30 | Betera Esports        | W   | 0.294      | 0.262        | 0.004 (0.000)    | -                | -         |     2.15 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           35 |     2646 | 2024-11-30 | HOTU                  | W   | 0.294      | 0.262        | -                | 0.588 (0.054)    | -         |     2.10 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           34 |     2931 | 2024-11-24 | HOTU                  | W   | 0.258      | 0.143        | -                | 0.588 (0.026)    | -         |     1.79 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           33 |     2999 | 2024-11-23 | Nuclear TigeRES       | L   | 0.254      | -            | -                | -                | -         |    -5.24 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           32 |     3010 | 2024-11-23 | Haspers Team          | L   | 0.253      | -            | -                | -                | -         |    -6.45 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           31 |     3223 | 2024-11-20 | Fire Flux Esports     | L   | 0.238      | -            | -                | -                | -         |    -4.27 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           30 |     3289 | 2024-11-19 | 500                   | L   | 0.231      | -            | -                | -                | -         |    -2.85 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           29 |     3331 | 2024-11-18 | RUSTEC                | W   | 0.226      | -            | -                | -                | -         |     1.10 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           28 |     3336 | 2024-11-18 | Ex-RUBY               | W   | 0.226      | -            | -                | -                | -         |     0.58 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           27 |     3369 | 2024-11-17 | RUSTEC                | W   | 0.221      | -            | -                | -                | -         |     0.57 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           26 |     3447 | 2024-11-16 | XGOD ARENA            | W   | 0.215      | -            | -                | -                | -         |     0.80 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           25 |     3458 | 2024-11-16 | FORZE Reload          | L   | 0.214      | -            | -                | -                | -         |    -4.67 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           24 |     3491 | 2024-11-15 | FLuffy Gangsters      | L   | 0.210      | -            | -                | -                | -         |    -4.99 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           23 |     3496 | 2024-11-15 | Leo Team              | W   | 0.210      | 0.372        | 0.020 (0.002)    | 0.553 (0.052)    | -         |     2.01 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           22 |     3561 | 2024-11-14 | 1win                  | W   | 0.204      | 0.372        | -                | 0.281 (0.026)    | -         |     1.35 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           21 |     3637 | 2024-11-12 | Poslednii3ae3d        | L   | 0.194      | -            | -                | -                | -         |    -5.33 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           20 |     4079 | 2024-11-04 | QUAZAR Academy        | W   | 0.148      | -            | -                | -                | -         |     0.18 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           19 |     4083 | 2024-11-04 | 4z                    | W   | 0.147      | -            | -                | -                | -         |     0.74 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           18 |     4366 | 2024-10-30 | GamerLegion Academy   | W   | 0.121      | -            | -                | -                | -         |     0.28 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           17 |     4550 | 2024-10-27 | RUSH B (Russian team) | L   | 0.104      | -            | -                | -                | -         |    -1.82 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           16 |     4636 | 2024-10-26 | Hyuga                 | L   | 0.097      | -            | -                | -                | -         |    -2.86 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           15 |     4755 | 2024-10-23 | Nexus Gaming          | L   | 0.082      | -            | -                | -                | -         |    -0.75 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           14 |     4765 | 2024-10-23 | ARCRED                | L   | 0.081      | -            | -                | -                | -         |    -1.83 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           13 |     4800 | 2024-10-22 | Underrated            | W   | 0.076      | -            | -                | -                | -         |     0.44 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           12 |     4807 | 2024-10-22 | NewBALLS              | W   | 0.076      | -            | -                | -                | -         |     0.34 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           11 |     4847 | 2024-10-21 | ARCRED                | L   | 0.071      | -            | -                | -                | -         |    -1.59 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|           10 |     4852 | 2024-10-21 | Team Spirit Academy   | L   | 0.070      | -            | -                | -                | -         |    -1.21 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            9 |     4860 | 2024-10-21 | Nexus Gaming          | W   | 0.069      | 0.333        | 0.161 (0.004)    | -                | -         |     1.54 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            8 |     4875 | 2024-10-20 | HOTU                  | W   | 0.065      | -            | -                | -                | -         |     0.39 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            7 |     4893 | 2024-10-20 | BC.Game Esports       | W   | 0.065      | 0.143        | 0.021 (0.000)    | -                | -         |     0.58 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            6 |     4923 | 2024-10-20 | Viperio               | W   | 0.064      | -            | -                | -                | -         |     0.41 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            5 |     4936 | 2024-10-19 | Kay Team              | L   | 0.060      | -            | -                | -                | -         |    -1.77 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            4 |     5014 | 2024-10-18 | FORZE Reload          | L   | 0.052      | -            | -                | -                | -         |    -1.16 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            3 |     5033 | 2024-10-17 | FLuffy Gangsters      | W   | 0.049      | -            | -                | -                | -         |     0.36 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            2 |     5094 | 2024-10-16 | RUSTEC                | W   | 0.043      | -            | -                | -                | -         |     0.10 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |
|            1 |     5209 | 2024-10-15 | BC.Game Esports       | L   | 0.036      | -            | -                | -                | -         |    -0.83 | aliot, kashl1d, qw1nk1, relaxxie, XeeDo   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,912.49)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-16 |      0.873 | $1,225.82      | $1,070.12       |
| 2024-12-15 |      0.452 | $968.43        | $437.45         |
| 2024-11-30 |      0.353 | $500.00        | $176.52         |
| 2024-11-03 |      0.172 | $1,021.74      | $175.97         |
| 2024-10-24 |      0.105 | $500.00        | $52.43          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
