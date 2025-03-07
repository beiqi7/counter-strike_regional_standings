### Roster Details<br />
Team Name: BESTIA<br />
Roster: cass1n, leo_drk, luchov, Noktse, tomaszin<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  856.1<br />
<br />
Final Rank Value (856.1) = Starting Rank Value (868.4) + Head To Head Adjustments (-12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.127[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.212<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.4
- 400 + ( ( 0.212 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 868.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      104 | 2025-02-25 | Sharks Esports           | L   | 0.778      | -            | -                | -                | -         |    -6.05 | cass1n, leo_drk, luchov, Noktse, tomaszin |
|           35 |      106 | 2025-02-25 | Sharks Esports           | L   | 0.778      | -            | -                | -                | -         |    -6.38 | cass1n, leo_drk, luchov, Noktse, tomaszin |
|           34 |      326 | 2025-02-20 | Swingers                 | L   | 0.748      | -            | -                | -                | -         |   -15.95 | luchov, naz, Noktse, pancc, tomaszin      |
|           33 |      764 | 2025-02-08 | Legacy                   | L   | 0.683      | -            | -                | -                | -         |   -10.63 | luchov, naz, Noktse, pancc, tomaszin      |
|           32 |      767 | 2025-02-08 | ODDIK                    | W   | 0.683      | 0.143        | 0.024 (0.003)    | 0.568 (0.066)    | 0 (0.000) |    10.38 | luchov, naz, Noktse, pancc, tomaszin      |
|           31 |      795 | 2025-02-08 | Sharks Esports           | L   | 0.682      | -            | -                | -                | -         |    -5.84 | luchov, naz, Noktse, pancc, tomaszin      |
|           30 |      839 | 2025-02-07 | Game Hunters             | W   | 0.678      | -            | -                | -                | 0 (0.000) |     5.21 | luchov, naz, Noktse, pancc, tomaszin      |
|           29 |      885 | 2025-02-07 | ODDIK                    | W   | 0.677      | 0.143        | 0.024 (0.003)    | -                | 0 (0.000) |    10.79 | luchov, naz, Noktse, pancc, tomaszin      |
|           28 |      920 | 2025-02-06 | Bounty Hunters Esports   | W   | 0.672      | 0.143        | -                | 0.693 (0.080)    | 0 (0.000) |     6.96 | luchov, naz, Noktse, pancc, tomaszin      |
|           27 |      929 | 2025-02-06 | Swingers                 | W   | 0.671      | -            | -                | -                | 0 (0.000) |     6.68 | luchov, naz, Noktse, pancc, tomaszin      |
|           26 |      984 | 2025-02-05 | Bounty Hunters Esports   | L   | 0.666      | -            | -                | -                | -         |   -14.08 | luchov, naz, Noktse, pancc, tomaszin      |
|           25 |     1260 | 2025-01-27 | Floripa Stars            | W   | 0.617      | 0.450        | -                | 0.278 (0.093)    | 0 (0.000) |     3.62 | luchov, Noktse, tomaszin                  |
|           24 |     1265 | 2025-01-27 | Floripa Stars            | W   | 0.617      | 0.450        | -                | 0.278 (0.093)    | 0 (0.000) |     3.75 | luchov, Noktse, tomaszin                  |
|           23 |     1310 | 2025-01-24 | Bounty Hunters Esports   | W   | 0.600      | 0.450        | 0.003 (0.001)    | 0.693 (0.225)    | 0 (0.000) |     6.49 | luchov, Noktse, tomaszin                  |
|           22 |     1316 | 2025-01-24 | Bounty Hunters Esports   | W   | 0.600      | 0.450        | 0.003 (0.001)    | 0.693 (0.225)    | 0 (0.000) |     6.82 | luchov, Noktse, tomaszin                  |
|           21 |     1343 | 2025-01-23 | Swingers                 | W   | 0.595      | -            | -                | -                | 0 (0.000) |     1.37 | luchov, Noktse, tomaszin                  |
|           20 |     1349 | 2025-01-23 | Swingers                 | L   | 0.595      | -            | -                | -                | -         |   -15.84 | luchov, Noktse, tomaszin                  |
|           19 |     1384 | 2025-01-22 | Game Hunters             | L   | 0.589      | -            | -                | -                | -         |   -12.89 | luchov, Noktse, tomaszin                  |
|           18 |     1388 | 2025-01-22 | Game Hunters             | W   | 0.589      | 0.450        | 0.002 (0.001)    | 0.391 (0.124)    | -         |     5.68 | luchov, Noktse, tomaszin                  |
|           17 |     1414 | 2025-01-21 | TROPA DO TACO            | W   | 0.584      | -            | -                | -                | -         |     1.20 | luchov, Noktse, tomaszin                  |
|           16 |     1419 | 2025-01-21 | TROPA DO TACO            | L   | 0.584      | -            | -                | -                | -         |   -15.84 | luchov, Noktse, tomaszin                  |
|           15 |     1466 | 2025-01-12 | Legacy                   | W   | 0.533      | 0.384        | 0.032 (0.008)    | 0.556 (0.137)    | -         |     7.88 | luchov, naz, Noktse, pancc, tomaszin      |
|           14 |     1469 | 2025-01-11 | Team Solid               | W   | 0.527      | 0.384        | 0.023 (0.006)    | 0.624 (0.152)    | -         |     8.46 | luchov, naz, Noktse, pancc, tomaszin      |
|           13 |     1473 | 2025-01-10 | Elevate                  | W   | 0.522      | 0.384        | -                | 0.318 (0.077)    | -         |     2.41 | luchov, naz, Noktse, pancc, tomaszin      |
|           12 |     4583 | 2024-10-26 | 3DMAX                    | L   | 0.099      | -            | -                | -                | -         |    -0.07 | luchov, naz, Noktse, tomaszin, zock       |
|           11 |     4658 | 2024-10-25 | M80                      | W   | 0.093      | 0.934        | 0.010 (0.001)    | -                | -         |     1.46 | luchov, naz, Noktse, tomaszin, zock       |
|           10 |     4706 | 2024-10-24 | BIG                      | L   | 0.088      | -            | -                | -                | -         |    -0.13 | luchov, naz, Noktse, tomaszin, zock       |
|            9 |     4720 | 2024-10-24 | M80                      | W   | 0.086      | 0.934        | 0.010 (0.001)    | -                | -         |     1.36 | luchov, naz, Noktse, tomaszin, zock       |
|            8 |     4934 | 2024-10-19 | MIBR                     | L   | 0.061      | -            | -                | -                | -         |    -0.23 | luchov, naz, Noktse, tomaszin, zock       |
|            7 |     4979 | 2024-10-18 | RED Canids               | W   | 0.055      | -            | -                | -                | -         |     0.59 | luchov, naz, Noktse, tomaszin, zock       |
|            6 |     5026 | 2024-10-17 | InSanitY Sports          | W   | 0.050      | -            | -                | -                | -         |     0.38 | luchov, naz, Noktse, tomaszin, zock       |
|            5 |     5084 | 2024-10-16 | ODDIK                    | W   | 0.044      | 0.450        | 0.024 (0.001)    | -                | -         |     0.76 | luchov, naz, Noktse, tomaszin, zock       |
|            4 |     5166 | 2024-10-15 | RED Canids               | L   | 0.039      | -            | -                | -                | -         |    -0.81 | luchov, naz, Noktse, tomaszin, zock       |
|            3 |     5469 | 2024-10-09 | KRÜ Esports              | W   | 0.006      | -            | -                | -                | -         |     0.05 | luchov, naz, Noktse, tomaszin, zock       |
|            2 |     5478 | 2024-10-09 | KRÜ Esports              | W   | 0.005      | -            | -                | -                | -         |     0.05 | luchov, naz, Noktse, tomaszin, zock       |
|            1 |     5546 | 2024-10-08 | Players (Brazilian team) | W   | 0.000      | -            | -                | -                | -         |     0.00 | luchov, naz, Noktse, tomaszin, zock       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,025.35)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-12 |      0.640 | $12,500.00     | $7,996.53       |
| 2024-11-03 |      0.172 | $20,000.00     | $3,436.11       |
| 2024-10-20 |      0.079 | $7,500.00      | $592.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
