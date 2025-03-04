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
|           67 |       28 | 2025-02-27 | Fire Flux Esports      | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    16.72 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           66 |       67 | 2025-02-26 | FAVBET Team            | L   | 1.000      | -            | -                | -                | -         |   -17.88 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           65 |      219 | 2025-02-22 | Natus Vincere Junior   | L   | 1.000      | -            | -                | -                | -         |   -13.74 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           64 |      277 | 2025-02-21 | Passion UA             | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.494 (0.215)    | 0 (0.000) |    16.98 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           63 |      348 | 2025-02-19 | GameAgents             | L   | 1.000      | -            | -                | -                | -         |   -25.96 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           62 |      619 | 2025-02-12 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -8.44 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           61 |      853 | 2025-02-07 | Hesta                  | L   | 1.000      | -            | -                | -                | -         |   -25.83 | fineshine, Lack1, Sdaim, SELLTER, xiELO |
|           60 |     1203 | 2025-01-28 | Aurora Gaming          | W   | 0.971      | 0.500        | 0.022 (0.011)    | 0.671 (0.326)    | 0 (0.000) |     8.49 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           59 |     1249 | 2025-01-24 | Rebels Gaming          | L   | 0.944      | -            | -                | -                | -         |   -23.27 | easy, Lack1, Sdaim, SELLTER, xiELO      |
|           58 |     1289 | 2025-01-22 | Natus Vincere Junior   | L   | 0.931      | -            | -                | -                | -         |   -14.34 | easy, fineshine, Sdaim, SELLTER, xiELO  |
|           57 |     1685 | 2024-12-17 | Dynamo Eclot           | W   | 0.690      | 0.435        | 0.150 (0.045)    | 0.705 (0.211)    | 0 (0.000) |    12.81 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           56 |     1695 | 2024-12-17 | Natus Vincere Junior   | W   | 0.688      | 0.371        | 0.106 (0.027)    | 1.000 (0.255)    | 0 (0.000) |    12.15 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           55 |     1700 | 2024-12-16 | Natus Vincere Junior   | W   | 0.684      | 0.435        | 0.106 (0.032)    | 1.000 (0.297)    | 0 (0.000) |    12.83 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           54 |     1713 | 2024-12-16 | Chimera Esports        | W   | 0.682      | 0.371        | -                | 0.597 (0.151)    | 0 (0.000) |     9.84 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           53 |     1756 | 2024-12-15 | Natus Vincere Junior   | L   | 0.675      | -            | -                | -                | -         |    -8.40 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           52 |     1923 | 2024-12-13 | Iberian Soul           | W   | 0.661      | -            | -                | -                | 0 (0.000) |     7.28 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           51 |     1947 | 2024-12-12 | Chimera Esports        | L   | 0.656      | -            | -                | -                | -         |   -12.01 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           50 |     1982 | 2024-12-11 | Aurora Gaming          | W   | 0.651      | 0.435        | -                | 0.671 (0.190)    | 0 (0.000) |     6.80 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           49 |     2014 | 2024-12-10 | Sashi Esport           | W   | 0.644      | 0.435        | -                | 0.606 (0.170)    | 0 (0.000) |    10.82 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           48 |     2039 | 2024-12-10 | 9INE                   | W   | 0.641      | 0.371        | -                | 0.863 (0.205)    | -         |     8.50 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           47 |     2055 | 2024-12-09 | Monte                  | L   | 0.637      | -            | -                | -                | -         |   -12.38 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           46 |     2291 | 2024-12-04 | Chimera Esports        | W   | 0.602      | -            | -                | -                | -         |     6.84 | fineshine, Sdaim, SELLTER, tN1R, xiELO  |
|           45 |     2565 | 2024-11-30 | BC.Game Esports        | W   | 0.575      | -            | -                | -                | -         |     7.06 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           44 |     2634 | 2024-11-28 | Tricked Esport         | L   | 0.564      | -            | -                | -                | -         |   -10.74 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           43 |     2645 | 2024-11-28 | Iberian Soul           | W   | 0.563      | -            | -                | -                | -         |     6.26 | Pumpkin66, Sdaim, SELLTER, tN1R, xiELO  |
|           42 |     2680 | 2024-11-27 | Betclic Apogee Esports | L   | 0.557      | -            | -                | -                | -         |   -11.14 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           41 |     3525 | 2024-11-12 | 500                    | L   | 0.455      | -            | -                | -                | -         |    -5.67 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           40 |     3585 | 2024-11-11 | BIG                    | W   | 0.448      | 0.384        | 0.244 (0.042)    | -                | -         |    13.03 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           39 |     3636 | 2024-11-10 | 9INE                   | W   | 0.441      | -            | -                | -                | -         |     3.63 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           38 |     3660 | 2024-11-09 | Zero Tenacity          | L   | 0.437      | -            | -                | -                | -         |    -8.09 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           37 |     3946 | 2024-11-04 | Dynamo Eclot           | W   | 0.401      | 0.384        | 0.150 (0.023)    | -                | -         |     8.39 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           36 |     3998 | 2024-11-03 | Dynamo Eclot           | L   | 0.395      | -            | -                | -                | -         |    -4.24 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           35 |     4065 | 2024-11-02 | ECSTATIC               | W   | 0.389      | -            | -                | -                | -         |     5.17 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           34 |     4167 | 2024-10-31 | 500                    | W   | 0.377      | 0.384        | 0.114 (0.016)    | -                | -         |     7.48 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           33 |     4250 | 2024-10-30 | Wild Lotus             | L   | 0.369      | -            | -                | -                | -         |    -8.89 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           32 |     4310 | 2024-10-29 | Sashi Esport           | W   | 0.361      | -            | -                | -                | -         |     6.31 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           31 |     4426 | 2024-10-26 | FLuffy Gangsters       | L   | 0.343      | -            | -                | -                | -         |    -7.87 | mo0N, Sdaim, SELLTER, tN1R, xiELO       |
|           30 |     4484 | 2024-10-26 | Dynamo Eclot           | W   | 0.341      | 0.371        | 0.150 (0.019)    | -                | -         |     7.12 | easy, Sdaim, SELLTER, Xant3r, xiELO     |
|           29 |     4553 | 2024-10-24 | Insilio                | W   | 0.328      | -            | -                | -                | -         |     1.23 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           28 |     4589 | 2024-10-23 | Nuclear TigeRES        | L   | 0.323      | -            | -                | -                | -         |    -6.92 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           27 |     4662 | 2024-10-21 | FLuffy Gangsters       | W   | 0.310      | -            | -                | -                | -         |     2.69 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           26 |     5001 | 2024-10-15 | Tricked Esport         | L   | 0.267      | -            | -                | -                | -         |    -5.72 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           25 |     5060 | 2024-10-13 | Wild Lotus             | W   | 0.256      | -            | -                | -                | -         |     1.75 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           24 |     5108 | 2024-10-12 | SINNERS Esports        | L   | 0.250      | -            | -                | -                | -         |    -3.89 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           23 |     5177 | 2024-10-11 | GamerLegion            | W   | 0.243      | 0.435        | 0.103 (0.011)    | -                | -         |     7.36 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           22 |     5206 | 2024-10-10 | Los kogutos            | L   | 0.236      | -            | -                | -                | -         |    -3.50 | easy, Norwi, Sdaim, SELLTER, xiELO      |
|           21 |     5402 | 2024-10-07 | ALTERNATE aTTaX        | W   | 0.216      | -            | -                | -                | -         |     3.01 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           20 |     5458 | 2024-10-06 | ECSTATIC               | W   | 0.208      | -            | -                | -                | -         |     2.62 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           19 |     5541 | 2024-10-05 | FAVBET Team            | W   | 0.201      | -            | -                | -                | -         |     2.42 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           18 |     5627 | 2024-10-03 | Partizan Esports       | L   | 0.189      | -            | -                | -                | -         |    -1.80 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           17 |     5633 | 2024-10-03 | Preasy Esport          | W   | 0.188      | -            | -                | -                | -         |     1.72 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           16 |     5641 | 2024-10-03 | Passion UA             | L   | 0.187      | -            | -                | -                | -         |    -3.33 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           15 |     5679 | 2024-10-02 | Los kogutos            | W   | 0.182      | -            | -                | -                | -         |     3.22 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           14 |     5769 | 2024-10-01 | HOTU                   | W   | 0.175      | -            | -                | -                | -         |     1.13 | Sdaim, SELLTER, tN1R, tried, xiELO      |
|           13 |     6089 | 2024-09-26 | Nemiga Gaming          | L   | 0.143      | -            | -                | -                | -         |    -1.49 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           12 |     6094 | 2024-09-26 | EYEBALLERS             | W   | 0.143      | -            | -                | -                | -         |     1.27 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           11 |     6165 | 2024-09-25 | Team M33               | W   | 0.137      | -            | -                | -                | -         |     0.15 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|           10 |     6482 | 2024-09-21 | Revenant Esports       | W   | 0.109      | -            | -                | -                | -         |     0.21 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            9 |     6738 | 2024-09-17 | BC.Game Esports        | L   | 0.082      | -            | -                | -                | -         |    -0.97 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            8 |     6748 | 2024-09-17 | Wild Lotus             | L   | 0.081      | -            | -                | -                | -         |    -2.03 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            7 |     6925 | 2024-09-14 | SINNERS Esports        | L   | 0.062      | -            | -                | -                | -         |    -0.91 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            6 |     6982 | 2024-09-13 | Team Space             | W   | 0.056      | -            | -                | -                | -         |     0.10 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            5 |     7023 | 2024-09-12 | PARIVISION             | W   | 0.050      | -            | -                | -                | -         |     0.30 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            4 |     7204 | 2024-09-09 | Monte                  | W   | 0.028      | -            | -                | -                | -         |     0.43 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            3 |     7351 | 2024-09-07 | Young Ninjas           | W   | 0.015      | -            | -                | -                | -         |     0.02 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            2 |     7403 | 2024-09-06 | Rebels Gaming          | W   | 0.009      | -            | -                | -                | -         |     0.01 | easy, Sdaim, SELLTER, tN1R, xiELO       |
|            1 |     7470 | 2024-09-05 | EYEBALLERS             | L   | 0.003      | -            | -                | -                | -         |    -0.07 | easy, Sdaim, SELLTER, tN1R, xiELO       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,943.80)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-26 |      1.000 | $500.00        | $500.00         |
| 2025-02-23 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-12-17 |      0.690 | $30,000.00     | $20,713.95      |
| 2024-12-17 |      0.688 | $11,000.00     | $7,567.62       |
| 2024-11-12 |      0.456 | $1,500.00      | $684.62         |
| 2024-11-03 |      0.397 | $1,021.74      | $405.76         |
| 2024-10-13 |      0.256 | $2,000.00      | $512.83         |
| 2024-10-03 |      0.189 | $7,500.00      | $1,419.81       |
| 2024-09-15 |      0.070 | $2,000.00      | $139.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
