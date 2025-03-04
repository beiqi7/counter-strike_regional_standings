### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: Ax1Le, Boombl4, Magnojez, s1ren, zorte<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1115.0<br />
<br />
Final Rank Value (1115.0) = Starting Rank Value (1057.6) + Head To Head Adjustments (57.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.217[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1057.6
- 400 + ( ( 0.316 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1057.6


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
|           31 |      634 | 2025-02-11 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -0.89 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           30 |      641 | 2025-02-11 | Hesta              | W   | 1.000      | 0.143        | -                | 0.676 (0.097)    | 0 (0.000) |     5.47 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           29 |      670 | 2025-02-10 | Team Falcons       | L   | 1.000      | -            | -                | -                | -         |    -0.48 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           28 |      680 | 2025-02-10 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.204 (0.029)    | 0.424 (0.061)    | 0 (0.000) |    14.01 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           27 |      872 | 2025-02-07 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -19.69 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           26 |      918 | 2025-02-06 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     2.84 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           25 |      977 | 2025-02-05 | Passion UA         | L   | 1.000      | -            | -                | -                | -         |   -21.22 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           24 |      988 | 2025-02-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     2.27 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           23 |     1271 | 2025-01-23 | G2 Esports         | L   | 0.938      | -            | -                | -                | -         |    -0.95 | Ax1Le, KaiR0N-, Magnojez, nafany, s1ren  |
|           22 |     1310 | 2025-01-19 | FURIA              | W   | 0.910      | 0.363        | 0.062 (0.020)    | 0.180 (0.059)    | 0 (0.000) |    14.80 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           21 |     1325 | 2025-01-17 | MOUZ               | W   | 0.898      | 0.363        | 1.000 (0.326)    | 0.420 (0.137)    | 0 (0.000) |    28.02 | Ax1Le, Boombl4, Magnojez, s1ren, zorte   |
|           20 |     3124 | 2024-11-20 | GamerLegion        | L   | 0.510      | -            | -                | -                | -         |    -1.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           19 |     3134 | 2024-11-19 | SAW                | W   | 0.506      | 0.143        | 0.315 (0.023)    | -                | 1 (0.506) |    13.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           18 |     3174 | 2024-11-18 | Nemiga Gaming      | W   | 0.501      | 0.143        | 0.204 (0.015)    | -                | 1 (0.501) |     9.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           17 |     3216 | 2024-11-17 | Fnatic             | L   | 0.494      | -            | -                | -                | -         |    -6.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           16 |     3263 | 2024-11-17 | Team Vitality      | L   | 0.489      | -            | -                | -                | -         |    -0.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           15 |     3274 | 2024-11-16 | UNiTY esports      | W   | 0.488      | -            | -                | -                | 1 (0.488) |     3.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           14 |     3511 | 2024-11-12 | 500                | W   | 0.457      | 0.384        | 0.114 (0.020)    | 1.000 (0.176)    | -         |     7.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           13 |     3516 | 2024-11-12 | Ninjas in Pyjamas  | W   | 0.456      | 0.384        | 0.028 (0.005)    | -                | -         |     4.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           12 |     3563 | 2024-11-11 | Dynamo Eclot       | W   | 0.450      | 0.384        | 0.150 (0.026)    | 0.705 (0.122)    | -         |     8.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           11 |     3797 | 2024-11-06 | OG                 | L   | 0.418      | -            | -                | -                | -         |    -8.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|           10 |     5183 | 2024-10-11 | FAVBET Team        | L   | 0.242      | -            | -                | -                | -         |    -5.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            9 |     5476 | 2024-10-05 | SAW                | L   | 0.205      | -            | -                | -                | -         |    -0.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            8 |     5511 | 2024-10-05 | Rooster            | W   | 0.203      | 0.500        | -                | 0.376 (0.038)    | 1 (0.203) |     0.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            7 |     5580 | 2024-10-04 | FlyQuest           | L   | 0.196      | -            | -                | -                | -         |    -1.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            6 |     5915 | 2024-09-28 | GamerLegion        | W   | 0.157      | -            | -                | -                | -         |     0.64 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            5 |     5971 | 2024-09-28 | 3DMAX              | W   | 0.155      | 0.435        | 0.302 (0.020)    | -                | -         |     4.67 | KaiR0N-, Magnojez, s1ren, SELLTER, zorte |
|            4 |     6011 | 2024-09-27 | HEROIC             | W   | 0.151      | 0.435        | 0.154 (0.010)    | -                | -         |     2.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            3 |     6105 | 2024-09-26 | Monte              | W   | 0.143      | 0.435        | -                | 0.866 (0.054)    | -         |     1.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            2 |     7417 | 2024-09-06 | CYBERSHOKE Esports | L   | 0.008      | -            | -                | -                | -         |    -0.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |
|            1 |     7491 | 2024-09-05 | Tricked Esport     | W   | 0.003      | -            | -                | -                | -         |     0.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,717.44)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-26 |      0.957 | $25,000.00     | $23,916.78      |
| 2024-11-12 |      0.457 | $12,500.00     | $5,709.84       |
| 2024-10-06 |      0.211 | $3,000.00      | $634.39         |
| 2024-09-28 |      0.157 | $22,000.00     | $3,456.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
