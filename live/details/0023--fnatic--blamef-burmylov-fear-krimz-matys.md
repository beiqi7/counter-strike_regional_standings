### Roster Details<br />
Team Name: Fnatic<br />
Roster: blameF, Burmylov, fear, KRIMZ, matys<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1143.2<br />
<br />
Final Rank Value (1143.2) = Starting Rank Value (1124.3) + Head To Head Adjustments (19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 0.266[<sup>2</sup>](#table1)

The average of these factors is 0.348<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1124.3
- 400 + ( ( 0.348 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1124.3


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
|           31 |       61 | 2025-02-26 | BC.Game Esports        | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.976 (0.424)    | 0 (0.000) |    17.43 | blameF, Burmylov, fear, KRIMZ, matys |
|           30 |      320 | 2025-02-20 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -         |   -17.98 | blameF, Burmylov, fear, KRIMZ, matys |
|           29 |      418 | 2025-02-17 | RUSH B (Russian team)  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.985 (0.428)    | 0 (0.000) |    10.10 | blameF, Burmylov, fear, KRIMZ, matys |
|           28 |      502 | 2025-02-15 | Monte                  | L   | 1.000      | -            | -                | -                | -         |   -21.63 | blameF, Burmylov, fear, KRIMZ, matys |
|           27 |      599 | 2025-02-13 | 500                    | W   | 1.000      | 0.435        | 0.114 (0.049)    | 1.000 (0.435)    | 0 (0.000) |    15.03 | blameF, Burmylov, fear, KRIMZ, matys |
|           26 |      621 | 2025-02-12 | Partizan Esports       | L   | 1.000      | -            | -                | -                | -         |   -19.40 | blameF, Burmylov, fear, KRIMZ, matys |
|           25 |      684 | 2025-02-10 | ECSTATIC               | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.809 (0.352)    | 0 (0.000) |     6.35 | blameF, Burmylov, fear, KRIMZ, matys |
|           24 |      779 | 2025-02-08 | Team Novaq             | L   | 1.000      | -            | -                | -                | -         |   -14.89 | blameF, Burmylov, fear, KRIMZ, matys |
|           23 |      854 | 2025-02-07 | Permitta Esports       | W   | 1.000      | 0.143        | -                | 0.497 (0.071)    | -         |     4.88 | blameF, Burmylov, fear, KRIMZ, matys |
|           22 |      900 | 2025-02-06 | Team Spirit Academy    | W   | 1.000      | 0.435        | 0.080 (0.035)    | 0.863 (0.375)    | -         |    12.04 | blameF, Burmylov, fear, KRIMZ, matys |
|           21 |     1055 | 2025-02-04 | Betclic Apogee Esports | W   | 1.000      | 0.435        | -                | 0.528 (0.230)    | -         |     8.07 | blameF, Burmylov, fear, KRIMZ, matys |
|           20 |     1137 | 2025-02-01 | OG                     | W   | 0.995      | 0.435        | 0.072 (0.031)    | 0.985 (0.426)    | -         |     7.97 | blameF, Burmylov, fear, KRIMZ, matys |
|           19 |     1342 | 2025-01-14 | Team Spirit            | L   | 0.877      | -            | -                | -                | -         |    -0.28 | blameF, Burmylov, fear, KRIMZ, matys |
|           18 |     3134 | 2024-11-19 | Dynamo Eclot           | W   | 0.507      | 0.143        | 0.150 (0.011)    | 0.705 (0.051)    | 1 (0.507) |     7.61 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           17 |     3171 | 2024-11-19 | FaZe Clan              | L   | 0.501      | -            | -                | -                | -         |    -0.35 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           16 |     3218 | 2024-11-17 | BetBoom Team           | W   | 0.494      | 0.143        | 0.122 (0.009)    | -                | 1 (0.494) |     6.73 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           15 |     3264 | 2024-11-17 | Rebels Gaming          | W   | 0.488      | -            | -                | -                | 1 (0.488) |     2.46 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           14 |     3284 | 2024-11-16 | Natus Vincere          | L   | 0.487      | -            | -                | -                | -         |    -0.55 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           13 |     4450 | 2024-10-26 | Team Falcons           | L   | 0.342      | -            | -                | -                | -         |    -0.12 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           12 |     4532 | 2024-10-25 | Cloud9                 | W   | 0.334      | -            | -                | -                | -         |     1.43 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           11 |     4612 | 2024-10-22 | The MongolZ            | L   | 0.317      | -            | -                | -                | -         |    -0.15 | blameF, bodyy, KRIMZ, matys, nawwk   |
|           10 |     4629 | 2024-10-22 | 9z Team                | W   | 0.315      | -            | -                | -                | -         |     1.05 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            9 |     4779 | 2024-10-19 | Nemiga Gaming          | L   | 0.295      | -            | -                | -                | -         |    -4.55 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            8 |     4848 | 2024-10-17 | PARIVISION             | W   | 0.283      | -            | -                | -                | 1 (0.283) |     0.99 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            7 |     4905 | 2024-10-16 | BC.Game Esports        | W   | 0.277      | 0.624        | 0.091 (0.016)    | 0.976 (0.169)    | 1 (0.277) |     3.94 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            6 |     5212 | 2024-10-10 | Metizport              | L   | 0.235      | -            | -                | -                | -         |    -3.52 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            5 |     6292 | 2024-09-24 | Wild Lotus             | L   | 0.129      | -            | -                | -                | -         |    -3.58 | blameF, bodyy, KRIMZ, matys, nawwk   |
|            4 |     6924 | 2024-09-14 | MOUZ                   | L   | 0.062      | -            | -                | -                | -         |    -0.02 | afro, blameF, bodyy, KRIMZ, matys    |
|            3 |     7022 | 2024-09-12 | BIG                    | L   | 0.050      | -            | -                | -                | -         |    -0.20 | afro, blameF, bodyy, KRIMZ, matys    |
|            2 |     7074 | 2024-09-11 | M80                    | L   | 0.043      | -            | -                | -                | -         |    -0.99 | afro, blameF, bodyy, KRIMZ, matys    |
|            1 |     7143 | 2024-09-10 | Astralis               | W   | 0.035      | 0.889        | 0.734 (0.023)    | -                | 1 (0.035) |     1.09 | afro, blameF, bodyy, KRIMZ, matys    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,312.31)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.397 | $20,000.00     | $7,934.30       |
| 2024-10-19 |      0.297 | $25,000.00     | $7,423.08       |
| 2024-09-26 |      0.143 | $1,000.00      | $142.78         |
| 2024-09-22 |      0.116 | $7,000.00      | $812.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
