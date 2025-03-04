### Roster Details<br />
Team Name: MIBR<br />
Roster: drop, exit, insani, Lucaozy, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1130.7<br />
<br />
Final Rank Value (1130.7) = Starting Rank Value (1150.2) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.519[<sup>1</sup>](#table2)
- Bounty Collected: 0.500[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.276[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.2
- 400 + ( ( 0.361 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1150.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      415 | 2025-02-17 | Astralis                 | L   | 1.000      | -            | -                | -                | -         |    -1.15 | drop, exit, insani, Lucaozy, saffee |
|           41 |      474 | 2025-02-16 | 3DMAX                    | L   | 1.000      | -            | -                | -                | -         |    -2.21 | drop, exit, insani, Lucaozy, saffee |
|           40 |      517 | 2025-02-15 | Imperial Female          | W   | 1.000      | 1.000        | 0.160 (0.160)    | 0.213 (0.213)    | 1 (1.000) |    12.34 | drop, exit, insani, Lucaozy, saffee |
|           39 |      566 | 2025-02-14 | Wildcard                 | L   | 1.000      | -            | -                | -                | -         |   -15.01 | drop, exit, insani, Lucaozy, saffee |
|           38 |      696 | 2025-02-09 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -20.78 | drop, exit, insani, Lucaozy, saffee |
|           37 |      712 | 2025-02-09 | Sharks Esports           | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.683 (0.098)    | 0 (0.000) |    12.80 | drop, exit, insani, Lucaozy, saffee |
|           36 |      763 | 2025-02-08 | Legacy                   | W   | 1.000      | 0.143        | 0.043 (0.006)    | 0.628 (0.090)    | 0 (0.000) |     8.39 | drop, exit, insani, Lucaozy, saffee |
|           35 |     1161 | 2025-01-31 | Virtus.pro               | L   | 0.990      | -            | -                | -                | -         |    -1.72 | drop, exit, insani, Lucaozy, saffee |
|           34 |     1169 | 2025-01-30 | 3DMAX                    | L   | 0.983      | -            | -                | -                | -         |    -2.49 | drop, exit, insani, Lucaozy, saffee |
|           33 |     1181 | 2025-01-29 | Astralis                 | W   | 0.975      | 1.000        | 0.734 (0.716)    | 0.811 (0.791)    | 1 (0.975) |    30.11 | drop, exit, insani, Lucaozy, saffee |
|           32 |     1345 | 2025-01-14 | FlyQuest                 | L   | 0.875      | -            | -                | -                | -         |   -10.30 | drop, exit, insani, Lucaozy, saffee |
|           31 |     4510 | 2024-10-25 | Monte                    | L   | 0.337      | -            | -                | -                | -         |    -8.40 | drop, exit, insani, Lucaozy, saffee |
|           30 |     4524 | 2024-10-25 | Legacy                   | L   | 0.336      | -            | -                | -                | -         |    -8.20 | drop, exit, insani, Lucaozy, saffee |
|           29 |     4679 | 2024-10-20 | PaiN Gaming              | L   | 0.304      | -            | -                | -                | -         |    -1.21 | drop, exit, insani, Lucaozy, saffee |
|           28 |     4747 | 2024-10-19 | BESTIA                   | W   | 0.298      | 0.450        | 0.081 (0.011)    | 0.433 (0.058)    | 0 (0.000) |     2.15 | drop, exit, insani, Lucaozy, saffee |
|           27 |     4833 | 2024-10-17 | PaiN Gaming              | L   | 0.285      | -            | -                | -                | -         |    -1.13 | drop, exit, insani, Lucaozy, saffee |
|           26 |     4886 | 2024-10-16 | RED Canids               | W   | 0.278      | -            | -                | -                | 0 (0.000) |     1.45 | drop, exit, insani, Lucaozy, saffee |
|           25 |     5234 | 2024-10-09 | RED Canids               | W   | 0.232      | -            | -                | -                | 0 (0.000) |     1.19 | drop, exit, insani, Lucaozy, saffee |
|           24 |     5242 | 2024-10-09 | RED Canids               | W   | 0.231      | -            | -                | -                | -         |     1.21 | drop, exit, insani, Lucaozy, saffee |
|           23 |     5304 | 2024-10-08 | KRÜ Esports              | W   | 0.225      | -            | -                | -                | -         |     0.53 | drop, exit, insani, Lucaozy, saffee |
|           22 |     5312 | 2024-10-08 | KRÜ Esports              | W   | 0.225      | -            | -                | -                | -         |     0.53 | drop, exit, insani, Lucaozy, saffee |
|           21 |     5327 | 2024-10-08 | PaiN Gaming              | L   | 0.224      | -            | -                | -                | -         |    -0.79 | drop, exit, insani, Lucaozy, saffee |
|           20 |     5332 | 2024-10-08 | PaiN Gaming              | L   | 0.224      | -            | -                | -                | -         |    -0.80 | drop, exit, insani, Lucaozy, saffee |
|           19 |     5419 | 2024-10-06 | Imperial Esports         | W   | 0.212      | 0.450        | 0.083 (0.008)    | 0.533 (0.051)    | -         |     1.60 | drop, exit, insani, Lucaozy, saffee |
|           18 |     5421 | 2024-10-06 | Imperial Esports         | L   | 0.211      | -            | -                | -                | -         |    -5.11 | drop, exit, insani, Lucaozy, saffee |
|           17 |     5558 | 2024-10-04 | Fluxo                    | L   | 0.198      | -            | -                | -                | -         |    -4.28 | drop, exit, insani, Lucaozy, saffee |
|           16 |     5560 | 2024-10-04 | Fluxo                    | W   | 0.198      | 0.450        | 0.065 (0.006)    | 0.479 (0.043)    | -         |     1.98 | drop, exit, insani, Lucaozy, saffee |
|           15 |     5648 | 2024-10-02 | Players (Brazilian team) | W   | 0.185      | -            | -                | -                | -         |     0.09 | drop, exit, insani, Lucaozy, saffee |
|           14 |     5654 | 2024-10-02 | Players (Brazilian team) | W   | 0.185      | -            | -                | -                | -         |     0.09 | drop, exit, insani, Lucaozy, saffee |
|           13 |     5717 | 2024-10-01 | Case Esports             | W   | 0.179      | -            | -                | -                | -         |     0.45 | drop, exit, insani, Lucaozy, saffee |
|           12 |     5721 | 2024-10-01 | Case Esports             | L   | 0.178      | -            | -                | -                | -         |    -5.18 | drop, exit, insani, Lucaozy, saffee |
|           11 |     5738 | 2024-10-01 | Sharks Esports           | L   | 0.177      | -            | -                | -                | -         |    -3.00 | drop, exit, insani, Lucaozy, saffee |
|           10 |     5741 | 2024-10-01 | Sharks Esports           | W   | 0.177      | 0.450        | 0.064 (0.005)    | 0.683 (0.054)    | -         |     2.61 | drop, exit, insani, Lucaozy, saffee |
|            9 |     6083 | 2024-09-26 | BESTIA                   | L   | 0.144      | -            | -                | -                | -         |    -3.67 | drop, exit, insani, Lucaozy, saffee |
|            8 |     6152 | 2024-09-25 | Team Solid               | W   | 0.138      | -            | -                | -                | -         |     0.75 | drop, exit, insani, Lucaozy, saffee |
|            7 |     6158 | 2024-09-25 | Team Solid               | L   | 0.138      | -            | -                | -                | -         |    -3.62 | drop, exit, insani, Lucaozy, saffee |
|            6 |     6194 | 2024-09-25 | Sharks Esports           | L   | 0.136      | -            | -                | -                | -         |    -2.28 | drop, exit, insani, Lucaozy, saffee |
|            5 |     6481 | 2024-09-21 | Eternal Fire             | L   | 0.109      | -            | -                | -                | -         |    -0.04 | brnz4n, drop, exit, insani, saffee  |
|            4 |     6601 | 2024-09-19 | M80                      | W   | 0.096      | 0.889        | 0.043 (0.004)    | 0.460 (0.039)    | 1 (0.096) |     0.74 | brnz4n, drop, exit, insani, saffee  |
|            3 |     6670 | 2024-09-18 | Team Falcons             | W   | 0.088      | 0.889        | 1.000 (0.078)    | 0.565 (0.044)    | 1 (0.088) |     2.75 | brnz4n, drop, exit, insani, saffee  |
|            2 |     7226 | 2024-09-08 | G2 Esports               | L   | 0.023      | -            | -                | -                | -         |    -0.03 | brnz4n, drop, exit, insani, saffee  |
|            1 |     7501 | 2024-09-05 | Team Spirit              | W   | 0.002      | -            | -                | -                | 1 (0.002) |     0.05 | brnz4n, drop, exit, insani, saffee  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32,666.95)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-10-27 |      0.350 | $2,000.00      | $700.74         |
| 2024-10-20 |      0.304 | $11,500.00     | $3,495.28       |
| 2024-09-22 |      0.116 | $45,000.00     | $5,220.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
