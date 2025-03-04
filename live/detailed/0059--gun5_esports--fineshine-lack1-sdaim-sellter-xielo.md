### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: fineshine, Lack1, Sdaim, SELLTER, xiELO<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  972.4<br />
<br />
Final Rank Value (972.4) = Starting Rank Value (997.8) + Head To Head Adjustments (-25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.381[<sup>2</sup>](#table1)
- Opponent Network: 0.245[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.8
- 400 + ( ( 0.287 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 997.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           67 |       26 | 2025-02-27 | Fire Flux Esports      | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    16.72 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           66 |       65 | 2025-02-26 | FAVBET Team            | L   | 1.000      | -            | -                | -                | -         |   -17.89 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           65 |      217 | 2025-02-22 | Natus Vincere Junior   | L   | 1.000      | -            | -                | -                | -         |   -13.74 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           64 |      275 | 2025-02-21 | Passion UA             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.495 (0.215)    | 0 (0.000) |    16.97 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           63 |      346 | 2025-02-19 | GameAgents             | L   | 1.000      | -            | -                | -                | -         |   -25.96 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           62 |      617 | 2025-02-12 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -8.44 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           61 |      851 | 2025-02-07 | Hesta                  | L   | 1.000      | -            | -                | -                | -         |   -25.83 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           60 |     1201 | 2025-01-28 | Aurora Gaming          | W   | 0.971      | 0.500        | 0.022 (0.011)    | 0.671 (0.326)    | 0 (0.000) |     8.49 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           59 |     1247 | 2025-01-24 | Rebels Gaming          | L   | 0.944      | -            | -                | -                | -         |   -23.28 | easy, Lack1, Sdaim, SELLTER, xiELO      |
|           58 |     1287 | 2025-01-22 | Natus Vincere Junior   | L   | 0.931      | -            | -                | -                | -         |   -14.35 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           57 |     1683 | 2024-12-17 | Dynamo Eclot           | W   | 0.691      | 0.435        | 0.150 (0.045)    | 0.705 (0.212)    | 0 (0.000) |    12.81 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           56 |     1693 | 2024-12-17 | Natus Vincere Junior   | W   | 0.688      | 0.371        | 0.106 (0.027)    | 1.000 (0.255)    | 0 (0.000) |    12.16 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           55 |     1698 | 2024-12-16 | Natus Vincere Junior   | W   | 0.685      | 0.435        | 0.106 (0.032)    | 1.000 (0.297)    | 0 (0.000) |    12.83 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           54 |     1711 | 2024-12-16 | Chimera Esports        | W   | 0.682      | 0.371        | -                | 0.597 (0.151)    | 0 (0.000) |     9.84 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           53 |     1754 | 2024-12-15 | Natus Vincere Junior   | L   | 0.676      | -            | -                | -                | -         |    -8.40 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           52 |     1921 | 2024-12-13 | Iberian Soul           | W   | 0.662      | -            | -                | -                | 0 (0.000) |     7.29 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           51 |     1945 | 2024-12-12 | Chimera Esports        | L   | 0.657      | -            | -                | -                | -         |   -12.02 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           50 |     1980 | 2024-12-11 | Aurora Gaming          | W   | 0.651      | 0.435        | -                | 0.671 (0.190)    | 0 (0.000) |     6.81 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           49 |     2012 | 2024-12-10 | Sashi Esport           | W   | 0.645      | 0.435        | -                | 0.606 (0.170)    | 0 (0.000) |    10.83 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           48 |     2037 | 2024-12-10 | 9INE                   | W   | 0.642      | 0.371        | -                | 0.862 (0.205)    | -         |     8.51 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           47 |     2053 | 2024-12-09 | Monte                  | L   | 0.637      | -            | -                | -                | -         |   -12.39 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           46 |     2289 | 2024-12-04 | Chimera Esports        | W   | 0.603      | -            | -                | -                | -         |     6.85 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           45 |     2563 | 2024-11-30 | BC.Game Esports        | W   | 0.575      | -            | -                | -                | -         |     7.06 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           44 |     2632 | 2024-11-28 | Tricked Esport         | L   | 0.564      | -            | -                | -                | -         |   -10.75 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           43 |     2643 | 2024-11-28 | Iberian Soul           | W   | 0.564      | -            | -                | -                | -         |     6.27 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           42 |     2678 | 2024-11-27 | Betclic Apogee Esports | L   | 0.557      | -            | -                | -                | -         |   -11.15 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           41 |     3523 | 2024-11-12 | 500                    | L   | 0.455      | -            | -                | -                | -         |    -5.68 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           40 |     3583 | 2024-11-11 | BIG                    | W   | 0.448      | 0.384        | 0.244 (0.042)    | -                | -         |    13.04 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           39 |     3634 | 2024-11-10 | 9INE                   | W   | 0.442      | -            | -                | -                | -         |     3.64 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           38 |     3658 | 2024-11-09 | Zero Tenacity          | L   | 0.437      | -            | -                | -                | -         |    -8.10 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           37 |     3944 | 2024-11-04 | Dynamo Eclot           | W   | 0.402      | 0.384        | 0.150 (0.023)    | -                | -         |     8.40 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           36 |     3996 | 2024-11-03 | Dynamo Eclot           | L   | 0.396      | -            | -                | -                | -         |    -4.24 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           35 |     4063 | 2024-11-02 | ECSTATIC               | W   | 0.390      | -            | -                | -                | -         |     5.17 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           34 |     4165 | 2024-10-31 | 500                    | W   | 0.378      | 0.384        | 0.114 (0.016)    | -                | -         |     7.49 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           33 |     4248 | 2024-10-30 | Wild Lotus             | L   | 0.369      | -            | -                | -                | -         |    -8.90 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           32 |     4308 | 2024-10-29 | Sashi Esport           | W   | 0.362      | -            | -                | -                | -         |     6.32 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           31 |     4424 | 2024-10-26 | FLuffy Gangsters       | L   | 0.344      | -            | -                | -                | -         |    -7.88 | mo0N, Sdaim, SELLTER, tN1R, xiELO       |
|           30 |     4482 | 2024-10-26 | Dynamo Eclot           | W   | 0.341      | 0.371        | 0.150 (0.019)    | -                | -         |     7.13 | easy, Sdaim, SELLTER, Xant3r, xiELO     |
|           29 |     4551 | 2024-10-24 | Insilio                | W   | 0.329      | -            | -                | -                | -         |     1.23 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           28 |     4587 | 2024-10-23 | Nuclear TigeRES        | L   | 0.323      | -            | -                | -                | -         |    -6.93 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           27 |     4660 | 2024-10-21 | FLuffy Gangsters       | W   | 0.310      | -            | -                | -                | -         |     2.69 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           26 |     4999 | 2024-10-15 | Tricked Esport         | L   | 0.268      | -            | -                | -                | -         |    -5.73 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           25 |     5058 | 2024-10-13 | Wild Lotus             | W   | 0.256      | -            | -                | -                | -         |     1.76 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           24 |     5106 | 2024-10-12 | SINNERS Esports        | L   | 0.250      | -            | -                | -                | -         |    -3.90 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           23 |     5175 | 2024-10-11 | GamerLegion            | W   | 0.243      | 0.435        | 0.103 (0.011)    | -                | -         |     7.37 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           22 |     5204 | 2024-10-10 | Los kogutos            | L   | 0.236      | -            | -                | -                | -         |    -3.50 | easy, Norwi, Sdaim, SELLTER, xiELO      |
|           21 |     5400 | 2024-10-07 | ALTERNATE aTTaX        | W   | 0.217      | -            | -                | -                | -         |     3.01 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           20 |     5456 | 2024-10-06 | ECSTATIC               | W   | 0.208      | -            | -                | -                | -         |     2.62 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           19 |     5539 | 2024-10-05 | FAVBET Team            | W   | 0.201      | -            | -                | -                | -         |     2.43 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           18 |     5625 | 2024-10-03 | Partizan Esports       | L   | 0.190      | -            | -                | -                | -         |    -1.81 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           17 |     5631 | 2024-10-03 | Preasy Esport          | W   | 0.189      | -            | -                | -                | -         |     1.72 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           16 |     5639 | 2024-10-03 | Passion UA             | L   | 0.188      | -            | -                | -                | -         |    -3.33 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           15 |     5677 | 2024-10-02 | Los kogutos            | W   | 0.183      | -            | -                | -                | -         |     3.23 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           14 |     5767 | 2024-10-01 | HOTU                   | W   | 0.175      | -            | -                | -                | -         |     1.13 | Sdaim, SELLTER, tN1R, tried, xiELO      |
|           13 |     6087 | 2024-09-26 | Nemiga Gaming          | L   | 0.144      | -            | -                | -                | -         |    -1.50 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           12 |     6092 | 2024-09-26 | EYEBALLERS             | W   | 0.143      | -            | -                | -                | -         |     1.27 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           11 |     6163 | 2024-09-25 | Team M33               | W   | 0.138      | -            | -                | -                | -         |     0.15 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           10 |     6480 | 2024-09-21 | Revenant Esports       | W   | 0.109      | -            | -                | -                | -         |     0.21 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            9 |     6736 | 2024-09-17 | BC.Game Esports        | L   | 0.083      | -            | -                | -                | -         |    -0.97 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            8 |     6746 | 2024-09-17 | Wild Lotus             | L   | 0.082      | -            | -                | -                | -         |    -2.04 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            7 |     6923 | 2024-09-14 | SINNERS Esports        | L   | 0.062      | -            | -                | -                | -         |    -0.92 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            6 |     6980 | 2024-09-13 | Team Space             | W   | 0.056      | -            | -                | -                | -         |     0.10 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            5 |     7021 | 2024-09-12 | PARIVISION             | W   | 0.050      | -            | -                | -                | -         |     0.30 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            4 |     7202 | 2024-09-09 | Monte                  | W   | 0.028      | -            | -                | -                | -         |     0.44 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            3 |     7349 | 2024-09-07 | Young Ninjas           | W   | 0.015      | -            | -                | -                | -         |     0.02 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            2 |     7401 | 2024-09-06 | Rebels Gaming          | W   | 0.010      | -            | -                | -                | -         |     0.01 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            1 |     7468 | 2024-09-05 | EYEBALLERS             | L   | 0.004      | -            | -                | -                | -         |    -0.08 | easy, Sdaim, SELLTER, tN1R, xiELO       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,964.31)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $500.00        | $500.00         |
| 2025-02-23 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-12-17 |      0.691 | $30,000.00     | $20,725.13      |
| 2024-12-17 |      0.688 | $11,000.00     | $7,571.72       |
| 2024-11-12 |      0.457 | $1,500.00      | $685.18         |
| 2024-11-03 |      0.398 | $1,021.74      | $406.14         |
| 2024-10-13 |      0.257 | $2,000.00      | $513.57         |
| 2024-10-03 |      0.190 | $7,500.00      | $1,422.60       |
| 2024-09-15 |      0.070 | $2,000.00      | $139.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
