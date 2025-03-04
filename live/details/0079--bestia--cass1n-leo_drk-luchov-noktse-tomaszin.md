### Roster Details<br />
Team Name: BESTIA<br />
Roster: cass1n, leo_drk, luchov, Noktse, tomaszin<br />
Global Rank: [79](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  917.6<br />
<br />
Final Rank Value (917.6) = Starting Rank Value (891.4) + Head To Head Adjustments (26.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.025[<sup>2</sup>](#table1)

The average of these factors is 0.236<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.4
- 400 + ( ( 0.236 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 891.4


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
|           48 |      100 | 2025-02-25 | Sharks Esports           | L   | 1.000      | -            | -                | -                | -         |    -9.02 | cass1n, leo_drk, luchov, Noktse, tomaszin |
|           47 |      102 | 2025-02-25 | Sharks Esports           | L   | 1.000      | -            | -                | -                | -         |    -9.71 | cass1n, leo_drk, luchov, Noktse, tomaszin |
|           46 |      319 | 2025-02-20 | Swingers                 | L   | 1.000      | -            | -                | -                | -         |   -23.70 | luchov, naz, Noktse, pancc, tomaszin      |
|           45 |      742 | 2025-02-08 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |   -15.74 | luchov, naz, Noktse, pancc, tomaszin      |
|           44 |      745 | 2025-02-08 | ODDIK                    | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.552 (0.079)    | 0 (0.000) |    13.65 | luchov, naz, Noktse, pancc, tomaszin      |
|           43 |      773 | 2025-02-08 | Sharks Esports           | L   | 1.000      | -            | -                | -                | -         |   -10.76 | luchov, naz, Noktse, pancc, tomaszin      |
|           42 |      817 | 2025-02-07 | Game Hunters             | W   | 1.000      | 0.143        | -                | 0.402 (0.057)    | 0 (0.000) |     5.46 | luchov, naz, Noktse, pancc, tomaszin      |
|           41 |      863 | 2025-02-07 | ODDIK                    | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.552 (0.079)    | 0 (0.000) |    14.41 | luchov, naz, Noktse, pancc, tomaszin      |
|           40 |      898 | 2025-02-06 | Bounty Hunters Esports   | W   | 1.000      | 0.143        | -                | 0.638 (0.091)    | 0 (0.000) |     9.59 | luchov, naz, Noktse, pancc, tomaszin      |
|           39 |      907 | 2025-02-06 | Swingers                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.91 | luchov, naz, Noktse, pancc, tomaszin      |
|           38 |      963 | 2025-02-05 | Bounty Hunters Esports   | L   | 1.000      | -            | -                | -                | -         |   -21.72 | luchov, naz, Noktse, pancc, tomaszin      |
|           37 |     1346 | 2025-01-12 | Legacy                   | W   | 0.865      | 0.384        | 0.043 (0.014)    | 0.628 (0.209)    | 0 (0.000) |    12.66 | luchov, naz, Noktse, pancc, tomaszin      |
|           36 |     1349 | 2025-01-11 | Team Solid               | W   | 0.857      | 0.384        | 0.027 (0.009)    | 0.616 (0.203)    | 0 (0.000) |    12.32 | luchov, naz, Noktse, pancc, tomaszin      |
|           35 |     1353 | 2025-01-10 | Elevate                  | W   | 0.851      | 0.384        | -                | 0.326 (0.107)    | 0 (0.000) |     3.46 | luchov, naz, Noktse, pancc, tomaszin      |
|           34 |     4423 | 2024-10-26 | 3DMAX                    | L   | 0.344      | -            | -                | -                | -         |    -0.29 | luchov, naz, Noktse, tomaszin, zock       |
|           33 |     4497 | 2024-10-25 | M80                      | W   | 0.337      | 0.934        | 0.043 (0.014)    | 0.460 (0.145)    | 0 (0.000) |     6.15 | luchov, naz, Noktse, tomaszin, zock       |
|           32 |     4539 | 2024-10-24 | BIG                      | L   | 0.330      | -            | -                | -                | -         |    -0.48 | luchov, naz, Noktse, tomaszin, zock       |
|           31 |     4551 | 2024-10-24 | M80                      | W   | 0.329      | 0.934        | 0.043 (0.013)    | 0.460 (0.141)    | -         |     6.12 | luchov, naz, Noktse, tomaszin, zock       |
|           30 |     4747 | 2024-10-19 | MIBR                     | L   | 0.298      | -            | -                | -                | -         |    -2.15 | luchov, naz, Noktse, tomaszin, zock       |
|           29 |     4789 | 2024-10-18 | RED Canids               | W   | 0.291      | 0.450        | 0.023 (0.003)    | -                | -         |     3.75 | luchov, naz, Noktse, tomaszin, zock       |
|           28 |     4834 | 2024-10-17 | InSanitY Sports          | W   | 0.285      | -            | -                | -                | -         |     2.78 | luchov, naz, Noktse, tomaszin, zock       |
|           27 |     4888 | 2024-10-16 | ODDIK                    | W   | 0.278      | 0.450        | 0.033 (0.004)    | 0.552 (0.069)    | -         |     4.22 | luchov, naz, Noktse, tomaszin, zock       |
|           26 |     4952 | 2024-10-15 | RED Canids               | L   | 0.271      | -            | -                | -                | -         |    -5.11 | luchov, naz, Noktse, tomaszin, zock       |
|           25 |     5238 | 2024-10-09 | KRÜ Esports              | W   | 0.232      | -            | -                | -                | -         |     1.57 | luchov, naz, Noktse, tomaszin, zock       |
|           24 |     5246 | 2024-10-09 | KRÜ Esports              | W   | 0.231      | -            | -                | -                | -         |     1.59 | luchov, naz, Noktse, tomaszin, zock       |
|           23 |     5307 | 2024-10-08 | Players (Brazilian team) | W   | 0.225      | -            | -                | -                | -         |     0.38 | luchov, naz, Noktse, tomaszin, zock       |
|           22 |     5315 | 2024-10-08 | Players (Brazilian team) | W   | 0.225      | -            | -                | -                | -         |     0.38 | luchov, naz, Noktse, tomaszin, zock       |
|           21 |     5367 | 2024-10-07 | RED Canids               | W   | 0.218      | -            | -                | -                | -         |     2.86 | luchov, naz, Noktse, tomaszin, zock       |
|           20 |     5369 | 2024-10-07 | RED Canids               | W   | 0.218      | -            | -                | -                | -         |     2.91 | luchov, naz, Noktse, tomaszin, zock       |
|           19 |     5501 | 2024-10-05 | RED Canids               | L   | 0.203      | -            | -                | -                | -         |    -3.74 | luchov, naz, Noktse, tomaszin, zock       |
|           18 |     5577 | 2024-10-04 | PaiN Gaming              | W   | 0.197      | 0.143        | 0.333 (0.009)    | -                | 1 (0.197) |     5.99 | luchov, naz, Noktse, tomaszin, zock       |
|           17 |     5663 | 2024-10-02 | Case Esports             | W   | 0.184      | -            | -                | -                | -         |     1.43 | luchov, naz, Noktse, tomaszin, zock       |
|           16 |     5667 | 2024-10-02 | Case Esports             | W   | 0.184      | -            | -                | -                | -         |     1.45 | luchov, naz, Noktse, tomaszin, zock       |
|           15 |     5731 | 2024-10-01 | Team Solid               | W   | 0.178      | -            | -                | -                | -         |     2.61 | luchov, naz, Noktse, tomaszin, zock       |
|           14 |     5733 | 2024-10-01 | Team Solid               | W   | 0.177      | -            | -                | -                | -         |     2.65 | luchov, naz, Noktse, tomaszin, zock       |
|           13 |     6077 | 2024-09-26 | Sharks Esports           | W   | 0.144      | -            | -                | -                | -         |     3.58 | luchov, naz, Noktse, tomaszin, zock       |
|           12 |     6083 | 2024-09-26 | MIBR                     | W   | 0.144      | -            | -                | -                | -         |     3.67 | luchov, naz, Noktse, tomaszin, zock       |
|           11 |     6154 | 2024-09-25 | Imperial Esports         | W   | 0.138      | 0.450        | 0.083 (0.005)    | -                | -         |     2.41 | luchov, naz, Noktse, tomaszin, zock       |
|           10 |     6160 | 2024-09-25 | Imperial Esports         | L   | 0.138      | -            | -                | -                | -         |    -1.96 | luchov, naz, Noktse, tomaszin, zock       |
|            9 |     6186 | 2024-09-25 | Imperial Esports         | L   | 0.137      | -            | -                | -                | -         |    -1.96 | luchov, naz, Noktse, tomaszin, zock       |
|            8 |     6246 | 2024-09-24 | Hype Esports             | W   | 0.132      | -            | -                | -                | -         |     1.00 | luchov, naz, Noktse, tomaszin, zock       |
|            7 |     6252 | 2024-09-24 | Hype Esports             | L   | 0.131      | -            | -                | -                | -         |    -3.16 | luchov, naz, Noktse, tomaszin, zock       |
|            6 |     6629 | 2024-09-18 | PaiN Gaming              | L   | 0.091      | -            | -                | -                | -         |    -0.08 | luchov, naz, Noktse, tomaszin, zock       |
|            5 |     6633 | 2024-09-18 | PaiN Gaming              | L   | 0.091      | -            | -                | -                | -         |    -0.08 | luchov, naz, Noktse, tomaszin, zock       |
|            4 |     6695 | 2024-09-17 | InSanitY Sports          | W   | 0.085      | -            | -                | -                | -         |     0.81 | luchov, naz, Noktse, tomaszin, zock       |
|            3 |     6697 | 2024-09-17 | InSanitY Sports          | L   | 0.085      | -            | -                | -                | -         |    -1.87 | luchov, naz, Noktse, tomaszin, zock       |
|            2 |     7110 | 2024-09-10 | Dusty Roots              | W   | 0.038      | -            | -                | -                | -         |     0.48 | luchov, naz, Noktse, tomaszin, zock       |
|            1 |     7112 | 2024-09-10 | Dusty Roots              | W   | 0.038      | -            | -                | -                | -         |     0.48 | luchov, naz, Noktse, tomaszin, zock       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,510.40)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-12 |      0.865 | $12,500.00     | $10,807.90      |
| 2024-11-03 |      0.397 | $20,000.00     | $7,934.30       |
| 2024-10-20 |      0.304 | $7,500.00      | $2,279.53       |
| 2024-10-05 |      0.203 | $7,329.63      | $1,488.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
