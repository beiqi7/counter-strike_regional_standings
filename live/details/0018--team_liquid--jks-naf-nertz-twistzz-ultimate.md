### Roster Details<br />
Team Name: Team Liquid<br />
Roster: jks, NAF, NertZ, Twistzz, ultimate<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1192.2<br />
<br />
Final Rank Value (1192.2) = Starting Rank Value (1179.3) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.471[<sup>1</sup>](#table2)
- Bounty Collected: 0.500[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.353<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1179.3
- 400 + ( ( 0.353 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1179.3


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
|           10 |     1085 | 2025-02-04 | Team Spirit   | L   | 0.659      | -            | -                | -                | -         |    -0.27 | jks, NAF, NertZ, Twistzz, ultimate    |
|            9 |     1120 | 2025-02-03 | MOUZ          | W   | 0.653      | 1.000        | 1.000 (0.784)    | 0.384 (0.301)    | 1 (0.784) |    20.32 | jks, NAF, NertZ, Twistzz, ultimate    |
|            8 |     1132 | 2025-02-02 | The MongolZ   | L   | 0.648      | -            | -                | -                | -         |    -0.41 | jks, NAF, NertZ, Twistzz, ultimate    |
|            7 |     1184 | 2025-01-31 | Wildcard      | W   | 0.638      | 1.000        | 0.162 (0.124)    | 0.216 (0.166)    | 1 (0.765) |     9.07 | jks, NAF, NertZ, Twistzz, ultimate    |
|            6 |     1188 | 2025-01-31 | Complexity    | W   | 0.637      | 1.000        | 0.092 (0.070)    | 0.102 (0.078)    | 1 (0.764) |     4.62 | jks, NAF, NertZ, Twistzz, ultimate    |
|            5 |     1200 | 2025-01-29 | HEROIC        | L   | 0.627      | -            | -                | -                | -         |   -12.63 | jks, NAF, NertZ, Twistzz, ultimate    |
|            4 |     1443 | 2025-01-18 | HEROIC        | L   | 0.564      | -            | -                | -                | -         |   -11.93 | jks, NAF, NertZ, Twistzz, ultimate    |
|            3 |     1463 | 2025-01-14 | 9Pandas       | W   | 0.543      | 0.363        | 0.084 (0.020)    | 0.481 (0.114)    | 0 (0.000) |     4.88 | jks, NAF, NertZ, Twistzz, ultimate    |
|            2 |     4322 | 2024-10-31 | Team Vitality | L   | 0.125      | -            | -                | -                | -         |    -0.08 | jks, NAF, Twistzz, ultimate, YEKINDAR |
|            1 |     4400 | 2024-10-30 | G2 Esports    | L   | 0.120      | -            | -                | -                | -         |    -0.64 | jks, NAF, Twistzz, ultimate, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,745.83)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $16,000.00     | $13,200.00      |
| 2024-11-03 |      0.170 | $15,000.00     | $2,545.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
