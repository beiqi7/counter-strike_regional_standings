### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: Ax1Le, Boombl4, Magnojez, s1ren, zorte<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1027.7<br />
<br />
Final Rank Value (1027.7) = Starting Rank Value (999.3) + Head To Head Adjustments (28.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.501[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.134[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 999.3
- 400 + ( ( 0.272 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 999.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      654 | 2025-02-11 | Astralis          | L   | 0.699      | -            | -                | -                | -         |    -0.24 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           21 |      662 | 2025-02-11 | Hesta             | W   | 0.698      | 0.143        | 0.002 (0.000)    | 0.665 (0.080)    | 0 (0.000) |     4.88 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           20 |      691 | 2025-02-10 | Team Falcons      | L   | 0.693      | -            | -                | -                | -         |    -0.17 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           19 |      703 | 2025-02-10 | Nemiga Gaming     | W   | 0.692      | 0.143        | 0.074 (0.009)    | 0.313 (0.037)    | 0 (0.000) |     8.66 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           18 |      896 | 2025-02-07 | Passion UA        | L   | 0.675      | -            | -                | -                | -         |   -13.86 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           17 |      942 | 2025-02-06 | Ninjas in Pyjamas | W   | 0.669      | 0.143        | -                | 0.649 (0.075)    | 0 (0.000) |     2.29 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           16 |     1000 | 2025-02-05 | Passion UA        | L   | 0.665      | -            | -                | -                | -         |   -14.32 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           15 |     1011 | 2025-02-05 | Ninjas in Pyjamas | W   | 0.664      | 0.143        | -                | 0.649 (0.074)    | 0 (0.000) |     1.97 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           14 |     1362 | 2025-01-23 | G2 Esports        | L   | 0.594      | -            | -                | -                | -         |    -1.38 | Ax1Le, KaiR0N-, Magnojez, nafany, s1ren |
|           13 |     1432 | 2025-01-19 | FURIA             | W   | 0.570      | 0.363        | 0.042 (0.010)    | 0.192 (0.048)    | 0 (0.000) |    10.63 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           12 |     1447 | 2025-01-17 | MOUZ              | W   | 0.560      | 0.363        | 1.000 (0.244)    | 0.384 (0.094)    | 0 (0.000) |    17.57 | Ax1Le, Boombl4, Magnojez, s1ren, zorte  |
|           11 |     3247 | 2024-11-20 | GamerLegion       | L   | 0.237      | -            | -                | -                | -         |    -0.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           10 |     3260 | 2024-11-19 | SAW               | W   | 0.234      | 0.143        | 0.316 (0.013)    | 0.260 (0.010)    | 1 (0.281) |     6.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            9 |     3304 | 2024-11-18 | Nemiga Gaming     | W   | 0.229      | 0.143        | 0.074 (0.003)    | 0.313 (0.012)    | 1 (0.275) |     3.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            8 |     3348 | 2024-11-17 | Fnatic            | L   | 0.224      | -            | -                | -                | -         |    -3.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            7 |     3395 | 2024-11-17 | Team Vitality     | L   | 0.220      | -            | -                | -                | -         |    -0.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            6 |     3406 | 2024-11-16 | UNiTY esports     | W   | 0.219      | 0.143        | 0.019 (0.001)    | -                | 1 (0.263) |     1.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            5 |     3646 | 2024-11-12 | 500               | W   | 0.193      | 0.384        | 0.118 (0.010)    | 1.000 (0.089)    | 0 (0.000) |     3.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            4 |     3651 | 2024-11-12 | Ninjas in Pyjamas | W   | 0.192      | 0.384        | 0.015 (0.001)    | -                | -         |     1.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            3 |     3698 | 2024-11-11 | Dynamo Eclot      | W   | 0.187      | 0.384        | 0.114 (0.010)    | 0.468 (0.040)    | -         |     3.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            2 |     3935 | 2024-11-06 | OG                | L   | 0.160      | -            | -                | -                | -         |    -3.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            1 |     5410 | 2024-10-11 | FAVBET Team       | L   | 0.014      | -            | -                | -                | -         |    -0.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,178.53)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-01-26 |      0.731 | $25,000.00     | $18,284.72      |
| 2024-11-12 |      0.232 | $12,500.00     | $2,893.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
