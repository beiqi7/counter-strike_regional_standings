### Roster Details<br />
Team Name: NRG<br />
Roster: br0, HexT, Jeorge, nitr0, oSee<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1051.5<br />
<br />
Final Rank Value (1051.5) = Starting Rank Value (1094.2) + Head To Head Adjustments (-42.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.400[<sup>2</sup>](#table1)

The average of these factors is 0.334<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.2
- 400 + ( ( 0.334 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1094.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |      560 | 2025-02-14 | M80                   | L   | 1.000      | -            | -                | -                | -         |   -17.74 | br0, HexT, Jeorge, nitr0, oSee       |
|           48 |      595 | 2025-02-13 | Exceritus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | br0, HexT, Jeorge, nitr0, oSee       |
|           47 |      606 | 2025-02-12 | Nouns Esports         | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    10.09 | br0, HexT, Jeorge, nitr0, oSee       |
|           46 |      626 | 2025-02-11 | BLUEJAYS              | W   | 1.000      | 0.143        | 0.016 (0.002)    | -                | 0 (0.000) |    10.99 | br0, HexT, Jeorge, nitr0, oSee       |
|           45 |      632 | 2025-02-11 | Marsborne             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.02 | br0, HexT, Jeorge, nitr0, oSee       |
|           44 |     1189 | 2025-01-28 | Vagrants              | W   | 0.973      | 0.477        | -                | 0.522 (0.242)    | 0 (0.000) |     7.12 | br0, HexT, Jeorge, nitr0, oSee       |
|           43 |     1194 | 2025-01-28 | Vagrants              | L   | 0.973      | -            | -                | -                | -         |   -24.08 | br0, HexT, Jeorge, nitr0, oSee       |
|           42 |     1241 | 2025-01-24 | Getting Info          | L   | 0.946      | -            | -                | -                | -         |   -20.44 | br0, HexT, Jeorge, nitr0, oSee       |
|           41 |     1242 | 2025-01-24 | Getting Info          | L   | 0.946      | -            | -                | -                | -         |   -21.90 | br0, HexT, Jeorge, nitr0, oSee       |
|           40 |     1259 | 2025-01-23 | Chill Guys            | W   | 0.940      | 0.477        | -                | 0.634 (0.284)    | -         |     5.83 | br0, HexT, Jeorge, nitr0, oSee       |
|           39 |     1261 | 2025-01-23 | Chill Guys            | W   | 0.939      | 0.477        | -                | 0.634 (0.284)    | -         |     6.15 | br0, HexT, Jeorge, nitr0, oSee       |
|           38 |     1721 | 2024-12-15 | Getting Info          | L   | 0.679      | -            | -                | -                | -         |   -16.54 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           37 |     1728 | 2024-12-15 | Party Astronauts      | W   | 0.678      | 0.303        | -                | 0.528 (0.108)    | -         |     4.19 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           36 |     2068 | 2024-12-08 | Sharks Esports        | W   | 0.633      | 0.384        | 0.064 (0.016)    | 0.683 (0.166)    | 1 (0.633) |     9.61 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           35 |     2072 | 2024-12-08 | Sharks Esports        | W   | 0.631      | 0.384        | 0.064 (0.016)    | 0.683 (0.166)    | 1 (0.631) |     9.96 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           34 |     2142 | 2024-12-07 | BLUEJAYS              | W   | 0.626      | 0.384        | 0.016 (0.004)    | 0.360 (0.087)    | 1 (0.626) |     6.16 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           33 |     2155 | 2024-12-07 | Undone                | W   | 0.625      | -            | -                | -                | 1 (0.625) |     3.48 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           32 |     2206 | 2024-12-06 | Stand On Business     | W   | 0.619      | -            | -                | -                | 1 (0.619) |     0.45 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           31 |     2764 | 2024-11-24 | Nouns Esports         | L   | 0.539      | -            | -                | -                | -         |   -11.43 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           30 |     2770 | 2024-11-24 | Getting Info          | W   | 0.538      | 0.303        | -                | 0.600 (0.098)    | -         |     3.67 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           29 |     2820 | 2024-11-23 | Chill Guys            | W   | 0.532      | 0.303        | -                | 0.634 (0.102)    | -         |     3.71 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           28 |     4677 | 2024-10-20 | M80                   | L   | 0.305      | -            | -                | -                | -         |    -6.10 | autimatic, Brehze, HexT, nitr0, oSee |
|           27 |     4746 | 2024-10-19 | Legacy                | W   | 0.299      | 0.477        | 0.043 (0.006)    | 0.628 (0.090)    | -         |     2.76 | autimatic, Brehze, HexT, nitr0, oSee |
|           26 |     4784 | 2024-10-18 | Party Astronauts      | W   | 0.292      | -            | -                | -                | -         |     2.09 | autimatic, Brehze, HexT, nitr0, oSee |
|           25 |     4830 | 2024-10-17 | Wildcard              | W   | 0.285      | 0.477        | 0.161 (0.022)    | -                | -         |     5.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           24 |     4879 | 2024-10-16 | M80                   | L   | 0.279      | -            | -                | -                | -         |    -5.64 | autimatic, Brehze, HexT, nitr0, oSee |
|           23 |     4948 | 2024-10-15 | Party Astronauts      | W   | 0.272      | -            | -                | -                | -         |     1.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           22 |     5295 | 2024-10-08 | Nouns Esports         | L   | 0.226      | -            | -                | -                | -         |    -4.91 | autimatic, Brehze, HexT, nitr0, oSee |
|           21 |     5301 | 2024-10-08 | Nouns Esports         | L   | 0.225      | -            | -                | -                | -         |    -4.98 | autimatic, Brehze, HexT, nitr0, oSee |
|           20 |     5602 | 2024-10-03 | BLUEJAYS              | L   | 0.192      | -            | -                | -                | -         |    -4.34 | autimatic, Brehze, HexT, nitr0, oSee |
|           19 |     5708 | 2024-10-01 | Legacy                | L   | 0.179      | -            | -                | -                | -         |    -4.14 | autimatic, Brehze, HexT, nitr0, oSee |
|           18 |     5714 | 2024-10-01 | Legacy                | L   | 0.179      | -            | -                | -                | -         |    -4.19 | autimatic, Brehze, HexT, nitr0, oSee |
|           17 |     5728 | 2024-10-01 | Final Form            | W   | 0.178      | -            | -                | -                | -         |     0.36 | autimatic, Brehze, HexT, nitr0, oSee |
|           16 |     5987 | 2024-09-27 | Legacy                | L   | 0.152      | -            | -                | -                | -         |    -3.63 | autimatic, Brehze, HexT, nitr0, oSee |
|           15 |     5994 | 2024-09-27 | Familia Maquininha    | W   | 0.151      | -            | -                | -                | -         |     0.47 | autimatic, Brehze, HexT, nitr0, oSee |
|           14 |     6073 | 2024-09-26 | Seoul (American team) | W   | 0.145      | -            | -                | -                | -         |     0.09 | autimatic, Brehze, HexT, nitr0, oSee |
|           13 |     6141 | 2024-09-25 | M80                   | L   | 0.139      | -            | -                | -                | -         |    -3.07 | autimatic, Brehze, HexT, nitr0, oSee |
|           12 |     6146 | 2024-09-25 | M80                   | W   | 0.139      | 0.477        | 0.043 (0.003)    | -                | -         |     1.32 | autimatic, Brehze, HexT, nitr0, oSee |
|           11 |     6234 | 2024-09-24 | Timbermen             | W   | 0.132      | -            | -                | -                | -         |     0.32 | autimatic, Brehze, HexT, nitr0, oSee |
|           10 |     6238 | 2024-09-24 | Timbermen             | W   | 0.132      | -            | -                | -                | -         |     0.32 | autimatic, Brehze, HexT, nitr0, oSee |
|            9 |     6394 | 2024-09-22 | Nouns Esports         | W   | 0.119      | -            | -                | -                | -         |     1.08 | autimatic, Brehze, HexT, nitr0, oSee |
|            8 |     6400 | 2024-09-22 | FLUFFY AIMERS         | W   | 0.117      | -            | -                | -                | -         |     0.69 | autimatic, Brehze, HexT, nitr0, oSee |
|            7 |     6447 | 2024-09-21 | Party Astronauts      | W   | 0.111      | -            | -                | -                | -         |     0.63 | autimatic, Brehze, HexT, nitr0, oSee |
|            6 |     6563 | 2024-09-19 | Wildcard              | W   | 0.099      | 0.477        | 0.161 (0.008)    | -                | -         |     1.79 | autimatic, Brehze, HexT, nitr0, oSee |
|            5 |     6567 | 2024-09-19 | Wildcard              | W   | 0.098      | 0.477        | 0.161 (0.008)    | -                | -         |     1.80 | autimatic, Brehze, HexT, nitr0, oSee |
|            4 |     6615 | 2024-09-18 | Bad News Capybaras    | W   | 0.092      | -            | -                | -                | -         |     0.28 | autimatic, Brehze, HexT, nitr0, oSee |
|            3 |     6622 | 2024-09-18 | Bad News Capybaras    | W   | 0.092      | -            | -                | -                | -         |     0.29 | autimatic, Brehze, HexT, nitr0, oSee |
|            2 |     6680 | 2024-09-17 | LAG Gaming            | W   | 0.086      | -            | -                | -                | -         |     0.19 | autimatic, Brehze, HexT, nitr0, oSee |
|            1 |     6691 | 2024-09-17 | LAG Gaming            | W   | 0.085      | -            | -                | -                | -         |     0.19 | autimatic, Brehze, HexT, nitr0, oSee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,912.56)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.679 | $1,000.00      | $679.22         |
| 2024-12-08 |      0.633 | $15,000.00     | $9,491.35       |
| 2024-11-24 |      0.539 | $1,000.00      | $538.96         |
| 2024-10-20 |      0.305 | $15,000.00     | $4,573.64       |
| 2024-10-05 |      0.206 | $750.00        | $154.20         |
| 2024-09-22 |      0.119 | $4,000.00      | $475.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
