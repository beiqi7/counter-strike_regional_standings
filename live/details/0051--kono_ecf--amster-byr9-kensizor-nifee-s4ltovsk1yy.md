### Roster Details<br />
Team Name: KONO.ECF<br />
Roster: amster, byr9, kensizor, nifee, s4ltovsk1yy<br />
Global Rank: [51](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.5<br />
<br />
Final Rank Value (996.5) = Starting Rank Value (957.1) + Head To Head Adjustments (39.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.441[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.199[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 957.1
- 400 + ( ( 0.268 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 957.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |     1394 | 2024-12-30 | Dark Cloud Esports                        | W   | 0.776      | 0.333        | 0.045 (0.012)    | 0.837 (0.217)    | 0 (0.000) |     9.41 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           71 |     1412 | 2024-12-29 | Los kogutos                               | W   | 0.769      | 0.333        | 0.037 (0.010)    | -                | 0 (0.000) |    10.34 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           70 |     1448 | 2024-12-28 | Kubix Esports                             | W   | 0.763      | 0.333        | 0.053 (0.013)    | -                | 0 (0.000) |    10.89 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           69 |     1489 | 2024-12-25 | WOPA Esport                               | W   | 0.742      | 0.333        | 0.037 (0.009)    | 0.794 (0.196)    | 0 (0.000) |     9.69 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           68 |     1499 | 2024-12-23 | TEAM NEXT LEVEL                           | L   | 0.729      | -            | -                | -                | -         |   -12.89 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           67 |     1502 | 2024-12-23 | ENCE Academy                              | W   | 0.728      | -            | -                | -                | 0 (0.000) |     7.74 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           66 |     1507 | 2024-12-22 | Monte                                     | W   | 0.725      | 0.371        | 0.052 (0.014)    | 0.866 (0.232)    | 0 (0.000) |    13.03 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           65 |     1519 | 2024-12-22 | TEAM NEXT LEVEL                           | W   | 0.724      | -            | -                | -                | 0 (0.000) |    10.80 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           64 |     1529 | 2024-12-22 | Nexus Gaming                              | W   | 0.723      | 0.371        | 0.219 (0.059)    | 0.808 (0.216)    | 0 (0.000) |    15.92 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           63 |     1565 | 2024-12-21 | JANO Esports                              | W   | 0.717      | 0.371        | 0.026 (0.007)    | -                | 0 (0.000) |    10.42 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           62 |     1587 | 2024-12-21 | ADEPTS                                    | W   | 0.716      | -            | -                | -                | -         |     4.28 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           61 |     1604 | 2024-12-21 | WOPA Esport                               | L   | 0.715      | -            | -                | -                | -         |   -13.22 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           60 |     1622 | 2024-12-20 | TEAM NEXT LEVEL                           | L   | 0.711      | -            | -                | -                | -         |   -11.93 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           59 |     1645 | 2024-12-19 | Nexus Gaming                              | W   | 0.705      | 0.371        | 0.219 (0.057)    | 0.808 (0.211)    | -         |    16.20 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           58 |     1651 | 2024-12-19 | Astralis Talent                           | W   | 0.703      | 0.333        | -                | 0.740 (0.173)    | -         |     7.67 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           57 |     1664 | 2024-12-19 | Preasy Esport                             | W   | 0.702      | 0.333        | -                | 0.714 (0.167)    | -         |     7.57 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           56 |     1682 | 2024-12-17 | Lazer Cats                                | W   | 0.691      | -            | -                | -                | -         |     7.18 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           55 |     1685 | 2024-12-17 | Dark Cloud Esports                        | L   | 0.690      | -            | -                | -                | -         |   -11.68 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           54 |     1702 | 2024-12-16 | Monte                                     | W   | 0.684      | 0.371        | 0.052 (0.013)    | 0.866 (0.219)    | -         |    14.24 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           53 |     1713 | 2024-12-16 | GenOne                                    | W   | 0.682      | 0.333        | -                | 0.853 (0.194)    | -         |    10.05 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           52 |     1940 | 2024-12-12 | Astralis Talent                           | W   | 0.657      | 0.333        | -                | 0.740 (0.162)    | -         |     8.58 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           51 |     1950 | 2024-12-12 | Lilmix                                    | W   | 0.656      | -            | -                | -                | -         |     3.69 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           50 |     2104 | 2024-12-08 | GODSENT                                   | W   | 0.630      | -            | -                | -                | -         |     5.45 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           49 |     2121 | 2024-12-08 | GenOne                                    | L   | 0.628      | -            | -                | -                | -         |    -8.89 | amster, byr9, kensizor, nifee, s4ltovsk1yy      |
|           48 |     2463 | 2024-12-01 | BC.Game Esports                           | L   | 0.583      | -            | -                | -                | -         |    -7.98 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           47 |     2560 | 2024-11-30 | Betclic Apogee Esports                    | L   | 0.576      | -            | -                | -                | -         |    -8.02 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |     2605 | 2024-11-29 | BC.Game Esports                           | L   | 0.569      | -            | -                | -                | -         |    -8.63 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |     2717 | 2024-11-26 | ALTERNATE aTTaX                           | L   | 0.551      | -            | -                | -                | -         |    -6.97 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           44 |     2759 | 2024-11-25 | Preasy Esport                             | W   | 0.542      | -            | -                | -                | -         |     5.97 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |     2772 | 2024-11-24 | Copenhagen Wolves (American organization) | L   | 0.538      | -            | -                | -                | -         |    -8.58 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           42 |     2840 | 2024-11-23 | RUSTEC                                    | L   | 0.531      | -            | -                | -                | -         |   -13.54 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           41 |     2876 | 2024-11-23 | GenOne                                    | W   | 0.530      | -            | -                | -                | -         |     7.22 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |     2974 | 2024-11-22 | FLuffy Gangsters                          | L   | 0.523      | -            | -                | -                | -         |    -9.35 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           39 |     3013 | 2024-11-21 | Leo Team                                  | L   | 0.518      | -            | -                | -                | -         |    -8.54 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           38 |     3031 | 2024-11-21 | RUSTEC                                    | W   | 0.517      | -            | -                | -                | -         |     2.07 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           37 |     3369 | 2024-11-15 | Team Novaq                                | L   | 0.477      | -            | -                | -                | -         |    -2.88 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |     3412 | 2024-11-14 | Team Latvia                               | L   | 0.471      | -            | -                | -                | -         |   -12.79 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |     3422 | 2024-11-14 | Nexus Gaming                              | L   | 0.471      | -            | -                | -                | -         |    -3.56 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |     3431 | 2024-11-14 | GnG x Amazigh                             | W   | 0.470      | -            | -                | -                | 1 (0.470) |     0.66 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |     3791 | 2024-11-06 | Heimo Esports                             | W   | 0.418      | -            | -                | -                | -         |     3.63 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           32 |     3804 | 2024-11-06 | QUAZAR                                    | W   | 0.417      | -            | -                | -                | -         |     3.30 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           31 |     3954 | 2024-11-03 | Preasy Esport                             | L   | 0.398      | -            | -                | -                | -         |    -8.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |     4226 | 2024-10-30 | Fire Flux Esports                         | L   | 0.371      | -            | -                | -                | -         |    -5.69 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           29 |     4287 | 2024-10-29 | CYBERSHOKE Esports                        | W   | 0.364      | -            | -                | -                | -         |     4.75 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           28 |     4383 | 2024-10-27 | MOUZ NXT                                  | W   | 0.350      | -            | -                | -                | -         |     1.29 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           27 |     4555 | 2024-10-24 | Chimera Esports                           | L   | 0.328      | -            | -                | -                | -         |    -6.17 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     4628 | 2024-10-22 | Natus Vincere Junior                      | W   | 0.315      | 0.333        | 0.106 (0.011)    | -                | -         |     6.32 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     4652 | 2024-10-21 | Endpoint                                  | L   | 0.310      | -            | -                | -                | -         |    -7.03 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           24 |     4736 | 2024-10-20 | Copenhagen Wolves (American organization) | W   | 0.301      | -            | -                | -                | -         |     4.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     4822 | 2024-10-18 | GenOne                                    | L   | 0.288      | -            | -                | -                | -         |    -5.73 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     4862 | 2024-10-17 | Illuminar Gaming                          | W   | 0.282      | -            | -                | -                | -         |     3.90 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     5000 | 2024-10-15 | Heimo Esports                             | W   | 0.268      | -            | -                | -                | -         |     2.27 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     5010 | 2024-10-14 | ALASKA                                    | W   | 0.264      | -            | -                | -                | -         |     6.65 | amster, byr9, Dafra1D, kensizor, s4ltovsk1yy    |
|           19 |     5035 | 2024-10-14 | Natus Vincere Junior                      | L   | 0.261      | -            | -                | -                | -         |    -3.09 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     5072 | 2024-10-13 | ADEPTS                                    | L   | 0.255      | -            | -                | -                | -         |    -7.05 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     5212 | 2024-10-10 | ENCE Academy                              | W   | 0.235      | -            | -                | -                | -         |     2.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     5287 | 2024-10-09 | Heimo Esports                             | W   | 0.228      | -            | -                | -                | -         |     1.92 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     5410 | 2024-10-07 | FAVBET Team                               | L   | 0.215      | -            | -                | -                | -         |    -3.77 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           14 |     5525 | 2024-10-05 | LOADING (French team)                     | W   | 0.202      | -            | -                | -                | -         |     0.54 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           13 |     5849 | 2024-09-29 | Leo Team                                  | L   | 0.164      | -            | -                | -                | -         |    -3.24 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           12 |     5867 | 2024-09-29 | TEAM NEXT LEVEL                           | W   | 0.163      | -            | -                | -                | -         |     2.09 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           11 |     5923 | 2024-09-28 | Iron Branch (Ukrainian team)              | W   | 0.157      | -            | -                | -                | -         |     0.35 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           10 |     6227 | 2024-09-25 | Los kogutos                               | L   | 0.134      | -            | -                | -                | -         |    -1.60 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            9 |     6489 | 2024-09-21 | Tricked Esport                            | L   | 0.109      | -            | -                | -                | -         |    -2.16 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            8 |     6744 | 2024-09-17 | Dynamo Eclot                              | L   | 0.082      | -            | -                | -                | -         |    -0.68 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            7 |     6790 | 2024-09-16 | Leo Team                                  | W   | 0.076      | -            | -                | -                | -         |     0.88 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            6 |     6837 | 2024-09-15 | Lazer Cats                                | L   | 0.069      | -            | -                | -                | -         |    -1.68 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            5 |     6850 | 2024-09-15 | Ex-ENTERPRISE esports                     | W   | 0.068      | -            | -                | -                | -         |     0.49 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            4 |     6928 | 2024-09-14 | Fragmatic                                 | W   | 0.062      | -            | -                | -                | -         |     0.14 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            3 |     6997 | 2024-09-13 | Preasy Esport                             | W   | 0.054      | -            | -                | -                | -         |     0.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            2 |     7100 | 2024-09-11 | Dynamo Eclot                              | L   | 0.041      | -            | -                | -                | -         |    -0.34 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|            1 |     7406 | 2024-09-06 | ALASKA                                    | W   | 0.009      | -            | -                | -                | -         |     0.24 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,878.30)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.776 | $6,000.00      | $4,655.03       |
| 2024-12-25 |      0.742 | $6,000.00      | $4,454.61       |
| 2024-12-23 |      0.729 | $5,000.00      | $3,646.55       |
| 2024-12-22 |      0.724 | $1,196.99      | $866.16         |
| 2024-10-24 |      0.328 | $3,000.00      | $983.35         |
| 2024-09-29 |      0.164 | $971.82        | $159.27         |
| 2024-09-18 |      0.088 | $1,000.00      | $87.78          |
| 2024-09-15 |      0.070 | $362.53        | $25.56          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
