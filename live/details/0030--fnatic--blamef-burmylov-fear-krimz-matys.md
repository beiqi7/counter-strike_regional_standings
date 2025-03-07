### Roster Details<br />
Team Name: Fnatic<br />
Roster: blameF, Burmylov, fear, KRIMZ, matys<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1035.4<br />
<br />
Final Rank Value (1035.4) = Starting Rank Value (1008.4) + Head To Head Adjustments (27.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.151[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1008.4
- 400 + ( ( 0.276 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1008.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       65 | 2025-02-26 | BC.Game Esports        | W   | 0.783      | 0.435        | 0.061 (0.025)    | 1.000 (0.408)    | 0 (0.000) |    14.34 | blameF, Burmylov, fear, KRIMZ, matys |
|           25 |      327 | 2025-02-20 | Dynamo Eclot           | L   | 0.748      | -            | -                | -                | -         |   -12.85 | blameF, Burmylov, fear, KRIMZ, matys |
|           24 |      441 | 2025-02-17 | RUSH B (Russian team)  | W   | 0.731      | 0.435        | 0.026 (0.010)    | 0.901 (0.343)    | 0 (0.000) |     8.89 | blameF, Burmylov, fear, KRIMZ, matys |
|           23 |      525 | 2025-02-15 | Monte                  | L   | 0.721      | -            | -                | -                | -         |   -13.73 | blameF, Burmylov, fear, KRIMZ, matys |
|           22 |      616 | 2025-02-13 | 500                    | W   | 0.709      | 0.435        | 0.118 (0.044)    | 1.000 (0.370)    | 0 (0.000) |    12.62 | blameF, Burmylov, fear, KRIMZ, matys |
|           21 |      639 | 2025-02-12 | Partizan Esports       | L   | 0.703      | -            | -                | -                | -         |   -11.31 | blameF, Burmylov, fear, KRIMZ, matys |
|           20 |      705 | 2025-02-10 | ECSTATIC               | W   | 0.691      | 0.435        | 0.027 (0.010)    | 0.659 (0.238)    | 0 (0.000) |     5.97 | blameF, Burmylov, fear, KRIMZ, matys |
|           19 |      801 | 2025-02-08 | Team Novaq             | L   | 0.682      | -            | -                | -                | -         |   -13.12 | blameF, Burmylov, fear, KRIMZ, matys |
|           18 |      876 | 2025-02-07 | Permitta Esports       | W   | 0.677      | 0.143        | -                | 0.349 (0.041)    | 0 (0.000) |     4.81 | blameF, Burmylov, fear, KRIMZ, matys |
|           17 |      922 | 2025-02-06 | Team Spirit Academy    | W   | 0.672      | 0.435        | 0.053 (0.019)    | 0.682 (0.239)    | -         |     9.10 | blameF, Burmylov, fear, KRIMZ, matys |
|           16 |     1075 | 2025-02-04 | Betclic Apogee Esports | W   | 0.659      | 0.435        | 0.012 (0.004)    | 0.528 (0.181)    | -         |     7.16 | blameF, Burmylov, fear, KRIMZ, matys |
|           15 |     1160 | 2025-02-01 | OG                     | W   | 0.642      | 0.435        | 0.041 (0.014)    | 0.989 (0.331)    | -         |     6.52 | blameF, Burmylov, fear, KRIMZ, matys |
|           14 |     1462 | 2025-01-14 | Team Spirit            | L   | 0.544      | -            | -                | -                | -         |    -0.08 | blameF, Burmylov, fear, KRIMZ, matys |
|           13 |     3257 | 2024-11-19 | Dynamo Eclot           | W   | 0.235      | 0.143        | 0.114 (0.005)    | 0.468 (0.019)    | 1 (0.282) |     3.79 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           12 |     3299 | 2024-11-19 | FaZe Clan              | L   | 0.230      | -            | -                | -                | -         |    -0.07 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           11 |     3348 | 2024-11-17 | BetBoom Team           | W   | 0.224      | 0.143        | 0.101 (0.004)    | -                | 1 (0.269) |     3.48 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           10 |     3394 | 2024-11-17 | Rebels Gaming          | W   | 0.220      | -            | -                | -                | 1 (0.264) |     1.52 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            9 |     3414 | 2024-11-16 | Natus Vincere          | L   | 0.218      | -            | -                | -                | -         |    -0.30 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            8 |     4611 | 2024-10-26 | Team Falcons           | L   | 0.098      | -            | -                | -                | -         |    -0.02 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            7 |     4698 | 2024-10-25 | Cloud9                 | W   | 0.091      | -            | -                | -                | -         |     0.28 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            6 |     4789 | 2024-10-22 | The MongolZ            | L   | 0.077      | -            | -                | -                | -         |    -0.02 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            5 |     4811 | 2024-10-22 | 9z Team                | W   | 0.075      | -            | -                | -                | -         |     0.30 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            4 |     4968 | 2024-10-19 | Nemiga Gaming          | L   | 0.058      | -            | -                | -                | -         |    -1.02 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            3 |     5041 | 2024-10-17 | PARIVISION             | W   | 0.048      | -            | -                | -                | 1 (0.058) |     0.20 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            2 |     5114 | 2024-10-16 | BC.Game Esports        | W   | 0.043      | 0.624        | 0.061 (0.002)    | 1.000 (0.032)    | 1 (0.052) |     0.70 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            1 |     5440 | 2024-10-10 | Metizport              | L   | 0.008      | -            | -                | -                | -         |    -0.13 | blameF, bodyy, KRIMZ, matys, nawwk   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,236.46)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.172 | $20,000.00     | $3,436.11       |
| 2024-10-19 |      0.072 | $25,000.00     | $1,800.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
