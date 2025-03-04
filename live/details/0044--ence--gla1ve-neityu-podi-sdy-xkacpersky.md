### Roster Details<br />
Team Name: ENCE<br />
Roster: gla1ve, Neityu, podi, sdy, xKacpersky<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1030.7<br />
<br />
Final Rank Value (1030.7) = Starting Rank Value (1040.1) + Head To Head Adjustments (-9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.555[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.149[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1040.1
- 400 + ( ( 0.308 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1040.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      287 | 2025-02-21 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -17.01 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           24 |      516 | 2025-02-15 | Partizan Esports     | L   | 1.000      | -            | -                | -                | -         |   -13.99 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           23 |      551 | 2025-02-14 | Passion UA           | W   | 1.000      | 0.435        | 0.027 (0.012)    | 0.494 (0.215)    | 0 (0.000) |    14.34 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           22 |      615 | 2025-02-12 | Alliance             | W   | 1.000      | 0.435        | 0.018 (0.008)    | 0.585 (0.254)    | 0 (0.000) |    10.36 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           21 |      764 | 2025-02-08 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -20.88 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           20 |      777 | 2025-02-08 | AgenciUSB            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.48 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           19 |      823 | 2025-02-07 | Boiets Esports Club  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.78 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           18 |      871 | 2025-02-07 | 9INE                 | L   | 1.000      | -            | -                | -                | -         |   -19.07 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           17 |      973 | 2025-02-05 | 9INE                 | W   | 1.000      | 0.143        | 0.044 (0.006)    | 0.863 (0.123)    | 0 (0.000) |    11.22 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           16 |     1339 | 2025-01-15 | Team Falcons         | L   | 0.883      | -            | -                | -                | -         |    -0.25 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           15 |     1750 | 2024-12-15 | Team Spirit Academy  | L   | 0.676      | -            | -                | -                | -         |   -11.28 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           14 |     1799 | 2024-12-14 | AMKAL ESPORTS        | W   | 0.670      | 0.435        | 0.020 (0.006)    | 0.386 (0.113)    | 0 (0.000) |     5.13 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           13 |     1951 | 2024-12-12 | Endpoint             | W   | 0.655      | 0.435        | 0.010 (0.003)    | 0.382 (0.109)    | -         |     3.20 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           12 |     2792 | 2024-11-24 | Monte                | W   | 0.536      | 0.143        | 0.034 (0.003)    | 0.236 (0.018)    | -         |     5.27 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           11 |     2871 | 2024-11-23 | Zero Tenacity        | W   | 0.530      | 0.143        | -                | 0.843 (0.064)    | -         |     6.01 | gla1ve, Neityu, podi, sdy, xKacpersky |
|           10 |     3571 | 2024-11-11 | 500                  | L   | 0.449      | -            | -                | -                | -         |    -6.56 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            9 |     3674 | 2024-11-09 | Wild Lotus           | W   | 0.436      | 0.143        | -                | 0.446 (0.028)    | -         |     2.68 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            8 |     4715 | 2024-10-20 | Team Falcons         | W   | 0.303      | 0.589        | 1.000 (0.178)    | 0.565 (0.101)    | 1 (0.303) |     9.46 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            7 |     4769 | 2024-10-19 | The MongolZ          | W   | 0.296      | 0.589        | 1.000 (0.174)    | 0.463 (0.081)    | 1 (0.296) |     9.23 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            6 |     4809 | 2024-10-18 | 9z Team              | W   | 0.290      | 0.589        | 0.018 (0.003)    | -                | 1 (0.290) |     1.42 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            5 |     4857 | 2024-10-17 | Team Falcons         | L   | 0.282      | -            | -                | -                | -         |    -0.06 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            4 |     4866 | 2024-10-17 | 9z Team              | W   | 0.282      | 0.589        | 0.018 (0.003)    | -                | 1 (0.282) |     1.36 | gla1ve, Neityu, podi, sdy, xKacpersky |
|            3 |     6971 | 2024-09-13 | ATOX Esports         | L   | 0.057      | -            | -                | -                | -         |    -0.80 | gla1ve, Goofy, Kylar, podi, sdy       |
|            2 |     7030 | 2024-09-12 | RED Canids           | L   | 0.049      | -            | -                | -                | -         |    -1.17 | gla1ve, Goofy, Kylar, podi, sdy       |
|            1 |     7137 | 2024-09-10 | Team Liquid          | L   | 0.036      | -            | -                | -                | -         |    -0.28 | gla1ve, Goofy, Kylar, podi, sdy       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,791.92)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-12-15 |      0.677 | $5,000.00      | $3,383.58       |
| 2024-11-24 |      0.536 | $7,992.37      | $4,284.07       |
| 2024-11-12 |      0.456 | $1,000.00      | $456.41         |
| 2024-10-20 |      0.303 | $100,000.00    | $30,261.78      |
| 2024-09-22 |      0.116 | $3,500.00      | $406.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
