### Roster Details<br />
Team Name: Team Liquid<br />
Roster: jks, NAF, NertZ, Twistzz, ultimate<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1263.4<br />
<br />
Final Rank Value (1263.4) = Starting Rank Value (1237.6) + Head To Head Adjustments (25.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.509[<sup>1</sup>](#table2)
- Bounty Collected: 0.541[<sup>2</sup>](#table1)
- Opponent Network: 0.113[<sup>2</sup>](#table1)
- LAN Wins: 0.447[<sup>2</sup>](#table1)

The average of these factors is 0.403<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1237.6
- 400 + ( ( 0.403 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1237.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     1065 | 2025-02-04 | Team Spirit   | L   | 1.000      | -            | -                | -                | -         |    -0.63 | jks, NAF, NertZ, Twistzz, ultimate    |
|           20 |     1097 | 2025-02-03 | MOUZ          | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.420 (0.420)    | 1 (1.000) |    30.65 | jks, NAF, NertZ, Twistzz, ultimate    |
|           19 |     1109 | 2025-02-02 | The MongolZ   | L   | 1.000      | -            | -                | -                | -         |    -0.82 | jks, NAF, NertZ, Twistzz, ultimate    |
|           18 |     1160 | 2025-01-31 | Wildcard      | W   | 0.990      | 1.000        | 0.161 (0.160)    | 0.279 (0.276)    | 1 (0.990) |    12.01 | jks, NAF, NertZ, Twistzz, ultimate    |
|           17 |     1164 | 2025-01-31 | Complexity    | W   | 0.989      | 1.000        | 0.091 (0.090)    | 0.118 (0.117)    | 1 (0.989) |     7.04 | jks, NAF, NertZ, Twistzz, ultimate    |
|           16 |     1174 | 2025-01-29 | HEROIC        | L   | 0.977      | -            | -                | -                | -         |   -18.22 | jks, NAF, NertZ, Twistzz, ultimate    |
|           15 |     1323 | 2025-01-18 | HEROIC        | L   | 0.902      | -            | -                | -                | -         |   -18.23 | jks, NAF, NertZ, Twistzz, ultimate    |
|           14 |     1343 | 2025-01-14 | 9Pandas       | W   | 0.877      | 0.363        | 0.104 (0.033)    | 0.628 (0.200)    | 0 (0.000) |     8.55 | jks, NAF, NertZ, Twistzz, ultimate    |
|           13 |     4182 | 2024-10-31 | Team Vitality | L   | 0.375      | -            | -                | -                | -         |    -0.28 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           12 |     4252 | 2024-10-30 | G2 Esports    | L   | 0.368      | -            | -                | -                | -         |    -0.83 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           11 |     5329 | 2024-10-08 | FaZe Clan     | L   | 0.224      | -            | -                | -                | -         |    -0.28 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|           10 |     5368 | 2024-10-07 | Natus Vincere | L   | 0.218      | -            | -                | -                | -         |    -0.48 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            9 |     5404 | 2024-10-07 | Complexity    | W   | 0.216      | 0.624        | 0.091 (0.012)    | 0.118 (0.016)    | 1 (0.216) |     1.40 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            8 |     6021 | 2024-09-27 | FaZe Clan     | L   | 0.150      | -            | -                | -                | -         |    -0.18 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            7 |     6080 | 2024-09-26 | Team Vitality | L   | 0.144      | -            | -                | -                | -         |    -0.10 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            6 |     6190 | 2024-09-25 | Team Spirit   | W   | 0.137      | 0.729        | 1.000 (0.100)    | 0.569 (0.057)    | 1 (0.137) |     4.24 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            5 |     6524 | 2024-09-20 | G2 Esports    | L   | 0.103      | -            | -                | -                | -         |    -0.24 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            4 |     6651 | 2024-09-18 | Complexity    | W   | 0.090      | 0.889        | 0.091 (0.007)    | 0.118 (0.009)    | 1 (0.090) |     0.60 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            3 |     6820 | 2024-09-15 | Team Vitality | L   | 0.070      | -            | -                | -                | -         |    -0.05 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            2 |     7037 | 2024-09-12 | Virtus.pro    | W   | 0.048      | 0.889        | 0.299 (0.013)    | 0.419 (0.018)    | 1 (0.048) |     1.42 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            1 |     7137 | 2024-09-10 | ENCE          | W   | 0.036      | 0.889        | 0.158 (0.005)    | 0.423 (0.014)    | 1 (0.036) |     0.28 | jks, NAF, Twistzz, ultimate, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,163.21)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.395 | $15,000.00     | $5,919.48       |
| 2024-10-13 |      0.257 | $5,000.00      | $1,282.88       |
| 2024-09-29 |      0.162 | $20,000.00     | $3,248.19       |
| 2024-09-22 |      0.116 | $32,000.00     | $3,712.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
