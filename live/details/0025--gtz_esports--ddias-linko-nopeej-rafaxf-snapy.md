### Roster Details<br />
Team Name: GTZ.ESPORTS<br />
Roster: DDias, Linko, NOPEEj, rafaxF, snapy<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.8<br />
<br />
Final Rank Value (1094.8) = Starting Rank Value (1211.7) + Head To Head Adjustments (-117.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.461[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.569[<sup>2</sup>](#table1)

The average of these factors is 0.368<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1211.7
- 400 + ( ( 0.368 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1211.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |       76 | 2025-02-26 | Sashi Esport                              | W   | 0.781      | 0.435        | 0.007 (0.003)    | 0.535 (0.218)    | -         |     6.88 | DDias, Linko, NOPEEj, rafaxF, snapy   |
|           39 |      436 | 2025-02-17 | Copenhagen Wolves (American organization) | L   | 0.732      | -            | -                | -                | -         |   -18.61 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           38 |      588 | 2025-02-14 | RUSH B (Russian team)                     | L   | 0.715      | -            | -                | -                | -         |   -16.08 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           37 |      618 | 2025-02-13 | 9INE                                      | L   | 0.709      | -            | -                | -                | -         |   -16.74 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           36 |      700 | 2025-02-10 | BC.Game Esports                           | W   | 0.692      | 0.435        | 0.061 (0.022)    | 1.000 (0.361)    | -         |     9.21 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           35 |      740 | 2025-02-09 | Alliance                                  | L   | 0.687      | -            | -                | -                | -         |   -17.81 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           34 |      815 | 2025-02-08 | Betclic Apogee Esports                    | L   | 0.682      | -            | -                | -                | -         |   -16.98 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           33 |      935 | 2025-02-06 | Fire Flux Esports                         | W   | 0.670      | 0.435        | 0.008 (0.003)    | 1.000 (0.350)    | -         |     4.42 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           32 |     1114 | 2025-02-03 | ECSTATIC                                  | W   | 0.654      | 0.435        | 0.027 (0.009)    | 0.659 (0.225)    | -         |     3.44 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           31 |     1143 | 2025-02-01 | SINNERS Esports                           | L   | 0.644      | -            | -                | -                | -         |   -15.85 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           30 |     1625 | 2024-12-22 | The Agency Clan                           | W   | 0.416      | 0.143        | 0.006 (0.000)    | 0.237 (0.017)    | 1 (0.500) |     1.97 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           29 |     1632 | 2024-12-22 | Reinado do Fuzil                          | W   | 0.416      | 0.143        | 0.001 (0.000)    | -                | 1 (0.499) |     0.97 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           28 |     1662 | 2024-12-22 | THE LAST DANCE (Portuguese team)          | W   | 0.414      | -            | -                | -                | 1 (0.497) |     0.66 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           27 |     1684 | 2024-12-21 | QUERNE                                    | W   | 0.410      | -            | -                | -                | 1 (0.492) |     0.32 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           26 |     2964 | 2024-11-23 | Lausanne-Sport Esports                    | L   | 0.255      | -            | -                | -                | -         |    -7.79 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           25 |     3095 | 2024-11-22 | Rhyno Esports                             | L   | 0.248      | -            | -                | -                | -         |    -6.93 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           24 |     3141 | 2024-11-21 | HOTU                                      | L   | 0.243      | -            | -                | -                | -         |    -7.17 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           23 |     3195 | 2024-11-20 | THE SPELLS                                | W   | 0.238      | 0.372        | -                | 0.073 (0.008)    | -         |     0.19 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           22 |     3365 | 2024-11-17 | Nexus Gaming                              | L   | 0.221      | -            | -                | -                | -         |    -4.15 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           21 |     3398 | 2024-11-17 | Partizan Esports                          | W   | 0.219      | 0.617        | 0.082 (0.013)    | 0.618 (0.100)    | 1 (0.263) |     2.28 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           20 |     3430 | 2024-11-16 | Team Novaq                                | W   | 0.216      | 0.617        | 0.026 (0.004)    | 0.301 (0.048)    | 1 (0.259) |     1.42 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           19 |     3494 | 2024-11-15 | MAFE MA3LOM                               | W   | 0.210      | -            | -                | -                | 1 (0.252) |     0.09 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           18 |     3509 | 2024-11-15 | ALTERNATE aTTaX                           | L   | 0.209      | -            | -                | -                | -         |    -5.60 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           17 |     3570 | 2024-11-14 | Team Kosovo                               | W   | 0.204      | -            | -                | -                | 1 (0.244) |     0.07 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           16 |     3576 | 2024-11-14 | Team Chile                                | W   | 0.203      | -            | -                | -                | 1 (0.244) |     0.09 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           15 |     3583 | 2024-11-14 | Team Hungary                              | W   | 0.203      | 0.617        | 0.002 (0.000)    | 0.093 (0.014)    | 1 (0.244) |     0.48 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           14 |     3677 | 2024-11-11 | Ex-9INE Academy                           | W   | 0.188      | -            | -                | -                | -         |     0.10 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           13 |     3806 | 2024-11-09 | Mixzada                                   | W   | 0.176      | -            | -                | -                | -         |     0.19 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           12 |     3987 | 2024-11-05 | ADEPTS                                    | L   | 0.155      | -            | -                | -                | -         |    -4.75 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           11 |     4044 | 2024-11-04 | Illuminar Gaming                          | L   | 0.149      | -            | -                | -                | -         |    -4.27 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           10 |     4360 | 2024-10-30 | Kay Team                                  | W   | 0.122      | -            | -                | -                | -         |     0.07 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            9 |     4455 | 2024-10-29 | MOUZ NXT                                  | W   | 0.115      | -            | -                | -                | -         |     0.08 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            8 |     4459 | 2024-10-29 | BC.Game Esports                           | L   | 0.115      | -            | -                | -                | -         |    -3.25 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            7 |     4507 | 2024-10-28 | GODSENT                                   | W   | 0.110      | 0.372        | 0.001 (0.000)    | 0.156 (0.008)    | -         |     0.15 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            6 |     4593 | 2024-10-26 | Infinite Gaming                           | W   | 0.098      | -            | -                | -                | -         |     0.07 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            5 |     4829 | 2024-10-21 | Daystar                                   | W   | 0.071      | -            | -                | -                | -         |     0.05 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            4 |     4965 | 2024-10-19 | RUSH B (Russian team)                     | L   | 0.058      | -            | -                | -                | -         |    -1.50 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            3 |     5127 | 2024-10-16 | The Suspect                               | L   | 0.043      | -            | -                | -                | -         |    -1.27 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            2 |     5237 | 2024-10-14 | ALTERNATE aTTaX                           | L   | 0.032      | -            | -                | -                | -         |    -0.86 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            1 |     5350 | 2024-10-12 | Tricked Esport                            | L   | 0.020      | -            | -                | -                | -         |    -0.57 | krazy, NOPEEj, rafaxF, snapy, TMKj    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,246.53)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.500 | $1,668.84      | $833.61         |
| 2024-11-22 |      0.298 | $523.55        | $155.97         |
| 2024-11-17 |      0.265 | $50,000.00     | $13,256.94      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
