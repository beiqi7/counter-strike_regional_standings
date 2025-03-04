### Roster Details<br />
Team Name: Team Solid<br />
Roster: destiny, drg, gbb, nython, tomate<br />
Global Rank: [88](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  904.4<br />
<br />
Final Rank Value (904.4) = Starting Rank Value (862.9) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.132[<sup>2</sup>](#table1)
- LAN Wins: 0.067[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 862.9
- 400 + ( ( 0.223 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 862.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |       51 | 2025-02-26 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -19.63 | destiny, drg, gbb, nython, tomate |
|           57 |       54 | 2025-02-26 | Bounty Hunters Esports | W   | 1.000      | 0.450        | 0.005 (0.002)    | 0.638 (0.287)    | 0 (0.000) |    11.55 | destiny, drg, gbb, nython, tomate |
|           56 |      245 | 2025-02-21 | Fluxo                  | L   | 1.000      | -            | -                | -                | -         |   -11.19 | destiny, drg, gbb, nython, tomate |
|           55 |      338 | 2025-02-19 | RED Canids             | W   | 1.000      | 0.371        | 0.023 (0.008)    | 0.197 (0.073)    | 0 (0.000) |    11.65 | destiny, drg, gbb, nython, tomate |
|           54 |      535 | 2025-02-14 | Dusty Roots            | W   | 1.000      | 0.371        | 0.010 (0.004)    | 0.372 (0.138)    | 0 (0.000) |    10.90 | destiny, drg, gbb, nython, tomate |
|           53 |      605 | 2025-02-12 | Game Hunters           | W   | 1.000      | 0.371        | -                | 0.402 (0.149)    | 0 (0.000) |     7.91 | destiny, drg, gbb, nython, tomate |
|           52 |      863 | 2025-02-07 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -13.64 | destiny, drg, gbb, nython, tomate |
|           51 |      897 | 2025-02-06 | Dusty Roots            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.66 | destiny, drg, gbb, nython, tomate |
|           50 |      942 | 2025-02-05 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -14.40 | destiny, drg, gbb, nython, tomate |
|           49 |      964 | 2025-02-05 | Dusty Roots            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.40 | destiny, drg, gbb, nython, tomate |
|           48 |     1347 | 2025-01-11 | BESTIA                 | L   | 0.858      | -            | -                | -                | -         |   -12.32 | destiny, drg, gbb, nython, tomate |
|           47 |     1355 | 2025-01-10 | Familia Maquininha     | W   | 0.850      | 0.384        | -                | 0.206 (0.067)    | 0 (0.000) |     6.50 | destiny, drg, gbb, nython, tomate |
|           46 |     1361 | 2025-01-09 | UNO MILLE              | W   | 0.844      | 0.384        | 0.012 (0.004)    | 0.628 (0.204)    | 0 (0.000) |    10.06 | destiny, drg, gbb, nython, tomate |
|           45 |     1642 | 2024-12-19 | LaChampionsLiga        | W   | 0.705      | 0.384        | -                | 0.450 (0.122)    | 0 (0.000) |     5.06 | destiny, drg, gbb, nython, tomate |
|           44 |     1665 | 2024-12-18 | 9z Academy             | W   | 0.699      | 0.384        | -                | 0.392 (0.105)    | -         |     5.40 | destiny, drg, gbb, nython, tomate |
|           43 |     1704 | 2024-12-16 | Fake do Biru           | L   | 0.683      | -            | -                | -                | -         |   -18.37 | destiny, drg, gbb, nython, tomate |
|           42 |     1866 | 2024-12-13 | Patins da Ferrari      | W   | 0.666      | -            | -                | -                | -         |     2.37 | destiny, drg, gbb, nython, tomate |
|           41 |     2539 | 2024-11-30 | Fluxo                  | L   | 0.577      | -            | -                | -                | -         |    -5.89 | ALLE, destiny, drg, gbb, Misfit   |
|           40 |     2589 | 2024-11-29 | Dusty Roots            | W   | 0.571      | 0.371        | -                | 0.372 (0.079)    | -         |     6.24 | ALLE, destiny, drg, gbb, Misfit   |
|           39 |     2661 | 2024-11-27 | MIBR Academy           | W   | 0.559      | 0.371        | -                | 0.474 (0.098)    | -         |     4.71 | ALLE, destiny, drg, gbb, Misfit   |
|           38 |     2770 | 2024-11-24 | Fluxo                  | L   | 0.538      | -            | -                | -                | -         |    -5.64 | ALLE, destiny, drg, gbb, Misfit   |
|           37 |     2937 | 2024-11-22 | ODDIK                  | W   | 0.525      | 0.143        | 0.033 (0.002)    | -                | 1 (0.525) |     8.60 | ALLE, destiny, drg, gbb, Misfit   |
|           36 |     3660 | 2024-11-09 | Sharks Esports         | L   | 0.437      | -            | -                | -                | -         |    -3.30 | ALLE, destiny, drg, gbb, Misfit   |
|           35 |     3720 | 2024-11-08 | Hype Esports           | W   | 0.430      | -            | -                | -                | -         |     3.35 | ALLE, destiny, drg, gbb, Misfit   |
|           34 |     3785 | 2024-11-06 | Patins da Ferrari      | W   | 0.418      | -            | -                | -                | -         |     1.59 | ALLE, destiny, drg, gbb, Misfit   |
|           33 |     3832 | 2024-11-05 | América eSports        | W   | 0.412      | -            | -                | -                | -         |     2.21 | ALLE, destiny, drg, gbb, Misfit   |
|           32 |     3884 | 2024-11-04 | AdalYamigos            | W   | 0.406      | -            | -                | -                | -         |     3.47 | ALLE, destiny, drg, gbb, Misfit   |
|           31 |     3946 | 2024-11-03 | Sharks Esports         | W   | 0.399      | 0.143        | 0.064 (0.004)    | -                | -         |     9.92 | ALLE, destiny, drg, gbb, Misfit   |
|           30 |     4020 | 2024-11-02 | UNO MILLE              | W   | 0.392      | -            | -                | -                | -         |     4.86 | ALLE, destiny, drg, gbb, Misfit   |
|           29 |     4089 | 2024-11-01 | Intense Game           | W   | 0.386      | -            | -                | -                | -         |     3.53 | ALLE, destiny, drg, gbb, Misfit   |
|           28 |     4151 | 2024-10-31 | ODDIK                  | L   | 0.379      | -            | -                | -                | -         |    -5.62 | ALLE, destiny, drg, gbb, Misfit   |
|           27 |     4230 | 2024-10-30 | Galorys Academy        | W   | 0.371      | -            | -                | -                | -         |     2.61 | ALLE, destiny, drg, gbb, Misfit   |
|           26 |     4309 | 2024-10-28 | Fluxo                  | W   | 0.359      | 0.143        | 0.065 (0.003)    | -                | -         |     7.53 | ALLE, destiny, drg, gbb, Misfit   |
|           25 |     4856 | 2024-10-17 | BC.Game Esports        | L   | 0.283      | -            | -                | -                | -         |    -2.05 | ALLE, destiny, drg, gbb, Misfit   |
|           24 |     4919 | 2024-10-16 | PARIVISION             | L   | 0.277      | -            | -                | -                | -         |    -5.80 | ALLE, destiny, drg, gbb, Misfit   |
|           23 |     5233 | 2024-10-09 | Imperial Esports       | L   | 0.232      | -            | -                | -                | -         |    -3.05 | ALLE, destiny, drg, gbb, Misfit   |
|           22 |     5241 | 2024-10-09 | Imperial Esports       | L   | 0.232      | -            | -                | -                | -         |    -3.11 | ALLE, destiny, drg, gbb, Misfit   |
|           21 |     5306 | 2024-10-08 | Hype Esports           | L   | 0.225      | -            | -                | -                | -         |    -5.34 | ALLE, destiny, drg, gbb, Misfit   |
|           20 |     5314 | 2024-10-08 | Hype Esports           | W   | 0.225      | -            | -                | -                | -         |     1.77 | ALLE, destiny, drg, gbb, Misfit   |
|           19 |     5320 | 2024-10-08 | RED Canids             | W   | 0.224      | -            | -                | -                | -         |     3.17 | ALLE, destiny, drg, gbb, Misfit   |
|           18 |     5329 | 2024-10-08 | RED Canids             | W   | 0.224      | -            | -                | -                | -         |     3.23 | ALLE, destiny, drg, gbb, Misfit   |
|           17 |     5649 | 2024-10-02 | Sharks Esports         | L   | 0.185      | -            | -                | -                | -         |    -1.21 | ALLE, destiny, drg, gbb, Misfit   |
|           16 |     5655 | 2024-10-02 | Sharks Esports         | W   | 0.185      | 0.450        | 0.064 (0.005)    | -                | -         |     4.67 | ALLE, destiny, drg, gbb, Misfit   |
|           15 |     5729 | 2024-10-01 | BESTIA                 | L   | 0.178      | -            | -                | -                | -         |    -2.61 | ALLE, destiny, drg, gbb, Misfit   |
|           14 |     5731 | 2024-10-01 | BESTIA                 | L   | 0.178      | -            | -                | -                | -         |    -2.65 | ALLE, destiny, drg, gbb, Misfit   |
|           13 |     5843 | 2024-09-29 | PaiN Gaming            | L   | 0.164      | -            | -                | -                | -         |    -0.13 | ALLE, destiny, drg, gbb, Misfit   |
|           12 |     5892 | 2024-09-28 | Fluxo                  | L   | 0.159      | -            | -                | -                | -         |    -1.76 | ALLE, destiny, drg, gbb, Misfit   |
|           11 |     5901 | 2024-09-28 | PaiN Gaming            | W   | 0.158      | 0.143        | 0.333 (0.008)    | -                | -         |     4.84 | ALLE, destiny, drg, gbb, Misfit   |
|           10 |     5983 | 2024-09-27 | Case Esports           | W   | 0.152      | -            | -                | -                | -         |     1.33 | ALLE, destiny, drg, gbb, Misfit   |
|            9 |     5994 | 2024-09-27 | ODDIK                  | W   | 0.152      | -            | -                | -                | -         |     2.56 | ALLE, destiny, drg, gbb, Misfit   |
|            8 |     6073 | 2024-09-26 | ShindeN                | W   | 0.145      | -            | -                | -                | -         |     1.52 | ALLE, destiny, drg, gbb, Misfit   |
|            7 |     6150 | 2024-09-25 | MIBR                   | L   | 0.139      | -            | -                | -                | -         |    -0.76 | ALLE, destiny, drg, gbb, Misfit   |
|            6 |     6156 | 2024-09-25 | MIBR                   | W   | 0.138      | 0.450        | 0.118 (0.007)    | -                | -         |     3.63 | ALLE, destiny, drg, gbb, Misfit   |
|            5 |     6241 | 2024-09-24 | Dusty Roots            | L   | 0.132      | -            | -                | -                | -         |    -2.37 | ALLE, destiny, drg, gbb, Misfit   |
|            4 |     6247 | 2024-09-24 | Dusty Roots            | W   | 0.132      | -            | -                | -                | -         |     1.80 | ALLE, destiny, drg, gbb, Misfit   |
|            3 |     6858 | 2024-09-14 | Bad News Chickens      | W   | 0.065      | -            | -                | -                | -         |     0.57 | ALLE, destiny, drg, gbb, Misfit   |
|            2 |     6875 | 2024-09-14 | Sharks Esports         | W   | 0.064      | -            | -                | -                | -         |     1.65 | ALLE, destiny, drg, gbb, Misfit   |
|            1 |     6881 | 2024-09-14 | MIBR Academy           | W   | 0.064      | -            | -                | -                | -         |     0.56 | ALLE, destiny, drg, gbb, Misfit   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,512.37)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $750.00        | $750.00         |
| 2025-01-12 |      0.865 | $2,500.00      | $2,162.51       |
| 2024-11-30 |      0.579 | $1,500.00      | $868.24         |
| 2024-11-24 |      0.538 | $5,171.49      | $2,781.73       |
| 2024-11-09 |      0.439 | $1,500.00      | $658.51         |
| 2024-10-20 |      0.304 | $900.00        | $273.88         |
| 2024-09-14 |      0.065 | $269.53        | $17.50          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
