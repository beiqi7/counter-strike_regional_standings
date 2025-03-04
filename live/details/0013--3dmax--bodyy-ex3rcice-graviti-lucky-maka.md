### Roster Details<br />
Team Name: 3DMAX<br />
Roster: bodyy, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1535.4<br />
<br />
Final Rank Value (1535.4) = Starting Rank Value (1611.9) + Head To Head Adjustments (-76.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.658[<sup>1</sup>](#table2)
- Bounty Collected: 0.510[<sup>2</sup>](#table1)
- Opponent Network: 0.280[<sup>2</sup>](#table1)
- LAN Wins: 0.883[<sup>2</sup>](#table1)

The average of these factors is 0.583<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1611.9
- 400 + ( ( 0.583 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1611.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |        7 | 2025-03-01 | TYLOO                      | L   | 1.000      | -            | -                | -                | -         |   -29.96 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           47 |      379 | 2025-02-18 | SAW                        | L   | 1.000      | -            | -                | -                | -         |   -25.21 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           46 |      414 | 2025-02-17 | Eternal Fire               | L   | 1.000      | -            | -                | -                | -         |    -5.20 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           45 |      474 | 2025-02-16 | MIBR                       | W   | 1.000      | 1.000        | 0.118 (0.118)    | 0.285 (0.285)    | 1 (1.000) |     2.21 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           44 |      525 | 2025-02-15 | MOUZ                       | L   | 1.000      | -            | -                | -                | -         |    -5.43 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           43 |      582 | 2025-02-14 | Virtus.pro                 | W   | 1.000      | 1.000        | 0.299 (0.299)    | 0.419 (0.419)    | 1 (1.000) |    19.16 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           42 |      666 | 2025-02-10 | HEROIC                     | W   | 1.000      | -            | -                | -                | -         |     2.64 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           41 |      675 | 2025-02-10 | NEVERMORE (Ukrainian team) | W   | 1.000      | 0.143        | -                | 0.928 (0.133)    | -         |     0.60 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           40 |     1084 | 2025-02-03 | Eternal Fire               | L   | 1.000      | -            | -                | -                | -         |    -4.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           39 |     1099 | 2025-02-02 | BIG                        | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     9.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           38 |     1134 | 2025-02-01 | Team Vitality              | L   | 0.996      | -            | -                | -                | -         |    -4.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           37 |     1169 | 2025-01-30 | MIBR                       | W   | 0.983      | 1.000        | 0.118 (0.116)    | 0.285 (0.280)    | 1 (0.983) |     2.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           36 |     1184 | 2025-01-29 | FlyQuest                   | W   | 0.975      | 1.000        | 0.099 (0.096)    | 0.267 (0.260)    | 1 (0.975) |     3.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           35 |     1344 | 2025-01-14 | HEROIC                     | L   | 0.876      | -            | -                | -                | -         |   -25.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           34 |     2992 | 2024-11-22 | G2 Esports                 | W   | 0.521      | 0.143        | 0.970 (0.072)    | -                | 1 (0.521) |    11.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           33 |     3047 | 2024-11-21 | Eternal Fire               | W   | 0.516      | 0.143        | 0.708 (0.052)    | -                | 1 (0.516) |    14.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           32 |     3060 | 2024-11-20 | TSM                        | W   | 0.514      | -            | -                | -                | 1 (0.514) |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           31 |     3990 | 2024-11-03 | OG                         | W   | 0.396      | 0.934        | 0.072 (0.027)    | 0.985 (0.364)    | 1 (0.396) |     0.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           30 |     4035 | 2024-11-02 | The MongolZ                | L   | 0.391      | -            | -                | -                | -         |    -1.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           29 |     4423 | 2024-10-26 | BESTIA                     | W   | 0.344      | 0.934        | 0.081 (0.026)    | 0.433 (0.139)    | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           28 |     4637 | 2024-10-21 | OG                         | W   | 0.310      | 0.934        | -                | 0.985 (0.286)    | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           27 |     4672 | 2024-10-21 | Team Falcons               | W   | 0.308      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           26 |     4763 | 2024-10-19 | Nemiga Gaming              | L   | 0.296      | -            | -                | -                | -         |    -8.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           25 |     4807 | 2024-10-18 | SAW                        | W   | 0.290      | 0.500        | 0.315 (0.046)    | -                | -         |     2.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           24 |     4846 | 2024-10-17 | Sashi Esport               | W   | 0.283      | -            | -                | -                | -         |     0.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           23 |     4906 | 2024-10-16 | Nemiga Gaming              | L   | 0.277      | -            | -                | -                | -         |    -8.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           22 |     4975 | 2024-10-15 | TSM                        | W   | 0.270      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           21 |     5125 | 2024-10-12 | Team Spirit Academy        | L   | 0.249      | -            | -                | -                | -         |    -7.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           20 |     5196 | 2024-10-10 | CYBERSHOKE Esports         | W   | 0.237      | 0.435        | -                | 1.000 (0.103)    | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           19 |     5459 | 2024-10-06 | Passion UA                 | L   | 0.208      | -            | -                | -                | -         |    -6.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           18 |     5538 | 2024-10-05 | PARIVISION                 | W   | 0.201      | -            | -                | -                | -         |     0.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           17 |     5626 | 2024-10-03 | Rhyno Esports              | W   | 0.189      | -            | -                | -                | -         |     0.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           16 |     5867 | 2024-09-29 | SAW                        | L   | 0.162      | -            | -                | -                | -         |    -3.77 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           15 |     5919 | 2024-09-28 | B8                         | L   | 0.157      | -            | -                | -                | -         |    -4.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           14 |     5973 | 2024-09-28 | BetBoom Team               | L   | 0.155      | -            | -                | -                | -         |    -4.66 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           13 |     6019 | 2024-09-27 | 9z Team                    | W   | 0.150      | -            | -                | -                | -         |     0.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           12 |     6039 | 2024-09-27 | Nemiga Gaming              | W   | 0.149      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           11 |     6056 | 2024-09-27 | CYBERSHOKE Esports         | W   | 0.148      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           10 |     6105 | 2024-09-26 | Aurora Gaming              | W   | 0.143      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            9 |     6132 | 2024-09-26 | Monte                      | W   | 0.141      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            8 |     6210 | 2024-09-25 | Zero Tenacity              | W   | 0.135      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            7 |     6316 | 2024-09-24 | Zero Tenacity              | W   | 0.127      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            6 |     6987 | 2024-09-13 | Zero Tenacity              | L   | 0.055      | -            | -                | -                | -         |    -1.71 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            5 |     7243 | 2024-09-08 | The MongolZ                | L   | 0.022      | -            | -                | -                | -         |    -0.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            4 |     7311 | 2024-09-07 | Wildcard                   | W   | 0.016      | -            | -                | -                | 1 (0.016) |     0.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            3 |     7384 | 2024-09-06 | Team Spirit                | L   | 0.010      | -            | -                | -                | -         |    -0.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            2 |     7413 | 2024-09-06 | 9z Team                    | W   | 0.008      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            1 |     7484 | 2024-09-05 | G2 Esports                 | L   | 0.003      | -            | -                | -                | -         |    -0.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($83,634.97)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.30) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.397 | $70,000.00     | $27,770.05      |
| 2024-10-20 |      0.303 | $10,000.00     | $3,026.87       |
| 2024-10-13 |      0.256 | $2,000.00      | $512.83         |
| 2024-10-06 |      0.210 | $5,000.00      | $1,051.28       |
| 2024-09-28 |      0.157 | $5,000.00      | $783.69         |
| 2024-09-26 |      0.143 | $12,500.00     | $1,784.75       |
| 2024-09-22 |      0.116 | $12,000.00     | $1,392.25       |
| 2024-09-14 |      0.063 | $1,000.00      | $63.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
