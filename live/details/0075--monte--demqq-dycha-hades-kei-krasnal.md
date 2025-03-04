### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, dycha, hades, KEi, kRaSnaL<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  928.2<br />
<br />
Final Rank Value (928.2) = Starting Rank Value (869.8) + Head To Head Adjustments (58.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.406[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.087[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.8
- 400 + ( ( 0.226 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 869.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     1703 | 2024-12-16 | Dynamo Eclot        | L   | 0.683      | -            | -                | -                | -         |    -5.66 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           29 |     1912 | 2024-12-13 | Metizport           | L   | 0.662      | -            | -                | -                | -         |    -5.84 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           28 |     2029 | 2024-12-10 | Aurora Gaming       | W   | 0.643      | 0.435        | 0.022 (0.006)    | 0.671 (0.188)    | 0 (0.000) |     9.30 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           27 |     2055 | 2024-12-09 | GUN5 Esports        | W   | 0.637      | 0.435        | 0.123 (0.034)    | 0.576 (0.159)    | 0 (0.000) |    12.38 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           26 |     2792 | 2024-11-24 | ENCE                | L   | 0.536      | -            | -                | -                | -         |    -5.27 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           25 |     2886 | 2024-11-23 | Johnny Speeds       | W   | 0.529      | 0.143        | 0.046 (0.003)    | 0.347 (0.026)    | 0 (0.000) |     9.39 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           24 |     3619 | 2024-11-10 | FAVBET Team         | W   | 0.443      | 0.143        | 0.037 (0.002)    | 0.952 (0.060)    | 0 (0.000) |     7.51 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           23 |     3774 | 2024-11-07 | 500                 | L   | 0.422      | -            | -                | -                | -         |    -3.77 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           22 |     3819 | 2024-11-06 | Team Spirit Academy | W   | 0.416      | 0.143        | 0.080 (0.005)    | 0.863 (0.051)    | 0 (0.000) |     8.64 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           21 |     4401 | 2024-10-27 | SAW                 | L   | 0.349      | -            | -                | -                | -         |    -0.61 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           20 |     4454 | 2024-10-26 | Legacy              | W   | 0.342      | 0.500        | 0.043 (0.007)    | 0.628 (0.107)    | 1 (0.342) |     5.74 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           19 |     4510 | 2024-10-25 | MIBR                | W   | 0.337      | 0.500        | 0.118 (0.020)    | 0.285 (0.048)    | 1 (0.337) |     8.40 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           18 |     4526 | 2024-10-25 | PaiN Gaming         | L   | 0.335      | -            | -                | -                | -         |    -0.36 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           17 |     5169 | 2024-10-11 | SINNERS Esports     | L   | 0.243      | -            | -                | -                | -         |    -2.62 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           16 |     5415 | 2024-10-07 | Metizport           | W   | 0.214      | 0.435        | 0.087 (0.008)    | 0.517 (0.048)    | 0 (0.000) |     5.44 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           15 |     5528 | 2024-10-05 | Adventurers         | W   | 0.202      | -            | -                | -                | 0 (0.000) |     2.54 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           14 |     5628 | 2024-10-03 | Team Spirit Academy | L   | 0.189      | -            | -                | -                | -         |    -1.97 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           13 |     5819 | 2024-09-30 | ECSTATIC            | W   | 0.169      | 0.435        | 0.038 (0.003)    | 0.809 (0.059)    | 0 (0.000) |     2.96 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           12 |     6132 | 2024-09-26 | 3DMAX               | L   | 0.141      | -            | -                | -                | -         |    -0.07 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           11 |     6271 | 2024-09-24 | Rebels Gaming       | W   | 0.130      | -            | -                | -                | -         |     1.79 | DemQQ, dycha, hades, KEi, kRaSnaL |
|           10 |     6274 | 2024-09-24 | GameAgents          | W   | 0.130      | -            | -                | -                | -         |     1.38 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            9 |     6308 | 2024-09-24 | BIG                 | W   | 0.128      | 0.384        | 0.244 (0.012)    | 0.528 (0.026)    | -         |     3.91 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            8 |     6335 | 2024-09-23 | 4wb                 | W   | 0.124      | -            | -                | -                | -         |     0.26 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            7 |     6362 | 2024-09-23 | Ins (Polish team)   | W   | 0.124      | -            | -                | -                | -         |     1.00 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            6 |     6384 | 2024-09-23 | PARIVISION          | W   | 0.122      | -            | -                | -                | -         |     1.22 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            5 |     6607 | 2024-09-19 | Sashi Esport        | W   | 0.095      | -            | -                | -                | -         |     2.15 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            4 |     6743 | 2024-09-17 | EYEBALLERS          | W   | 0.082      | -            | -                | -                | -         |     1.15 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            3 |     7035 | 2024-09-12 | Nemiga Gaming       | L   | 0.048      | -            | -                | -                | -         |    -0.29 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            2 |     7360 | 2024-09-07 | GamerLegion         | L   | 0.014      | -            | -                | -                | -         |    -0.32 | DemQQ, dycha, hades, KEi, kRaSnaL |
|            1 |     7508 | 2024-09-05 | SINNERS Esports     | W   | 0.001      | -            | -                | -                | -         |     0.02 | DemQQ, dycha, hades, KEi, kRaSnaL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,507.61)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.690 | $5,000.00      | $3,452.33       |
| 2024-11-24 |      0.536 | $4,262.60      | $2,284.84       |
| 2024-11-09 |      0.436 | $15.18         | $6.62           |
| 2024-10-27 |      0.350 | $10,000.00     | $3,503.72       |
| 2024-09-26 |      0.143 | $1,500.00      | $214.17         |
| 2024-09-08 |      0.023 | $2,000.00      | $45.93          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
