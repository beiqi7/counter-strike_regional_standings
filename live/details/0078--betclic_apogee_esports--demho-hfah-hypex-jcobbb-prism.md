### Roster Details<br />
Team Name: Betclic Apogee Esports<br />
Roster: Demho, hfah, hypex, jcobbb, Prism<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  886.0<br />
<br />
Final Rank Value (886.0) = Starting Rank Value (866.1) + Head To Head Adjustments (20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.343[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.1
- 400 + ( ( 0.211 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 866.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      194 | 2025-02-23 | Ninjas in Pyjamas                         | L   | 0.764      | -            | -                | -                | -         |   -17.65 | Demho, hfah, hypex, jcobbb, Prism |
|           36 |      331 | 2025-02-20 | Rhyno Esports                             | W   | 0.747      | -            | -                | -                | 0 (0.000) |     7.12 | Demho, hfah, hypex, jcobbb, Prism |
|           35 |      368 | 2025-02-19 | Ninjas in Pyjamas                         | L   | 0.742      | -            | -                | -                | -         |   -17.65 | Demho, hfah, hypex, jcobbb, Prism |
|           34 |      613 | 2025-02-13 | Passion UA                                | L   | 0.710      | -            | -                | -                | -         |   -11.26 | Demho, hfah, hypex, jcobbb, Prism |
|           33 |      793 | 2025-02-08 | ALASKA                                    | L   | 0.682      | -            | -                | -                | -         |    -7.73 | Demho, hfah, hypex, jcobbb, Prism |
|           32 |      815 | 2025-02-08 | GTZ.ESPORTS                               | W   | 0.682      | 0.435        | 0.068 (0.024)    | 0.498 (0.177)    | 0 (0.000) |    16.98 | Demho, hfah, hypex, jcobbb, Prism |
|           31 |      880 | 2025-02-07 | FAVBET Team                               | W   | 0.677      | 0.143        | -                | 0.790 (0.092)    | 0 (0.000) |     9.90 | Demho, hfah, hypex, jcobbb, Prism |
|           30 |      934 | 2025-02-06 | Copenhagen Wolves (American organization) | L   | 0.671      | -            | -                | -                | -         |   -12.06 | Demho, hfah, hypex, jcobbb, Prism |
|           29 |      938 | 2025-02-06 | Monte                                     | W   | 0.669      | 0.435        | 0.036 (0.013)    | 0.766 (0.267)    | 0 (0.000) |    11.76 | Demho, hfah, hypex, jcobbb, Prism |
|           28 |     1075 | 2025-02-04 | Fnatic                                    | L   | 0.659      | -            | -                | -                | -         |    -7.16 | Demho, hfah, hypex, jcobbb, Prism |
|           27 |     1131 | 2025-02-02 | 500                                       | W   | 0.648      | 0.435        | 0.118 (0.040)    | 1.000 (0.338)    | 0 (0.000) |    12.95 | Demho, hfah, hypex, jcobbb, Prism |
|           26 |     1205 | 2025-01-29 | FAVBET Team                               | W   | 0.626      | 0.143        | -                | 0.790 (0.085)    | 0 (0.000) |    10.47 | Demho, hfah, hypex, jcobbb, Prism |
|           25 |     1240 | 2025-01-28 | ALASKA                                    | W   | 0.620      | 0.143        | -                | 0.737 (0.078)    | 0 (0.000) |    14.54 | Demho, hfah, hypex, jcobbb, Prism |
|           24 |     1287 | 2025-01-25 | Chimera Esports                           | W   | 0.604      | -            | -                | -                | 0 (0.000) |     9.85 | Demho, hfah, hypex, jcobbb, Prism |
|           23 |     1324 | 2025-01-24 | Fire Flux Esports                         | L   | 0.599      | -            | -                | -                | -         |    -8.33 | Demho, hfah, hypex, jcobbb, Prism |
|           22 |     1634 | 2024-12-22 | 9INE                                      | L   | 0.416      | -            | -                | -                | -         |    -5.47 | Demho, hfah, hypex, jcobbb, Prism |
|           21 |     1643 | 2024-12-22 | Nexus Gaming                              | W   | 0.415      | 0.354        | 0.161 (0.028)    | 0.539 (0.095)    | 0 (0.000) |     9.74 | Demho, hfah, hypex, jcobbb, Prism |
|           20 |     1687 | 2024-12-21 | 500                                       | W   | 0.410      | 0.354        | 0.118 (0.020)    | 1.000 (0.174)    | 0 (0.000) |     9.29 | Demho, hfah, hypex, jcobbb, Prism |
|           19 |     1704 | 2024-12-21 | Ex-GODSENT                                | W   | 0.409      | -            | -                | -                | -         |     1.80 | Demho, hfah, hypex, jcobbb, Prism |
|           18 |     1750 | 2024-12-20 | 9INE                                      | L   | 0.404      | -            | -                | -                | -         |    -5.36 | Demho, hfah, hypex, jcobbb, Prism |
|           17 |     2070 | 2024-12-12 | Chimera Esports                           | L   | 0.359      | -            | -                | -                | -         |    -5.66 | Demho, hfah, hypex, jcobbb, Prism |
|           16 |     2125 | 2024-12-11 | Natus Vincere Junior                      | L   | 0.353      | -            | -                | -                | -         |    -3.73 | Demho, hfah, hypex, jcobbb, Prism |
|           15 |     2185 | 2024-12-09 | Tricked Esport                            | W   | 0.342      | 0.371        | 0.030 (0.005)    | 0.549 (0.084)    | -         |     5.05 | Demho, hfah, hypex, jcobbb, Prism |
|           14 |     2384 | 2024-12-05 | Iberian Soul                              | L   | 0.320      | -            | -                | -                | -         |    -5.02 | Demho, hfah, hypex, jcobbb, Prism |
|           13 |     2526 | 2024-12-02 | Dark Cloud Esports                        | L   | 0.303      | -            | -                | -                | -         |    -5.33 | Demho, hfah, hypex, jcobbb, Prism |
|           12 |     2597 | 2024-12-01 | Team Sampi                                | W   | 0.297      | -            | -                | -                | -         |     3.02 | Demho, hfah, hypex, jcobbb, Prism |
|           11 |     2659 | 2024-11-30 | Tricked Esport                            | L   | 0.293      | -            | -                | -                | -         |    -4.88 | Demho, hfah, hypex, jcobbb, Prism |
|           10 |     2680 | 2024-11-30 | KONO.ECF                                  | W   | 0.292      | 0.333        | 0.047 (0.005)    | -                | -         |     4.77 | Demho, hfah, hypex, jcobbb, Prism |
|            9 |     2702 | 2024-11-29 | WOPA Esport                               | W   | 0.288      | 0.354        | 0.031 (0.004)    | 0.611 (0.075)    | -         |     4.10 | Demho, hfah, hypex, jcobbb, Prism |
|            8 |     2726 | 2024-11-29 | Illuminar Gaming                          | L   | 0.286      | -            | -                | -                | -         |    -5.59 | Demho, hfah, hypex, jcobbb, Prism |
|            7 |     2788 | 2024-11-27 | Tricked Esport                            | W   | 0.277      | 0.354        | 0.030 (0.003)    | -                | -         |     4.07 | Demho, hfah, hypex, jcobbb, Prism |
|            6 |     2796 | 2024-11-27 | GUN5 Esports                              | W   | 0.276      | 0.354        | 0.105 (0.012)    | -                | -         |     5.78 | Demho, hfah, hypex, jcobbb, Prism |
|            5 |     2805 | 2024-11-27 | Tricked Esport                            | L   | 0.275      | -            | -                | -                | -         |    -4.68 | Demho, hfah, hypex, jcobbb, Prism |
|            4 |     2851 | 2024-11-26 | WOPA Esport                               | W   | 0.271      | -            | -                | -                | -         |     3.91 | Demho, hfah, hypex, jcobbb, Prism |
|            3 |     2855 | 2024-11-26 | Astralis Talent                           | W   | 0.270      | -            | -                | -                | -         |     3.33 | Demho, hfah, hypex, jcobbb, Prism |
|            2 |     2877 | 2024-11-25 | Chimera Esports                           | L   | 0.264      | -            | -                | -                | -         |    -4.48 | Demho, hfah, hypex, jcobbb, Prism |
|            1 |     3113 | 2024-11-22 | Tricked Esport                            | W   | 0.247      | -            | -                | -                | -         |     3.56 | Demho, hfah, hypex, jcobbb, Prism |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,551.67)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $3,000.00      | $1,495.83       |
| 2024-11-30 |      0.352 | $3,000.00      | $1,055.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
