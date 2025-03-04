### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HeavyGod, huNter-, m0NESY, malbsMd, Snax<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1723.5<br />
<br />
Final Rank Value (1723.5) = Starting Rank Value (1695.7) + Head To Head Adjustments (27.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.987[<sup>1</sup>](#table2)
- Bounty Collected: 0.637[<sup>2</sup>](#table1)
- Opponent Network: 0.205[<sup>2</sup>](#table1)
- LAN Wins: 0.662[<sup>2</sup>](#table1)

The average of these factors is 0.623<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.7
- 400 + ( ( 0.623 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1695.7


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
|           26 |     1081 | 2025-02-03 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |   -13.49 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           25 |     1104 | 2025-02-02 | Team Falcons      | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.565 (0.565)    | 1 (1.000) |    21.54 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           24 |     1129 | 2025-02-01 | Virtus.pro        | L   | 0.997      | -            | -                | -                | -         |   -18.74 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           23 |     1234 | 2025-01-25 | Eternal Fire      | L   | 0.950      | -            | -                | -                | -         |    -7.97 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           22 |     1271 | 2025-01-23 | BetBoom Team      | W   | 0.938      | 0.769        | 0.122 (0.088)    | 0.387 (0.279)    | 1 (0.938) |     0.95 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           21 |     1302 | 2025-01-19 | BIG               | W   | 0.911      | 0.363        | 0.244 (0.081)    | 0.528 (0.175)    | -         |     4.75 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           20 |     1322 | 2025-01-17 | B8                | W   | 0.899      | 0.363        | -                | 0.790 (0.257)    | -         |     1.43 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           19 |     2902 | 2024-11-23 | Team Spirit       | W   | 0.529      | 0.143        | 1.000 (0.076)    | -                | 1 (0.529) |    13.18 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           18 |     2990 | 2024-11-22 | 3DMAX             | L   | 0.522      | -            | -                | -                | -         |   -11.34 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           17 |     3049 | 2024-11-21 | 9Pandas           | W   | 0.516      | -            | -                | -                | 1 (0.516) |     0.51 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           16 |     3066 | 2024-11-20 | Ninjas in Pyjamas | W   | 0.514      | -            | -                | -                | 1 (0.514) |     0.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           15 |     4010 | 2024-11-03 | Team Spirit       | W   | 0.395      | 1.000        | 1.000 (0.395)    | 0.569 (0.225)    | 1 (0.395) |    10.16 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           14 |     4079 | 2024-11-02 | Team Vitality     | W   | 0.388      | 1.000        | 1.000 (0.388)    | 0.391 (0.152)    | 1 (0.388) |     9.21 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           13 |     4173 | 2024-10-31 | Team Spirit       | W   | 0.377      | 1.000        | 1.000 (0.377)    | 0.569 (0.214)    | 1 (0.377) |     9.89 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           12 |     4250 | 2024-10-30 | Team Liquid       | W   | 0.369      | 1.000        | -                | 0.198 (0.073)    | 1 (0.369) |     0.83 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           11 |     5334 | 2024-10-08 | Eternal Fire      | L   | 0.224      | -            | -                | -                | -         |    -1.42 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|           10 |     5393 | 2024-10-07 | Team Falcons      | L   | 0.217      | -            | -                | -                | -         |    -1.50 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            9 |     5861 | 2024-09-29 | Natus Vincere     | W   | 0.163      | 0.729        | 0.602 (0.071)    | 0.434 (0.052)    | 1 (0.163) |     2.58 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            8 |     5944 | 2024-09-28 | Team Vitality     | W   | 0.156      | 0.729        | 1.000 (0.114)    | -                | -         |     3.81 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            7 |     6033 | 2024-09-27 | Team Spirit       | W   | 0.149      | 0.729        | 1.000 (0.109)    | 0.569 (0.062)    | -         |     3.96 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            6 |     6111 | 2024-09-26 | Natus Vincere     | L   | 0.143      | -            | -                | -                | -         |    -2.22 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            5 |     6206 | 2024-09-25 | FaZe Clan         | W   | 0.136      | -            | -                | -                | -         |     2.89 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            4 |     6468 | 2024-09-21 | Natus Vincere     | L   | 0.110      | -            | -                | -                | -         |    -1.74 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            3 |     6522 | 2024-09-20 | Team Liquid       | W   | 0.104      | -            | -                | -                | -         |     0.24 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            2 |     7224 | 2024-09-08 | MIBR              | W   | 0.024      | -            | -                | -                | -         |     0.03 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            1 |     7482 | 2024-09-05 | 3DMAX             | W   | 0.003      | -            | -                | -                | -         |     0.04 | huNter-, m0NESY, malbsMd, NiKo, Snax     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($269,065.87)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.97) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2025-01-26 |      0.957 | $17,500.00     | $16,741.74      |
| 2024-11-03 |      0.395 | $500,000.00    | $197,502.20     |
| 2024-10-13 |      0.257 | $4,000.00      | $1,027.80       |
| 2024-09-29 |      0.163 | $200,000.00    | $32,556.44      |
| 2024-09-22 |      0.116 | $45,000.00     | $5,237.70       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
