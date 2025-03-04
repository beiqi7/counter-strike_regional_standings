### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, Lucky, niko, Zyphon<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  939.3<br />
<br />
Final Rank Value (939.3) = Starting Rank Value (1039.9) + Head To Head Adjustments (-100.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.346[<sup>2</sup>](#table1)
- LAN Wins: 0.132[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1039.9
- 400 + ( ( 0.308 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1039.9


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
|           56 |       10 | 2025-02-28 | Zero Tenacity                             | L   | 1.000      | -            | -                | -                | -         |   -16.24 | Cabbi, IceBerg, Lucky, niko, Zyphon   |
|           55 |       70 | 2025-02-26 | GTZ.ESPORTS                               | L   | 1.000      | -            | -                | -                | -         |   -10.08 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           54 |      105 | 2025-02-25 | Betera Esports                            | L   | 1.000      | -            | -                | -                | -         |   -24.97 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           53 |      136 | 2025-02-24 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -13.57 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           52 |      321 | 2025-02-20 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -13.36 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           51 |      370 | 2025-02-18 | CYBERSHOKE Esports                        | W   | 1.000      | 0.500        | -                | 1.000 (0.500)    | 0 (0.000) |    11.23 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           50 |      448 | 2025-02-16 | Natus Vincere Junior                      | W   | 1.000      | 0.435        | 0.106 (0.046)    | 1.000 (0.435)    | 0 (0.000) |    16.65 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           49 |      521 | 2025-02-15 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.597 (0.259)    | 0 (0.000) |    14.94 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           48 |      601 | 2025-02-13 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -12.58 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      618 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    12.34 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      666 | 2025-02-10 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -14.82 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      720 | 2025-02-09 | OG                                        | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.984 (0.428)    | 0 (0.000) |    16.76 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      849 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 1.000      | -            | -                | -                | -         |   -24.87 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      857 | 2025-02-07 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.86 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      973 | 2025-02-05 | 9INE                                      | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.862 (0.375)    | 0 (0.000) |    15.28 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |     1060 | 2025-02-04 | 9INE                                      | L   | 1.000      | -            | -                | -                | -         |   -16.16 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |     1080 | 2025-02-03 | Monte                                     | L   | 1.000      | -            | -                | -                | -         |   -16.42 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |     1109 | 2025-02-02 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -8.11 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |     1252 | 2025-01-24 | Fire Flux Esports                         | L   | 0.943      | -            | -                | -                | -         |   -17.51 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |     1269 | 2025-01-23 | 500                                       | W   | 0.938      | 0.500        | 0.114 (0.053)    | 1.000 (0.469)    | 0 (0.000) |    15.33 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           36 |     1765 | 2024-12-15 | Chimera Esports                           | L   | 0.675      | -            | -                | -                | -         |   -12.28 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           35 |     1835 | 2024-12-14 | 9INE                                      | W   | 0.668      | 0.371        | 0.044 (0.011)    | 0.862 (0.214)    | -         |     8.44 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           34 |     1909 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.663      | -            | -                | -                | -         |    -9.24 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           33 |     1994 | 2024-12-11 | Chimera Esports                           | W   | 0.649      | -            | -                | -                | -         |     8.11 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           32 |     2012 | 2024-12-10 | GUN5 Esports                              | L   | 0.645      | -            | -                | -                | -         |   -10.83 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           31 |     2047 | 2024-12-09 | Aurora Gaming                             | L   | 0.638      | -            | -                | -                | -         |   -14.04 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           30 |     2191 | 2024-12-07 | Alliance                                  | W   | 0.622      | -            | -                | -                | -         |     6.49 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           29 |     2347 | 2024-12-03 | 9INE                                      | W   | 0.595      | 0.371        | 0.044 (0.010)    | 0.862 (0.190)    | -         |     6.59 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           28 |     2811 | 2024-11-24 | Team Spirit                               | L   | 0.535      | -            | -                | -                | -         |    -0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     2917 | 2024-11-22 | Virtus.pro                                | L   | 0.527      | -            | -                | -                | -         |    -0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     2998 | 2024-11-21 | Eternal Fire                              | W   | 0.521      | 0.143        | 0.708 (0.053)    | -                | 1 (0.521) |    16.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3046 | 2024-11-21 | Astralis                                  | W   | 0.516      | 0.143        | 0.734 (0.054)    | -                | 1 (0.516) |    16.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3059 | 2024-11-20 | BIG                                       | L   | 0.515      | -            | -                | -                | -         |    -1.30 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3682 | 2024-11-09 | Dynamo Eclot                              | L   | 0.436      | -            | -                | -                | -         |    -4.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3732 | 2024-11-08 | 500                                       | L   | 0.428      | -            | -                | -                | -         |    -5.61 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3767 | 2024-11-07 | Endpoint                                  | W   | 0.423      | -            | -                | -                | -         |     3.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3771 | 2024-11-07 | OG                                        | W   | 0.423      | 0.384        | 0.072 (0.012)    | 0.984 (0.160)    | -         |     5.85 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3875 | 2024-11-05 | Rebels Gaming                             | W   | 0.409      | -            | -                | -                | -         |     3.42 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     4065 | 2024-11-02 | Wild Lotus                                | L   | 0.389      | -            | -                | -                | -         |    -9.36 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     4106 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.384      | -            | -                | -                | -         |    -9.11 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     4109 | 2024-11-01 | Insilio                                   | L   | 0.384      | -            | -                | -                | -         |   -10.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4131 | 2024-11-01 | Los kogutos                               | W   | 0.382      | -            | -                | -                | -         |     5.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4308 | 2024-10-29 | GUN5 Esports                              | L   | 0.362      | -            | -                | -                | -         |    -6.32 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4547 | 2024-10-24 | Dynamo Eclot                              | W   | 0.329      | -            | -                | -                | -         |     1.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4844 | 2024-10-17 | 3DMAX                                     | L   | 0.284      | -            | -                | -                | -         |    -0.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4902 | 2024-10-16 | PARIVISION                                | W   | 0.277      | -            | -                | -                | -         |     1.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4974 | 2024-10-15 | HEROIC                                    | L   | 0.270      | -            | -                | -                | -         |    -3.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     5151 | 2024-10-12 | Fire Flux Esports                         | W   | 0.249      | -            | -                | -                | -         |     2.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     6605 | 2024-09-19 | Monte                                     | L   | 0.095      | -            | -                | -                | -         |    -2.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     6730 | 2024-09-17 | BC.Game Esports                           | L   | 0.083      | -            | -                | -                | -         |    -1.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     6737 | 2024-09-17 | Wild Lotus                                | L   | 0.083      | -            | -                | -                | -         |    -2.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     6747 | 2024-09-17 | BC.Game Esports                           | W   | 0.082      | -            | -                | -                | -         |     1.46 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     6878 | 2024-09-14 | Rebels Gaming                             | L   | 0.064      | -            | -                | -                | -         |    -1.53 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     6908 | 2024-09-14 | OG                                        | W   | 0.063      | -            | -                | -                | -         |     0.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     7030 | 2024-09-12 | TSM                                       | W   | 0.049      | -            | -                | -                | -         |     0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     7144 | 2024-09-10 | GamerLegion                               | W   | 0.035      | -            | -                | -                | -         |     0.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,238.26)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.688 | $1,000.00      | $688.34         |
| 2024-11-10 |      0.444 | $2,500.00      | $1,110.43       |
| 2024-10-20 |      0.303 | $7,000.00      | $2,121.42       |
| 2024-09-14 |      0.064 | $5,000.00      | $318.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
