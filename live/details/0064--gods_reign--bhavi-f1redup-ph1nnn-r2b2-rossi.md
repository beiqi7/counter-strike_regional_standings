### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, f1redup, Ph1NNN, R2B2, Rossi<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  903.2<br />
<br />
Final Rank Value (903.2) = Starting Rank Value (925.0) + Head To Head Adjustments (-21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.321[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.0
- 400 + ( ( 0.238 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 925.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       21 | 2025-02-27 | Flashback Gaming        | W   | 0.791      | 0.143        | 0.006 (0.001)    | 0.115 (0.016)    | 1 (0.949) |     9.61 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           27 |       36 | 2025-02-27 | Victores Sumus          | W   | 0.786      | 0.143        | 0.009 (0.001)    | 0.115 (0.016)    | 1 (0.943) |     6.85 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           26 |      134 | 2025-02-24 | ATOX Esports            | L   | 0.773      | -            | -                | -                | -         |    -7.27 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           25 |      158 | 2025-02-23 | Nomads (Mongolian team) | L   | 0.768      | -            | -                | -                | -         |   -21.16 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           24 |      707 | 2025-02-09 | Unsettled Resentment    | L   | 0.691      | -            | -                | -                | -         |   -16.08 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           23 |      750 | 2025-02-08 | Unsettled Resentment    | W   | 0.685      | 0.143        | 0.013 (0.002)    | 0.198 (0.023)    | 0 (0.000) |     5.43 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           22 |      828 | 2025-02-07 | Only One Word           | W   | 0.679      | 0.143        | -                | 0.170 (0.020)    | 0 (0.000) |     3.98 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           21 |     1519 | 2024-12-29 | Flashback Gaming        | W   | 0.454      | 0.143        | 0.006 (0.000)    | 0.115 (0.009)    | 0 (0.000) |     5.39 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           20 |     1523 | 2024-12-29 | Red Viperz              | W   | 0.454      | -            | -                | -                | 0 (0.000) |     0.75 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           19 |     1963 | 2024-12-14 | Big W                   | W   | 0.369      | 0.262        | 0.005 (0.001)    | 0.050 (0.006)    | 0 (0.000) |     2.82 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           18 |     1970 | 2024-12-13 | Victores Sumus          | W   | 0.368      | 0.262        | 0.009 (0.001)    | 0.115 (0.013)    | 0 (0.000) |     3.49 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           17 |     2207 | 2024-12-08 | Impact (Pakistani team) | W   | 0.338      | 0.270        | 0.001 (0.000)    | -                | 0 (0.000) |     1.20 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           16 |     2231 | 2024-12-08 | Flashback Gaming        | W   | 0.337      | 0.270        | 0.006 (0.001)    | 0.115 (0.013)    | -         |     4.17 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           15 |     2313 | 2024-12-07 | PPeeks                  | W   | 0.332      | -            | -                | -                | -         |     0.59 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           14 |     2678 | 2024-11-30 | Real Original Gaming    | L   | 0.292      | -            | -                | -                | -         |    -6.78 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           13 |     2920 | 2024-11-24 | Half Of Devil           | W   | 0.259      | 0.333        | 0.002 (0.000)    | 0.018 (0.002)    | -         |     1.48 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           12 |     3016 | 2024-11-23 | SUBUTAI                 | W   | 0.253      | -            | -                | -                | -         |     0.87 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|           11 |     3300 | 2024-11-18 | St4rboys                | L   | 0.230      | -            | -                | -                | -         |    -5.83 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|           10 |     3301 | 2024-11-18 | Indian Gamers           | W   | 0.230      | -            | -                | -                | -         |     0.39 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|            9 |     3464 | 2024-11-16 | Big W                   | L   | 0.214      | -            | -                | -                | -         |    -5.17 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|            8 |     3965 | 2024-11-06 | Clutch Gaming           | L   | 0.158      | -            | -                | -                | -         |    -4.51 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|            7 |     3968 | 2024-11-05 | The Huns Esports        | L   | 0.157      | -            | -                | -                | -         |    -2.42 | Bhavi, f1redup, Ph1NNN, R2B2, Rossi    |
|            6 |     4572 | 2024-10-27 | Big W                   | W   | 0.102      | 0.262        | 0.005 (0.000)    | 0.050 (0.002)    | -         |     0.72 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            5 |     4573 | 2024-10-26 | St4rboys                | W   | 0.102      | -            | -                | -                | -         |     0.59 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            4 |     4924 | 2024-10-20 | True Rippers Esports    | W   | 0.063      | -            | -                | -                | 1 (0.076) |     0.10 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            3 |     5212 | 2024-10-15 | SayGGTeam               | L   | 0.036      | -            | -                | -                | -         |    -0.92 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            2 |     5507 | 2024-10-09 | DEWA United             | L   | 0.003      | -            | -                | -                | -         |    -0.09 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |
|            1 |     5513 | 2024-10-09 | DEWA United             | W   | 0.003      | -            | -                | -                | -         |     0.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,851.33)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-28 |      0.950 | $2,863.20      | $2,719.64       |
| 2024-12-29 |      0.545 | $340.32        | $185.58         |
| 2024-12-14 |      0.443 | $1,000.00      | $442.87         |
| 2024-12-08 |      0.406 | $1,000.00      | $405.69         |
| 2024-11-30 |      0.351 | $2,000.00      | $701.11         |
| 2024-11-18 |      0.276 | $500.00        | $137.99         |
| 2024-11-03 |      0.170 | $800.00        | $135.74         |
| 2024-10-27 |      0.123 | $1,000.00      | $122.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
