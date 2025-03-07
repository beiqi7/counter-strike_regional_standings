### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1131.8<br />
<br />
Final Rank Value (1131.8) = Starting Rank Value (1120.2) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.559[<sup>1</sup>](#table2)
- Bounty Collected: 0.395[<sup>2</sup>](#table1)
- Opponent Network: 0.091[<sup>2</sup>](#table1)
- LAN Wins: 0.262[<sup>2</sup>](#table1)

The average of these factors is 0.327<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1120.2
- 400 + ( ( 0.327 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1120.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      439 | 2025-02-17 | BIG              | L   | 0.731      | -            | -                | -                | -         |    -5.58 | JBa, phzy, Sonic, stanislaw, susp |
|           16 |      489 | 2025-02-16 | Virtus.pro       | L   | 0.725      | -            | -                | -                | -         |    -1.28 | JBa, phzy, Sonic, stanislaw, susp |
|           15 |      546 | 2025-02-15 | The MongolZ      | L   | 0.720      | -            | -                | -                | -         |    -0.40 | JBa, phzy, Sonic, stanislaw, susp |
|           14 |      589 | 2025-02-14 | MIBR             | W   | 0.715      | 1.000        | 0.105 (0.090)    | 0.265 (0.228)    | 1 (0.858) |    13.76 | JBa, phzy, Sonic, stanislaw, susp |
|           13 |     1184 | 2025-01-31 | Team Liquid      | L   | 0.638      | -            | -                | -                | -         |    -9.07 | JBa, phzy, Sonic, stanislaw, susp |
|           12 |     1187 | 2025-01-31 | FURIA            | L   | 0.637      | -            | -                | -                | -         |   -11.11 | JBa, phzy, Sonic, stanislaw, susp |
|           11 |     1204 | 2025-01-29 | BIG              | W   | 0.626      | 1.000        | 0.234 (0.176)    | 0.400 (0.301)    | 1 (0.751) |    16.07 | JBa, phzy, Sonic, stanislaw, susp |
|           10 |     1461 | 2025-01-15 | Astralis         | L   | 0.547      | -            | -                | -                | -         |    -0.22 | JBa, phzy, Sonic, stanislaw, susp |
|            9 |     1467 | 2025-01-12 | 9Pandas          | W   | 0.531      | 0.417        | 0.084 (0.022)    | 0.481 (0.128)    | 0 (0.000) |     6.01 | JBa, phzy, Sonic, stanislaw, susp |
|            8 |     1470 | 2025-01-11 | SINNERS Esports  | W   | 0.527      | 0.417        | 0.016 (0.004)    | 0.494 (0.130)    | 0 (0.000) |     4.15 | JBa, phzy, Sonic, stanislaw, susp |
|            7 |     1474 | 2025-01-10 | Insilio          | W   | 0.522      | 0.417        | 0.000 (0.000)    | 0.433 (0.113)    | 0 (0.000) |     1.22 | JBa, phzy, Sonic, stanislaw, susp |
|            6 |     5022 | 2024-10-17 | NRG              | L   | 0.050      | -            | -                | -                | -         |    -1.00 | JBa, phzy, Sonic, stanislaw, susp |
|            5 |     5077 | 2024-10-16 | BLUEJAYS         | W   | 0.045      | 0.477        | 0.006 (0.000)    | 0.287 (0.007)    | 0 (0.000) |     0.27 | JBa, phzy, Sonic, stanislaw, susp |
|            4 |     5163 | 2024-10-15 | Nouns Esports    | L   | 0.039      | -            | -                | -                | -         |    -0.96 | JBa, phzy, Sonic, stanislaw, susp |
|            3 |     5453 | 2024-10-09 | Party Astronauts | L   | 0.006      | -            | -                | -                | -         |    -0.16 | JBa, phzy, Sonic, stanislaw, susp |
|            2 |     5460 | 2024-10-09 | Party Astronauts | L   | 0.006      | -            | -                | -                | -         |    -0.16 | JBa, phzy, Sonic, stanislaw, susp |
|            1 |     5542 | 2024-10-08 | M80              | L   | 0.000      | -            | -                | -                | -         |     0.00 | JBa, phzy, Sonic, stanislaw, susp |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,036.35)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $18,750.00     | $17,228.30      |
| 2025-02-09 |      0.825 | $4,500.00      | $3,712.50       |
| 2025-01-12 |      0.638 | $20,000.00     | $12,755.56      |
| 2024-10-20 |      0.080 | $4,250.00      | $340.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
