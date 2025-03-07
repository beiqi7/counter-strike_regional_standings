### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1618.4<br />
<br />
Final Rank Value (1618.4) = Starting Rank Value (1556.5) + Head To Head Adjustments (61.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.726[<sup>1</sup>](#table2)
- Bounty Collected: 0.595[<sup>2</sup>](#table1)
- Opponent Network: 0.134[<sup>2</sup>](#table1)
- LAN Wins: 0.643[<sup>2</sup>](#table1)

The average of these factors is 0.524<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1556.5
- 400 + ( ( 0.524 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1556.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      792 | 2025-02-08 | Team Spirit     | L   | 0.682      | -            | -                | -                | -         |    -2.63 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1033 | 2025-02-04 | The MongolZ     | W   | 0.660      | 1.000        | 1.000 (0.792)    | 0.374 (0.296)    | 1 (0.792) |    16.80 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     1116 | 2025-02-03 | Team Spirit     | W   | 0.654      | 1.000        | 1.000 (0.785)    | 0.503 (0.395)    | 1 (0.785) |    18.47 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     1146 | 2025-02-01 | FURIA           | W   | 0.644      | 1.000        | 0.042 (0.033)    | 0.192 (0.148)    | 1 (0.772) |     1.33 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     1286 | 2025-01-25 | Team Spirit     | L   | 0.605      | -            | -                | -                | -         |    -2.02 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     1325 | 2025-01-24 | PaiN Gaming     | W   | 0.599      | 0.769        | 0.357 (0.197)    | 0.371 (0.205)    | 1 (0.719) |    11.32 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     1434 | 2025-01-18 | Astralis        | W   | 0.566      | 0.363        | 0.788 (0.194)    | 0.807 (0.199)    | -         |    15.48 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     1454 | 2025-01-16 | Imperial Female | W   | 0.555      | 0.363        | 0.146 (0.035)    | 0.159 (0.038)    | -         |     0.98 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3303 | 2024-11-18 | SAW             | W   | 0.229      | 0.143        | 0.316 (0.012)    | 0.260 (0.010)    | 1 (0.275) |     1.80 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3347 | 2024-11-17 | MOUZ            | L   | 0.224      | -            | -                | -                | -         |    -0.56 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3397 | 2024-11-17 | SINNERS Esports | W   | 0.219      | 0.143        | -                | 0.494 (0.019)    | 1 (0.263) |     0.21 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3414 | 2024-11-16 | Fnatic          | W   | 0.218      | 0.143        | -                | 0.471 (0.018)    | 1 (0.262) |     0.30 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     4329 | 2024-10-30 | FaZe Clan       | L   | 0.124      | -            | -                | -                | -         |    -0.69 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4405 | 2024-10-29 | Astralis        | L   | 0.119      | -            | -                | -                | -         |    -0.43 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     5267 | 2024-10-13 | MOUZ            | W   | 0.026      | 0.624        | 1.000 (0.020)    | 0.384 (0.008)    | 1 (0.032) |     0.77 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     5340 | 2024-10-12 | Team Falcons    | W   | 0.020      | 0.624        | 1.000 (0.015)    | -                | 1 (0.024) |     0.57 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     5403 | 2024-10-11 | Virtus.pro      | W   | 0.015      | 0.624        | 0.320 (0.004)    | -                | 1 (0.018) |     0.30 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     5497 | 2024-10-09 | FURIA           | L   | 0.004      | -            | -                | -                | -         |    -0.12 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($88,168.75)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $80,000.00     | $66,000.00      |
| 2025-01-26 |      0.731 | $22,500.00     | $16,456.25      |
| 2024-11-03 |      0.170 | $15,000.00     | $2,545.83       |
| 2024-10-13 |      0.032 | $100,000.00    | $3,166.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
