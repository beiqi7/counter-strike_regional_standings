### Roster Details<br />
Team Name: Team Falcons<br />
Roster: degster, kyxsan, Magisk, NiKo, TeSeS<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1904.3<br />
<br />
Final Rank Value (1904.3) = Starting Rank Value (1939.4) + Head To Head Adjustments (-35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.644[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.904[<sup>2</sup>](#table1)

The average of these factors is 0.698<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1939.4
- 400 + ( ( 0.698 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1939.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      174 | 2025-02-23 | MOUZ              | L   | 0.766      | -            | -                | -                | -         |   -11.24 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           27 |      213 | 2025-02-22 | FaZe Clan         | W   | 0.760      | 1.000        | 0.498 (0.455)    | 0.354 (0.323)    | 1 (0.912) |     9.46 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           26 |      288 | 2025-02-21 | Eternal Fire      | W   | 0.754      | 1.000        | 0.731 (0.661)    | 0.557 (0.504)    | 1 (0.904) |    11.96 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           25 |      440 | 2025-02-17 | MOUZ              | W   | 0.731      | 1.000        | 1.000 (0.877)    | 0.384 (0.337)    | 1 (0.877) |    12.70 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           24 |      486 | 2025-02-16 | Astralis          | W   | 0.725      | 1.000        | 0.788 (0.686)    | 0.807 (0.702)    | 1 (0.870) |     9.36 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           23 |      529 | 2025-02-15 | PaiN Gaming       | L   | 0.721      | -            | -                | -                | -         |   -18.13 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           22 |      593 | 2025-02-14 | FlyQuest          | W   | 0.714      | 1.000        | 0.096 (0.082)    | 0.190 (0.163)    | 1 (0.857) |     0.33 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           21 |      691 | 2025-02-10 | BetBoom Team      | W   | 0.693      | 0.143        | 0.101 (0.012)    | -                | -         |     0.17 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           20 |      704 | 2025-02-10 | TEAM NEXT LEVEL   | W   | 0.692      | 0.143        | -                | 0.442 (0.052)    | -         |     0.04 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           19 |     1129 | 2025-02-02 | G2 Esports        | L   | 0.648      | -            | -                | -                | -         |   -18.58 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           18 |     1158 | 2025-02-01 | Eternal Fire      | L   | 0.642      | -            | -                | -                | -         |    -9.70 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           17 |     1433 | 2025-01-19 | Eternal Fire      | L   | 0.570      | -            | -                | -                | -         |    -9.11 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           16 |     1459 | 2025-01-15 | ENCE              | W   | 0.549      | 0.363        | 0.081 (0.019)    | 0.416 (0.099)    | -         |     0.06 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           15 |     3031 | 2024-11-22 | Passion UA        | W   | 0.252      | -            | -                | -                | 1 (0.302) |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           14 |     3117 | 2024-11-21 | Ninjas in Pyjamas | W   | 0.246      | -            | -                | -                | 1 (0.295) |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           13 |     3159 | 2024-11-21 | BIG               | L   | 0.243      | -            | -                | -                | -         |    -7.26 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           12 |     3183 | 2024-11-20 | PARIVISION        | W   | 0.241      | -            | -                | -                | 1 (0.289) |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           11 |     4113 | 2024-11-03 | The MongolZ       | L   | 0.143      | -            | -                | -                | -         |    -2.70 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           10 |     4193 | 2024-11-02 | OG                | W   | 0.138      | 0.934        | 0.041 (0.006)    | 0.989 (0.152)    | 1 (0.165) |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            9 |     4611 | 2024-10-26 | Fnatic            | W   | 0.098      | 0.934        | -                | 0.471 (0.052)    | -         |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            8 |     4733 | 2024-10-23 | Ninjas in Pyjamas | W   | 0.083      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            7 |     4776 | 2024-10-23 | Legacy            | W   | 0.080      | 0.934        | -                | 0.556 (0.050)    | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            6 |     4902 | 2024-10-20 | ENCE              | L   | 0.065      | -            | -                | -                | -         |    -2.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            5 |     4939 | 2024-10-19 | B8                | W   | 0.060      | 0.589        | 0.134 (0.006)    | -                | 1 (0.072) |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            4 |     5050 | 2024-10-17 | ENCE              | W   | 0.048      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            3 |     5064 | 2024-10-17 | Rebels Gaming     | W   | 0.047      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            2 |     5340 | 2024-10-12 | Natus Vincere     | L   | 0.020      | -            | -                | -                | -         |    -0.57 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            1 |     5498 | 2024-10-09 | Team Vitality     | W   | 0.004      | 0.624        | 1.000 (0.003)    | -                | -         |     0.05 | degster, kyxsan, NertZ, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($210,045.49)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $187,500.00    | $172,282.99     |
| 2025-02-09 |      0.825 | $10,000.00     | $8,250.00       |
| 2024-11-03 |      0.172 | $150,000.00    | $25,770.83      |
| 2024-10-20 |      0.078 | $40,000.00     | $3,108.33       |
| 2024-10-13 |      0.032 | $20,000.00     | $633.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
