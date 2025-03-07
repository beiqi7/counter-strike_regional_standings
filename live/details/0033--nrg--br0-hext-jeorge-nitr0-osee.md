### Roster Details<br />
Team Name: NRG<br />
Roster: br0, HexT, Jeorge, nitr0, oSee<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1002.2<br />
<br />
Final Rank Value (1002.2) = Starting Rank Value (1024.9) + Head To Head Adjustments (-22.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.414[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.328[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1024.9
- 400 + ( ( 0.283 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1024.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      584 | 2025-02-14 | M80               | L   | 0.716      | -            | -                | -                | -         |   -14.63 | br0, HexT, Jeorge, nitr0, oSee       |
|           37 |      612 | 2025-02-13 | Exceritus         | W   | 0.710      | -            | -                | -                | 0 (0.000) |     1.67 | br0, HexT, Jeorge, nitr0, oSee       |
|           36 |      624 | 2025-02-12 | Nouns Esports     | W   | 0.707      | 0.143        | 0.008 (0.001)    | 0.649 (0.079)    | 0 (0.000) |     7.17 | br0, HexT, Jeorge, nitr0, oSee       |
|           35 |      644 | 2025-02-11 | BLUEJAYS          | W   | 0.701      | -            | -                | -                | 0 (0.000) |     7.17 | br0, HexT, Jeorge, nitr0, oSee       |
|           34 |      650 | 2025-02-11 | Marsborne         | W   | 0.700      | 0.143        | -                | 0.579 (0.069)    | 0 (0.000) |     3.32 | br0, HexT, Jeorge, nitr0, oSee       |
|           33 |     1216 | 2025-01-28 | Vagrants          | W   | 0.623      | 0.477        | -                | 0.487 (0.174)    | 0 (0.000) |     4.90 | br0, HexT, Jeorge, nitr0, oSee       |
|           32 |     1222 | 2025-01-28 | Vagrants          | L   | 0.623      | -            | -                | -                | -         |   -15.09 | br0, HexT, Jeorge, nitr0, oSee       |
|           31 |     1252 | 2025-01-27 | BOSS              | W   | 0.618      | -            | -                | -                | -         |     0.63 | br0, HexT, Jeorge, nitr0, oSee       |
|           30 |     1257 | 2025-01-27 | BOSS              | L   | 0.618      | -            | -                | -                | -         |   -18.07 | br0, HexT, Jeorge, nitr0, oSee       |
|           29 |     1298 | 2025-01-24 | Getting Info      | L   | 0.601      | -            | -                | -                | -         |   -12.99 | br0, HexT, Jeorge, nitr0, oSee       |
|           28 |     1304 | 2025-01-24 | Getting Info      | L   | 0.601      | -            | -                | -                | -         |   -13.58 | br0, HexT, Jeorge, nitr0, oSee       |
|           27 |     1336 | 2025-01-23 | Chill Guys        | W   | 0.596      | 0.477        | 0.002 (0.001)    | 0.582 (0.198)    | -         |     4.52 | br0, HexT, Jeorge, nitr0, oSee       |
|           26 |     1342 | 2025-01-23 | Chill Guys        | W   | 0.595      | 0.477        | -                | 0.582 (0.198)    | -         |     4.70 | br0, HexT, Jeorge, nitr0, oSee       |
|           25 |     1374 | 2025-01-22 | LAG Gaming        | W   | 0.590      | -            | -                | -                | -         |     1.60 | br0, HexT, Jeorge, nitr0, oSee       |
|           24 |     1380 | 2025-01-22 | LAG Gaming        | W   | 0.590      | -            | -                | -                | -         |     1.63 | br0, HexT, Jeorge, nitr0, oSee       |
|           23 |     1405 | 2025-01-21 | Alter Iron Club   | W   | 0.584      | -            | -                | -                | -         |     0.50 | br0, HexT, Jeorge, nitr0, oSee       |
|           22 |     1410 | 2025-01-21 | Alter Iron Club   | W   | 0.584      | -            | -                | -                | -         |     0.50 | br0, HexT, Jeorge, nitr0, oSee       |
|           21 |     1845 | 2024-12-15 | Getting Info      | L   | 0.379      | -            | -                | -                | -         |    -8.74 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           20 |     1852 | 2024-12-15 | Party Astronauts  | W   | 0.377      | 0.303        | -                | 0.459 (0.063)    | -         |     2.71 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           19 |     1898 | 2024-12-14 | Make Your Mind    | W   | 0.373      | 0.303        | 0.014 (0.002)    | -                | -         |     2.09 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           18 |     2192 | 2024-12-08 | Sharks Esports    | W   | 0.340      | 0.384        | 0.051 (0.008)    | 0.636 (0.100)    | 1 (0.408) |     5.75 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           17 |     2196 | 2024-12-08 | Sharks Esports    | W   | 0.339      | 0.384        | 0.051 (0.008)    | 0.636 (0.099)    | 1 (0.406) |     5.86 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           16 |     2270 | 2024-12-07 | BLUEJAYS          | W   | 0.334      | 0.384        | 0.006 (0.001)    | -                | 1 (0.401) |     3.03 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           15 |     2284 | 2024-12-07 | Undone            | W   | 0.333      | -            | -                | -                | 1 (0.400) |     2.15 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           14 |     2341 | 2024-12-06 | Stand On Business | W   | 0.329      | -            | -                | -                | 1 (0.395) |     0.30 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           13 |     2777 | 2024-11-27 | InControl         | W   | 0.279      | -            | -                | -                | -         |     0.48 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           12 |     2882 | 2024-11-24 | Nouns Esports     | L   | 0.262      | -            | -                | -                | -         |    -5.59 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           11 |     2888 | 2024-11-24 | Getting Info      | W   | 0.261      | 0.303        | 0.009 (0.001)    | 0.604 (0.057)    | -         |     2.23 | Brehze, HexT, Jeorge, nitr0, oSee    |
|           10 |     2940 | 2024-11-23 | Chill Guys        | W   | 0.256      | 0.303        | -                | 0.582 (0.054)    | -         |     2.10 | Brehze, HexT, Jeorge, nitr0, oSee    |
|            9 |     3259 | 2024-11-19 | Make Your Mind    | W   | 0.234      | 0.384        | 0.014 (0.002)    | -                | -         |     1.21 | Brehze, HexT, nitr0, oSee            |
|            8 |     4864 | 2024-10-20 | M80               | L   | 0.067      | -            | -                | -                | -         |    -1.49 | autimatic, Brehze, HexT, nitr0, oSee |
|            7 |     4933 | 2024-10-19 | Legacy            | W   | 0.062      | 0.477        | 0.032 (0.001)    | -                | -         |     0.54 | autimatic, Brehze, HexT, nitr0, oSee |
|            6 |     4974 | 2024-10-18 | Party Astronauts  | W   | 0.056      | -            | -                | -                | -         |     0.45 | autimatic, Brehze, HexT, nitr0, oSee |
|            5 |     5022 | 2024-10-17 | Wildcard          | W   | 0.050      | 0.477        | 0.162 (0.005)    | -                | -         |     1.00 | autimatic, Brehze, HexT, nitr0, oSee |
|            4 |     5074 | 2024-10-16 | M80               | L   | 0.045      | -            | -                | -                | -         |    -1.00 | autimatic, Brehze, HexT, nitr0, oSee |
|            3 |     5162 | 2024-10-15 | Party Astronauts  | W   | 0.039      | -            | -                | -                | -         |     0.31 | autimatic, Brehze, HexT, nitr0, oSee |
|            2 |     5534 | 2024-10-08 | Nouns Esports     | L   | 0.001      | -            | -                | -                | -         |    -0.01 | autimatic, Brehze, HexT, nitr0, oSee |
|            1 |     5540 | 2024-10-08 | Nouns Esports     | L   | 0.000      | -            | -                | -                | -         |    -0.01 | autimatic, Brehze, HexT, nitr0, oSee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,086.06)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.454 | $1,000.00      | $454.31         |
| 2024-12-08 |      0.408 | $15,000.00     | $6,117.71       |
| 2024-11-24 |      0.314 | $1,000.00      | $314.05         |
| 2024-10-20 |      0.080 | $15,000.00     | $1,200.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
