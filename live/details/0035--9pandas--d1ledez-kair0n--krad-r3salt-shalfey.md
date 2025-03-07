### Roster Details<br />
Team Name: 9Pandas<br />
Roster: d1Ledez, KaiR0N-, Krad, r3salt, shalfey<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  995.9<br />
<br />
Final Rank Value (995.9) = Starting Rank Value (991.9) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.482[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 991.9
- 400 + ( ( 0.268 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 991.9


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
|           41 |       38 | 2025-02-27 | Monte                                     | W   | 0.786      | 0.435        | 0.036 (0.015)    | 0.766 (0.314)    | 0 (0.000) |    10.76 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           40 |      110 | 2025-02-25 | PARIVISION                                | L   | 0.777      | -            | -                | -                | -         |   -16.38 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           39 |      193 | 2025-02-23 | B8                                        | L   | 0.764      | -            | -                | -                | -         |    -8.59 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           38 |      244 | 2025-02-22 | Dynamo Eclot                              | W   | 0.758      | 0.435        | 0.114 (0.045)    | 0.468 (0.185)    | 0 (0.000) |    11.87 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           37 |      330 | 2025-02-20 | Sashi Esport                              | W   | 0.748      | 0.435        | -                | 0.535 (0.209)    | 0 (0.000) |    10.85 | d1Ledez, KaiR0N-, Krad, r3salt, shalfey         |
|           36 |      356 | 2025-02-19 | SINNERS Esports                           | W   | 0.744      | 0.500        | 0.016 (0.007)    | 0.494 (0.221)    | 0 (0.000) |     8.83 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           35 |      390 | 2025-02-18 | Copenhagen Wolves (American organization) | L   | 0.738      | -            | -                | -                | -         |   -15.73 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           34 |      607 | 2025-02-13 | 500                                       | L   | 0.710      | -            | -                | -                | -         |    -8.96 | d1Ledez, Krad, mo0N, r3salt, shalfey            |
|           33 |     1356 | 2025-01-23 | JiJieHao                                  | W   | 0.594      | 0.500        | -                | 0.252 (0.090)    | 0 (0.000) |     1.36 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           32 |     1421 | 2025-01-21 | Monte                                     | L   | 0.583      | -            | -                | -                | -         |   -10.49 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           31 |     1463 | 2025-01-14 | Team Liquid                               | L   | 0.543      | -            | -                | -                | -         |    -4.88 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           30 |     1467 | 2025-01-12 | Wildcard                                  | L   | 0.531      | -            | -                | -                | -         |    -6.01 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           29 |     1471 | 2025-01-11 | EYEBALLERS                                | W   | 0.526      | 0.417        | 0.018 (0.005)    | 0.262 (0.069)    | 0 (0.000) |     4.05 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           28 |     1478 | 2025-01-10 | GenOne                                    | W   | 0.520      | 0.417        | -                | 0.644 (0.168)    | 0 (0.000) |     4.24 | Alv, d1Ledez, Krad, r3salt, shalfey             |
|           27 |     2938 | 2024-11-23 | Ninjas in Pyjamas                         | L   | 0.256      | -            | -                | -                | -         |    -5.83 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           26 |     3041 | 2024-11-22 | Aurora Gaming                             | W   | 0.251      | -            | -                | -                | 1 (0.302) |     2.04 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           25 |     3119 | 2024-11-21 | Virtus.pro                                | L   | 0.246      | -            | -                | -                | -         |    -0.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           24 |     3170 | 2024-11-21 | G2 Esports                                | L   | 0.242      | -            | -                | -                | -         |    -0.55 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           23 |     3182 | 2024-11-20 | Astralis                                  | W   | 0.241      | 0.143        | 0.788 (0.033)    | -                | 1 (0.289) |     7.54 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           22 |     3717 | 2024-11-11 | Dynamo Eclot                              | W   | 0.186      | 0.371        | 0.114 (0.009)    | -                | 0 (0.000) |     3.09 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           21 |     3738 | 2024-11-10 | Dynamo Eclot                              | W   | 0.182      | 0.384        | 0.114 (0.010)    | -                | -         |     3.08 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           20 |     3760 | 2024-11-10 | 500                                       | L   | 0.181      | -            | -                | -                | -         |    -2.57 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           19 |     3803 | 2024-11-09 | Tricked Esport                            | W   | 0.176      | -            | -                | -                | -         |     1.54 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           18 |     3816 | 2024-11-09 | Natus Vincere Junior                      | W   | 0.176      | 0.371        | 0.078 (0.006)    | 0.786 (0.061)    | -         |     2.72 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           17 |     3862 | 2024-11-08 | Fire Flux Esports                         | W   | 0.170      | 0.384        | -                | 1.000 (0.078)    | -         |     1.93 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           16 |     3900 | 2024-11-07 | Aurora Gaming                             | L   | 0.165      | -            | -                | -                | -         |    -3.83 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           15 |     3910 | 2024-11-07 | Dynamo Eclot                              | W   | 0.164      | 0.371        | 0.114 (0.008)    | -                | -         |     2.75 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           14 |     3996 | 2024-11-05 | Insilio                                   | W   | 0.155      | -            | -                | -                | -         |     0.45 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           13 |     4017 | 2024-11-05 | Los kogutos                               | W   | 0.153      | -            | -                | -                | -         |     1.54 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           12 |     4138 | 2024-11-03 | Tricked Esport                            | W   | 0.142      | -            | -                | -                | -         |     1.26 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           11 |     4201 | 2024-11-02 | Endpoint                                  | W   | 0.137      | -            | -                | -                | -         |     0.90 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|           10 |     4268 | 2024-11-01 | Natus Vincere Junior                      | W   | 0.131      | 0.371        | 0.078 (0.005)    | 0.786 (0.046)    | -         |     2.05 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            9 |     4328 | 2024-10-31 | 9INE                                      | W   | 0.125      | -            | -                | -                | -         |     0.58 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            8 |     4396 | 2024-10-30 | Johnny Speeds                             | W   | 0.120      | -            | -                | -                | -         |     1.15 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            7 |     4522 | 2024-10-28 | ALASKA                                    | W   | 0.109      | -            | -                | -                | -         |     2.67 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            6 |     4688 | 2024-10-25 | Fire Flux Esports                         | W   | 0.092      | -            | -                | -                | -         |     1.07 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            5 |     4914 | 2024-10-20 | Dynamo Eclot                              | L   | 0.064      | -            | -                | -                | -         |    -0.93 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            4 |     5038 | 2024-10-17 | SAW                                       | L   | 0.049      | -            | -                | -                | -         |    -0.17 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            3 |     5123 | 2024-10-16 | TSM                                       | W   | 0.043      | -            | -                | -                | -         |     0.22 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            2 |     5193 | 2024-10-15 | Zero Tenacity                             | W   | 0.037      | -            | -                | -                | -         |     0.44 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |
|            1 |     5344 | 2024-10-12 | NewBALLS                                  | W   | 0.020      | -            | -                | -                | -         |     0.09 | d1Ledez, glowiing, iDISBALANCE, r3salt, shalfey |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,685.81)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      0.939 | $1,000.00      | $939.17         |
| 2025-02-23 |      0.919 | $5,000.00      | $4,593.52       |
| 2025-01-12 |      0.638 | $10,000.00     | $6,377.78       |
| 2024-11-12 |      0.232 | $500.00        | $115.75         |
| 2024-11-11 |      0.223 | $11,000.00     | $2,453.61       |
| 2024-11-10 |      0.219 | $12,500.00     | $2,736.11       |
| 2024-11-09 |      0.211 | $15.18         | $3.21           |
| 2024-10-20 |      0.078 | $6,000.00      | $466.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
