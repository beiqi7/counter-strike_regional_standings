### Roster Details<br />
Team Name: GTZ.ESPORTS<br />
Roster: DDias, Linko, NOPEEj, rafaxF, snapy<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.1<br />
<br />
Final Rank Value (1100.1) = Starting Rank Value (1316.1) + Head To Head Adjustments (-216.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.493[<sup>1</sup>](#table2)
- Bounty Collected: 0.338[<sup>2</sup>](#table1)
- Opponent Network: 0.198[<sup>2</sup>](#table1)
- LAN Wins: 0.733[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1316.1
- 400 + ( ( 0.440 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1316.1


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
|           43 |       70 | 2025-02-26 | Sashi Esport                              | W   | 1.000      | 0.435        | 0.015 (0.007)    | 0.606 (0.263)    | -         |    10.08 | DDias, Linko, NOPEEj, rafaxF, snapy   |
|           42 |      411 | 2025-02-17 | Copenhagen Wolves (American organization) | L   | 1.000      | -            | -                | -                | -         |   -24.62 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           41 |      563 | 2025-02-14 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -20.22 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           40 |      599 | 2025-02-13 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -22.12 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           39 |      677 | 2025-02-10 | BC.Game Esports                           | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.976 (0.424)    | -         |    16.10 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           38 |      716 | 2025-02-09 | Alliance                                  | L   | 1.000      | -            | -                | -                | -         |   -25.19 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           37 |      791 | 2025-02-08 | Betclic Apogee Esports                    | L   | 1.000      | -            | -                | -                | -         |   -23.80 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           36 |      911 | 2025-02-06 | Fire Flux Esports                         | W   | 1.000      | 0.435        | 0.009 (0.004)    | 1.000 (0.435)    | -         |     7.62 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           35 |     1089 | 2025-02-03 | ECSTATIC                                  | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.809 (0.352)    | -         |     6.19 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           34 |     1118 | 2025-02-01 | SINNERS Esports                           | L   | 0.998      | -            | -                | -                | -         |   -23.01 | Linko, ms, NOPEEj, rafaxF, snapy      |
|           33 |     1504 | 2024-12-22 | The Agency Clan                           | W   | 0.725      | 0.143        | 0.008 (0.001)    | 0.298 (0.031)    | 1 (0.725) |     3.54 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           32 |     1511 | 2024-12-22 | Reinado do Fuzil                          | W   | 0.724      | -            | -                | -                | 1 (0.724) |     1.51 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           31 |     1541 | 2024-12-22 | THE LAST DANCE (Portuguese team)          | W   | 0.722      | -            | -                | -                | 1 (0.722) |     1.00 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           30 |     1563 | 2024-12-21 | QUERNE                                    | W   | 0.717      | -            | -                | -                | 1 (0.717) |     0.47 | Linko, N0VAISj, NOPEEj, rafaxF, snapy |
|           29 |     2841 | 2024-11-23 | Lausanne-Sport Esports                    | L   | 0.531      | -            | -                | -                | -         |   -16.24 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           28 |     2975 | 2024-11-22 | Rhyno Esports                             | L   | 0.523      | -            | -                | -                | -         |   -13.96 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           27 |     3021 | 2024-11-21 | HOTU                                      | L   | 0.517      | -            | -                | -                | -         |   -15.41 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           26 |     3073 | 2024-11-20 | THE SPELLS                                | W   | 0.511      | 0.372        | -                | 0.146 (0.028)    | -         |     0.41 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           25 |     3233 | 2024-11-17 | Nexus Gaming                              | L   | 0.490      | -            | -                | -                | -         |    -9.34 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           24 |     3266 | 2024-11-17 | Partizan Esports                          | W   | 0.488      | 0.617        | 0.097 (0.029)    | 0.819 (0.247)    | 1 (0.488) |     5.33 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           23 |     3299 | 2024-11-16 | Team Novaq                                | W   | 0.484      | 0.617        | 0.035 (0.011)    | 0.402 (0.120)    | 1 (0.484) |     6.59 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           22 |     3366 | 2024-11-15 | MAFE MA3LOM                               | W   | 0.477      | -            | -                | -                | 1 (0.477) |     0.26 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           21 |     3379 | 2024-11-15 | ALTERNATE aTTaX                           | L   | 0.476      | -            | -                | -                | -         |   -12.59 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           20 |     3437 | 2024-11-14 | Team Kosovo                               | W   | 0.470      | -            | -                | -                | 1 (0.470) |     0.33 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           19 |     3443 | 2024-11-14 | Team Chile                                | W   | 0.469      | -            | -                | -                | 1 (0.469) |     0.29 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           18 |     3450 | 2024-11-14 | Team Hungary                              | W   | 0.469      | 0.617        | 0.003 (0.001)    | 0.162 (0.047)    | 1 (0.469) |     1.22 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           17 |     3542 | 2024-11-11 | Ex-9INE Academy                           | W   | 0.451      | -            | -                | -                | -         |     0.33 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           16 |     3671 | 2024-11-09 | Mixzada                                   | W   | 0.436      | -            | -                | -                | -         |     0.38 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           15 |     3848 | 2024-11-05 | ADEPTS                                    | L   | 0.411      | -            | -                | -                | -         |   -12.61 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           14 |     3902 | 2024-11-04 | Illuminar Gaming                          | L   | 0.404      | -            | -                | -                | -         |   -11.37 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           13 |     4214 | 2024-10-30 | Kay Team                                  | W   | 0.371      | -            | -                | -                | -         |     0.17 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           12 |     4300 | 2024-10-29 | MOUZ NXT                                  | W   | 0.363      | -            | -                | -                | -         |     0.24 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           11 |     4303 | 2024-10-29 | BC.Game Esports                           | L   | 0.363      | -            | -                | -                | -         |   -10.43 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|           10 |     4349 | 2024-10-28 | GODSENT                                   | W   | 0.357      | 0.372        | 0.001 (0.000)    | 0.271 (0.036)    | -         |     0.39 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            9 |     4644 | 2024-10-21 | Daystar                                   | W   | 0.311      | -            | -                | -                | -         |     0.29 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            8 |     4774 | 2024-10-19 | RUSH B (Russian team)                     | L   | 0.295      | -            | -                | -                | -         |    -7.99 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            7 |     4915 | 2024-10-16 | The Suspect                               | L   | 0.277      | -            | -                | -                | -         |    -8.32 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            6 |     5017 | 2024-10-14 | ALTERNATE aTTaX                           | L   | 0.264      | -            | -                | -                | -         |    -7.25 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            5 |     5126 | 2024-10-12 | Tricked Esport                            | L   | 0.249      | -            | -                | -                | -         |    -7.25 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            4 |     5461 | 2024-10-06 | Johnny Speeds                             | L   | 0.208      | -            | -                | -                | -         |    -5.86 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            3 |     5855 | 2024-09-29 | CYBERSHOKE Esports                        | W   | 0.163      | 0.143        | 0.015 (0.000)    | -                | -         |     0.49 | krazy, NOPEEj, rafaxF, snapy, TMKj    |
|            2 |     6995 | 2024-09-13 | TALON                                     | L   | 0.055      | -            | -                | -                | -         |    -1.69 | Ag1l, krazy, NOPEEj, rafaxF, snapy    |
|            1 |     7149 | 2024-09-10 | WW Team                                   | W   | 0.035      | -            | -                | -                | -         |     0.01 | Ag1l, krazy, NOPEEj, rafaxF, snapy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,004.54)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.725 | $1,668.84      | $1,209.57       |
| 2024-11-22 |      0.523 | $523.55        | $273.92         |
| 2024-11-17 |      0.490 | $50,000.00     | $24,521.05      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
