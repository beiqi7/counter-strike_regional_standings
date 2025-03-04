### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1230.9<br />
<br />
Final Rank Value (1230.9) = Starting Rank Value (1191.0) + Head To Head Adjustments (39.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.114[<sup>2</sup>](#table1)
- LAN Wins: 0.492[<sup>2</sup>](#table1)

The average of these factors is 0.380<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1191.0
- 400 + ( ( 0.380 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1191.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |        5 | 2025-03-01 | Lynn Vision Gaming | W   | 1.000      | 0.889        | 0.013 (0.011)    | 0.333 (0.296)    | 1 (1.000) |     5.51 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           17 |     1094 | 2025-02-03 | Astralis           | L   | 1.000      | -            | -                | -                | -         |    -1.22 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           16 |     1123 | 2025-02-01 | Natus Vincere      | L   | 0.997      | -            | -                | -                | -         |    -1.78 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           15 |     1163 | 2025-01-31 | Wildcard           | W   | 0.989      | 1.000        | 0.161 (0.160)    | 0.279 (0.276)    | 1 (0.989) |    12.77 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           14 |     1177 | 2025-01-29 | Imperial Female    | W   | 0.976      | 1.000        | 0.160 (0.156)    | 0.213 (0.208)    | 1 (0.976) |    11.04 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           13 |     1312 | 2025-01-19 | BetBoom Team       | L   | 0.909      | -            | -                | -                | -         |   -17.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           12 |     1332 | 2025-01-17 | Nemiga Gaming      | W   | 0.896      | 0.363        | 0.204 (0.066)    | 0.424 (0.138)    | -         |    10.19 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           11 |     5104 | 2024-10-12 | MOUZ               | L   | 0.250      | -            | -                | -                | -         |    -0.11 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           10 |     5260 | 2024-10-09 | Natus Vincere      | W   | 0.230      | 0.624        | 0.602 (0.086)    | 0.434 (0.062)    | 1 (0.230) |     6.82 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            9 |     5381 | 2024-10-07 | MOUZ               | W   | 0.217      | 0.624        | 1.000 (0.135)    | 0.420 (0.057)    | 1 (0.217) |     6.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            8 |     5407 | 2024-10-07 | FaZe Clan          | W   | 0.216      | 0.624        | 0.475 (0.064)    | 0.399 (0.054)    | 1 (0.216) |     6.60 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            7 |     6737 | 2024-09-17 | Team Spirit        | L   | 0.082      | -            | -                | -                | -         |    -0.03 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            6 |     6831 | 2024-09-15 | RED Canids         | W   | 0.069      | 0.889        | 0.023 (0.001)    | 0.197 (0.012)    | 1 (0.069) |     0.27 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            5 |     6896 | 2024-09-14 | ATOX Esports       | W   | 0.063      | 0.889        | 0.069 (0.004)    | 0.525 (0.029)    | 1 (0.063) |     0.68 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            4 |     6955 | 2024-09-13 | Virtus.pro         | L   | 0.057      | -            | -                | -                | -         |    -0.10 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            3 |     6991 | 2024-09-13 | RED Canids         | W   | 0.055      | 0.889        | 0.023 (0.001)    | 0.197 (0.010)    | 1 (0.055) |     0.21 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            2 |     7029 | 2024-09-12 | Team Vitality      | L   | 0.049      | -            | -                | -                | -         |    -0.03 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            1 |     7089 | 2024-09-11 | Team Falcons       | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.10 | chelo, FalleN, KSCERATO, skullz, yuurih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,161.88)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-10-13 |      0.257 | $20,000.00     | $5,131.52       |
| 2024-09-22 |      0.116 | $17,500.00     | $2,030.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
