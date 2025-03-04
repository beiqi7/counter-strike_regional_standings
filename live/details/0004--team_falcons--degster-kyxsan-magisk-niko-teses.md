### Roster Details<br />
Team Name: Team Falcons<br />
Roster: degster, kyxsan, Magisk, NiKo, TeSeS<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1867.8<br />
<br />
Final Rank Value (1867.8) = Starting Rank Value (1934.1) + Head To Head Adjustments (-66.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.685[<sup>2</sup>](#table1)
- Opponent Network: 0.340[<sup>2</sup>](#table1)
- LAN Wins: 0.925[<sup>2</sup>](#table1)

The average of these factors is 0.738<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1934.1
- 400 + ( ( 0.738 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1934.1


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
|           35 |      168 | 2025-02-23 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |   -15.82 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           34 |      207 | 2025-02-22 | FaZe Clan         | W   | 1.000      | 1.000        | 0.475 (0.475)    | 0.399 (0.399)    | 1 (1.000) |    13.01 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           33 |      282 | 2025-02-21 | Eternal Fire      | W   | 1.000      | 1.000        | 0.708 (0.708)    | 0.524 (0.524)    | 1 (1.000) |    16.39 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           32 |      417 | 2025-02-17 | MOUZ              | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.420 (0.420)    | 1 (1.000) |    16.04 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           31 |      463 | 2025-02-16 | Astralis          | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |    10.99 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           30 |      506 | 2025-02-15 | PaiN Gaming       | L   | 1.000      | -            | -                | -                | -         |   -27.01 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           29 |      573 | 2025-02-14 | FlyQuest          | W   | 1.000      | 1.000        | 0.099 (0.099)    | 0.267 (0.267)    | 1 (1.000) |     0.83 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           28 |      672 | 2025-02-10 | BetBoom Team      | W   | 1.000      | -            | -                | -                | -         |     0.49 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           27 |      683 | 2025-02-10 | TEAM NEXT LEVEL   | W   | 1.000      | -            | -                | -                | -         |     0.09 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           26 |     1106 | 2025-02-02 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |   -21.56 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           25 |     1135 | 2025-02-01 | Eternal Fire      | L   | 0.996      | -            | -                | -                | -         |   -14.06 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           24 |     1313 | 2025-01-19 | Eternal Fire      | L   | 0.909      | -            | -                | -                | -         |   -14.46 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           23 |     1339 | 2025-01-15 | ENCE              | W   | 0.883      | 0.363        | 0.158 (0.051)    | 0.423 (0.136)    | -         |     0.25 | degster, kyxsan, Magisk, NiKo, TeSeS  |
|           22 |     2910 | 2024-11-22 | Passion UA        | W   | 0.527      | -            | -                | -                | 1 (0.527) |     0.08 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           21 |     2999 | 2024-11-21 | Ninjas in Pyjamas | W   | 0.520      | -            | -                | -                | 1 (0.520) |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           20 |     3040 | 2024-11-21 | BIG               | L   | 0.516      | -            | -                | -                | -         |   -15.14 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           19 |     3064 | 2024-11-20 | PARIVISION        | W   | 0.514      | -            | -                | -                | 1 (0.514) |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           18 |     3972 | 2024-11-03 | The MongolZ       | L   | 0.397      | -            | -                | -                | -         |    -7.10 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           17 |     4054 | 2024-11-02 | OG                | W   | 0.390      | 0.934        | -                | 0.985 (0.359)    | 1 (0.390) |     0.05 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           16 |     4450 | 2024-10-26 | Fnatic            | W   | 0.342      | 0.934        | -                | 0.508 (0.162)    | -         |     0.12 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           15 |     4562 | 2024-10-23 | Ninjas in Pyjamas | W   | 0.324      | -            | -                | -                | -         |     0.03 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           14 |     4600 | 2024-10-23 | Legacy            | W   | 0.321      | 0.934        | -                | 0.628 (0.188)    | -         |     0.04 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           13 |     4715 | 2024-10-20 | ENCE              | L   | 0.303      | -            | -                | -                | -         |    -9.46 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           12 |     4752 | 2024-10-19 | B8                | W   | 0.297      | 0.589        | -                | 0.790 (0.138)    | 1 (0.297) |     0.17 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           11 |     4857 | 2024-10-17 | ENCE              | W   | 0.282      | 0.589        | 0.158 (0.026)    | -                | -         |     0.06 | degster, kyxsan, NertZ, sjuush, TeSeS |
|           10 |     4870 | 2024-10-17 | Rebels Gaming     | W   | 0.281      | -            | -                | -                | -         |     0.02 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            9 |     5119 | 2024-10-12 | Natus Vincere     | L   | 0.249      | -            | -                | -                | -         |    -6.20 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            8 |     5261 | 2024-10-09 | Team Vitality     | W   | 0.230      | 0.624        | 1.000 (0.143)    | -                | -         |     3.45 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            7 |     5333 | 2024-10-08 | Astralis          | W   | 0.223      | 0.624        | 0.734 (0.102)    | -                | -         |     3.10 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            6 |     5395 | 2024-10-07 | G2 Esports        | W   | 0.216      | 0.624        | 0.970 (0.131)    | -                | -         |     1.49 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            5 |     6670 | 2024-09-18 | MIBR              | L   | 0.088      | -            | -                | -                | -         |    -2.75 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            4 |     6744 | 2024-09-17 | Virtus.pro        | W   | 0.082      | -            | -                | -                | -         |     0.53 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            3 |     7235 | 2024-09-08 | HEROIC            | W   | 0.023      | -            | -                | -                | -         |     0.01 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            2 |     7310 | 2024-09-07 | Ninjas in Pyjamas | W   | 0.016      | -            | -                | -                | -         |     0.00 | degster, kyxsan, NertZ, sjuush, TeSeS |
|            1 |     7467 | 2024-09-05 | HEROIC            | L   | 0.003      | -            | -                | -                | -         |    -0.11 | degster, kyxsan, NertZ, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($276,969.98)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $187,500.00    | $187,500.00     |
| 2025-02-09 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-11-03 |      0.397 | $150,000.00    | $59,507.26      |
| 2024-10-20 |      0.303 | $40,000.00     | $12,104.71      |
| 2024-10-13 |      0.257 | $20,000.00     | $5,131.52       |
| 2024-09-22 |      0.116 | $23,500.00     | $2,726.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
