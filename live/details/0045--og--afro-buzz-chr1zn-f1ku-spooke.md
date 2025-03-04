### Roster Details<br />
Team Name: OG<br />
Roster: afro, Buzz, Chr1zN, F1KU, spooke<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1027.0<br />
<br />
Final Rank Value (1027.0) = Starting Rank Value (944.8) + Head To Head Adjustments (82.2)<br />

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
|           47 |      110 | 2025-02-25 | ESC Gaming            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           46 |      132 | 2025-02-24 | Iberian Soul          | L   | 1.000      | -            | -                | -                | -         |   -21.99 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           45 |      142 | 2025-02-24 | Tricked Esport        | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.702 (0.100)    | 0 (0.000) |     9.81 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           44 |      223 | 2025-02-22 | BC.Game Esports       | W   | 1.000      | 0.143        | 0.091 (0.013)    | 0.976 (0.139)    | 0 (0.000) |    23.32 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           43 |      283 | 2025-02-21 | Aurora Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.75 | Buzz, Chr1zN, F1KU, nicoodoz, spooke |
|           42 |      389 | 2025-02-17 | Leo Team              | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.763 (0.109)    | 0 (0.000) |    11.88 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           41 |      392 | 2025-02-17 | CYBERSHOKE Esports    | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |    12.20 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           40 |      401 | 2025-02-17 | WeLoveUSmooya         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.57 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           39 |      408 | 2025-02-17 | Moneytrees            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.31 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           38 |      424 | 2025-02-16 | QUAZAR                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.68 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           37 |      515 | 2025-02-15 | Rebels Gaming         | L   | 1.000      | -            | -                | -                | -         |   -21.91 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           36 |      543 | 2025-02-14 | PARIVISION            | W   | 1.000      | 0.143        | -                | 0.870 (0.124)    | 0 (0.000) |    12.51 | afro, Buzz, Chr1zN, F1KU, spooke     |
|           35 |      670 | 2025-02-10 | BIG                   | L   | 1.000      | -            | -                | -                | -         |    -3.18 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           34 |      680 | 2025-02-10 | Astralis              | L   | 1.000      | -            | -                | -                | -         |    -0.36 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           33 |      717 | 2025-02-09 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -15.74 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           32 |      722 | 2025-02-09 | Sashi Esport          | L   | 1.000      | -            | -                | -                | -         |   -16.76 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           31 |      753 | 2025-02-08 | TEAM NEXT LEVEL       | W   | 1.000      | -            | -                | -                | -         |     7.30 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           30 |      762 | 2025-02-08 | Benched               | W   | 1.000      | -            | -                | -                | -         |     2.84 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           29 |      772 | 2025-02-08 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -10.69 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           28 |      782 | 2025-02-08 | Mission Possible      | W   | 1.000      | -            | -                | -                | -         |     2.74 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           27 |      844 | 2025-02-07 | Nuclear TigeRES       | W   | 1.000      | -            | -                | -                | -         |     7.11 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           26 |      868 | 2025-02-07 | AMKAL ESPORTS         | W   | 1.000      | -            | -                | -                | -         |    10.14 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           25 |      923 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |    13.47 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           24 |      945 | 2025-02-05 | SINNERS Esports       | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | -         |    16.71 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           23 |     1098 | 2025-02-03 | Natus Vincere Junior  | W   | 1.000      | 0.435        | 0.106 (0.046)    | 1.000 (0.435)    | -         |    19.71 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           22 |     1137 | 2025-02-01 | Fnatic                | L   | 0.995      | -            | -                | -                | -         |    -7.97 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|           21 |     3599 | 2024-11-10 | Johnny Speeds         | L   | 0.444      | -            | -                | -                | -         |    -7.17 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           20 |     3752 | 2024-11-07 | Natus Vincere Junior  | L   | 0.424      | -            | -                | -                | -         |    -4.94 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           19 |     3773 | 2024-11-07 | Sashi Esport          | L   | 0.422      | -            | -                | -                | -         |    -5.84 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           18 |     3799 | 2024-11-06 | BetBoom Team          | W   | 0.417      | 0.143        | 0.122 (0.007)    | -                | -         |     8.31 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           17 |     3856 | 2024-11-05 | Los kogutos           | W   | 0.410      | 0.384        | 0.037 (0.006)    | -                | -         |     6.19 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           16 |     3990 | 2024-11-03 | 3DMAX                 | L   | 0.396      | -            | -                | -                | -         |    -0.39 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           15 |     4054 | 2024-11-02 | Team Falcons          | L   | 0.390      | -            | -                | -                | -         |    -0.05 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           14 |     4124 | 2024-11-01 | Johnny Speeds         | L   | 0.383      | -            | -                | -                | -         |    -6.22 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           13 |     4255 | 2024-10-30 | 9INE                  | L   | 0.368      | -            | -                | -                | -         |    -8.14 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           12 |     4303 | 2024-10-29 | Zero Tenacity         | W   | 0.363      | -            | -                | -                | -         |     5.23 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           11 |     4309 | 2024-10-29 | Wu-Tang Clan          | W   | 0.362      | -            | -                | -                | -         |     0.90 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|           10 |     4360 | 2024-10-28 | 500                   | L   | 0.356      | -            | -                | -                | -         |    -3.85 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            9 |     4476 | 2024-10-26 | BIG                   | W   | 0.341      | 0.934        | 0.244 (0.078)    | 0.528 (0.168)    | -         |    10.15 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            8 |     4525 | 2024-10-25 | Virtus.pro            | W   | 0.335      | 0.934        | 0.299 (0.094)    | 0.419 (0.131)    | -         |    10.40 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            7 |     4637 | 2024-10-21 | 3DMAX                 | L   | 0.310      | -            | -                | -                | -         |    -0.29 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            6 |     4667 | 2024-10-21 | Virtus.pro            | W   | 0.309      | 0.934        | 0.299 (0.086)    | 0.419 (0.121)    | -         |     9.59 | Buzz, Chr1zN, F1KU, M1key, MoDo      |
|            5 |     5207 | 2024-10-10 | Team Spirit Academy   | L   | 0.236      | -            | -                | -                | -         |    -2.93 | Buzz, Chr1zN, F1KU, MoDo, spooke     |
|            4 |     6012 | 2024-09-27 | GameAgents            | L   | 0.150      | -            | -                | -                | -         |    -3.46 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            3 |     6037 | 2024-09-27 | B8                    | L   | 0.149      | -            | -                | -                | -         |    -0.87 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            2 |     6910 | 2024-09-14 | Sashi Esport          | L   | 0.062      | -            | -                | -                | -         |    -0.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |
|            1 |     7042 | 2024-09-12 | Team Sampi            | W   | 0.048      | -            | -                | -                | -         |     0.52 | Buzz, Chr1zN, F1KU, MoDo, Nexius     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,968.86)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.436 | $15.18         | $6.62           |
| 2024-11-03 |      0.397 | $50,000.00     | $19,835.75      |
| 2024-09-14 |      0.063 | $2,000.00      | $126.49         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
