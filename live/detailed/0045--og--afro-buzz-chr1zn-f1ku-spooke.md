### Roster Details<br />
Team Name: OG<br />
Roster: afro, Buzz, Chr1zN, F1KU, spooke<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1027.1<br />
<br />
Final Rank Value (1027.1) = Starting Rank Value (944.8) + Head To Head Adjustments (82.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.408[<sup>2</sup>](#table1)
- Opponent Network: 0.173[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.8
- 400 + ( ( 0.262 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 944.8


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
|           47 |      108 | 2025-02-25 | ESC Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           46 |      130 | 2025-02-24 | Iberian Soul          | L   | 1.000      | -            | -                | -                | -         |   -21.99 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           45 |      140 | 2025-02-24 | Tricked Esport        | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.702 (0.100)    | 0 (0.000) |     9.81 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           44 |      221 | 2025-02-22 | BC.Game Esports       | W   | 1.000      | 0.143        | 0.091 (0.013)    | 0.976 (0.139)    | 0 (0.000) |    23.32 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           43 |      281 | 2025-02-21 | Aurora Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.75 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           42 |      387 | 2025-02-17 | Leo Team              | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.763 (0.109)    | 0 (0.000) |    11.88 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           41 |      390 | 2025-02-17 | CYBERSHOKE Esports    | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    12.20 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           40 |      399 | 2025-02-17 | WeLoveUSmooya         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.57 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           39 |      406 | 2025-02-17 | Moneytrees            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.31 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           38 |      422 | 2025-02-16 | QUAZAR                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.68 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           37 |      513 | 2025-02-15 | Rebels Gaming         | L   | 1.000      | -            | -                | -                | -         |   -21.91 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           36 |      541 | 2025-02-14 | PARIVISION            | W   | 1.000      | 0.143        | -                | 0.869 (0.124)    | 0 (0.000) |    12.51 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           35 |      668 | 2025-02-10 | BIG                   | L   | 1.000      | -            | -                | -                | -         |    -3.18 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           34 |      678 | 2025-02-10 | Astralis              | L   | 1.000      | -            | -                | -                | -         |    -0.36 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           33 |      715 | 2025-02-09 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -15.74 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           32 |      720 | 2025-02-09 | Sashi Esport          | L   | 1.000      | -            | -                | -                | -         |   -16.76 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           31 |      751 | 2025-02-08 | TEAM NEXT LEVEL       | W   | 1.000      | -            | -                | -                | -         |     7.30 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           30 |      760 | 2025-02-08 | Benched               | W   | 1.000      | -            | -                | -                | -         |     2.84 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           29 |      770 | 2025-02-08 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -10.70 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           28 |      780 | 2025-02-08 | Mission Possible      | W   | 1.000      | -            | -                | -                | -         |     2.74 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           27 |      842 | 2025-02-07 | Nuclear TigeRES       | W   | 1.000      | -            | -                | -                | -         |     7.11 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           26 |      866 | 2025-02-07 | AMKAL ESPORTS         | W   | 1.000      | -            | -                | -                | -         |    10.14 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           25 |      921 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |    13.47 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           24 |      943 | 2025-02-05 | SINNERS Esports       | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | -         |    16.71 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           23 |     1096 | 2025-02-03 | Natus Vincere Junior  | W   | 1.000      | 0.435        | 0.106 (0.046)    | 1.000 (0.435)    | -         |    19.71 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           22 |     1135 | 2025-02-01 | Fnatic                | L   | 0.995      | -            | -                | -                | -         |    -7.97 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           21 |     3597 | 2024-11-10 | Johnny Speeds         | L   | 0.444      | -            | -                | -                | -         |    -7.18 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           20 |     3750 | 2024-11-07 | Natus Vincere Junior  | L   | 0.424      | -            | -                | -                | -         |    -4.95 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           19 |     3771 | 2024-11-07 | Sashi Esport          | L   | 0.423      | -            | -                | -                | -         |    -5.85 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           18 |     3797 | 2024-11-06 | BetBoom Team          | W   | 0.418      | 0.143        | 0.122 (0.007)    | -                | -         |     8.30 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           17 |     3854 | 2024-11-05 | Los kogutos           | W   | 0.411      | 0.384        | 0.037 (0.006)    | -                | -         |     6.20 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           16 |     3988 | 2024-11-03 | 3DMAX                 | L   | 0.396      | -            | -                | -                | -         |    -0.39 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           15 |     4052 | 2024-11-02 | Team Falcons          | L   | 0.390      | -            | -                | -                | -         |    -0.05 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           14 |     4122 | 2024-11-01 | Johnny Speeds         | L   | 0.383      | -            | -                | -                | -         |    -6.22 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           13 |     4253 | 2024-10-30 | 9INE                  | L   | 0.368      | -            | -                | -                | -         |    -8.15 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           12 |     4301 | 2024-10-29 | Zero Tenacity         | W   | 0.363      | -            | -                | -                | -         |     5.24 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           11 |     4307 | 2024-10-29 | Wu-Tang Clan          | W   | 0.362      | -            | -                | -                | -         |     0.90 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           10 |     4358 | 2024-10-28 | 500                   | L   | 0.357      | -            | -                | -                | -         |    -3.85 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            9 |     4474 | 2024-10-26 | BIG                   | W   | 0.342      | 0.934        | 0.244 (0.078)    | 0.528 (0.169)    | -         |    10.16 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            8 |     4523 | 2024-10-25 | Virtus.pro            | W   | 0.336      | 0.934        | 0.298 (0.094)    | 0.418 (0.131)    | -         |    10.41 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            7 |     4635 | 2024-10-21 | 3DMAX                 | L   | 0.311      | -            | -                | -                | -         |    -0.29 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            6 |     4665 | 2024-10-21 | Virtus.pro            | W   | 0.309      | 0.934        | 0.298 (0.086)    | 0.418 (0.121)    | -         |     9.60 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            5 |     5205 | 2024-10-10 | Team Spirit Academy   | L   | 0.236      | -            | -                | -                | -         |    -2.94 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|            4 |     6010 | 2024-09-27 | GameAgents            | L   | 0.151      | -            | -                | -                | -         |    -3.46 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            3 |     6035 | 2024-09-27 | B8                    | L   | 0.149      | -            | -                | -                | -         |    -0.87 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            2 |     6908 | 2024-09-14 | Sashi Esport          | L   | 0.063      | -            | -                | -                | -         |    -0.73 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            1 |     7040 | 2024-09-12 | Team Sampi            | W   | 0.048      | -            | -                | -                | -         |     0.53 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,988.24)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.436 | $15.18         | $6.63           |
| 2024-11-03 |      0.397 | $50,000.00     | $19,854.39      |
| 2024-09-14 |      0.064 | $2,000.00      | $127.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
