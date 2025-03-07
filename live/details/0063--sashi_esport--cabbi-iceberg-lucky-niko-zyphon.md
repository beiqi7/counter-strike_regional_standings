### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, Lucky, niko, Zyphon<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  903.9<br />
<br />
Final Rank Value (903.9) = Starting Rank Value (977.0) + Head To Head Adjustments (-73.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.367[<sup>2</sup>](#table1)
- Opponent Network: 0.265[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 977.0
- 400 + ( ( 0.262 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 977.0


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
|           49 |       16 | 2025-02-28 | Zero Tenacity                             | L   | 0.793      | -            | -                | -                | -         |   -13.38 | Cabbi, IceBerg, Lucky, niko, Zyphon   |
|           48 |       76 | 2025-02-26 | GTZ.ESPORTS                               | L   | 0.781      | -            | -                | -                | -         |    -6.88 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      113 | 2025-02-25 | Betera Esports                            | L   | 0.777      | -            | -                | -                | -         |   -19.81 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      144 | 2025-02-24 | Nemiga Gaming                             | L   | 0.771      | -            | -                | -                | -         |   -12.53 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      330 | 2025-02-20 | 9Pandas                                   | L   | 0.748      | -            | -                | -                | -         |   -10.85 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      394 | 2025-02-18 | CYBERSHOKE Esports                        | W   | 0.738      | 0.500        | 0.014 (0.006)    | 1.000 (0.443)    | 0 (0.000) |     8.78 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      473 | 2025-02-16 | Natus Vincere Junior                      | W   | 0.726      | 0.435        | 0.078 (0.030)    | 0.786 (0.298)    | 0 (0.000) |    12.14 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      547 | 2025-02-15 | SINNERS Esports                           | W   | 0.719      | 0.435        | 0.016 (0.006)    | 0.494 (0.185)    | 0 (0.000) |    10.45 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |      620 | 2025-02-13 | Nemiga Gaming                             | L   | 0.708      | -            | -                | -                | -         |   -11.32 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |      638 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 0.703      | 0.435        | 0.017 (0.006)    | 1.000 (0.367)    | 0 (0.000) |     8.90 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |      687 | 2025-02-10 | RUSH B (Russian team)                     | L   | 0.694      | -            | -                | -                | -         |   -10.74 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |      744 | 2025-02-09 | OG                                        | W   | 0.686      | 0.435        | 0.041 (0.015)    | 0.989 (0.354)    | 0 (0.000) |    10.49 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |      873 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 0.677      | -            | -                | -                | -         |   -16.57 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           36 |      881 | 2025-02-07 | MoneyF                                    | W   | 0.677      | -            | -                | -                | 0 (0.000) |     2.21 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           35 |      996 | 2025-02-05 | 9INE                                      | W   | 0.665      | 0.435        | 0.039 (0.014)    | 0.876 (0.304)    | 0 (0.000) |    10.12 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           34 |     1082 | 2025-02-04 | 9INE                                      | L   | 0.659      | -            | -                | -                | -         |   -10.98 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           33 |     1104 | 2025-02-03 | Monte                                     | L   | 0.655      | -            | -                | -                | -         |   -10.70 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           32 |     1134 | 2025-02-02 | B8                                        | L   | 0.647      | -            | -                | -                | -         |    -6.47 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           31 |     1327 | 2025-01-24 | Fire Flux Esports                         | L   | 0.598      | -            | -                | -                | -         |   -11.39 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           30 |     1360 | 2025-01-23 | 500                                       | W   | 0.594      | 0.500        | 0.118 (0.042)    | 1.000 (0.356)    | 0 (0.000) |    10.53 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           29 |     1893 | 2024-12-15 | Chimera Esports                           | L   | 0.375      | -            | -                | -                | -         |    -7.43 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           28 |     1962 | 2024-12-14 | 9INE                                      | W   | 0.369      | 0.371        | 0.039 (0.006)    | 0.876 (0.144)    | -         |     4.96 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           27 |     2034 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.364      | -            | -                | -                | -         |    -5.35 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           26 |     2117 | 2024-12-11 | Chimera Esports                           | W   | 0.353      | -            | -                | -                | -         |     3.96 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           25 |     2135 | 2024-12-10 | GUN5 Esports                              | L   | 0.349      | -            | -                | -                | -         |    -5.42 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           24 |     2172 | 2024-12-09 | Aurora Gaming                             | L   | 0.344      | -            | -                | -                | -         |    -7.66 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           23 |     2328 | 2024-12-07 | Alliance                                  | W   | 0.331      | 0.371        | -                | 0.516 (0.076)    | -         |     3.77 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           22 |     2481 | 2024-12-03 | 9INE                                      | W   | 0.308      | 0.371        | -                | 0.876 (0.120)    | -         |     3.93 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           21 |     2933 | 2024-11-24 | Team Spirit                               | L   | 0.258      | -            | -                | -                | -         |    -0.03 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3040 | 2024-11-22 | Virtus.pro                                | L   | 0.251      | -            | -                | -                | -         |    -0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3118 | 2024-11-21 | Eternal Fire                              | W   | 0.246      | 0.143        | 0.731 (0.031)    | -                | 1 (0.295) |     7.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3167 | 2024-11-21 | Astralis                                  | W   | 0.242      | 0.143        | 0.788 (0.033)    | -                | 1 (0.291) |     7.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3180 | 2024-11-20 | BIG                                       | L   | 0.241      | -            | -                | -                | -         |    -0.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3817 | 2024-11-09 | Dynamo Eclot                              | L   | 0.176      | -            | -                | -                | -         |    -2.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     3867 | 2024-11-08 | 500                                       | L   | 0.169      | -            | -                | -                | -         |    -2.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     3903 | 2024-11-07 | Endpoint                                  | W   | 0.165      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     3907 | 2024-11-07 | OG                                        | W   | 0.165      | -            | -                | -                | -         |     2.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4016 | 2024-11-05 | Rebels Gaming                             | W   | 0.153      | -            | -                | -                | -         |     1.27 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4206 | 2024-11-02 | Wild Lotus                                | L   | 0.137      | -            | -                | -                | -         |    -3.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4245 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.132      | -            | -                | -                | -         |    -3.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4248 | 2024-11-01 | Insilio                                   | L   | 0.132      | -            | -                | -                | -         |    -3.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4270 | 2024-11-01 | Los kogutos                               | W   | 0.131      | -            | -                | -                | -         |     1.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4465 | 2024-10-29 | GUN5 Esports                              | L   | 0.114      | -            | -                | -                | -         |    -1.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4718 | 2024-10-24 | Dynamo Eclot                              | W   | 0.087      | -            | -                | -                | -         |     0.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4964 | 2024-10-19 | Team Space                                | W   | 0.058      | -            | -                | -                | -         |     0.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     5039 | 2024-10-17 | 3DMAX                                     | L   | 0.049      | -            | -                | -                | -         |    -0.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     5113 | 2024-10-16 | PARIVISION                                | W   | 0.043      | -            | -                | -                | -         |     0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     5192 | 2024-10-15 | HEROIC                                    | L   | 0.037      | -            | -                | -                | -         |    -0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     5375 | 2024-10-12 | Fire Flux Esports                         | W   | 0.019      | -            | -                | -                | -         |     0.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,554.72)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.463 | $1,000.00      | $463.06         |
| 2024-11-10 |      0.219 | $2,500.00      | $547.22         |
| 2024-10-20 |      0.078 | $7,000.00      | $544.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
