### Roster Details<br />
Team Name: G2 Esports<br />
Roster: HeavyGod, huNter-, m0NESY, malbsMd, Snax<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1499.6<br />
<br />
Final Rank Value (1499.6) = Starting Rank Value (1463.4) + Head To Head Adjustments (36.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.783[<sup>1</sup>](#table2)
- Bounty Collected: 0.545[<sup>2</sup>](#table1)
- Opponent Network: 0.112[<sup>2</sup>](#table1)
- LAN Wins: 0.489[<sup>2</sup>](#table1)

The average of these factors is 0.482<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1463.4
- 400 + ( ( 0.482 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1463.4


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
|           15 |     1105 | 2025-02-03 | FaZe Clan         | L   | 0.655      | -            | -                | -                | -         |    -3.11 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           14 |     1129 | 2025-02-02 | Team Falcons      | W   | 0.648      | 1.000        | 1.000 (0.778)    | 0.495 (0.385)    | 1 (0.778) |    18.58 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           13 |     1154 | 2025-02-01 | Virtus.pro        | L   | 0.643      | -            | -                | -                | -         |    -6.01 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           12 |     1288 | 2025-01-25 | Eternal Fire      | L   | 0.604      | -            | -                | -                | -         |    -1.47 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           11 |     1362 | 2025-01-23 | BetBoom Team      | W   | 0.594      | 0.769        | 0.101 (0.055)    | 0.308 (0.168)    | 1 (0.712) |     1.38 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|           10 |     1424 | 2025-01-19 | BIG               | W   | 0.572      | 0.363        | 0.234 (0.058)    | 0.400 (0.100)    | 0 (0.000) |     7.12 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|            9 |     1444 | 2025-01-17 | B8                | W   | 0.561      | 0.363        | 0.134 (0.033)    | 0.740 (0.181)    | -         |     1.95 | HeavyGod, huNter-, m0NESY, malbsMd, Snax |
|            8 |     3025 | 2024-11-23 | Team Spirit       | W   | 0.253      | 0.143        | 1.000 (0.043)    | 0.503 (0.022)    | 1 (0.303) |     7.50 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            7 |     3110 | 2024-11-22 | 3DMAX             | L   | 0.247      | -            | -                | -                | -         |    -3.02 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            6 |     3170 | 2024-11-21 | 9Pandas           | W   | 0.242      | 0.143        | 0.084 (0.003)    | 0.481 (0.020)    | 1 (0.290) |     0.55 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            5 |     3187 | 2024-11-20 | Ninjas in Pyjamas | W   | 0.240      | -            | -                | -                | 1 (0.288) |     0.21 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            4 |     4153 | 2024-11-03 | Team Spirit       | W   | 0.141      | 1.000        | 1.000 (0.170)    | 0.503 (0.085)    | 1 (0.170) |     4.22 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            3 |     4219 | 2024-11-02 | Team Vitality     | W   | 0.136      | 1.000        | 1.000 (0.163)    | 0.333 (0.054)    | 1 (0.163) |     3.86 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            2 |     4315 | 2024-10-31 | Team Spirit       | W   | 0.126      | 1.000        | 1.000 (0.151)    | 0.503 (0.076)    | 1 (0.151) |     3.77 | huNter-, m0NESY, malbsMd, NiKo, Snax     |
|            1 |     4400 | 2024-10-30 | Team Liquid       | W   | 0.120      | 1.000        | 0.075 (0.011)    | 0.180 (0.026)    | 1 (0.144) |     0.64 | huNter-, m0NESY, malbsMd, NiKo, Snax     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,860.42)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.53) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $16,000.00     | $13,200.00      |
| 2025-01-26 |      0.731 | $17,500.00     | $12,799.31      |
| 2024-11-03 |      0.170 | $500,000.00    | $84,861.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
