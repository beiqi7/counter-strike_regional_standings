### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, FreeZe, hyped, PerX, prosus<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  898.8<br />
<br />
Final Rank Value (898.8) = Starting Rank Value (886.8) + Head To Head Adjustments (11.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.364[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.201[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 886.8
- 400 + ( ( 0.221 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 886.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     2030 | 2024-12-13 | 9INE                   | L   | 0.365      | -            | -                | -                | -         |    -5.50 | ArroW, FreeZe, hyped, PerX, prosus |
|           36 |     2422 | 2024-12-04 | 500                    | L   | 0.316      | -            | -                | -                | -         |    -3.15 | ArroW, FreeZe, hyped, PerX, prosus |
|           35 |     2470 | 2024-12-03 | FAVBET Team            | W   | 0.310      | 0.372        | 0.023 (0.003)    | 0.790 (0.109)    | 0 (0.000) |     4.78 | ArroW, FreeZe, hyped, PerX, prosus |
|           34 |     2508 | 2024-12-02 | GameAgents             | W   | 0.305      | 0.372        | -                | 0.144 (0.020)    | 0 (0.000) |     2.13 | ArroW, FreeZe, hyped, PerX, prosus |
|           33 |     2562 | 2024-12-01 | Viperio                | W   | 0.299      | 0.372        | -                | 0.325 (0.043)    | 0 (0.000) |     2.87 | ArroW, FreeZe, hyped, PerX, prosus |
|           32 |     2758 | 2024-11-28 | Leo Team               | L   | 0.282      | -            | -                | -                | -         |    -5.24 | ArroW, FreeZe, hyped, PerX, prosus |
|           31 |     2836 | 2024-11-26 | KONO.ECF               | W   | 0.272      | 0.372        | 0.047 (0.006)    | 0.597 (0.072)    | 0 (0.000) |     4.28 | ArroW, FreeZe, hyped, PerX, prosus |
|           30 |     2905 | 2024-11-24 | Underrated             | W   | 0.259      | 0.372        | 0.002 (0.000)    | 0.219 (0.025)    | 0 (0.000) |     2.09 | ArroW, FreeZe, hyped, PerX, prosus |
|           29 |     3083 | 2024-11-22 | RUSTEC                 | W   | 0.249      | -            | -                | -                | -         |     1.65 | ArroW, FreeZe, hyped, PerX, prosus |
|           28 |     3092 | 2024-11-22 | PCIFIC Espor           | W   | 0.248      | 0.372        | 0.004 (0.000)    | 0.155 (0.017)    | -         |     2.44 | ArroW, FreeZe, hyped, PerX, prosus |
|           27 |     3142 | 2024-11-21 | Kay Team               | W   | 0.243      | -            | -                | -                | -         |     0.72 | ArroW, FreeZe, hyped, PerX, prosus |
|           26 |     3435 | 2024-11-16 | Nexus Gaming           | L   | 0.215      | -            | -                | -                | -         |    -1.49 | ArroW, faveN, FreeZe, hyped, PerX  |
|           25 |     3495 | 2024-11-15 | Team Hungary           | W   | 0.210      | 0.617        | 0.002 (0.000)    | 0.093 (0.014)    | 1 (0.252) |     2.07 | ArroW, faveN, FreeZe, hyped, PerX  |
|           24 |     3509 | 2024-11-15 | GTZ.ESPORTS            | W   | 0.209      | 0.617        | 0.068 (0.011)    | 0.498 (0.077)    | 1 (0.251) |     5.60 | ArroW, faveN, FreeZe, hyped, PerX  |
|           23 |     3569 | 2024-11-14 | MAFE MA3LOM            | W   | 0.204      | -            | -                | -                | 1 (0.244) |     0.45 | ArroW, faveN, FreeZe, hyped, PerX  |
|           22 |     3574 | 2024-11-14 | Team Kosovo            | W   | 0.203      | -            | -                | -                | 1 (0.244) |     0.39 | ArroW, faveN, FreeZe, hyped, PerX  |
|           21 |     3581 | 2024-11-14 | Team Chile             | W   | 0.203      | -            | -                | -                | 1 (0.244) |     0.50 | ArroW, faveN, FreeZe, hyped, PerX  |
|           20 |     4110 | 2024-11-03 | Permitta Esports       | L   | 0.143      | -            | -                | -                | -         |    -2.78 | ArroW, awzek, FreeZe, hyped, PerX  |
|           19 |     4187 | 2024-11-02 | BIG                    | L   | 0.138      | -            | -                | -                | -         |    -0.22 | ArroW, awzek, FreeZe, hyped, PerX  |
|           18 |     4240 | 2024-11-01 | Permitta Esports       | W   | 0.133      | 0.143        | 0.013 (0.000)    | -                | -         |     1.61 | ArroW, awzek, FreeZe, hyped, PerX  |
|           17 |     4256 | 2024-11-01 | HyperSpirit            | W   | 0.132      | -            | -                | -                | -         |     0.94 | ArroW, FreeZe, hyped, PerX, prosus |
|           16 |     4361 | 2024-10-30 | XPERION NXT            | W   | 0.122      | -            | -                | -                | -         |     0.84 | ArroW, awzek, FreeZe, hyped, PerX  |
|           15 |     4370 | 2024-10-30 | Ex-Soul's Heart Esport | W   | 0.121      | -            | -                | -                | -         |     0.42 | ArroW, FreeZe, hyped, PerX, prosus |
|           14 |     4383 | 2024-10-30 | ADEPTS                 | L   | 0.121      | -            | -                | -                | -         |    -3.28 | ArroW, FreeZe, hyped, PerX, prosus |
|           13 |     4503 | 2024-10-28 | ROUNDS                 | W   | 0.110      | -            | -                | -                | -         |     0.40 | ArroW, FreeZe, hyped, PerX, prosus |
|           12 |     4520 | 2024-10-28 | BIG                    | L   | 0.109      | -            | -                | -                | -         |    -0.17 | ArroW, awzek, FreeZe, hyped, PerX  |
|           11 |     4687 | 2024-10-25 | Passion UA             | L   | 0.092      | -            | -                | -                | -         |    -1.51 | ArroW, FreeZe, hyped, PerX, prosus |
|           10 |     4726 | 2024-10-24 | Dynamo Eclot           | L   | 0.085      | -            | -                | -                | -         |    -2.04 | ArroW, awzek, FreeZe, PerX, Rulz   |
|            9 |     4760 | 2024-10-23 | Sissi State Punks      | W   | 0.082      | -            | -                | -                | -         |     0.42 | ArroW, awzek, FreeZe, hyped, PerX  |
|            8 |     4771 | 2024-10-23 | ALASKA                 | W   | 0.081      | 0.372        | 0.033 (0.001)    | 0.737 (0.027)    | -         |     2.22 | ArroW, FreeZe, hyped, PerX, prosus |
|            7 |     4777 | 2024-10-23 | Preasy Esport          | W   | 0.080      | 0.384        | 0.010 (0.000)    | 0.647 (0.024)    | -         |     0.94 | ArroW, awzek, FreeZe, hyped, PerX  |
|            6 |     5205 | 2024-10-15 | QUAZAR                 | L   | 0.037      | -            | -                | -                | -         |    -0.86 | ArroW, FreeZe, hyped, PerX, prosus |
|            5 |     5213 | 2024-10-15 | HOTU                   | L   | 0.036      | -            | -                | -                | -         |    -0.82 | ArroW, awzek, FreeZe, hyped, PerX  |
|            4 |     5233 | 2024-10-14 | Permitta Esports       | W   | 0.032      | -            | -                | -                | -         |     0.39 | ArroW, awzek, FreeZe, hyped, PerX  |
|            3 |     5237 | 2024-10-14 | GTZ.ESPORTS            | W   | 0.032      | 0.372        | 0.068 (0.001)    | -                | -         |     0.86 | ArroW, FreeZe, hyped, PerX, prosus |
|            2 |     5489 | 2024-10-09 | Fire Flux Esports      | L   | 0.004      | -            | -                | -                | -         |    -0.07 | ArroW, FreeZe, hyped, PerX, prosus |
|            1 |     5500 | 2024-10-09 | TEAM NEXT LEVEL        | W   | 0.004      | -            | -                | -                | -         |     0.03 | ArroW, FreeZe, hyped, PerX, prosus |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,735.15)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.445 | $262.62        | $116.96         |
| 2024-12-08 |      0.405 | $750.00        | $303.96         |
| 2024-11-17 |      0.265 | $12,500.00     | $3,314.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
