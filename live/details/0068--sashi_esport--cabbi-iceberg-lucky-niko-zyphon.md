### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, Lucky, niko, Zyphon<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  939.4<br />
<br />
Final Rank Value (939.4) = Starting Rank Value (1039.8) + Head To Head Adjustments (-100.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.132[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1039.8
- 400 + ( ( 0.308 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1039.8


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
|           56 |       12 | 2025-02-28 | Zero Tenacity                             | L   | 1.000      | -            | -                | -                | -         |   -16.25 | Cabbi, IceBerg, Lucky, niko, Zyphon   |
|           55 |       72 | 2025-02-26 | GTZ.ESPORTS                               | L   | 1.000      | -            | -                | -                | -         |   -10.09 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           54 |      107 | 2025-02-25 | Betera Esports                            | L   | 1.000      | -            | -                | -                | -         |   -24.97 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           53 |      138 | 2025-02-24 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -13.48 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           52 |      323 | 2025-02-20 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -13.37 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           51 |      372 | 2025-02-18 | CYBERSHOKE Esports                        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | 0 (0.000) |    11.23 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           50 |      450 | 2025-02-16 | Natus Vincere Junior                      | W   | 1.000      | 0.435        | 0.106 (0.046)    | 1.000 (0.435)    | 0 (0.000) |    16.64 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           49 |      523 | 2025-02-15 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | 0 (0.000) |    14.93 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           48 |      603 | 2025-02-13 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -12.48 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      620 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    12.34 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      668 | 2025-02-10 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -14.82 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      722 | 2025-02-09 | OG                                        | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.985 (0.428)    | 0 (0.000) |    16.76 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      851 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 1.000      | -            | -                | -                | -         |   -24.87 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      859 | 2025-02-07 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.87 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      975 | 2025-02-05 | 9INE                                      | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.863 (0.375)    | 0 (0.000) |    15.28 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |     1062 | 2025-02-04 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -16.16 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |     1082 | 2025-02-03 | Monte                                     | L   | 1.000      | -            | -                | -                | -         |   -16.42 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |     1111 | 2025-02-02 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -8.11 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |     1254 | 2025-01-24 | Fire Flux Esports                         | L   | 0.943      | -            | -                | -                | -         |   -17.50 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |     1271 | 2025-01-23 | 500                                       | W   | 0.937      | 0.500        | 0.114 (0.053)    | 1.000 (0.469)    | 0 (0.000) |    15.32 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           36 |     1767 | 2024-12-15 | Chimera Esports                           | L   | 0.675      | -            | -                | -                | -         |   -12.27 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           35 |     1837 | 2024-12-14 | 9INE                                      | W   | 0.668      | 0.371        | 0.044 (0.011)    | 0.863 (0.214)    | -         |     8.43 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           34 |     1911 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.662      | -            | -                | -                | -         |    -9.24 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           33 |     1996 | 2024-12-11 | Chimera Esports                           | W   | 0.649      | -            | -                | -                | -         |     8.11 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           32 |     2014 | 2024-12-10 | GUN5 Esports                              | L   | 0.644      | -            | -                | -                | -         |   -10.82 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           31 |     2049 | 2024-12-09 | Aurora Gaming                             | L   | 0.637      | -            | -                | -                | -         |   -14.03 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           30 |     2193 | 2024-12-07 | Alliance                                  | W   | 0.622      | -            | -                | -                | -         |     6.49 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           29 |     2349 | 2024-12-03 | 9INE                                      | W   | 0.595      | 0.371        | 0.044 (0.010)    | 0.863 (0.190)    | -         |     6.59 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           28 |     2813 | 2024-11-24 | Team Spirit                               | L   | 0.534      | -            | -                | -                | -         |    -0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     2919 | 2024-11-22 | Virtus.pro                                | L   | 0.527      | -            | -                | -                | -         |    -0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3000 | 2024-11-21 | Eternal Fire                              | W   | 0.520      | 0.143        | 0.708 (0.053)    | -                | 1 (0.520) |    16.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3048 | 2024-11-21 | Astralis                                  | W   | 0.516      | 0.143        | 0.734 (0.054)    | -                | 1 (0.516) |    16.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3061 | 2024-11-20 | BIG                                       | L   | 0.514      | -            | -                | -                | -         |    -1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3684 | 2024-11-09 | Dynamo Eclot                              | L   | 0.436      | -            | -                | -                | -         |    -4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3734 | 2024-11-08 | 500                                       | L   | 0.428      | -            | -                | -                | -         |    -5.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3769 | 2024-11-07 | Endpoint                                  | W   | 0.423      | -            | -                | -                | -         |     3.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3773 | 2024-11-07 | OG                                        | W   | 0.422      | 0.384        | 0.072 (0.012)    | 0.985 (0.160)    | -         |     5.84 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3877 | 2024-11-05 | Rebels Gaming                             | W   | 0.409      | -            | -                | -                | -         |     3.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     4067 | 2024-11-02 | Wild Lotus                                | L   | 0.389      | -            | -                | -                | -         |    -9.35 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     4108 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.384      | -            | -                | -                | -         |    -9.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     4111 | 2024-11-01 | Insilio                                   | L   | 0.384      | -            | -                | -                | -         |   -10.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4133 | 2024-11-01 | Los kogutos                               | W   | 0.382      | -            | -                | -                | -         |     5.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4310 | 2024-10-29 | GUN5 Esports                              | L   | 0.361      | -            | -                | -                | -         |    -6.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4549 | 2024-10-24 | Dynamo Eclot                              | W   | 0.329      | -            | -                | -                | -         |     1.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4846 | 2024-10-17 | 3DMAX                                     | L   | 0.283      | -            | -                | -                | -         |    -0.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4904 | 2024-10-16 | PARIVISION                                | W   | 0.277      | -            | -                | -                | -         |     1.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4976 | 2024-10-15 | HEROIC                                    | L   | 0.270      | -            | -                | -                | -         |    -3.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     5153 | 2024-10-12 | Fire Flux Esports                         | W   | 0.248      | -            | -                | -                | -         |     2.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     6607 | 2024-09-19 | Monte                                     | L   | 0.095      | -            | -                | -                | -         |    -2.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     6732 | 2024-09-17 | BC.Game Esports                           | L   | 0.083      | -            | -                | -                | -         |    -1.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     6739 | 2024-09-17 | Wild Lotus                                | L   | 0.082      | -            | -                | -                | -         |    -2.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     6749 | 2024-09-17 | BC.Game Esports                           | W   | 0.081      | -            | -                | -                | -         |     1.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     6880 | 2024-09-14 | Rebels Gaming                             | L   | 0.063      | -            | -                | -                | -         |    -1.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     6910 | 2024-09-14 | OG                                        | W   | 0.062      | -            | -                | -                | -         |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     7032 | 2024-09-12 | TSM                                       | W   | 0.049      | -            | -                | -                | -         |     0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     7146 | 2024-09-10 | GamerLegion                               | W   | 0.035      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,232.49)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.688 | $1,000.00      | $687.97         |
| 2024-11-10 |      0.444 | $2,500.00      | $1,109.50       |
| 2024-10-20 |      0.303 | $7,000.00      | $2,118.81       |
| 2024-09-14 |      0.063 | $5,000.00      | $316.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
