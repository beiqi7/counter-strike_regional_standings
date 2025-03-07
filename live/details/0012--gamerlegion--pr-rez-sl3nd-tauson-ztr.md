### Roster Details<br />
Team Name: GamerLegion<br />
Roster: PR, REZ, sl3nd, Tauson, ztr<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1566.1<br />
<br />
Final Rank Value (1566.1) = Starting Rank Value (1549.1) + Head To Head Adjustments (17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.584[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.841[<sup>2</sup>](#table1)

The average of these factors is 0.521<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1549.1
- 400 + ( ( 0.521 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1549.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |        6 | 2025-03-03 | TYLOO           | W   | 0.812      | 0.415        | 0.052 (0.021)    | 0.200 (0.081)    | 1 (0.975) |     2.80 | PR, REZ, sl3nd, Tauson, ztr      |
|           17 |      684 | 2025-02-10 | Metizport       | W   | 0.694      | 0.143        | 0.062 (0.007)    | 0.367 (0.044)    | 0 (0.000) |     0.81 | PR, REZ, sl3nd, Tauson, ztr      |
|           16 |      699 | 2025-02-10 | Hesta           | W   | 0.692      | 0.143        | 0.002 (0.000)    | 0.665 (0.079)    | -         |     0.28 | PR, REZ, sl3nd, Tauson, ztr      |
|           15 |      821 | 2025-02-08 | PARIVISION      | L   | 0.681      | -            | -                | -                | -         |   -21.16 | PR, REZ, sl3nd, Tauson, ztr      |
|           14 |     1032 | 2025-02-04 | Team Spirit     | L   | 0.660      | -            | -                | -                | -         |    -2.20 | PR, REZ, sl3nd, Tauson, ztr      |
|           13 |     1086 | 2025-02-04 | Astralis        | W   | 0.659      | 1.000        | 0.788 (0.623)    | 0.807 (0.638)    | 1 (0.791) |    17.31 | PR, REZ, sl3nd, Tauson, ztr      |
|           12 |     1119 | 2025-02-03 | The MongolZ     | L   | 0.653      | -            | -                | -                | -         |    -3.25 | PR, REZ, sl3nd, Tauson, ztr      |
|           11 |     1147 | 2025-02-01 | MOUZ            | W   | 0.643      | 1.000        | 1.000 (0.772)    | 0.384 (0.297)    | 1 (0.772) |    18.45 | PR, REZ, sl3nd, Tauson, ztr      |
|           10 |     1195 | 2025-01-30 | PaiN Gaming     | W   | 0.631      | 1.000        | 0.357 (0.270)    | 0.371 (0.281)    | 1 (0.757) |    12.76 | PR, REZ, sl3nd, Tauson, ztr      |
|            9 |     1206 | 2025-01-29 | SAW             | W   | 0.625      | 1.000        | 0.316 (0.237)    | 0.260 (0.195)    | 1 (0.751) |     4.98 | PR, REZ, sl3nd, Tauson, ztr      |
|            8 |     1453 | 2025-01-17 | PaiN Gaming     | L   | 0.559      | -            | -                | -                | -         |    -6.48 | PR, REZ, sl3nd, Tauson, ztr      |
|            7 |     3247 | 2024-11-20 | BetBoom Team    | W   | 0.237      | 0.143        | 0.101 (0.004)    | 0.308 (0.012)    | 1 (0.284) |     0.37 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            6 |     3252 | 2024-11-20 | SINNERS Esports | W   | 0.236      | 0.143        | 0.016 (0.001)    | 0.494 (0.020)    | 1 (0.283) |     0.25 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            5 |     3298 | 2024-11-19 | Team Falcons    | W   | 0.230      | -            | -                | -                | 1 (0.276) |     0.06 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            4 |     3342 | 2024-11-18 | UNiTY esports   | W   | 0.225      | 0.143        | 0.019 (0.001)    | 0.213 (0.008)    | 1 (0.270) |     0.10 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            3 |     3396 | 2024-11-17 | Dynamo Eclot    | L   | 0.219      | -            | -                | -                | -         |    -6.57 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            2 |     3413 | 2024-11-16 | Team Vitality   | L   | 0.218      | -            | -                | -                | -         |    -1.01 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            1 |     5402 | 2024-10-11 | GUN5 Esports    | L   | 0.015      | -            | -                | -                | -         |    -0.45 | FL4MUS, sl3nd, Tauson, volt, ztr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,800.00)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $24,000.00     | $19,800.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
