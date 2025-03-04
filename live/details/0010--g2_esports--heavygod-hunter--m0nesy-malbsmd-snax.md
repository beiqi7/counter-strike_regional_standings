### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HeavyGod, huNter-, m0NESY, malbsMd, Snax<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1723.2<br />
<br />
Final Rank Value (1723.2) = Starting Rank Value (1695.3) + Head To Head Adjustments (27.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.987[<sup>1</sup>](#table2)
- Bounty Collected: 0.637[<sup>2</sup>](#table1)
- Opponent Network: 0.205[<sup>2</sup>](#table1)
- LAN Wins: 0.661[<sup>2</sup>](#table1)

The average of these factors is 0.623<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.3
- 400 + ( ( 0.623 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1695.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1083 | 2025-02-03 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |   -13.47 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           25 |     1106 | 2025-02-02 | Team Falcons      | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.565 (0.565)    | 1 (1.000) |    21.56 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           24 |     1131 | 2025-02-01 | Virtus.pro        | L   | 0.996      | -            | -                | -                | -         |   -18.72 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           23 |     1236 | 2025-01-25 | Eternal Fire      | L   | 0.950      | -            | -                | -                | -         |    -7.95 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           22 |     1273 | 2025-01-23 | BetBoom Team      | W   | 0.937      | 0.769        | 0.122 (0.088)    | 0.387 (0.279)    | 1 (0.937) |     0.97 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           21 |     1304 | 2025-01-19 | BIG               | W   | 0.911      | 0.363        | 0.244 (0.081)    | 0.528 (0.174)    | -         |     4.75 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           20 |     1324 | 2025-01-17 | B8                | W   | 0.898      | 0.363        | -                | 0.790 (0.257)    | -         |     1.43 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           19 |     2904 | 2024-11-23 | Team Spirit       | W   | 0.528      | 0.143        | 1.000 (0.075)    | -                | 1 (0.528) |    13.18 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           18 |     2992 | 2024-11-22 | 3DMAX             | L   | 0.521      | -            | -                | -                | -         |   -11.33 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           17 |     3051 | 2024-11-21 | 9Pandas           | W   | 0.515      | -            | -                | -                | 1 (0.515) |     0.51 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           16 |     3068 | 2024-11-20 | Ninjas in Pyjamas | W   | 0.513      | -            | -                | -                | 1 (0.513) |     0.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           15 |     4012 | 2024-11-03 | Team Spirit       | W   | 0.395      | 1.000        | 1.000 (0.395)    | 0.569 (0.225)    | 1 (0.395) |    10.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           14 |     4081 | 2024-11-02 | Team Vitality     | W   | 0.388      | 1.000        | 1.000 (0.388)    | 0.391 (0.152)    | 1 (0.388) |     9.21 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           13 |     4175 | 2024-10-31 | Team Spirit       | W   | 0.376      | 1.000        | 1.000 (0.376)    | 0.569 (0.214)    | 1 (0.376) |     9.89 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           12 |     4252 | 2024-10-30 | Team Liquid       | W   | 0.368      | 1.000        | -                | 0.198 (0.073)    | 1 (0.368) |     0.83 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           11 |     5336 | 2024-10-08 | Eternal Fire      | L   | 0.223      | -            | -                | -                | -         |    -1.42 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           10 |     5395 | 2024-10-07 | Team Falcons      | L   | 0.216      | -            | -                | -                | -         |    -1.49 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            9 |     5863 | 2024-09-29 | Natus Vincere     | W   | 0.162      | 0.729        | 0.602 (0.071)    | 0.434 (0.051)    | 1 (0.162) |     2.60 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            8 |     5946 | 2024-09-28 | Team Vitality     | W   | 0.156      | 0.729        | 1.000 (0.114)    | -                | -         |     3.81 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            7 |     6035 | 2024-09-27 | Team Spirit       | W   | 0.149      | 0.729        | 1.000 (0.109)    | 0.569 (0.062)    | -         |     3.96 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            6 |     6113 | 2024-09-26 | Natus Vincere     | L   | 0.142      | -            | -                | -                | -         |    -2.20 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            5 |     6208 | 2024-09-25 | FaZe Clan         | W   | 0.135      | -            | -                | -                | -         |     2.88 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            4 |     6470 | 2024-09-21 | Natus Vincere     | L   | 0.110      | -            | -                | -                | -         |    -1.72 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            3 |     6524 | 2024-09-20 | Team Liquid       | W   | 0.103      | -            | -                | -                | -         |     0.24 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            2 |     7226 | 2024-09-08 | MIBR              | W   | 0.023      | -            | -                | -                | -         |     0.03 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            1 |     7484 | 2024-09-05 | 3DMAX             | W   | 0.003      | -            | -                | -                | -         |     0.03 | huNter-, m0NESY, malbsMd, NiKo, Snax     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($268,780.21)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.97) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2025-01-26 |      0.956 | $17,500.00     | $16,735.22      |
| 2024-11-03 |      0.395 | $500,000.00    | $197,315.86     |
| 2024-10-13 |      0.257 | $4,000.00      | $1,026.30       |
| 2024-09-29 |      0.162 | $200,000.00    | $32,481.90      |
| 2024-09-22 |      0.116 | $45,000.00     | $5,220.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
