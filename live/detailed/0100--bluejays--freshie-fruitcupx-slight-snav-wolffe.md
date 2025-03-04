### Roster Details<br />
Team Name: BLUEJAYS<br />
Roster: freshie, Fruitcupx, SLIGHT, snav, Wolffe<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
<br />
Final Rank Value:  883.3<br />
<br />
Final Rank Value (883.3) = Starting Rank Value (929.2) + Head To Head Adjustments (-46.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.320[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 929.2
- 400 + ( ( 0.254 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 929.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |       41 | 2025-02-26 | Marsborne         | L   | 1.000      | -            | -                | -                | -         |   -22.07 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           38 |       46 | 2025-02-26 | Marsborne         | L   | 1.000      | -            | -                | -                | -         |   -23.68 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           37 |      536 | 2025-02-14 | M80               | L   | 1.000      | -            | -                | -                | -         |   -11.65 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           36 |      548 | 2025-02-14 | Getting Info      | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.600 (0.086)    | 0 (0.000) |    15.83 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           35 |      587 | 2025-02-13 | Immigrants Peek   | W   | 1.000      | 0.143        | -                | 0.378 (0.054)    | 0 (0.000) |     7.02 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           34 |      607 | 2025-02-12 | Nouns Esports     | L   | 1.000      | -            | -                | -                | -         |   -15.83 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           33 |      624 | 2025-02-11 | NRG               | L   | 1.000      | -            | -                | -                | -         |   -10.99 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           32 |      629 | 2025-02-11 | Nouns Esports     | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.601 (0.086)    | 0 (0.000) |    14.82 | freshie, Fruitcupx, SLIGHT, snav, Wolffe   |
|           31 |     1768 | 2024-12-14 | Getting Info      | L   | 0.673      | -            | -                | -                | -         |   -13.10 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           30 |     2067 | 2024-12-08 | Sharks Esports    | L   | 0.633      | -            | -                | -                | -         |    -6.42 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           29 |     2071 | 2024-12-08 | Nouns Esports     | W   | 0.632      | 0.384        | 0.014 (0.003)    | 0.601 (0.146)    | 1 (0.632) |    10.65 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           28 |     2091 | 2024-12-08 | FLUFFY AIMERS     | W   | 0.631      | 0.384        | 0.006 (0.001)    | 0.214 (0.052)    | 1 (0.631) |     7.10 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           27 |     2140 | 2024-12-07 | NRG               | L   | 0.627      | -            | -                | -                | -         |    -6.16 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           26 |     2155 | 2024-12-07 | ROOMBA PEEK       | W   | 0.625      | -            | -                | -                | 1 (0.625) |     2.20 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           25 |     2202 | 2024-12-06 | What's for Dinner | W   | 0.620      | -            | -                | -                | 1 (0.620) |     0.91 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           24 |     2371 | 2024-12-02 | Mythic            | W   | 0.593      | -            | -                | -                | 0 (0.000) |     1.56 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           23 |     2765 | 2024-11-24 | Nouns Esports     | L   | 0.539      | -            | -                | -                | -         |    -8.44 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           22 |     2825 | 2024-11-23 | Undone            | W   | 0.531      | 0.303        | -                | 0.313 (0.050)    | 0 (0.000) |     5.76 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           21 |     3133 | 2024-11-19 | MIGHT             | W   | 0.507      | 0.384        | -                | 0.455 (0.089)    | 0 (0.000) |     4.35 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           20 |     4880 | 2024-10-16 | Wildcard          | L   | 0.279      | -            | -                | -                | -         |    -2.32 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           19 |     4949 | 2024-10-15 | FLUFFY AIMERS     | W   | 0.273      | 0.477        | 0.006 (0.001)    | -                | -         |     3.13 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           18 |     5218 | 2024-10-09 | M80               | L   | 0.233      | -            | -                | -                | -         |    -3.32 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           17 |     5224 | 2024-10-09 | M80               | W   | 0.233      | 0.477        | 0.043 (0.005)    | 0.460 (0.051)    | -         |     4.08 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           16 |     5362 | 2024-10-07 | FLUFFY AIMERS     | W   | 0.219      | 0.477        | 0.006 (0.001)    | -                | -         |     2.70 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           15 |     5364 | 2024-10-07 | FLUFFY AIMERS     | L   | 0.219      | -            | -                | -                | -         |    -4.27 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           14 |     5466 | 2024-10-05 | FLUFFY AIMERS     | W   | 0.206      | -            | -                | -                | -         |     2.51 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           13 |     5478 | 2024-10-05 | Party Astronauts  | W   | 0.204      | 0.371        | 0.009 (0.001)    | 0.528 (0.040)    | -         |     2.40 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           12 |     5600 | 2024-10-03 | NRG               | W   | 0.193      | 0.371        | 0.057 (0.004)    | 0.516 (0.037)    | -         |     4.35 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           11 |     5708 | 2024-10-01 | Wildcard          | L   | 0.179      | -            | -                | -                | -         |    -1.25 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|           10 |     5711 | 2024-10-01 | Wildcard          | L   | 0.179      | -            | -                | -                | -         |    -1.26 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            9 |     5780 | 2024-09-30 | Mythic            | W   | 0.173      | -            | -                | -                | -         |     0.48 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            8 |     5991 | 2024-09-27 | Legacy            | L   | 0.152      | -            | -                | -                | -         |    -2.62 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            7 |     6070 | 2024-09-26 | Exceritus         | W   | 0.145      | -            | -                | -                | -         |     0.75 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            6 |     6137 | 2024-09-25 | Vagrants          | W   | 0.139      | -            | -                | -                | -         |     1.40 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            5 |     6141 | 2024-09-25 | Vagrants          | L   | 0.139      | -            | -                | -                | -         |    -3.02 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            4 |     6230 | 2024-09-24 | Party Astronauts  | W   | 0.133      | 0.477        | 0.009 (0.001)    | -                | -         |     1.54 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            3 |     6237 | 2024-09-24 | Party Astronauts  | L   | 0.133      | -            | -                | -                | -         |    -2.66 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            2 |     6395 | 2024-09-22 | Nouns Esports     | L   | 0.118      | -            | -                | -                | -         |    -1.83 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |
|            1 |     6443 | 2024-09-21 | Getting Info      | W   | 0.112      | -            | -                | -                | -         |     1.39 | Cryptic, d4rty, freshie, Fruitcupx, SLIGHT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,558.44)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.633 | $2,500.00      | $1,582.82       |
| 2024-10-20 |      0.305 | $3,000.00      | $915.85         |
| 2024-10-05 |      0.206 | $10,000.00     | $2,059.77       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
