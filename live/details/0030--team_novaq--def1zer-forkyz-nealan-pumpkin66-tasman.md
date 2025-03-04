### Roster Details<br />
Team Name: Team Novaq<br />
Roster: def1zer, forkyz, neaLaN, Pumpkin66, tasman<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1097.6<br />
<br />
Final Rank Value (1097.6) = Starting Rank Value (1180.1) + Head To Head Adjustments (-82.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.408[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.677[<sup>2</sup>](#table1)

The average of these factors is 0.375<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1180.1
- 400 + ( ( 0.375 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1180.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      179 | 2025-02-23 | Roler Coaster    | L   | 1.000      | -            | -                | -                | -         |   -30.02 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           25 |      203 | 2025-02-22 | Openai chatgpt   | W   | 1.000      | -            | -                | -                | -         |     0.53 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           24 |      305 | 2025-02-20 | POLET            | L   | 1.000      | -            | -                | -                | -         |   -30.47 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           23 |      767 | 2025-02-08 | Little Red Door  | L   | 1.000      | -            | -                | -                | -         |   -30.14 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           22 |      779 | 2025-02-08 | Fnatic           | W   | 1.000      | 0.143        | 0.059 (0.008)    | 0.508 (0.073)    | -         |    14.89 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           21 |      852 | 2025-02-07 | Iberian Soul     | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.615 (0.088)    | -         |     4.41 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           20 |     1758 | 2024-12-15 | AK BARS          | W   | 0.675      | 0.333        | 0.010 (0.002)    | 0.214 (0.048)    | 1 (0.675) |     3.94 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           19 |     1768 | 2024-12-15 | AimAssassins     | W   | 0.674      | 0.333        | 0.005 (0.001)    | 0.243 (0.055)    | 1 (0.674) |     5.67 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           18 |     1830 | 2024-12-14 | Mix52            | W   | 0.668      | 0.333        | 0.002 (0.001)    | 0.065 (0.014)    | 1 (0.668) |     2.36 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           17 |     1842 | 2024-12-13 | DEPO             | W   | 0.667      | 0.333        | 0.007 (0.002)    | 0.295 (0.066)    | 1 (0.667) |     2.72 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           16 |     1901 | 2024-12-13 | AK BARS          | L   | 0.663      | -            | -                | -                | -         |   -17.42 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           15 |     1909 | 2024-12-13 | Mix52            | W   | 0.663      | 0.333        | 0.002 (0.001)    | 0.065 (0.014)    | 1 (0.663) |     2.05 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           14 |     2429 | 2024-12-01 | MYSKILL          | W   | 0.584      | 0.143        | 0.003 (0.000)    | -                | -         |     1.28 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           13 |     2442 | 2024-12-01 | ALLINNERS        | L   | 0.584      | -            | -                | -                | -         |   -16.95 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           12 |     2461 | 2024-12-01 | Mix52            | W   | 0.583      | -            | -                | -                | -         |     1.71 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           11 |     3301 | 2024-11-16 | GTZ.ESPORTS      | L   | 0.484      | -            | -                | -                | -         |    -6.58 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|           10 |     3371 | 2024-11-15 | KONO.ECF         | W   | 0.477      | 0.617        | 0.054 (0.016)    | 0.762 (0.224)    | 1 (0.477) |     2.88 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            9 |     3377 | 2024-11-15 | GnG x Amazigh    | W   | 0.476      | -            | -                | -                | 1 (0.476) |     0.18 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            8 |     3425 | 2024-11-14 | Team Latvia      | W   | 0.470      | 0.617        | -                | 0.046 (0.013)    | 1 (0.470) |     0.57 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            7 |     3432 | 2024-11-14 | Nexus Gaming     | W   | 0.470      | 0.617        | 0.219 (0.064)    | 0.808 (0.234)    | 1 (0.470) |     6.90 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            6 |     6719 | 2024-09-17 | Partizan Esports | L   | 0.084      | -            | -                | -                | -         |    -1.39 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            5 |     6830 | 2024-09-15 | DEPO             | W   | 0.069      | -            | -                | -                | 1 (0.069) |     0.23 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            4 |     6928 | 2024-09-14 | MYSKILL          | W   | 0.062      | -            | -                | -                | -         |     0.11 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            3 |     6947 | 2024-09-13 | LostEverySense   | W   | 0.060      | -            | -                | -                | -         |     0.02 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            2 |     6961 | 2024-09-13 | PodREDBULom      | W   | 0.057      | -            | -                | -                | -         |     0.02 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            1 |     7497 | 2024-09-05 | Team Uzbekistan  | W   | 0.002      | -            | -                | -                | -         |     0.00 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,810.33)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.675 | $5,000.00      | $3,375.94       |
| 2024-11-17 |      0.490 | $12,500.00     | $6,125.60       |
| 2024-09-22 |      0.117 | $175.00        | $20.40          |
| 2024-09-15 |      0.069 | $4,166.59      | $288.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
