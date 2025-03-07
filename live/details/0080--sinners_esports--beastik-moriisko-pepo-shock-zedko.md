### Roster Details<br />
Team Name: SINNERS Esports<br />
Roster: beastik, MoriiSko, Pepo, SHOCK, ZEDKO<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  873.9<br />
<br />
Final Rank Value (873.9) = Starting Rank Value (939.2) + Head To Head Adjustments (-65.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.204[<sup>2</sup>](#table1)
- LAN Wins: 0.086[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 939.2
- 400 + ( ( 0.244 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 939.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |       14 | 2025-02-28 | Fire Flux Esports                         | W   | 0.793      | 0.435        | 0.008 (0.003)    | 1.000 (0.414)    | 0 (0.000) |    13.76 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           42 |       28 | 2025-02-27 | Iberian Soul                              | L   | 0.788      | -            | -                | -                | -         |   -13.47 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           41 |      109 | 2025-02-25 | Copenhagen Wolves (American organization) | L   | 0.777      | -            | -                | -                | -         |   -12.98 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           40 |      356 | 2025-02-19 | 9Pandas                                   | L   | 0.744      | -            | -                | -                | -         |    -8.83 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           39 |      391 | 2025-02-18 | JiJieHao                                  | W   | 0.738      | 0.500        | -                | 0.252 (0.112)    | 0 (0.000) |     2.81 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           38 |      469 | 2025-02-16 | ECSTATIC                                  | L   | 0.727      | -            | -                | -                | -         |   -12.65 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           37 |      547 | 2025-02-15 | Sashi Esport                              | L   | 0.719      | -            | -                | -                | -         |   -10.45 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           36 |      635 | 2025-02-12 | ALASKA                                    | W   | 0.704      | 0.435        | 0.033 (0.012)    | 0.737 (0.271)    | 0 (0.000) |    14.75 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           35 |      695 | 2025-02-10 | GUN5 Esports                              | L   | 0.693      | -            | -                | -                | -         |    -8.84 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           34 |      731 | 2025-02-09 | Fire Flux Esports                         | L   | 0.688      | -            | -                | -                | -         |   -10.78 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           33 |      800 | 2025-02-08 | Little Red Door                           | L   | 0.682      | -            | -                | -                | -         |   -18.98 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           32 |      850 | 2025-02-07 | Soul's Heart Esport                       | W   | 0.678      | -            | -                | -                | 0 (0.000) |     1.01 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           31 |      895 | 2025-02-07 | Monte                                     | W   | 0.675      | 0.435        | 0.036 (0.013)    | 0.766 (0.270)    | 0 (0.000) |    10.91 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           30 |      966 | 2025-02-05 | OG                                        | L   | 0.666      | -            | -                | -                | -         |   -11.55 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           29 |     1037 | 2025-02-04 | Alliance                                  | L   | 0.660      | -            | -                | -                | -         |   -12.11 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           28 |     1143 | 2025-02-01 | GTZ.ESPORTS                               | W   | 0.644      | 0.435        | 0.068 (0.023)    | 0.498 (0.167)    | 0 (0.000) |    15.85 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           27 |     1355 | 2025-01-23 | Monte                                     | W   | 0.594      | 0.500        | 0.036 (0.013)    | 0.766 (0.273)    | 0 (0.000) |    10.23 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           26 |     1422 | 2025-01-21 | PARIVISION                                | W   | 0.583      | 0.500        | -                | 0.910 (0.318)    | 0 (0.000) |     3.82 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           25 |     1470 | 2025-01-11 | Wildcard                                  | L   | 0.527      | -            | -                | -                | -         |    -4.15 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           24 |     1479 | 2025-01-10 | KONO.ECF                                  | W   | 0.519      | 0.417        | -                | 0.439 (0.114)    | -         |     2.53 | beastik, MoriiSko, Pepo, SHOCK, ZEDKO  |
|           23 |     2012 | 2024-12-13 | ECSTATIC                                  | L   | 0.366      | -            | -                | -                | -         |    -6.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           22 |     2040 | 2024-12-13 | Team Spirit Academy                       | L   | 0.364      | -            | -                | -                | -         |    -5.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           21 |     2058 | 2024-12-12 | Natus Vincere Junior                      | L   | 0.360      | -            | -                | -                | -         |    -4.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           20 |     3252 | 2024-11-20 | GamerLegion                               | L   | 0.236      | -            | -                | -                | -         |    -0.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           19 |     3307 | 2024-11-18 | Cloud9                                    | L   | 0.229      | -            | -                | -                | -         |    -6.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           18 |     3351 | 2024-11-17 | Dynamo Eclot                              | W   | 0.224      | 0.143        | 0.114 (0.004)    | -                | 1 (0.268) |     4.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           17 |     3397 | 2024-11-17 | Natus Vincere                             | L   | 0.219      | -            | -                | -                | -         |    -0.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           16 |     3409 | 2024-11-16 | SAW                                       | W   | 0.219      | 0.143        | 0.316 (0.012)    | -                | 1 (0.262) |     6.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           15 |     3755 | 2024-11-10 | Dynamo Eclot                              | L   | 0.182      | -            | -                | -                | -         |    -2.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           14 |     3916 | 2024-11-07 | 500                                       | W   | 0.164      | 0.384        | 0.118 (0.009)    | 1.000 (0.075)    | -         |     3.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           13 |     3949 | 2024-11-06 | PARIVISION                                | L   | 0.160      | -            | -                | -                | -         |    -4.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|           12 |     3963 | 2024-11-06 | Los kogutos                               | L   | 0.158      | -            | -                | -                | -         |    -3.03 | beastik, majky, MoriiSko, oskar, SHOCK |
|           11 |     4009 | 2024-11-05 | 9INE                                      | W   | 0.154      | -            | -                | -                | -         |     0.94 | beastik, majky, MoriiSko, oskar, SHOCK |
|           10 |     4020 | 2024-11-05 | Dynamo Eclot                              | L   | 0.153      | -            | -                | -                | -         |    -1.87 | beastik, majky, MoriiSko, oskar, SHOCK |
|            9 |     4115 | 2024-11-03 | ECSTATIC                                  | W   | 0.143      | 0.143        | 0.027 (0.001)    | -                | -         |     1.86 | beastik, majky, MoriiSko, oskar, SHOCK |
|            8 |     4143 | 2024-11-03 | ARCRED                                    | W   | 0.142      | -            | -                | -                | -         |     1.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|            7 |     4263 | 2024-11-01 | Endpoint                                  | W   | 0.132      | -            | -                | -                | -         |     1.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|            6 |     4314 | 2024-10-31 | Rebels Gaming                             | W   | 0.126      | 0.384        | -                | 0.396 (0.023)    | -         |     1.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|            5 |     4461 | 2024-10-29 | HOTU                                      | L   | 0.114      | -            | -                | -                | -         |    -2.80 | beastik, majky, MoriiSko, oskar, SHOCK |
|            4 |     4566 | 2024-10-27 | Insilio                                   | W   | 0.103      | -            | -                | -                | -         |     0.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|            3 |     5297 | 2024-10-13 | Team Spirit Academy                       | L   | 0.025      | -            | -                | -                | -         |    -0.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|            2 |     5329 | 2024-10-12 | GUN5 Esports                              | W   | 0.021      | 0.435        | 0.105 (0.001)    | -                | -         |     0.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|            1 |     5393 | 2024-10-11 | Monte                                     | W   | 0.015      | -            | -                | -                | -         |     0.16 | beastik, majky, MoriiSko, oskar, SHOCK |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,462.16)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-12 |      0.638 | $5,000.00      | $3,188.89       |
| 2024-11-12 |      0.232 | $500.00        | $115.75         |
| 2024-10-13 |      0.032 | $5,000.00      | $157.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
