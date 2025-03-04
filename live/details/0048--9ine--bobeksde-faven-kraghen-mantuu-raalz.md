### Roster Details<br />
Team Name: 9INE<br />
Roster: bobeksde, faveN, kraghen, mantuu, raalz<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1003.7<br />
<br />
Final Rank Value (1003.7) = Starting Rank Value (934.1) + Head To Head Adjustments (69.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.424[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.1
- 400 + ( ( 0.257 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 934.1


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
|           40 |      145 | 2025-02-24 | BC.Game Esports                           | L   | 1.000      | -            | -                | -                | -         |    -7.96 | bobeksde, faveN, kraghen, mantuu, raalz |
|           39 |      263 | 2025-02-21 | Partizan Esports                          | L   | 1.000      | -            | -                | -                | -         |   -12.40 | BERRY, bobeksde, faveN, kraghen, mantuu |
|           38 |      310 | 2025-02-20 | Alliance                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.48 | bobeksde, faveN, kraghen, mantuu, raalz |
|           37 |      349 | 2025-02-19 | Iberian Soul                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.28 | bobeksde, faveN, kraghen, mantuu, raalz |
|           36 |      601 | 2025-02-13 | GTZ.ESPORTS                               | W   | 1.000      | 0.435        | 0.094 (0.041)    | 0.619 (0.269)    | 0 (0.000) |    22.12 | bobeksde, faveN, kraghen, mantuu, raalz |
|           35 |      640 | 2025-02-11 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | 0.019 (0.008)    | 1.000 (0.435)    | 0 (0.000) |    13.11 | bobeksde, faveN, kraghen, mantuu, raalz |
|           34 |      794 | 2025-02-08 | Astralis                                  | L   | 1.000      | -            | -                | -                | -         |    -0.34 | bobeksde, faveN, kraghen, mantuu, raalz |
|           33 |      843 | 2025-02-07 | ToxicAndCritic                            | L   | 1.000      | -            | -                | -                | -         |   -29.01 | bobeksde, faveN, kraghen, mantuu, raalz |
|           32 |      871 | 2025-02-07 | ENCE                                      | W   | 1.000      | 0.143        | 0.158 (0.023)    | -                | 0 (0.000) |    19.07 | bobeksde, faveN, kraghen, mantuu, raalz |
|           31 |      917 | 2025-02-06 | Dynamo Eclot                              | W   | 1.000      | 0.143        | 0.150 (0.021)    | -                | 0 (0.000) |    21.63 | bobeksde, faveN, kraghen, mantuu, raalz |
|           30 |      973 | 2025-02-05 | ENCE                                      | L   | 1.000      | -            | -                | -                | -         |   -11.22 | bobeksde, faveN, kraghen, mantuu, raalz |
|           29 |      975 | 2025-02-05 | Sashi Esport                              | L   | 1.000      | -            | -                | -                | -         |   -15.28 | bobeksde, faveN, kraghen, mantuu, raalz |
|           28 |      984 | 2025-02-05 | Nexus Gaming                              | W   | 1.000      | 0.143        | 0.219 (0.031)    | -                | 0 (0.000) |    18.72 | bobeksde, faveN, kraghen, mantuu, raalz |
|           27 |     1022 | 2025-02-04 | Ninjas in Pyjamas                         | L   | 1.000      | -            | -                | -                | -         |   -26.50 | bobeksde, faveN, kraghen, mantuu, raalz |
|           26 |     1029 | 2025-02-04 | Johnny Speeds                             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.70 | bobeksde, faveN, kraghen, mantuu, raalz |
|           25 |     1043 | 2025-02-04 | Ex-GODSENT                                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.80 | bobeksde, faveN, kraghen, mantuu, raalz |
|           24 |     1062 | 2025-02-04 | Sashi Esport                              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.16 | bobeksde, faveN, kraghen, mantuu, raalz |
|           23 |     1095 | 2025-02-03 | 500                                       | L   | 1.000      | -            | -                | -                | -         |   -13.89 | bobeksde, faveN, kraghen, mantuu, raalz |
|           22 |     1104 | 2025-02-02 | Fire Flux Esports                         | L   | 1.000      | -            | -                | -                | -         |   -15.95 | bobeksde, faveN, kraghen, mantuu, raalz |
|           21 |     1362 | 2025-01-09 | EYEBALLERS                                | L   | 0.844      | -            | -                | -                | -         |   -19.29 | bobeksde, faveN, mantuu, raalz, refrezh |
|           20 |     1377 | 2025-01-05 | FLuffy Gangsters                          | W   | 0.816      | 0.417        | -                | 0.924 (0.314)    | -         |     8.50 | bobeksde, faveN, mantuu, raalz, refrezh |
|           19 |     1385 | 2025-01-03 | EYEBALLERS                                | W   | 0.802      | -            | -                | -                | -         |     6.24 | bobeksde, faveN, mantuu, raalz, refrezh |
|           18 |     1478 | 2024-12-27 | Dark Cloud Esports                        | W   | 0.755      | 0.417        | 0.045 (0.014)    | 0.837 (0.263)    | -         |     8.26 | bobeksde, faveN, mantuu, raalz, refrezh |
|           17 |     1515 | 2024-12-22 | Betclic Apogee Esports                    | W   | 0.724      | -            | -                | -                | -         |     9.37 | bobeksde, faveN, mantuu, raalz, refrezh |
|           16 |     1537 | 2024-12-22 | UNiTY esports                             | W   | 0.722      | 0.354        | 0.030 (0.008)    | -                | -         |     7.42 | bobeksde, faveN, mantuu, raalz, refrezh |
|           15 |     1628 | 2024-12-20 | 500                                       | W   | 0.710      | 0.354        | 0.114 (0.029)    | 1.000 (0.251)    | -         |    14.39 | bobeksde, faveN, mantuu, raalz, refrezh |
|           14 |     1630 | 2024-12-20 | Betclic Apogee Esports                    | W   | 0.710      | -            | -                | -                | -         |     9.38 | bobeksde, faveN, mantuu, raalz, refrezh |
|           13 |     1759 | 2024-12-15 | ECSTATIC                                  | L   | 0.675      | -            | -                | -                | -         |   -10.45 | bobeksde, faveN, mantuu, raalz, refrezh |
|           12 |     1817 | 2024-12-14 | Metizport                                 | W   | 0.670      | 0.435        | 0.087 (0.025)    | 0.517 (0.150)    | -         |    14.71 | bobeksde, faveN, mantuu, raalz, refrezh |
|           11 |     1837 | 2024-12-14 | Sashi Esport                              | L   | 0.668      | -            | -                | -                | -         |    -8.43 | bobeksde, faveN, mantuu, raalz, refrezh |
|           10 |     1905 | 2024-12-13 | ALTERNATE aTTaX                           | W   | 0.663      | 0.435        | -                | 0.559 (0.161)    | -         |    11.02 | bobeksde, faveN, mantuu, raalz, refrezh |
|            9 |     1957 | 2024-12-12 | TSM                                       | W   | 0.655      | -            | -                | -                | -         |     5.88 | bobeksde, faveN, mantuu, raalz, refrezh |
|            8 |     2031 | 2024-12-10 | Insilio                                   | W   | 0.643      | 0.435        | -                | 0.513 (0.143)    | -         |     4.30 | bobeksde, faveN, mantuu, raalz, refrezh |
|            7 |     2039 | 2024-12-10 | GUN5 Esports                              | L   | 0.641      | -            | -                | -                | -         |    -8.50 | bobeksde, faveN, mantuu, raalz, refrezh |
|            6 |     2087 | 2024-12-08 | Wild Lotus                                | L   | 0.630      | -            | -                | -                | -         |   -13.24 | bobeksde, faveN, mantuu, raalz, refrezh |
|            5 |     2116 | 2024-12-08 | Alliance                                  | W   | 0.629      | -            | -                | -                | -         |     8.81 | bobeksde, faveN, mantuu, raalz, refrezh |
|            4 |     2197 | 2024-12-07 | EYEBALLERS                                | W   | 0.621      | -            | -                | -                | -         |     6.21 | bobeksde, faveN, mantuu, raalz, refrezh |
|            3 |     2229 | 2024-12-06 | Iberian Soul                              | W   | 0.615      | 0.435        | -                | 0.615 (0.164)    | -         |     9.13 | bobeksde, faveN, mantuu, raalz, refrezh |
|            2 |     2298 | 2024-12-04 | Chimera Esports                           | W   | 0.601      | 0.435        | 0.030 (0.008)    | 0.597 (0.156)    | -         |     9.01 | bobeksde, faveN, mantuu, raalz, refrezh |
|            1 |     2349 | 2024-12-03 | Sashi Esport                              | L   | 0.595      | -            | -                | -                | -         |    -6.59 | bobeksde, faveN, mantuu, raalz, refrezh |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,065.82)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.724 | $12,000.00     | $8,682.25       |
| 2024-12-15 |      0.677 | $5,000.00      | $3,383.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
