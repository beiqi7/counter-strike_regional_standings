### Roster Details<br />
Team Name: BC.Game Esports<br />
Roster: CYPHER, jkaem, nawwk, nexa, pr1metapz<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1044.7<br />
<br />
Final Rank Value (1044.7) = Starting Rank Value (1018.7) + Head To Head Adjustments (26.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.409[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.031[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1018.7
- 400 + ( ( 0.281 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1018.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       12 | 2025-02-28 | Monte                                     | L   | 0.794      | -            | -                | -                | -         |   -16.31 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           35 |       15 | 2025-02-28 | PARIVISION                                | L   | 0.793      | -            | -                | -                | -         |   -18.76 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           34 |       40 | 2025-02-27 | Rhyno Esports                             | W   | 0.786      | -            | -                | -                | 0 (0.000) |     3.01 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           33 |       65 | 2025-02-26 | Fnatic                                    | L   | 0.783      | -            | -                | -                | -         |   -14.34 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           32 |       78 | 2025-02-26 | PARIVISION                                | L   | 0.781      | -            | -                | -                | -         |   -18.95 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           31 |      151 | 2025-02-24 | 9INE                                      | W   | 0.769      | 0.143        | -                | 0.876 (0.116)    | 0 (0.000) |     7.55 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           30 |      169 | 2025-02-23 | Aurora Gaming                             | W   | 0.766      | -            | -                | -                | 0 (0.000) |     4.63 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           29 |      175 | 2025-02-23 | B8                                        | L   | 0.766      | -            | -                | -                | -         |   -11.50 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           28 |      189 | 2025-02-23 | Natus Vincere Junior                      | W   | 0.765      | 0.435        | 0.078 (0.031)    | 0.786 (0.314)    | 0 (0.000) |     7.97 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           27 |      229 | 2025-02-22 | OG                                        | L   | 0.760      | -            | -                | -                | -         |   -17.09 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           26 |      238 | 2025-02-22 | Partizan Esports                          | W   | 0.759      | 0.435        | 0.082 (0.032)    | 0.618 (0.245)    | 0 (0.000) |     9.79 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           25 |      292 | 2025-02-21 | EYEBALLERS                                | W   | 0.753      | -            | -                | -                | 0 (0.000) |     3.06 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           24 |      332 | 2025-02-20 | Nexus Gaming                              | W   | 0.747      | 0.435        | 0.161 (0.063)    | 0.539 (0.210)    | 0 (0.000) |     8.44 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           23 |      398 | 2025-02-18 | Copenhagen Wolves (American organization) | W   | 0.737      | 0.435        | 0.017 (0.006)    | 1.000 (0.384)    | -         |     4.80 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           22 |      422 | 2025-02-17 | GUN5 Esports                              | L   | 0.732      | -            | -                | -                | -         |   -15.41 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           21 |      583 | 2025-02-14 | 500                                       | W   | 0.716      | 0.435        | 0.118 (0.044)    | 1.000 (0.373)    | -         |    10.70 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           20 |      641 | 2025-02-12 | CYBERSHOKE Esports                        | W   | 0.703      | 0.435        | -                | 1.000 (0.366)    | -         |     4.07 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           19 |      690 | 2025-02-10 | Astralis                                  | W   | 0.693      | 0.143        | 0.788 (0.094)    | 0.807 (0.096)    | -         |    21.54 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           18 |      700 | 2025-02-10 | GTZ.ESPORTS                               | L   | 0.692      | -            | -                | -                | -         |    -9.21 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           17 |      702 | 2025-02-10 | BIG                                       | W   | 0.692      | 0.143        | 0.234 (0.028)    | -                | -         |    18.24 | CacaNito, CYPHER, nawwk, nexa, pr1metapz |
|           16 |      781 | 2025-02-08 | Zero Tenacity                             | W   | 0.683      | 0.143        | -                | 0.778 (0.091)    | -         |     5.96 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           15 |      790 | 2025-02-08 | Partizan Esports                          | W   | 0.682      | 0.143        | 0.082 (0.010)    | -                | -         |    10.10 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           14 |      796 | 2025-02-08 | Aurora Gaming                             | W   | 0.682      | -            | -                | -                | -         |     5.22 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           13 |      858 | 2025-02-07 | Ninjas in Pyjamas                         | W   | 0.678      | -            | -                | -                | -         |     2.15 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           12 |      897 | 2025-02-07 | 500                                       | L   | 0.675      | -            | -                | -                | -         |   -10.83 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           11 |      997 | 2025-02-05 | 500                                       | W   | 0.665      | 0.143        | 0.118 (0.013)    | 1.000 (0.114)    | -         |     9.88 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|           10 |     1007 | 2025-02-05 | SAW                                       | W   | 0.664      | 0.143        | 0.316 (0.036)    | -                | -         |    17.68 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|            9 |     1038 | 2025-02-04 | Team smooya (European mix-team)           | W   | 0.660      | -            | -                | -                | -         |     1.24 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|            8 |     1043 | 2025-02-04 | Ex-Illuminar Gaming                       | W   | 0.660      | -            | -                | -                | -         |     0.71 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|            7 |     1054 | 2025-02-04 | Maestro Esports (Belgian team)            | W   | 0.659      | -            | -                | -                | -         |     1.12 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|            6 |     1089 | 2025-02-04 | Haspers Team                              | W   | 0.659      | -            | -                | -                | -         |     0.63 | CYPHER, jkaem, nawwk, nexa, pr1metapz    |
|            5 |     4938 | 2024-10-19 | Nemiga Gaming                             | L   | 0.060      | -            | -                | -                | -         |    -1.07 | CYPHER, h4rn, jkaem, nexa, VLDN          |
|            4 |     4960 | 2024-10-19 | HEROIC                                    | W   | 0.059      | -            | -                | -                | 1 (0.071) |     0.99 | CYPHER, h4rn, jkaem, nexa, VLDN          |
|            3 |     5006 | 2024-10-18 | PARIVISION                                | W   | 0.053      | -            | -                | -                | 1 (0.064) |     0.21 | CYPHER, h4rn, jkaem, nexa, VLDN          |
|            2 |     5051 | 2024-10-17 | Team Solid                                | W   | 0.048      | -            | -                | -                | 1 (0.057) |     0.46 | CYPHER, h4rn, jkaem, nexa, VLDN          |
|            1 |     5114 | 2024-10-16 | Fnatic                                    | L   | 0.043      | -            | -                | -                | -         |    -0.70 | CYPHER, h4rn, jkaem, nexa, VLDN          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,787.73)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $10,000.00     | $9,187.04       |
| 2024-10-19 |      0.072 | $50,000.00     | $3,600.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
