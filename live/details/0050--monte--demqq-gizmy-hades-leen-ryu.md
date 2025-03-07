### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, hades, leen, ryu<br />
Global Rank: [50](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  952.1<br />
<br />
Final Rank Value (952.1) = Starting Rank Value (949.2) + Head To Head Adjustments (2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.409[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 949.2
- 400 + ( ( 0.249 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 949.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |       12 | 2025-02-28 | BC.Game Esports                           | W   | 0.794      | 0.435        | 0.061 (0.025)    | 1.000 (0.414)    | 0 (0.000) |    16.31 | DemQQ, Gizmy, hades, leen, ryu   |
|           49 |       38 | 2025-02-27 | 9Pandas                                   | L   | 0.786      | -            | -                | -                | -         |   -10.76 | DemQQ, Gizmy, hades, leen, ryu   |
|           48 |      111 | 2025-02-25 | JiJieHao                                  | W   | 0.777      | 0.500        | -                | 0.252 (0.118)    | 0 (0.000) |     2.55 | DemQQ, Gizmy, hades, leen, ryu   |
|           47 |      321 | 2025-02-20 | B8                                        | L   | 0.749      | -            | -                | -                | -         |    -7.12 | DemQQ, Gizmy, hades, leen, ryu   |
|           46 |      392 | 2025-02-18 | PARIVISION                                | L   | 0.738      | -            | -                | -                | -         |   -15.94 | DemQQ, Gizmy, hades, leen, ryu   |
|           45 |      525 | 2025-02-15 | Fnatic                                    | W   | 0.721      | 0.435        | 0.025 (0.009)    | 0.471 (0.177)    | 0 (0.000) |    13.73 | DemQQ, dycha, Gizmy, hades, ryu  |
|           44 |      610 | 2025-02-13 | Natus Vincere Junior                      | W   | 0.710      | 0.435        | 0.078 (0.029)    | 0.786 (0.291)    | 0 (0.000) |    12.18 | DemQQ, dycha, Gizmy, hades, ryu  |
|           43 |      669 | 2025-02-11 | CYBERSHOKE Esports                        | W   | 0.697      | 0.435        | 0.014 (0.005)    | 1.000 (0.363)    | 0 (0.000) |     7.96 | DemQQ, dycha, Gizmy, hades, ryu  |
|           42 |      895 | 2025-02-07 | SINNERS Esports                           | L   | 0.675      | -            | -                | -                | -         |   -10.91 | DemQQ, dycha, Gizmy, hades, ryu  |
|           41 |      938 | 2025-02-06 | Betclic Apogee Esports                    | L   | 0.669      | -            | -                | -                | -         |   -11.76 | DemQQ, dycha, Gizmy, hades, ryu  |
|           40 |     1040 | 2025-02-04 | 500                                       | L   | 0.660      | -            | -                | -                | -         |    -9.07 | DemQQ, dycha, Gizmy, hades, ryu  |
|           39 |     1056 | 2025-02-04 | RUSH B (Russian team)                     | W   | 0.659      | -            | -                | -                | 0 (0.000) |    10.07 | DemQQ, dycha, Gizmy, hades, ryu  |
|           38 |     1104 | 2025-02-03 | Sashi Esport                              | W   | 0.655      | 0.435        | -                | 0.535 (0.183)    | 0 (0.000) |    10.70 | DemQQ, dycha, Gizmy, hades, ryu  |
|           37 |     1152 | 2025-02-01 | MoneyF                                    | L   | 0.643      | -            | -                | -                | -         |   -18.27 | DemQQ, dycha, Gizmy, hades, ryu  |
|           36 |     1269 | 2025-01-27 | Copenhagen Wolves (American organization) | W   | 0.616      | 0.500        | 0.017 (0.006)    | 1.000 (0.370)    | 0 (0.000) |     7.57 | DemQQ, dycha, Gizmy, hades, ryu  |
|           35 |     1355 | 2025-01-23 | SINNERS Esports                           | L   | 0.594      | -            | -                | -                | -         |   -10.23 | DemQQ, dycha, Gizmy, hades, ryu  |
|           34 |     1421 | 2025-01-21 | 9Pandas                                   | W   | 0.583      | 0.500        | 0.084 (0.029)    | 0.481 (0.168)    | 0 (0.000) |    10.49 | DemQQ, dycha, Gizmy, hades, ryu  |
|           33 |     1628 | 2024-12-22 | KONO.ECF                                  | L   | 0.416      | -            | -                | -                | -         |    -7.30 | fnl, Gizmy, leen, ryu, shield    |
|           32 |     1674 | 2024-12-21 | TEAM NEXT LEVEL                           | L   | 0.411      | -            | -                | -                | -         |    -8.26 | fnl, Gizmy, leen, ryu, shield    |
|           31 |     1705 | 2024-12-21 | AMKAL ESPORTS                             | L   | 0.409      | -            | -                | -                | -         |    -9.02 | fnl, Gizmy, leen, ryu, shield    |
|           30 |     1747 | 2024-12-20 | Dark Cloud Esports                        | W   | 0.404      | 0.333        | 0.035 (0.006)    | -                | 0 (0.000) |     4.26 | fnl, Gizmy, leen, ryu, shield    |
|           29 |     1756 | 2024-12-20 | Copenhagen Wolves (American organization) | W   | 0.403      | 0.371        | 0.017 (0.003)    | 1.000 (0.179)    | -         |     5.02 | fnl, Gizmy, leen, ryu, shield    |
|           28 |     1771 | 2024-12-19 | Betera Esports                            | W   | 0.399      | -            | -                | -                | -         |     2.80 | AiyvaN, Gizmy, leen, ryu, shield |
|           27 |     1778 | 2024-12-19 | JANO Esports                              | W   | 0.398      | 0.371        | 0.019 (0.003)    | -                | -         |     5.38 | fnl, Gizmy, leen, ryu, shield    |
|           26 |     1791 | 2024-12-18 | Lazer Cats                                | W   | 0.393      | -            | -                | -                | -         |     2.63 | fnl, Gizmy, leen, ryu, shield    |
|           25 |     1811 | 2024-12-17 | Preasy Esport                             | W   | 0.388      | 0.371        | -                | 0.647 (0.112)    | -         |     3.14 | fnl, Gizmy, leen, ryu, shield    |
|           24 |     1827 | 2024-12-16 | KONO.ECF                                  | L   | 0.382      | -            | -                | -                | -         |    -7.22 | fnl, Gizmy, leen, ryu, shield    |
|           23 |     2069 | 2024-12-12 | G2 Ares                                   | W   | 0.359      | -            | -                | -                | -         |     2.04 | fnl, Gizmy, leen, ryu, shield    |
|           22 |     2154 | 2024-12-10 | FLuffy Gangsters                          | W   | 0.348      | -            | -                | -                | -         |     3.22 | fnl, Gizmy, leen, ryu, shield    |
|           21 |     2183 | 2024-12-09 | Nexus Gaming                              | W   | 0.342      | 0.333        | 0.161 (0.022)    | -                | -         |     7.76 | fnl, Gizmy, leen, ryu, shield    |
|           20 |     2423 | 2024-12-04 | FORZE Reload                              | W   | 0.315      | -            | -                | -                | -         |     3.76 | fnl, Gizmy, leen, ryu, shield    |
|           19 |     2471 | 2024-12-03 | FLuffy Gangsters                          | W   | 0.310      | -            | -                | -                | -         |     3.13 | fnl, Gizmy, leen, ryu, shield    |
|           18 |     2507 | 2024-12-02 | Preasy Esport                             | W   | 0.305      | -            | -                | -                | -         |     2.67 | fnl, Gizmy, leen, ryu, shield    |
|           17 |     2722 | 2024-11-29 | G2 Ares                                   | W   | 0.287      | -            | -                | -                | -         |     1.75 | fnl, Gizmy, leen, ryu, shield    |
|           16 |     2801 | 2024-11-27 | Viperio                                   | L   | 0.276      | -            | -                | -                | -         |    -6.51 | fnl, Gizmy, leen, ryu, shield    |
|           15 |     2874 | 2024-11-25 | Betera Esports                            | L   | 0.265      | -            | -                | -                | -         |    -6.43 | Burmylov, fnl, Gizmy, leen, ryu  |
|           14 |     2915 | 2024-11-24 | TEAM NEXT LEVEL                           | L   | 0.259      | -            | -                | -                | -         |    -5.27 | Burmylov, fnl, Gizmy, leen, ryu  |
|           13 |     3023 | 2024-11-23 | Preasy Esport                             | W   | 0.253      | -            | -                | -                | -         |     2.12 | Burmylov, fnl, Gizmy, leen, ryu  |
|           12 |     3126 | 2024-11-21 | ADEPTS                                    | W   | 0.244      | -            | -                | -                | -         |     0.79 | Burmylov, fnl, Gizmy, leen, ryu  |
|           11 |     3743 | 2024-11-10 | Betera Esports                            | W   | 0.182      | -            | -                | -                | -         |     1.28 | fnl, Gizmy, leen, ryu, shield    |
|           10 |     3804 | 2024-11-09 | GenOne                                    | W   | 0.176      | -            | -                | -                | -         |     1.72 | fnl, Gizmy, leen, ryu, shield    |
|            9 |     3850 | 2024-11-08 | 777 Esports                               | W   | 0.171      | -            | -                | -                | -         |     0.83 | fnl, Gizmy, leen, ryu, shield    |
|            8 |     4008 | 2024-11-05 | Adventurers                               | W   | 0.154      | -            | -                | -                | -         |     1.13 | fnl, Gizmy, leen, ryu, shield    |
|            7 |     4074 | 2024-11-04 | Lazer Cats                                | W   | 0.148      | -            | -                | -                | -         |     1.01 | fnl, Gizmy, leen, ryu, shield    |
|            6 |     4133 | 2024-11-03 | Astralis Talent                           | W   | 0.142      | -            | -                | -                | -         |     1.18 | fnl, Gizmy, leen, ryu, shield    |
|            5 |     4816 | 2024-10-22 | Insilio                                   | L   | 0.074      | -            | -                | -                | -         |    -2.06 | fnl, Gizmy, leen, ryu, shield    |
|            4 |     5003 | 2024-10-18 | Adventurers                               | L   | 0.054      | -            | -                | -                | -         |    -1.31 | fnl, Gizmy, leen, ryu, shield    |
|            3 |     5046 | 2024-10-17 | ROYALS                                    | W   | 0.048      | -            | -                | -                | -         |     0.24 | fnl, Gizmy, leen, ryu, shield    |
|            2 |     5138 | 2024-10-16 | GenOne                                    | W   | 0.042      | -            | -                | -                | -         |     0.41 | fnl, Gizmy, leen, ryu, shield    |
|            1 |     5156 | 2024-10-16 | CYBERSHOKE Esports                        | W   | 0.041      | -            | -                | -                | -         |     0.52 | fnl, Gizmy, leen, ryu, shield    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,525.97)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-23 |      0.504 | $3,000.00      | $1,512.08       |
| 2024-12-21 |      0.491 | $3,000.00      | $1,472.92       |
| 2024-12-04 |      0.378 | $5,000.00      | $1,892.36       |
| 2024-11-10 |      0.219 | $7,000.00      | $1,530.28       |
| 2024-11-05 |      0.185 | $5,000.00      | $925.00         |
| 2024-10-18 |      0.064 | $3,000.00      | $193.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
