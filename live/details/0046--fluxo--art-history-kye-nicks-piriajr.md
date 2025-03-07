### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, history, kye, nicks, piriajr<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  962.9<br />
<br />
Final Rank Value (962.9) = Starting Rank Value (937.8) + Head To Head Adjustments (25.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.435[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.108[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 937.8
- 400 + ( ( 0.244 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 937.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      202 | 2025-02-22 | Imperial Esports       | L   | 0.761      | -            | -                | -                | -         |   -12.02 | arT, history, kye, nicks, piriajr          |
|           40 |      253 | 2025-02-21 | Team Solid             | W   | 0.755      | 0.371        | 0.023 (0.008)    | 0.624 (0.209)    | 0 (0.000) |     9.18 | arT, history, kye, nicks, piriajr          |
|           39 |      361 | 2025-02-19 | Yawara E-Sports        | W   | 0.743      | 0.371        | -                | 0.522 (0.172)    | 0 (0.000) |     5.02 | arT, history, kye, nicks, piriajr, tacitus |
|           38 |      626 | 2025-02-12 | Legacy                 | L   | 0.706      | -            | -                | -                | -         |   -12.16 | arT, history, kye, nicks, piriajr          |
|           37 |      629 | 2025-02-12 | Sharks Esports         | W   | 0.705      | 0.143        | 0.051 (0.006)    | 0.636 (0.077)    | 0 (0.000) |    13.74 | arT, history, kye, nicks, piriajr          |
|           36 |      647 | 2025-02-11 | Legacy                 | L   | 0.701      | -            | -                | -                | -         |   -12.40 | arT, history, kye, nicks, piriajr          |
|           35 |      652 | 2025-02-11 | Imperial Esports       | W   | 0.700      | 0.143        | 0.061 (0.007)    | -                | 0 (0.000) |    11.07 | arT, history, kye, nicks, piriajr          |
|           34 |      812 | 2025-02-08 | Imperial Esports       | L   | 0.682      | -            | -                | -                | -         |   -12.39 | arT, history, kye, nicks, piriajr          |
|           33 |     1223 | 2025-01-28 | UNO MILLE              | W   | 0.623      | 0.450        | 0.008 (0.003)    | 0.527 (0.177)    | 0 (0.000) |     4.88 | arT, history, kye, nicks, piriajr          |
|           32 |     1229 | 2025-01-28 | UNO MILLE              | L   | 0.622      | -            | -                | -                | -         |   -15.09 | arT, history, kye, nicks, piriajr          |
|           31 |     1262 | 2025-01-27 | Game Hunters           | W   | 0.617      | 0.450        | -                | 0.391 (0.130)    | 0 (0.000) |     3.61 | arT, history, kye, nicks, piriajr          |
|           30 |     1267 | 2025-01-27 | Game Hunters           | W   | 0.617      | 0.450        | -                | 0.391 (0.130)    | 0 (0.000) |     3.73 | arT, history, kye, nicks, piriajr          |
|           29 |     1308 | 2025-01-24 | Yawara E-Sports        | W   | 0.600      | 0.450        | -                | 0.522 (0.169)    | -         |     3.84 | arT, history, kye, nicks, piriajr          |
|           28 |     1314 | 2025-01-24 | Yawara E-Sports        | W   | 0.600      | 0.450        | -                | 0.522 (0.169)    | -         |     3.97 | arT, history, kye, nicks, piriajr          |
|           27 |     1456 | 2025-01-16 | Eternal Fire           | L   | 0.554      | -            | -                | -                | -         |    -0.09 | arT, history, kye, nicks, piriajr          |
|           26 |     2609 | 2024-11-30 | ODDIK                  | W   | 0.295      | 0.371        | 0.024 (0.003)    | 0.568 (0.074)    | -         |     3.88 | arT, kye, nicks, piriajr, zevy             |
|           25 |     2660 | 2024-11-30 | Team Solid             | W   | 0.293      | 0.371        | 0.023 (0.003)    | 0.624 (0.081)    | -         |     3.61 | arT, kye, nicks, piriajr, zevy             |
|           24 |     2700 | 2024-11-29 | TROPA DO TACO          | W   | 0.289      | -            | -                | -                | -         |     1.98 | arT, kye, nicks, piriajr, zevy             |
|           23 |     2778 | 2024-11-27 | Yawara E-Sports        | W   | 0.278      | -            | -                | -                | -         |     2.14 | arT, kye, nicks, piriajr, zevy             |
|           22 |     2891 | 2024-11-24 | Team Solid             | W   | 0.261      | 0.143        | 0.023 (0.001)    | -                | 1 (0.313) |     3.27 | arT, kye, nicks, piriajr, zevy             |
|           21 |     3048 | 2024-11-22 | Sharks Esports         | W   | 0.251      | 0.143        | 0.051 (0.002)    | -                | 1 (0.301) |     5.26 | arT, kye, nicks, piriajr, zevy             |
|           20 |     3770 | 2024-11-09 | Sharks Esports         | W   | 0.178      | 0.371        | 0.051 (0.004)    | -                | -         |     3.79 | arT, kye, nicks, piriajr, zevy             |
|           19 |     3777 | 2024-11-09 | ODDIK                  | W   | 0.177      | 0.371        | 0.024 (0.002)    | -                | -         |     2.48 | arT, kye, nicks, piriajr, zevy             |
|           18 |     3829 | 2024-11-08 | TROPA DO TACO          | W   | 0.173      | -            | -                | -                | -         |     1.17 | arT, kye, nicks, piriajr, zevy             |
|           17 |     3954 | 2024-11-06 | 9z Academy             | W   | 0.159      | -            | -                | -                | -         |     0.91 | arT, kye, nicks, piriajr, zevy             |
|           16 |     3978 | 2024-11-05 | Bounty Hunters Esports | W   | 0.155      | -            | -                | -                | -         |     1.33 | arT, kye, nicks, piriajr, zevy             |
|           15 |     4027 | 2024-11-04 | Galorys Academy        | W   | 0.150      | -            | -                | -                | -         |     0.69 | arT, kye, nicks, piriajr, zevy             |
|           14 |     4094 | 2024-11-03 | América eSports        | W   | 0.144      | -            | -                | -                | -         |     0.66 | arT, kye, nicks, piriajr, zevy             |
|           13 |     4163 | 2024-11-02 | AdalYamigos            | W   | 0.139      | -            | -                | -                | -         |     0.98 | arT, kye, nicks, piriajr, zevy             |
|           12 |     4222 | 2024-11-01 | Sharks Esports         | L   | 0.134      | -            | -                | -                | -         |    -1.32 | arT, kye, nicks, piriajr, zevy             |
|           11 |     4285 | 2024-10-31 | UNO MILLE              | W   | 0.128      | -            | -                | -                | -         |     1.18 | arT, kye, nicks, piriajr, zevy             |
|           10 |     4363 | 2024-10-30 | Intense Game           | W   | 0.121      | -            | -                | -                | -         |     0.69 | arT, kye, nicks, piriajr, zevy             |
|            9 |     4406 | 2024-10-29 | ODDIK                  | W   | 0.117      | -            | -                | -                | -         |     1.67 | arT, kye, nicks, piriajr, zevy             |
|            8 |     4466 | 2024-10-28 | Team Solid             | L   | 0.112      | -            | -                | -                | -         |    -2.08 | arT, kye, nicks, piriajr, zevy             |
|            7 |     4581 | 2024-10-26 | Sharks Esports         | L   | 0.100      | -            | -                | -                | -         |    -0.98 | arT, kye, nicks, piriajr, zevy             |
|            6 |     5013 | 2024-10-18 | Nemiga Gaming          | L   | 0.053      | -            | -                | -                | -         |    -0.76 | arT, kye, nicks, piriajr, zevy             |
|            5 |     5057 | 2024-10-17 | HEROIC                 | L   | 0.047      | -            | -                | -                | -         |    -0.54 | arT, kye, nicks, piriajr, zevy             |
|            4 |     5159 | 2024-10-16 | Aurora Gaming          | W   | 0.041      | -            | -                | -                | 1 (0.049) |     0.44 | arT, kye, nicks, piriajr, zevy             |
|            3 |     5466 | 2024-10-09 | Galorys                | L   | 0.006      | -            | -                | -                | -         |    -0.15 | arT, kye, nicks, piriajr, zevy             |
|            2 |     5475 | 2024-10-09 | Galorys                | L   | 0.005      | -            | -                | -                | -         |    -0.14 | arT, kye, nicks, piriajr, zevy             |
|            1 |     5545 | 2024-10-08 | InSanitY Sports        | L   | 0.000      | -            | -                | -                | -         |     0.00 | arT, kye, nicks, piriajr, zevy             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,526.54)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.914 | $1,500.00      | $1,371.32       |
| 2024-11-30 |      0.354 | $10,000.00     | $3,535.42       |
| 2024-11-24 |      0.313 | $10,342.97     | $3,233.38       |
| 2024-11-09 |      0.214 | $10,000.00     | $2,137.27       |
| 2024-10-27 |      0.126 | $1,226.46      | $154.33         |
| 2024-10-20 |      0.079 | $1,200.00      | $94.83          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
