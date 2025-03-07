### Roster Details<br />
Team Name: FlyQuest<br />
Roster: dexter, INS, Liazz, regali, Vexite<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1126.0<br />
<br />
Final Rank Value (1126.0) = Starting Rank Value (1131.6) + Head To Head Adjustments (-5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.496[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.431[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1131.6
- 400 + ( ( 0.332 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1131.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        0 | 2025-03-05 | TYLOO                       | L   | 0.820      | -            | -                | -                | -         |   -11.18 | dexter, INS, Liazz, regali, Vexite   |
|           19 |        2 | 2025-03-04 | Eternal Fire                | L   | 0.815      | -            | -                | -                | -         |    -0.42 | dexter, INS, Liazz, regali, Vexite   |
|           18 |        5 | 2025-03-03 | PaiN Gaming                 | W   | 0.812      | 0.415        | 0.357 (0.144)    | 0.371 (0.150)    | 1 (0.975) |    24.26 | dexter, INS, Liazz, regali, Vexite   |
|           17 |        7 | 2025-03-02 | Lynn Vision Gaming          | W   | 0.807      | 0.415        | 0.028 (0.011)    | 0.303 (0.122)    | 1 (0.968) |     7.29 | dexter, INS, Liazz, regali, Vexite   |
|           16 |       10 | 2025-03-01 | M80                         | L   | 0.801      | -            | -                | -                | -         |   -18.73 | dexter, INS, Liazz, regali, Vexite   |
|           15 |      475 | 2025-02-16 | SAW                         | L   | 0.726      | -            | -                | -                | -         |    -6.29 | dexter, INS, Liazz, regali, Vexite   |
|           14 |      548 | 2025-02-15 | BIG                         | L   | 0.719      | -            | -                | -                | -         |    -5.59 | dexter, INS, Liazz, regali, Vexite   |
|           13 |      593 | 2025-02-14 | Team Falcons                | L   | 0.714      | -            | -                | -                | -         |    -0.33 | dexter, INS, Liazz, regali, Vexite   |
|           12 |     1194 | 2025-01-30 | Astralis                    | L   | 0.632      | -            | -                | -                | -         |    -0.32 | dexter, INS, Liazz, regali, Vexite   |
|           11 |     1210 | 2025-01-29 | 3DMAX                       | L   | 0.625      | -            | -                | -                | -         |    -1.84 | dexter, INS, Liazz, regali, Vexite   |
|           10 |     1435 | 2025-01-18 | Team Spirit                 | L   | 0.566      | -            | -                | -                | -         |    -0.17 | dexter, INS, Liazz, regali, Vexite   |
|            9 |     1465 | 2025-01-14 | MIBR                        | W   | 0.542      | 0.363        | 0.105 (0.025)    | 0.265 (0.063)    | 0 (0.000) |    10.55 | dexter, INS, Liazz, regali, Vexite   |
|            8 |     3623 | 2024-11-13 | Lynn Vision Gaming          | W   | 0.197      | 0.143        | 0.028 (0.001)    | 0.303 (0.010)    | 1 (0.237) |     1.58 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     3630 | 2024-11-12 | Adventurers                 | W   | 0.196      | 0.143        | 0.006 (0.000)    | 0.062 (0.002)    | 1 (0.235) |     0.64 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     3665 | 2024-11-11 | Ex-GR Gaming                | W   | 0.191      | 0.143        | 0.008 (0.000)    | 0.028 (0.001)    | 1 (0.229) |     0.52 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     3702 | 2024-11-11 | TALON                       | L   | 0.187      | -            | -                | -                | -         |    -5.66 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4928 | 2024-10-19 | Mindfreak (Australian team) | W   | 0.063      | 0.333        | 0.001 (0.000)    | 0.118 (0.003)    | 0 (0.000) |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     5017 | 2024-10-18 | Mindfreak (Australian team) | W   | 0.052      | 0.333        | 0.001 (0.000)    | 0.118 (0.002)    | 0 (0.000) |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     5518 | 2024-10-09 | Mindfreak (Australian team) | L   | 0.003      | -            | -                | -                | -         |    -0.07 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     5522 | 2024-10-09 | Mindfreak (Australian team) | L   | 0.002      | -            | -                | -                | -         |    -0.07 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,191.63)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-05 |      0.984 | $6,500.00      | $6,398.95       |
| 2025-02-23 |      0.919 | $12,500.00     | $11,485.53      |
| 2025-02-09 |      0.825 | $2,500.00      | $2,062.50       |
| 2024-10-19 |      0.075 | $3,250.00      | $244.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
