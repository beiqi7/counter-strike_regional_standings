### Roster Details<br />
Team Name: 9INE<br />
Roster: bobeksde, faveN, kraghen, mantuu, raalz<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1003.8<br />
<br />
Final Rank Value (1003.8) = Starting Rank Value (934.2) + Head To Head Adjustments (69.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.424[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.2
- 400 + ( ( 0.257 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 934.2


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
|           40 |      143 | 2025-02-24 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -7.96 | bobeksde, faveN, kraghen, mantuu, raalz |
|           39 |      261 | 2025-02-21 | Partizan Esports                          | L   | 1.000      | -            | -                | -                | -         |   -12.40 | BERRY, bobeksde, faveN, kraghen, mantuu |
|           38 |      308 | 2025-02-20 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.48 | bobeksde, faveN, kraghen, mantuu, raalz |
|           37 |      347 | 2025-02-19 | Iberian Soul                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.28 | bobeksde, faveN, kraghen, mantuu, raalz |
|           36 |      599 | 2025-02-13 | GTZ.ESPORTS                               | W   | 1.000      | 0.435        | 0.094 (0.041)    | 0.619 (0.269)    | 0 (0.000) |    22.12 | bobeksde, faveN, kraghen, mantuu, raalz |
|           35 |      638 | 2025-02-11 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | 0.019 (0.008)    | 1.000 (0.435)    | 0 (0.000) |    13.11 | bobeksde, faveN, kraghen, mantuu, raalz |
|           34 |      792 | 2025-02-08 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.34 | bobeksde, faveN, kraghen, mantuu, raalz |
|           33 |      841 | 2025-02-07 | ToxicAndCritic                            | L   | 1.000      | -            | -                | -                | -         |   -29.02 | bobeksde, faveN, kraghen, mantuu, raalz |
|           32 |      869 | 2025-02-07 | ENCE                                      | W   | 1.000      | 0.143        | 0.158 (0.023)    | -                | 0 (0.000) |    19.07 | bobeksde, faveN, kraghen, mantuu, raalz |
|           31 |      915 | 2025-02-06 | Dynamo Eclot                              | W   | 1.000      | 0.143        | 0.150 (0.021)    | -                | 0 (0.000) |    21.63 | bobeksde, faveN, kraghen, mantuu, raalz |
|           30 |      971 | 2025-02-05 | ENCE                                      | L   | 1.000      | -            | -                | -                | -         |   -11.21 | bobeksde, faveN, kraghen, mantuu, raalz |
|           29 |      973 | 2025-02-05 | Sashi Esport                              | L   | 1.000      | -            | -                | -                | -         |   -15.28 | bobeksde, faveN, kraghen, mantuu, raalz |
|           28 |      982 | 2025-02-05 | Nexus Gaming                              | W   | 1.000      | 0.143        | 0.219 (0.031)    | -                | 0 (0.000) |    18.71 | bobeksde, faveN, kraghen, mantuu, raalz |
|           27 |     1020 | 2025-02-04 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -26.50 | bobeksde, faveN, kraghen, mantuu, raalz |
|           26 |     1027 | 2025-02-04 | Johnny Speeds                             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.70 | bobeksde, faveN, kraghen, mantuu, raalz |
|           25 |     1041 | 2025-02-04 | Ex-GODSENT                                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.79 | bobeksde, faveN, kraghen, mantuu, raalz |
|           24 |     1060 | 2025-02-04 | Sashi Esport                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.16 | bobeksde, faveN, kraghen, mantuu, raalz |
|           23 |     1093 | 2025-02-03 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -13.90 | bobeksde, faveN, kraghen, mantuu, raalz |
|           22 |     1102 | 2025-02-02 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -15.95 | bobeksde, faveN, kraghen, mantuu, raalz |
|           21 |     1360 | 2025-01-09 | EYEBALLERS                                | L   | 0.845      | -            | -                | -                | -         |   -19.30 | bobeksde, faveN, mantuu, raalz, refrezh |
|           20 |     1375 | 2025-01-05 | FLuffy Gangsters                          | W   | 0.817      | 0.417        | -                | 0.924 (0.315)    | -         |     8.50 | bobeksde, faveN, mantuu, raalz, refrezh |
|           19 |     1383 | 2025-01-03 | EYEBALLERS                                | W   | 0.803      | -            | -                | -                | -         |     6.24 | bobeksde, faveN, mantuu, raalz, refrezh |
|           18 |     1476 | 2024-12-27 | Dark Cloud Esports                        | W   | 0.755      | 0.417        | 0.045 (0.014)    | 0.837 (0.264)    | -         |     8.26 | bobeksde, faveN, mantuu, raalz, refrezh |
|           17 |     1513 | 2024-12-22 | Betclic Apogee Esports                    | W   | 0.724      | -            | -                | -                | -         |     9.38 | bobeksde, faveN, mantuu, raalz, refrezh |
|           16 |     1535 | 2024-12-22 | UNiTY esports                             | W   | 0.723      | 0.354        | 0.030 (0.008)    | -                | -         |     7.42 | bobeksde, faveN, mantuu, raalz, refrezh |
|           15 |     1626 | 2024-12-20 | 500                                       | W   | 0.711      | 0.354        | 0.114 (0.029)    | 1.000 (0.252)    | -         |    14.40 | bobeksde, faveN, mantuu, raalz, refrezh |
|           14 |     1628 | 2024-12-20 | Betclic Apogee Esports                    | W   | 0.710      | -            | -                | -                | -         |     9.39 | bobeksde, faveN, mantuu, raalz, refrezh |
|           13 |     1757 | 2024-12-15 | ECSTATIC                                  | L   | 0.675      | -            | -                | -                | -         |   -10.46 | bobeksde, faveN, mantuu, raalz, refrezh |
|           12 |     1815 | 2024-12-14 | Metizport                                 | W   | 0.670      | 0.435        | 0.087 (0.025)    | 0.517 (0.151)    | -         |    14.71 | bobeksde, faveN, mantuu, raalz, refrezh |
|           11 |     1835 | 2024-12-14 | Sashi Esport                              | L   | 0.668      | -            | -                | -                | -         |    -8.44 | bobeksde, faveN, mantuu, raalz, refrezh |
|           10 |     1903 | 2024-12-13 | ALTERNATE aTTaX                           | W   | 0.663      | 0.435        | -                | 0.560 (0.161)    | -         |    11.03 | bobeksde, faveN, mantuu, raalz, refrezh |
|            9 |     1955 | 2024-12-12 | TSM                                       | W   | 0.655      | -            | -                | -                | -         |     5.88 | bobeksde, faveN, mantuu, raalz, refrezh |
|            8 |     2029 | 2024-12-10 | Insilio                                   | W   | 0.643      | 0.435        | -                | 0.513 (0.143)    | -         |     4.30 | bobeksde, faveN, mantuu, raalz, refrezh |
|            7 |     2037 | 2024-12-10 | GUN5 Esports                              | L   | 0.642      | -            | -                | -                | -         |    -8.51 | bobeksde, faveN, mantuu, raalz, refrezh |
|            6 |     2085 | 2024-12-08 | Wild Lotus                                | L   | 0.631      | -            | -                | -                | -         |   -13.24 | bobeksde, faveN, mantuu, raalz, refrezh |
|            5 |     2114 | 2024-12-08 | Alliance                                  | W   | 0.629      | -            | -                | -                | -         |     8.81 | bobeksde, faveN, mantuu, raalz, refrezh |
|            4 |     2195 | 2024-12-07 | EYEBALLERS                                | W   | 0.622      | -            | -                | -                | -         |     6.21 | bobeksde, faveN, mantuu, raalz, refrezh |
|            3 |     2227 | 2024-12-06 | Iberian Soul                              | W   | 0.616      | 0.435        | -                | 0.615 (0.164)    | -         |     9.13 | bobeksde, faveN, mantuu, raalz, refrezh |
|            2 |     2296 | 2024-12-04 | Chimera Esports                           | W   | 0.602      | 0.435        | 0.030 (0.008)    | 0.597 (0.156)    | -         |     9.02 | bobeksde, faveN, mantuu, raalz, refrezh |
|            1 |     2347 | 2024-12-03 | Sashi Esport                              | L   | 0.595      | -            | -                | -                | -         |    -6.59 | bobeksde, faveN, mantuu, raalz, refrezh |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,072.16)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.724 | $12,000.00     | $8,686.72       |
| 2024-12-15 |      0.677 | $5,000.00      | $3,385.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
