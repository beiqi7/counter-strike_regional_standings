### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: fineshine, Lack1, Sdaim, SELLTER, xiELO<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  962.3<br />
<br />
Final Rank Value (962.3) = Starting Rank Value (990.3) + Head To Head Adjustments (-28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.219[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.3
- 400 + ( ( 0.268 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 990.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |       32 | 2025-02-27 | Fire Flux Esports      | W   | 0.787      | 0.435        | -                | 1.000 (0.411)    | 0 (0.000) |    11.49 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           50 |       71 | 2025-02-26 | FAVBET Team            | L   | 0.783      | -            | -                | -                | -         |   -14.93 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           49 |      225 | 2025-02-22 | Natus Vincere Junior   | L   | 0.760      | -            | -                | -                | -         |   -11.94 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           48 |      283 | 2025-02-21 | Passion UA             | W   | 0.754      | 0.435        | -                | 0.262 (0.103)    | 0 (0.000) |     9.90 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           47 |      359 | 2025-02-19 | GameAgents             | L   | 0.744      | -            | -                | -                | -         |   -19.31 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           46 |      422 | 2025-02-17 | BC.Game Esports        | W   | 0.732      | 0.435        | 0.061 (0.023)    | 1.000 (0.382)    | 0 (0.000) |    15.41 | fineshine, Sdaim, SELLTER, xiELO        |
|           45 |      532 | 2025-02-15 | 9INE                   | L   | 0.721      | -            | -                | -                | -         |   -12.19 | fineshine, Sdaim, SELLTER, xiELO        |
|           44 |      621 | 2025-02-13 | RUSH B (Russian team)  | W   | 0.708      | 0.435        | 0.026 (0.010)    | 0.901 (0.333)    | 0 (0.000) |    10.45 | fineshine, Sdaim, SELLTER, xiELO        |
|           43 |      637 | 2025-02-12 | B8                     | L   | 0.703      | -            | -                | -                | -         |    -7.67 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           42 |      695 | 2025-02-10 | SINNERS Esports        | W   | 0.693      | 0.435        | 0.016 (0.006)    | 0.494 (0.179)    | 0 (0.000) |     8.84 | fineshine, Sdaim, SELLTER, xiELO        |
|           41 |      875 | 2025-02-07 | Hesta                  | L   | 0.677      | -            | -                | -                | -         |   -17.00 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           40 |     1236 | 2025-01-28 | Aurora Gaming          | W   | 0.622      | 0.500        | -                | 0.633 (0.236)    | 0 (0.000) |     5.29 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           39 |     1322 | 2025-01-24 | Rebels Gaming          | L   | 0.599      | -            | -                | -                | -         |   -14.72 | easy, Lack1, Sdaim, SELLTER, xiELO      |
|           38 |     1393 | 2025-01-22 | Natus Vincere Junior   | L   | 0.588      | -            | -                | -                | -         |    -9.49 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           37 |     1806 | 2024-12-17 | Dynamo Eclot           | W   | 0.388      | 0.435        | 0.114 (0.023)    | -                | 0 (0.000) |     6.50 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           36 |     1818 | 2024-12-17 | Natus Vincere Junior   | W   | 0.386      | 0.371        | 0.078 (0.013)    | 0.786 (0.135)    | 0 (0.000) |     6.33 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           35 |     1823 | 2024-12-16 | Natus Vincere Junior   | W   | 0.383      | 0.435        | 0.078 (0.016)    | 0.786 (0.157)    | 0 (0.000) |     6.50 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           34 |     1837 | 2024-12-16 | Chimera Esports        | W   | 0.381      | -            | -                | -                | 0 (0.000) |     4.47 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           33 |     1881 | 2024-12-15 | Natus Vincere Junior   | L   | 0.375      | -            | -                | -                | -         |    -5.49 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           32 |     2044 | 2024-12-13 | Iberian Soul           | W   | 0.364      | -            | -                | -                | -         |     3.91 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           31 |     2067 | 2024-12-12 | Chimera Esports        | L   | 0.360      | -            | -                | -                | -         |    -7.46 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           30 |     2102 | 2024-12-11 | Aurora Gaming          | W   | 0.355      | 0.435        | -                | 0.633 (0.117)    | -         |     3.23 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           29 |     2135 | 2024-12-10 | Sashi Esport           | W   | 0.349      | -            | -                | -                | -         |     5.42 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           28 |     2162 | 2024-12-10 | 9INE                   | W   | 0.347      | 0.371        | 0.039 (0.006)    | 0.876 (0.135)    | -         |     4.50 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           27 |     2179 | 2024-12-09 | Monte                  | L   | 0.343      | -            | -                | -                | -         |    -7.79 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           26 |     2426 | 2024-12-04 | Chimera Esports        | W   | 0.315      | -            | -                | -                | -         |     3.07 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           25 |     2683 | 2024-11-30 | BC.Game Esports        | W   | 0.291      | -            | -                | -                | -         |     2.97 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           24 |     2750 | 2024-11-28 | Tricked Esport         | L   | 0.282      | -            | -                | -                | -         |    -6.05 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           23 |     2760 | 2024-11-28 | Iberian Soul           | W   | 0.282      | -            | -                | -                | -         |     3.01 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           22 |     2796 | 2024-11-27 | Betclic Apogee Esports | L   | 0.276      | -            | -                | -                | -         |    -5.78 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           21 |     3658 | 2024-11-12 | 500                    | L   | 0.191      | -            | -                | -                | -         |    -2.56 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           20 |     3718 | 2024-11-11 | BIG                    | W   | 0.186      | 0.384        | 0.234 (0.020)    | -                | -         |     5.36 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           19 |     3769 | 2024-11-10 | 9INE                   | W   | 0.180      | -            | -                | -                | -         |     0.89 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           18 |     3793 | 2024-11-09 | Zero Tenacity          | L   | 0.177      | -            | -                | -                | -         |    -3.48 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           17 |     4087 | 2024-11-04 | Dynamo Eclot           | W   | 0.147      | 0.384        | 0.114 (0.008)    | -                | -         |     2.55 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           16 |     4140 | 2024-11-03 | Dynamo Eclot           | L   | 0.142      | -            | -                | -                | -         |    -2.03 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           15 |     4204 | 2024-11-02 | ECSTATIC               | W   | 0.137      | -            | -                | -                | -         |     1.51 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           14 |     4306 | 2024-10-31 | 500                    | W   | 0.127      | 0.384        | 0.118 (0.007)    | -                | -         |     2.35 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           13 |     4398 | 2024-10-30 | Wild Lotus             | L   | 0.120      | -            | -                | -                | -         |    -3.40 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           12 |     4465 | 2024-10-29 | Sashi Esport           | W   | 0.114      | -            | -                | -                | -         |     1.74 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           11 |     4586 | 2024-10-26 | FLuffy Gangsters       | L   | 0.099      | -            | -                | -                | -         |    -2.41 | mo0N, Sdaim, SELLTER, tN1R, xiELO       |
|           10 |     4645 | 2024-10-26 | Dynamo Eclot           | W   | 0.097      | -            | -                | -                | -         |     1.66 | easy, Sdaim, SELLTER, Xant3r, xiELO     |
|            9 |     4723 | 2024-10-24 | Insilio                | W   | 0.086      | -            | -                | -                | -         |     0.27 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            8 |     4763 | 2024-10-23 | Nuclear TigeRES        | L   | 0.082      | -            | -                | -                | -         |    -1.70 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            7 |     4812 | 2024-10-22 | WW Team                | W   | 0.075      | -            | -                | -                | -         |     0.08 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            6 |     4848 | 2024-10-21 | FLuffy Gangsters       | W   | 0.071      | -            | -                | -                | -         |     0.51 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            5 |     5217 | 2024-10-15 | Tricked Esport         | L   | 0.035      | -            | -                | -                | -         |    -0.80 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            4 |     5281 | 2024-10-13 | Wild Lotus             | W   | 0.026      | -            | -                | -                | -         |     0.08 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            3 |     5329 | 2024-10-12 | SINNERS Esports        | L   | 0.021      | -            | -                | -                | -         |    -0.38 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            2 |     5402 | 2024-10-11 | GamerLegion            | W   | 0.015      | -            | -                | -                | -         |     0.45 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            1 |     5432 | 2024-10-10 | Los kogutos            | L   | 0.009      | -            | -                | -                | -         |    -0.18 | easy, Norwi, Sdaim, SELLTER, xiELO      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,953.50)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      0.939 | $500.00        | $469.58         |
| 2025-02-23 |      0.919 | $2,000.00      | $1,837.41       |
| 2024-12-17 |      0.466 | $30,000.00     | $13,966.67      |
| 2024-12-17 |      0.463 | $11,000.00     | $5,093.61       |
| 2024-11-12 |      0.232 | $1,500.00      | $347.26         |
| 2024-11-03 |      0.172 | $1,021.74      | $175.97         |
| 2024-10-13 |      0.032 | $2,000.00      | $63.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
