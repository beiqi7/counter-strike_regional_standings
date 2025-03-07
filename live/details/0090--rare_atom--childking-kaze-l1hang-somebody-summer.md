### Roster Details<br />
Team Name: Rare Atom<br />
Roster: ChildKing, kaze, L1haNg, somebody, Summer<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
<br />
Final Rank Value:  859.4<br />
<br />
Final Rank Value (859.4) = Starting Rank Value (824.7) + Head To Head Adjustments (34.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 824.7
- 400 + ( ( 0.193 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 824.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       81 | 2025-02-26 | Shika               | W   | 0.781      | 0.143        | 0.000 (0.000)    | 0.163 (0.022)    | 0 (0.000) |     3.56 | ChildKing, kaze, L1haNg, somebody, Summer |
|           17 |      123 | 2025-02-25 | DogEvil             | W   | 0.775      | 0.143        | 0.000 (0.000)    | 0.521 (0.069)    | 0 (0.000) |     4.57 | ChildKing, kaze, L1haNg, somebody, Summer |
|           16 |      159 | 2025-02-23 | T.Beast             | W   | 0.768      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.79 | ChildKing, kaze, L1haNg, somebody, Summer |
|           15 |      623 | 2025-02-12 | ATOX Esports        | L   | 0.707      | -            | -                | -                | -         |    -5.54 | ChildKing, kaze, L1haNg, somebody, Summer |
|           14 |      670 | 2025-02-10 | TYLOO               | W   | 0.697      | 0.143        | 0.052 (0.006)    | 0.200 (0.024)    | 0 (0.000) |    19.18 | ChildKing, kaze, L1haNg, somebody, Summer |
|           13 |      709 | 2025-02-09 | DogEvil             | W   | 0.691      | 0.143        | 0.000 (0.000)    | 0.521 (0.062)    | 0 (0.000) |     4.42 | ChildKing, kaze, L1haNg, somebody, Summer |
|           12 |      751 | 2025-02-08 | JiJieHao            | W   | 0.685      | 0.143        | 0.000 (0.000)    | 0.252 (0.030)    | 0 (0.000) |     3.78 | ChildKing, kaze, L1haNg, somebody, Summer |
|           11 |      825 | 2025-02-07 | DogEvil             | W   | 0.680      | 0.143        | 0.000 (0.000)    | 0.521 (0.061)    | 0 (0.000) |     4.15 | ChildKing, kaze, L1haNg, somebody, Summer |
|           10 |     1535 | 2024-12-28 | ATOX Esports        | L   | 0.452      | -            | -                | -                | -         |    -3.44 | ChildKing, L1haNg, somebody, Summer, z8z  |
|            9 |     1570 | 2024-12-28 | Eruption            | L   | 0.448      | -            | -                | -                | -         |    -5.58 | ChildKing, L1haNg, somebody, Summer, z8z  |
|            8 |     1596 | 2024-12-27 | The Huns Esports    | W   | 0.442      | 0.384        | 0.021 (0.004)    | 0.280 (0.057)    | 1 (0.530) |     8.71 | ChildKing, L1haNg, somebody, Summer, z8z  |
|            7 |     3655 | 2024-11-12 | TALON               | W   | 0.192      | 0.143        | -                | 0.258 (0.008)    | 1 (0.230) |     1.15 | ChildKing, kaze, L1haNg, somebody, Summer |
|            6 |     3711 | 2024-11-11 | Ex-GR Gaming        | W   | 0.186      | 0.143        | 0.008 (0.000)    | 0.028 (0.001)    | 1 (0.224) |     2.04 | ChildKing, kaze, L1haNg, somebody, Summer |
|            5 |     4318 | 2024-10-31 | Team Spirit Academy | L   | 0.126      | -            | -                | -                | -         |    -1.29 | ChildKing, kaze, L1haNg, somebody, Summer |
|            4 |     4324 | 2024-10-31 | CYBERSHOKE Esports  | W   | 0.125      | 0.143        | 0.014 (0.000)    | 1.000 (0.021)    | -         |     2.24 | ChildKing, kaze, L1haNg, somebody, Summer |
|            3 |     4399 | 2024-10-30 | Team Spirit Academy | L   | 0.120      | -            | -                | -                | -         |    -1.22 | ChildKing, kaze, L1haNg, somebody, Summer |
|            2 |     4435 | 2024-10-29 | Endpoint            | L   | 0.116      | -            | -                | -                | -         |    -2.13 | ChildKing, kaze, L1haNg, somebody, Summer |
|            1 |     4450 | 2024-10-29 | Johnny Speeds       | L   | 0.115      | -            | -                | -                | -         |    -1.70 | ChildKing, kaze, L1haNg, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,628.75)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.543 | $3,000.00      | $1,628.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
