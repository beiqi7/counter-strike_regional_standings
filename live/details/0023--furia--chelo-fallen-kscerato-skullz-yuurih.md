### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1116.5<br />
<br />
Final Rank Value (1116.5) = Starting Rank Value (1095.8) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.421[<sup>1</sup>](#table2)
- Bounty Collected: 0.388[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.405[<sup>2</sup>](#table1)

The average of these factors is 0.315<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1095.8
- 400 + ( ( 0.315 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1095.8


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
|            9 |        9 | 2025-03-01 | Lynn Vision Gaming | W   | 0.801      | 0.415        | 0.028 (0.011)    | 0.303 (0.121)    | 1 (0.962) |     7.37 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            8 |     1117 | 2025-02-03 | Astralis           | L   | 0.654      | -            | -                | -                | -         |    -0.29 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            7 |     1146 | 2025-02-01 | Natus Vincere      | L   | 0.644      | -            | -                | -                | -         |    -1.33 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            6 |     1187 | 2025-01-31 | Wildcard           | W   | 0.637      | 1.000        | 0.162 (0.124)    | 0.216 (0.165)    | 1 (0.764) |    11.11 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            5 |     1203 | 2025-01-29 | Imperial Female    | W   | 0.626      | 1.000        | 0.146 (0.110)    | 0.159 (0.119)    | 1 (0.751) |     8.68 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            4 |     1432 | 2025-01-19 | BetBoom Team       | L   | 0.570      | -            | -                | -                | -         |   -10.63 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            3 |     1452 | 2025-01-17 | Nemiga Gaming      | W   | 0.559      | 0.363        | 0.074 (0.018)    | 0.313 (0.076)    | 0 (0.000) |     5.68 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            2 |     5325 | 2024-10-12 | MOUZ               | L   | 0.021      | -            | -                | -                | -         |    -0.00 | chelo, FalleN, KSCERATO, skullz, yuurih |
|            1 |     5497 | 2024-10-09 | Natus Vincere      | W   | 0.004      | 0.624        | 0.420 (0.001)    | 0.321 (0.001)    | 1 (0.005) |     0.12 | chelo, FalleN, KSCERATO, skullz, yuurih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,883.33)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $10,000.00     | $8,250.00       |
| 2024-10-13 |      0.032 | $20,000.00     | $633.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
