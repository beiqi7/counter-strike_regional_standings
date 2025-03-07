### Roster Details<br />
Team Name: MIBR<br />
Roster: drop, exit, insani, Lucaozy, saffee<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1216.1<br />
<br />
Final Rank Value (1216.1) = Starting Rank Value (1225.6) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.471[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.423[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1225.6
- 400 + ( ( 0.374 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1225.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |        1 | 2025-03-04 | TYLOO            | W   | 0.815      | 0.415        | 0.052 (0.021)    | 0.200 (0.081)    | 1 (0.978) |    11.92 | drop, exit, insani, Lucaozy, saffee |
|           20 |      438 | 2025-02-17 | Astralis         | L   | 0.731      | -            | -                | -                | -         |    -0.77 | drop, exit, insani, Lucaozy, saffee |
|           19 |      497 | 2025-02-16 | 3DMAX            | L   | 0.725      | -            | -                | -                | -         |    -2.72 | drop, exit, insani, Lucaozy, saffee |
|           18 |      541 | 2025-02-15 | Imperial Female  | W   | 0.720      | 1.000        | 0.146 (0.126)    | 0.159 (0.137)    | 1 (0.864) |     5.72 | drop, exit, insani, Lucaozy, saffee |
|           17 |      589 | 2025-02-14 | Wildcard         | L   | 0.715      | -            | -                | -                | -         |   -13.76 | drop, exit, insani, Lucaozy, saffee |
|           16 |      717 | 2025-02-09 | Imperial Esports | L   | 0.689      | -            | -                | -                | -         |   -17.77 | drop, exit, insani, Lucaozy, saffee |
|           15 |      733 | 2025-02-09 | Sharks Esports   | W   | 0.688      | 0.143        | 0.051 (0.006)    | 0.636 (0.075)    | 0 (0.000) |     6.20 | drop, exit, insani, Lucaozy, saffee |
|           14 |      785 | 2025-02-08 | Legacy           | W   | 0.683      | 0.143        | 0.032 (0.004)    | 0.556 (0.065)    | 0 (0.000) |     2.85 | drop, exit, insani, Lucaozy, saffee |
|           13 |     1185 | 2025-01-31 | Virtus.pro       | L   | 0.637      | -            | -                | -                | -         |    -1.80 | drop, exit, insani, Lucaozy, saffee |
|           12 |     1193 | 2025-01-30 | 3DMAX            | L   | 0.632      | -            | -                | -                | -         |    -2.86 | drop, exit, insani, Lucaozy, saffee |
|           11 |     1207 | 2025-01-29 | Astralis         | W   | 0.625      | 1.000        | 0.788 (0.592)    | 0.807 (0.606)    | 1 (0.751) |    19.24 | drop, exit, insani, Lucaozy, saffee |
|           10 |     1465 | 2025-01-14 | FlyQuest         | L   | 0.542      | -            | -                | -                | -         |   -10.55 | drop, exit, insani, Lucaozy, saffee |
|            9 |     4672 | 2024-10-25 | Monte            | L   | 0.093      | -            | -                | -                | -         |    -2.68 | drop, exit, insani, Lucaozy, saffee |
|            8 |     4689 | 2024-10-25 | Legacy           | L   | 0.092      | -            | -                | -                | -         |    -2.59 | drop, exit, insani, Lucaozy, saffee |
|            7 |     4866 | 2024-10-20 | PaiN Gaming      | L   | 0.066      | -            | -                | -                | -         |    -0.19 | drop, exit, insani, Lucaozy, saffee |
|            6 |     4934 | 2024-10-19 | BESTIA           | W   | 0.061      | 0.450        | 0.057 (0.002)    | 0.459 (0.015)    | 0 (0.000) |     0.23 | drop, exit, insani, Lucaozy, saffee |
|            5 |     5025 | 2024-10-17 | PaiN Gaming      | L   | 0.050      | -            | -                | -                | -         |    -0.14 | drop, exit, insani, Lucaozy, saffee |
|            4 |     5082 | 2024-10-16 | RED Canids       | W   | 0.044      | 0.450        | 0.002 (0.000)    | 0.196 (0.005)    | 0 (0.000) |     0.09 | drop, exit, insani, Lucaozy, saffee |
|            3 |     5464 | 2024-10-09 | RED Canids       | W   | 0.006      | 0.450        | 0.002 (0.000)    | 0.196 (0.001)    | 0 (0.000) |     0.01 | drop, exit, insani, Lucaozy, saffee |
|            2 |     5473 | 2024-10-09 | RED Canids       | W   | 0.005      | 0.450        | 0.002 (0.000)    | 0.196 (0.001)    | 0 (0.000) |     0.01 | drop, exit, insani, Lucaozy, saffee |
|            1 |     5543 | 2024-10-08 | KRÜ Esports      | W   | 0.000      | 0.450        | 0.001 (0.000)    | 0.318 (0.000)    | 0 (0.000) |     0.00 | drop, exit, insani, Lucaozy, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,100.54)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $18,750.00     | $17,228.30      |
| 2025-02-09 |      0.825 | $4,500.00      | $3,712.50       |
| 2024-10-27 |      0.125 | $2,000.00      | $250.93         |
| 2024-10-20 |      0.079 | $11,500.00     | $908.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
