### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Neityu, podi, sdy, xKacpersky<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  926.7<br />
<br />
Final Rank Value (926.7) = Starting Rank Value (911.1) + Head To Head Adjustments (15.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.044[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 911.1
- 400 + ( ( 0.232 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 911.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      293 | 2025-02-21 | Natus Vincere Junior | L   | 0.753      | -            | -                | -                | -         |   -10.88 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           22 |      540 | 2025-02-15 | Partizan Esports     | L   | 0.721      | -            | -                | -                | -         |    -8.15 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           21 |      575 | 2025-02-14 | Passion UA           | W   | 0.716      | 0.435        | 0.009 (0.003)    | 0.262 (0.098)    | 0 (0.000) |    10.76 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           20 |      633 | 2025-02-12 | Alliance             | W   | 0.704      | 0.435        | 0.013 (0.005)    | 0.516 (0.190)    | 0 (0.000) |     9.47 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           19 |      786 | 2025-02-08 | Zero Tenacity        | L   | 0.682      | -            | -                | -                | -         |   -12.31 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           18 |      799 | 2025-02-08 | AgenciUSB            | W   | 0.682      | -            | -                | -                | 0 (0.000) |     1.63 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           17 |      845 | 2025-02-07 | Boiets Esports Club  | W   | 0.678      | -            | -                | -                | 0 (0.000) |     1.01 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           16 |      893 | 2025-02-07 | 9INE                 | L   | 0.676      | -            | -                | -                | -         |   -10.88 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           15 |      994 | 2025-02-05 | 9INE                 | W   | 0.665      | 0.143        | 0.039 (0.004)    | 0.876 (0.100)    | 0 (0.000) |    10.03 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           14 |     1004 | 2025-02-05 | Dynamo Eclot         | W   | 0.664      | 0.143        | 0.114 (0.013)    | 0.468 (0.053)    | 0 (0.000) |    13.01 | gla1ve, myltsi, Neityu, podi, sdy, xKacpersky |
|           13 |     1459 | 2025-01-15 | Team Falcons         | L   | 0.549      | -            | -                | -                | -         |    -0.06 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           12 |     1875 | 2024-12-15 | Team Spirit Academy  | L   | 0.376      | -            | -                | -                | -         |    -5.26 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           11 |     1925 | 2024-12-14 | AMKAL ESPORTS        | W   | 0.371      | 0.435        | 0.018 (0.003)    | 0.300 (0.058)    | -         |     4.02 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|           10 |     2071 | 2024-12-12 | Endpoint             | W   | 0.359      | 0.435        | 0.007 (0.001)    | 0.225 (0.042)    | -         |     2.91 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            9 |     2911 | 2024-11-24 | Monte                | W   | 0.259      | 0.143        | 0.023 (0.001)    | -                | -         |     2.97 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            8 |     2991 | 2024-11-23 | Zero Tenacity        | W   | 0.254      | 0.143        | 0.020 (0.001)    | 0.778 (0.034)    | -         |     3.88 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            7 |     3704 | 2024-11-11 | 500                  | L   | 0.187      | -            | -                | -                | -         |    -1.92 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            6 |     3807 | 2024-11-09 | Wild Lotus           | W   | 0.176      | 0.143        | -                | 0.334 (0.010)    | -         |     0.83 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            5 |     4902 | 2024-10-20 | Team Falcons         | W   | 0.065      | 0.589        | 1.000 (0.046)    | 0.495 (0.023)    | 1 (0.078) |     2.03 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            4 |     4957 | 2024-10-19 | The MongolZ          | W   | 0.059      | 0.589        | 1.000 (0.042)    | 0.374 (0.016)    | 1 (0.071) |     1.85 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            3 |     4999 | 2024-10-18 | 9z Team              | W   | 0.054      | -            | -                | -                | 1 (0.065) |     0.33 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            2 |     5050 | 2024-10-17 | Team Falcons         | L   | 0.048      | -            | -                | -                | -         |    -0.01 | gla1ve, Neityu, podi, sdy, xKacpersky         |
|            1 |     5060 | 2024-10-17 | 9z Team              | W   | 0.047      | -            | -                | -                | 1 (0.057) |     0.29 | gla1ve, Neityu, podi, sdy, xKacpersky         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,076.58)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      0.866 | $5,000.00      | $4,328.70       |
| 2024-12-15 |      0.452 | $5,000.00      | $2,259.03       |
| 2024-11-24 |      0.311 | $7,992.37      | $2,486.52       |
| 2024-11-12 |      0.232 | $1,000.00      | $231.50         |
| 2024-10-20 |      0.078 | $100,000.00    | $7,770.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
