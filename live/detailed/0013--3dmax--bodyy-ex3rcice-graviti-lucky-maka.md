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
Final Rank Value (1535.4) = Starting Rank Value (1612.1) + Head To Head Adjustments (-76.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.658[<sup>1</sup>](#table2)
- Bounty Collected: 0.510[<sup>2</sup>](#table1)
- Opponent Network: 0.280[<sup>2</sup>](#table1)
- LAN Wins: 0.883[<sup>2</sup>](#table1)

The average of these factors is 0.583<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1612.1
- 400 + ( ( 0.583 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1612.1


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
|           48 |        5 | 2025-03-01 | TYLOO                      | L   | 1.000      | -            | -                | -                | -         |   -30.00 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           47 |      377 | 2025-02-18 | SAW                        | L   | 1.000      | -            | -                | -                | -         |   -25.22 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           46 |      412 | 2025-02-17 | Eternal Fire               | L   | 1.000      | -            | -                | -                | -         |    -5.20 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           45 |      472 | 2025-02-16 | MIBR                       | W   | 1.000      | 1.000        | 0.118 (0.118)    | 0.285 (0.285)    | 1 (1.000) |     2.20 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           44 |      523 | 2025-02-15 | MOUZ                       | L   | 1.000      | -            | -                | -                | -         |    -5.44 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           43 |      580 | 2025-02-14 | Virtus.pro                 | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.418 (0.418)    | 1 (1.000) |    19.16 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           42 |      664 | 2025-02-10 | HEROIC                     | W   | 1.000      | -            | -                | -                | -         |     2.64 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           41 |      673 | 2025-02-10 | NEVERMORE (Ukrainian team) | W   | 1.000      | 0.143        | -                | 0.928 (0.133)    | -         |     0.60 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           40 |     1082 | 2025-02-03 | Eternal Fire               | L   | 1.000      | -            | -                | -                | -         |    -4.42 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           39 |     1097 | 2025-02-02 | BIG                        | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     9.37 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           38 |     1132 | 2025-02-01 | Team Vitality              | L   | 0.996      | -            | -                | -                | -         |    -4.19 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           37 |     1167 | 2025-01-30 | MIBR                       | W   | 0.983      | 1.000        | 0.118 (0.116)    | 0.285 (0.281)    | 1 (0.983) |     2.49 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           36 |     1182 | 2025-01-29 | FlyQuest                   | W   | 0.975      | 1.000        | 0.099 (0.096)    | 0.267 (0.260)    | 1 (0.975) |     3.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           35 |     1342 | 2025-01-14 | HEROIC                     | L   | 0.876      | -            | -                | -                | -         |   -25.73 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           34 |     2990 | 2024-11-22 | G2 Esports                 | W   | 0.522      | 0.143        | 0.971 (0.072)    | -                | 1 (0.522) |    11.34 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           33 |     3045 | 2024-11-21 | Eternal Fire               | W   | 0.516      | 0.143        | 0.708 (0.052)    | -                | 1 (0.516) |    14.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           32 |     3058 | 2024-11-20 | TSM                        | W   | 0.515      | -            | -                | -                | 1 (0.515) |     0.18 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           31 |     3988 | 2024-11-03 | OG                         | W   | 0.396      | 0.934        | 0.072 (0.027)    | 0.984 (0.364)    | 1 (0.396) |     0.39 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           30 |     4033 | 2024-11-02 | The MongolZ                | L   | 0.391      | -            | -                | -                | -         |    -1.93 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           29 |     4421 | 2024-10-26 | BESTIA                     | W   | 0.344      | 0.934        | 0.081 (0.026)    | 0.433 (0.139)    | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           28 |     4635 | 2024-10-21 | OG                         | W   | 0.311      | 0.934        | -                | 0.984 (0.286)    | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           27 |     4670 | 2024-10-21 | Team Falcons               | W   | 0.308      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           26 |     4761 | 2024-10-19 | Nemiga Gaming              | L   | 0.296      | -            | -                | -                | -         |    -8.62 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           25 |     4805 | 2024-10-18 | SAW                        | W   | 0.290      | 0.500        | 0.315 (0.046)    | -                | -         |     2.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           24 |     4844 | 2024-10-17 | Sashi Esport               | W   | 0.284      | -            | -                | -                | -         |     0.41 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           23 |     4904 | 2024-10-16 | Nemiga Gaming              | L   | 0.277      | -            | -                | -                | -         |    -8.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           22 |     4973 | 2024-10-15 | TSM                        | W   | 0.270      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           21 |     5123 | 2024-10-12 | Team Spirit Academy        | L   | 0.249      | -            | -                | -                | -         |    -7.55 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           20 |     5194 | 2024-10-10 | CYBERSHOKE Esports         | W   | 0.237      | 0.435        | -                | 1.000 (0.103)    | -         |     0.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           19 |     5457 | 2024-10-06 | Passion UA                 | L   | 0.208      | -            | -                | -                | -         |    -6.38 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           18 |     5536 | 2024-10-05 | PARIVISION                 | W   | 0.201      | -            | -                | -                | -         |     0.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           17 |     5624 | 2024-10-03 | Rhyno Esports              | W   | 0.190      | -            | -                | -                | -         |     0.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           16 |     5865 | 2024-09-29 | SAW                        | L   | 0.163      | -            | -                | -                | -         |    -3.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           15 |     5917 | 2024-09-28 | B8                         | L   | 0.157      | -            | -                | -                | -         |    -4.45 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           14 |     5971 | 2024-09-28 | BetBoom Team               | L   | 0.155      | -            | -                | -                | -         |    -4.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           13 |     6017 | 2024-09-27 | 9z Team                    | W   | 0.150      | -            | -                | -                | -         |     0.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           12 |     6037 | 2024-09-27 | Nemiga Gaming              | W   | 0.149      | -            | -                | -                | -         |     0.29 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           11 |     6054 | 2024-09-27 | CYBERSHOKE Esports         | W   | 0.148      | -            | -                | -                | -         |     0.09 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           10 |     6103 | 2024-09-26 | Aurora Gaming              | W   | 0.143      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            9 |     6130 | 2024-09-26 | Monte                      | W   | 0.141      | -            | -                | -                | -         |     0.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            8 |     6208 | 2024-09-25 | Zero Tenacity              | W   | 0.135      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            7 |     6314 | 2024-09-24 | Zero Tenacity              | W   | 0.128      | -            | -                | -                | -         |     0.10 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            6 |     6985 | 2024-09-13 | Zero Tenacity              | L   | 0.056      | -            | -                | -                | -         |    -1.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            5 |     7241 | 2024-09-08 | The MongolZ                | L   | 0.022      | -            | -                | -                | -         |    -0.13 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            4 |     7309 | 2024-09-07 | Wildcard                   | W   | 0.016      | -            | -                | -                | 1 (0.016) |     0.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            3 |     7382 | 2024-09-06 | Team Spirit                | L   | 0.010      | -            | -                | -                | -         |    -0.03 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            2 |     7411 | 2024-09-06 | 9z Team                    | W   | 0.009      | -            | -                | -                | -         |     0.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            1 |     7482 | 2024-09-05 | G2 Esports                 | L   | 0.003      | -            | -                | -                | -         |    -0.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($83,678.76)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.30) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.397 | $70,000.00     | $27,796.14      |
| 2024-10-20 |      0.303 | $10,000.00     | $3,030.60       |
| 2024-10-13 |      0.257 | $2,000.00      | $513.57         |
| 2024-10-06 |      0.211 | $5,000.00      | $1,053.15       |
| 2024-09-28 |      0.157 | $5,000.00      | $785.55         |
| 2024-09-26 |      0.143 | $12,500.00     | $1,789.41       |
| 2024-09-22 |      0.116 | $12,000.00     | $1,396.72       |
| 2024-09-14 |      0.064 | $1,000.00      | $63.62          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
