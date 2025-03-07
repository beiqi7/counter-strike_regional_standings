### Roster Details<br />
Team Name: 9INE<br />
Roster: bobeksde, faveN, kraghen, mantuu, raalz<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  959.2<br />
<br />
Final Rank Value (959.2) = Starting Rank Value (913.9) + Head To Head Adjustments (45.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.9
- 400 + ( ( 0.233 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 913.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      151 | 2025-02-24 | BC.Game Esports                           | L   | 0.769      | -            | -                | -                | -         |    -7.55 | bobeksde, faveN, kraghen, mantuu, raalz |
|           40 |      269 | 2025-02-21 | Partizan Esports                          | L   | 0.755      | -            | -                | -                | -         |    -9.51 | BERRY, bobeksde, faveN, kraghen, mantuu |
|           39 |      316 | 2025-02-20 | Alliance                                  | W   | 0.749      | -            | -                | -                | 0 (0.000) |     8.80 | bobeksde, faveN, kraghen, mantuu, raalz |
|           38 |      360 | 2025-02-19 | Iberian Soul                              | W   | 0.743      | 0.143        | -                | 0.620 (0.079)    | 0 (0.000) |     6.75 | bobeksde, faveN, kraghen, mantuu, raalz |
|           37 |      532 | 2025-02-15 | GUN5 Esports                              | W   | 0.721      | 0.435        | 0.105 (0.039)    | 0.562 (0.211)    | 0 (0.000) |    12.19 | bobeksde, faveN, kraghen, mantuu, raalz |
|           36 |      618 | 2025-02-13 | GTZ.ESPORTS                               | W   | 0.709      | 0.435        | 0.068 (0.025)    | 0.498 (0.184)    | 0 (0.000) |    16.74 | bobeksde, faveN, kraghen, mantuu, raalz |
|           35 |      659 | 2025-02-11 | Copenhagen Wolves (American organization) | W   | 0.698      | 0.435        | 0.017 (0.006)    | 1.000 (0.364)    | 0 (0.000) |     9.60 | bobeksde, faveN, kraghen, mantuu, raalz |
|           34 |      816 | 2025-02-08 | Astralis                                  | L   | 0.681      | -            | -                | -                | -         |    -0.12 | bobeksde, faveN, kraghen, mantuu, raalz |
|           33 |      865 | 2025-02-07 | ToxicAndCritic                            | L   | 0.678      | -            | -                | -                | -         |   -19.24 | bobeksde, faveN, kraghen, mantuu, raalz |
|           32 |      893 | 2025-02-07 | ENCE                                      | W   | 0.676      | 0.143        | 0.081 (0.009)    | -                | 0 (0.000) |    10.88 | bobeksde, faveN, kraghen, mantuu, raalz |
|           31 |      939 | 2025-02-06 | Dynamo Eclot                              | W   | 0.669      | 0.143        | 0.114 (0.013)    | -                | 0 (0.000) |    13.21 | bobeksde, faveN, kraghen, mantuu, raalz |
|           30 |      994 | 2025-02-05 | ENCE                                      | L   | 0.665      | -            | -                | -                | -         |   -10.03 | bobeksde, faveN, kraghen, mantuu, raalz |
|           29 |      996 | 2025-02-05 | Sashi Esport                              | L   | 0.665      | -            | -                | -                | -         |   -10.12 | bobeksde, faveN, kraghen, mantuu, raalz |
|           28 |     1005 | 2025-02-05 | Nexus Gaming                              | W   | 0.664      | 0.143        | 0.161 (0.018)    | -                | 0 (0.000) |    13.93 | bobeksde, faveN, kraghen, mantuu, raalz |
|           27 |     1042 | 2025-02-04 | Ninjas in Pyjamas                         | L   | 0.660      | -            | -                | -                | -         |   -17.52 | bobeksde, faveN, kraghen, mantuu, raalz |
|           26 |     1049 | 2025-02-04 | Johnny Speeds                             | W   | 0.659      | -            | -                | -                | 0 (0.000) |     2.13 | bobeksde, faveN, kraghen, mantuu, raalz |
|           25 |     1063 | 2025-02-04 | Ex-GODSENT                                | W   | 0.659      | -            | -                | -                | 0 (0.000) |     2.13 | bobeksde, faveN, kraghen, mantuu, raalz |
|           24 |     1082 | 2025-02-04 | Sashi Esport                              | W   | 0.659      | -            | -                | -                | -         |    10.98 | bobeksde, faveN, kraghen, mantuu, raalz |
|           23 |     1118 | 2025-02-03 | 500                                       | L   | 0.653      | -            | -                | -                | -         |    -8.41 | bobeksde, faveN, kraghen, mantuu, raalz |
|           22 |     1127 | 2025-02-02 | Fire Flux Esports                         | L   | 0.649      | -            | -                | -                | -         |   -10.72 | bobeksde, faveN, kraghen, mantuu, raalz |
|           21 |     1482 | 2025-01-09 | EYEBALLERS                                | L   | 0.516      | -            | -                | -                | -         |   -11.44 | bobeksde, faveN, mantuu, raalz, refrezh |
|           20 |     1498 | 2025-01-05 | FLuffy Gangsters                          | W   | 0.493      | 0.417        | -                | 0.635 (0.157)    | -         |     4.80 | bobeksde, faveN, mantuu, raalz, refrezh |
|           19 |     1507 | 2025-01-03 | EYEBALLERS                                | W   | 0.481      | 0.417        | 0.018 (0.004)    | -                | -         |     4.45 | bobeksde, faveN, mantuu, raalz, refrezh |
|           18 |     1597 | 2024-12-27 | Dark Cloud Esports                        | W   | 0.441      | 0.417        | 0.035 (0.008)    | 0.667 (0.147)    | -         |     5.18 | bobeksde, faveN, mantuu, raalz, refrezh |
|           17 |     1634 | 2024-12-22 | Betclic Apogee Esports                    | W   | 0.416      | 0.354        | -                | 0.528 (0.093)    | -         |     5.47 | bobeksde, faveN, mantuu, raalz, refrezh |
|           16 |     1656 | 2024-12-22 | UNiTY esports                             | W   | 0.414      | -            | -                | -                | -         |     3.91 | bobeksde, faveN, mantuu, raalz, refrezh |
|           15 |     1748 | 2024-12-20 | 500                                       | W   | 0.404      | 0.354        | 0.118 (0.020)    | 1.000 (0.172)    | -         |     8.33 | bobeksde, faveN, mantuu, raalz, refrezh |
|           14 |     1750 | 2024-12-20 | Betclic Apogee Esports                    | W   | 0.404      | 0.354        | -                | 0.528 (0.091)    | -         |     5.36 | bobeksde, faveN, mantuu, raalz, refrezh |
|           13 |     1884 | 2024-12-15 | ECSTATIC                                  | L   | 0.375      | -            | -                | -                | -         |    -6.45 | bobeksde, faveN, mantuu, raalz, refrezh |
|           12 |     1943 | 2024-12-14 | Metizport                                 | W   | 0.371      | 0.435        | 0.062 (0.012)    | -                | -         |     7.29 | bobeksde, faveN, mantuu, raalz, refrezh |
|           11 |     1962 | 2024-12-14 | Sashi Esport                              | L   | 0.369      | -            | -                | -                | -         |    -4.96 | bobeksde, faveN, mantuu, raalz, refrezh |
|           10 |     2030 | 2024-12-13 | ALTERNATE aTTaX                           | W   | 0.365      | -            | -                | -                | -         |     5.50 | bobeksde, faveN, mantuu, raalz, refrezh |
|            9 |     2077 | 2024-12-12 | TSM                                       | W   | 0.358      | -            | -                | -                | -         |     2.63 | bobeksde, faveN, mantuu, raalz, refrezh |
|            8 |     2153 | 2024-12-10 | Insilio                                   | W   | 0.348      | -            | -                | -                | -         |     1.83 | bobeksde, faveN, mantuu, raalz, refrezh |
|            7 |     2162 | 2024-12-10 | GUN5 Esports                              | L   | 0.347      | -            | -                | -                | -         |    -4.50 | bobeksde, faveN, mantuu, raalz, refrezh |
|            6 |     2212 | 2024-12-08 | Wild Lotus                                | L   | 0.338      | -            | -                | -                | -         |    -9.00 | bobeksde, faveN, mantuu, raalz, refrezh |
|            5 |     2244 | 2024-12-08 | Alliance                                  | W   | 0.336      | -            | -                | -                | -         |     4.67 | bobeksde, faveN, mantuu, raalz, refrezh |
|            4 |     2332 | 2024-12-07 | EYEBALLERS                                | W   | 0.330      | -            | -                | -                | -         |     3.43 | bobeksde, faveN, mantuu, raalz, refrezh |
|            3 |     2364 | 2024-12-06 | Iberian Soul                              | W   | 0.325      | 0.435        | -                | 0.620 (0.105)    | -         |     4.59 | bobeksde, faveN, mantuu, raalz, refrezh |
|            2 |     2433 | 2024-12-04 | Chimera Esports                           | W   | 0.314      | -            | -                | -                | -         |     4.06 | bobeksde, faveN, mantuu, raalz, refrezh |
|            1 |     2481 | 2024-12-03 | Sashi Esport                              | L   | 0.308      | -            | -                | -                | -         |    -3.93 | bobeksde, faveN, mantuu, raalz, refrezh |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,242.36)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $12,000.00     | $5,983.33       |
| 2024-12-15 |      0.452 | $5,000.00      | $2,259.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
