### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1765.6<br />
<br />
Final Rank Value (1765.6) = Starting Rank Value (1692.6) + Head To Head Adjustments (73.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.819[<sup>1</sup>](#table2)
- Bounty Collected: 0.667[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.787[<sup>2</sup>](#table1)

The average of these factors is 0.621<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1692.6
- 400 + ( ( 0.621 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1692.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      768 | 2025-02-08 | Team Spirit      | L   | 1.000      | -            | -                | -                | -         |    -7.67 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |     1011 | 2025-02-04 | The MongolZ      | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.463 (0.463)    | 1 (1.000) |    20.58 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |     1091 | 2025-02-03 | Team Spirit      | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.569 (0.569)    | 1 (1.000) |    24.73 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |     1121 | 2025-02-01 | FURIA            | W   | 0.998      | 1.000        | -                | 0.180 (0.179)    | 1 (0.998) |     1.25 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |     1233 | 2025-01-25 | Team Spirit      | L   | 0.951      | -            | -                | -                | -         |    -6.53 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1250 | 2025-01-24 | PaiN Gaming      | W   | 0.944      | 0.769        | 0.333 (0.242)    | 0.406 (0.295)    | 1 (0.944) |     6.86 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1312 | 2025-01-18 | Astralis         | W   | 0.904      | 0.363        | 0.734 (0.241)    | 0.811 (0.266)    | -         |    19.00 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1332 | 2025-01-16 | Imperial Female  | W   | 0.891      | 0.363        | -                | 0.213 (0.069)    | -         |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     3173 | 2024-11-18 | SAW              | W   | 0.501      | -            | -                | -                | 1 (0.501) |     2.41 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     3215 | 2024-11-17 | MOUZ             | L   | 0.494      | -            | -                | -                | -         |    -3.09 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     3265 | 2024-11-17 | SINNERS Esports  | W   | 0.488      | -            | -                | -                | 1 (0.488) |     0.31 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     3282 | 2024-11-16 | Fnatic           | W   | 0.487      | -            | -                | -                | 1 (0.487) |     0.55 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     4187 | 2024-10-30 | FaZe Clan        | L   | 0.374      | -            | -                | -                | -         |    -4.28 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     4255 | 2024-10-29 | Astralis         | L   | 0.368      | -            | -                | -                | -         |    -3.25 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     5046 | 2024-10-13 | MOUZ             | W   | 0.257      | 0.624        | 1.000 (0.160)    | 0.420 (0.067)    | 1 (0.257) |     6.58 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     5117 | 2024-10-12 | Team Falcons     | W   | 0.250      | 0.624        | 1.000 (0.156)    | 0.565 (0.088)    | 1 (0.250) |     6.22 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     5176 | 2024-10-11 | Virtus.pro       | W   | 0.243      | 0.624        | -                | 0.418 (0.063)    | 1 (0.243) |     3.88 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     5258 | 2024-10-09 | FURIA            | L   | 0.230      | -            | -                | -                | -         |    -6.98 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     5366 | 2024-10-07 | Team Liquid      | W   | 0.218      | -            | -                | -                | -         |     0.49 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     5401 | 2024-10-07 | Imperial Esports | W   | 0.216      | 0.624        | -                | 0.533 (0.072)    | -         |     0.09 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     5861 | 2024-09-29 | G2 Esports       | L   | 0.163      | -            | -                | -                | -         |    -2.58 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     5904 | 2024-09-28 | FaZe Clan        | W   | 0.157      | -            | -                | -                | -         |     3.28 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     6111 | 2024-09-26 | G2 Esports       | W   | 0.143      | 0.729        | 0.971 (0.101)    | -                | -         |     2.22 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     6217 | 2024-09-25 | Team Falcons     | W   | 0.135      | -            | -                | -                | -         |     0.02 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     6412 | 2024-09-22 | Eternal Fire     | W   | 0.116      | 0.889        | 0.708 (0.073)    | -                | -         |     2.97 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     6468 | 2024-09-21 | G2 Esports       | W   | 0.110      | 0.889        | 0.971 (0.095)    | -                | -         |     1.74 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     6533 | 2024-09-20 | Team Spirit      | W   | 0.103      | 0.889        | 1.000 (0.091)    | -                | -         |     2.75 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     7293 | 2024-09-07 | Eternal Fire     | W   | 0.017      | -            | -                | -                | -         |     0.44 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($166,768.39)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.60) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $80,000.00     | $80,000.00      |
| 2025-01-26 |      0.957 | $22,500.00     | $21,525.10      |
| 2024-11-03 |      0.395 | $15,000.00     | $5,925.07       |
| 2024-10-13 |      0.257 | $100,000.00    | $25,694.88      |
| 2024-09-29 |      0.163 | $85,000.00     | $13,836.48      |
| 2024-09-22 |      0.116 | $170,000.00    | $19,786.86      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
