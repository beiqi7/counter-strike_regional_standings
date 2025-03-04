### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: Ax1Le, Boombl4, Magnojez, s1ren, zorte<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1118.0<br />
<br />
Final Rank Value (1118.0) = Starting Rank Value (1058.3) + Head To Head Adjustments (59.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.433[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.216[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1058.3
- 400 + ( ( 0.316 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1058.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      636 | 2025-02-11 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -0.90 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           30 |      643 | 2025-02-11 | Hesta              | W   | 1.000      | 0.143        | -                | 0.676 (0.097)    | 0 (0.000) |     5.39 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           29 |      672 | 2025-02-10 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |    -0.49 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           28 |      682 | 2025-02-10 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.204 (0.029)    | 0.424 (0.061)    | 0 (0.000) |    13.98 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           27 |      874 | 2025-02-07 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -19.80 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           26 |      920 | 2025-02-06 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     2.79 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           25 |      979 | 2025-02-05 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -21.34 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           24 |      990 | 2025-02-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     2.23 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           23 |     1273 | 2025-01-23 | G2 Esports         | L   | 0.937      | -            | -                | -                | -         |    -0.97 | Ax1Le, KaiR0N-, Magnojez, nafany, s1ren  |
|           22 |     1312 | 2025-01-19 | FURIA              | W   | 0.909      | 0.363        | 0.062 (0.020)    | 0.228 (0.075)    | 0 (0.000) |    17.74 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           21 |     1327 | 2025-01-17 | MOUZ               | W   | 0.897      | 0.363        | 1.000 (0.325)    | 0.420 (0.137)    | 0 (0.000) |    28.01 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           20 |     3126 | 2024-11-20 | GamerLegion        | L   | 0.509      | -            | -                | -                | -         |    -1.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           19 |     3136 | 2024-11-19 | SAW                | W   | 0.506      | 0.143        | 0.315 (0.023)    | -                | 1 (0.506) |    13.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           18 |     3176 | 2024-11-18 | Nemiga Gaming      | W   | 0.500      | 0.143        | 0.204 (0.015)    | -                | 1 (0.500) |     9.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           17 |     3218 | 2024-11-17 | Fnatic             | L   | 0.494      | -            | -                | -                | -         |    -6.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           16 |     3265 | 2024-11-17 | Team Vitality      | L   | 0.488      | -            | -                | -                | -         |    -0.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           15 |     3276 | 2024-11-16 | UNiTY esports      | W   | 0.488      | -            | -                | -                | 1 (0.488) |     3.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           14 |     3513 | 2024-11-12 | 500                | W   | 0.456      | 0.384        | 0.114 (0.020)    | 1.000 (0.175)    | -         |     7.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           13 |     3518 | 2024-11-12 | Ninjas in Pyjamas  | W   | 0.456      | 0.384        | 0.028 (0.005)    | -                | -         |     4.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           12 |     3565 | 2024-11-11 | Dynamo Eclot       | W   | 0.450      | 0.384        | 0.150 (0.026)    | 0.705 (0.122)    | -         |     8.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           11 |     3799 | 2024-11-06 | OG                 | L   | 0.417      | -            | -                | -                | -         |    -8.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           10 |     5185 | 2024-10-11 | FAVBET Team        | L   | 0.242      | -            | -                | -                | -         |    -5.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            9 |     5478 | 2024-10-05 | SAW                | L   | 0.204      | -            | -                | -                | -         |    -0.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            8 |     5513 | 2024-10-05 | Rooster            | W   | 0.203      | 0.500        | -                | 0.377 (0.038)    | 1 (0.203) |     0.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            7 |     5582 | 2024-10-04 | FlyQuest           | L   | 0.196      | -            | -                | -                | -         |    -1.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            6 |     5917 | 2024-09-28 | GamerLegion        | W   | 0.157      | -            | -                | -                | -         |     0.64 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            5 |     5973 | 2024-09-28 | 3DMAX              | W   | 0.155      | 0.435        | 0.302 (0.020)    | -                | -         |     4.66 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            4 |     6013 | 2024-09-27 | HEROIC             | W   | 0.150      | 0.435        | 0.154 (0.010)    | -                | -         |     2.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            3 |     6107 | 2024-09-26 | Monte              | W   | 0.143      | 0.435        | -                | 0.866 (0.054)    | -         |     1.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            2 |     7419 | 2024-09-06 | CYBERSHOKE Esports | L   | 0.008      | -            | -                | -                | -         |    -0.16 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            1 |     7493 | 2024-09-05 | Tricked Esport     | W   | 0.002      | -            | -                | -                | -         |     0.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,694.15)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-26 |      0.956 | $25,000.00     | $23,907.46      |
| 2024-11-12 |      0.456 | $12,500.00     | $5,705.18       |
| 2024-10-06 |      0.211 | $3,000.00      | $633.27         |
| 2024-09-28 |      0.157 | $22,000.00     | $3,448.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
