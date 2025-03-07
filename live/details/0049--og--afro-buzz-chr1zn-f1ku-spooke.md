### Roster Details<br />
Team Name: OG<br />
Roster: afro, Buzz, Chr1zN, F1KU, spooke<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.7<br />
<br />
Final Rank Value (954.7) = Starting Rank Value (886.8) + Head To Head Adjustments (67.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.116[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.8
- 400 + ( ( 0.221 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 886.8


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
|           43 |      116 | 2025-02-25 | ESC Gaming            | W   | 0.776      | -            | -                | -                | 0 (0.000) |     3.08 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           42 |      138 | 2025-02-24 | Iberian Soul          | L   | 0.772      | -            | -                | -                | -         |   -16.06 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           41 |      148 | 2025-02-24 | Tricked Esport        | W   | 0.770      | 0.143        | 0.030 (0.004)    | 0.549 (0.072)    | 0 (0.000) |     8.26 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           40 |      229 | 2025-02-22 | BC.Game Esports       | W   | 0.760      | 0.143        | 0.061 (0.008)    | 1.000 (0.130)    | 0 (0.000) |    17.09 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           39 |      289 | 2025-02-21 | Aurora Gaming         | W   | 0.754      | 0.143        | -                | 0.633 (0.082)    | 0 (0.000) |     8.74 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           38 |      411 | 2025-02-17 | Leo Team              | W   | 0.733      | 0.143        | 0.020 (0.003)    | 0.553 (0.070)    | 0 (0.000) |     8.79 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           37 |      414 | 2025-02-17 | CYBERSHOKE Esports    | W   | 0.733      | 0.143        | 0.014 (0.002)    | 1.000 (0.126)    | 0 (0.000) |    10.01 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           36 |      424 | 2025-02-17 | WeLoveUSmooya         | W   | 0.732      | -            | -                | -                | 0 (0.000) |     2.46 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           35 |      431 | 2025-02-17 | Moneytrees            | W   | 0.732      | -            | -                | -                | 0 (0.000) |     1.31 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           34 |      447 | 2025-02-16 | QUAZAR                | W   | 0.728      | -            | -                | -                | 0 (0.000) |     5.30 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           33 |      539 | 2025-02-15 | Rebels Gaming         | L   | 0.721      | -            | -                | -                | -         |   -15.26 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           32 |      567 | 2025-02-14 | PARIVISION            | W   | 0.716      | 0.143        | -                | 0.910 (0.112)    | 0 (0.000) |     8.38 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           31 |      689 | 2025-02-10 | BIG                   | L   | 0.693      | -            | -                | -                | -         |    -1.75 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           30 |      701 | 2025-02-10 | Astralis              | L   | 0.692      | -            | -                | -                | -         |    -0.12 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           29 |      739 | 2025-02-09 | RUSH B (Russian team) | L   | 0.687      | -            | -                | -                | -         |   -10.23 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           28 |      744 | 2025-02-09 | Sashi Esport          | L   | 0.686      | -            | -                | -                | -         |   -10.49 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           27 |      775 | 2025-02-08 | TEAM NEXT LEVEL       | W   | 0.683      | -            | -                | -                | -         |     5.98 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           26 |      784 | 2025-02-08 | Benched               | W   | 0.683      | -            | -                | -                | -         |     2.68 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           25 |      794 | 2025-02-08 | 500                   | L   | 0.682      | -            | -                | -                | -         |    -6.83 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           24 |      804 | 2025-02-08 | Mission Possible      | W   | 0.682      | -            | -                | -                | -         |     2.19 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           23 |      866 | 2025-02-07 | Nuclear TigeRES       | W   | 0.678      | -            | -                | -                | -         |     7.36 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           22 |      890 | 2025-02-07 | AMKAL ESPORTS         | W   | 0.676      | 0.143        | -                | 0.588 (0.068)    | -         |     6.89 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           21 |      945 | 2025-02-06 | Alliance              | W   | 0.669      | 0.143        | -                | 0.516 (0.059)    | -         |    10.02 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           20 |      966 | 2025-02-05 | SINNERS Esports       | W   | 0.666      | 0.435        | 0.016 (0.006)    | 0.494 (0.172)    | -         |    11.55 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           19 |     1121 | 2025-02-03 | Natus Vincere Junior  | W   | 0.653      | 0.435        | 0.078 (0.027)    | 0.786 (0.268)    | -         |    13.20 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           18 |     1160 | 2025-02-01 | Fnatic                | L   | 0.642      | -            | -                | -                | -         |    -6.52 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           17 |     3732 | 2024-11-10 | Johnny Speeds         | L   | 0.183      | -            | -                | -                | -         |    -3.22 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           16 |     3886 | 2024-11-07 | Natus Vincere Junior  | L   | 0.166      | -            | -                | -                | -         |    -1.89 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           15 |     3907 | 2024-11-07 | Sashi Esport          | L   | 0.165      | -            | -                | -                | -         |    -2.07 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           14 |     3935 | 2024-11-06 | BetBoom Team          | W   | 0.160      | 0.143        | 0.101 (0.003)    | -                | -         |     3.25 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           13 |     3994 | 2024-11-05 | Los kogutos           | W   | 0.155      | -            | -                | -                | -         |     2.26 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           12 |     4132 | 2024-11-03 | 3DMAX                 | L   | 0.142      | -            | -                | -                | -         |    -0.11 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           11 |     4193 | 2024-11-02 | Team Falcons          | L   | 0.138      | -            | -                | -                | -         |    -0.01 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           10 |     4261 | 2024-11-01 | Johnny Speeds         | L   | 0.132      | -            | -                | -                | -         |    -2.33 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            9 |     4403 | 2024-10-30 | 9INE                  | L   | 0.119      | -            | -                | -                | -         |    -2.89 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            8 |     4456 | 2024-10-29 | Zero Tenacity         | W   | 0.115      | -            | -                | -                | -         |     1.82 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            7 |     4463 | 2024-10-29 | Wu-Tang Clan          | W   | 0.114      | -            | -                | -                | -         |     0.36 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            6 |     4517 | 2024-10-28 | 500                   | L   | 0.109      | -            | -                | -                | -         |    -1.03 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            5 |     4637 | 2024-10-26 | BIG                   | W   | 0.097      | 0.934        | 0.234 (0.025)    | -                | -         |     2.90 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            4 |     4691 | 2024-10-25 | Virtus.pro            | W   | 0.092      | 0.934        | 0.320 (0.033)    | -                | -         |     2.86 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            3 |     4820 | 2024-10-21 | 3DMAX                 | L   | 0.071      | -            | -                | -                | -         |    -0.05 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            2 |     4853 | 2024-10-21 | Virtus.pro            | W   | 0.070      | 0.934        | 0.320 (0.025)    | -                | -         |     2.17 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            1 |     5433 | 2024-10-10 | Team Spirit Academy   | L   | 0.009      | -            | -                | -                | -         |    -0.12 | Buzz, Chr1zN, F1KU, MoDo, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,593.48)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.211 | $15.18         | $3.21           |
| 2024-11-03 |      0.172 | $50,000.00     | $8,590.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
