### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: clax, gr1ks, KENSi, Norwi, Patsi<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
<br />
Final Rank Value:  867.6<br />
<br />
Final Rank Value (867.6) = Starting Rank Value (823.0) + Head To Head Adjustments (44.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.320[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.0
- 400 + ( ( 0.192 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 823.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |       70 | 2025-02-26 | Rebels Gaming        | W   | 0.783      | 0.500        | 0.003 (0.001)    | 0.396 (0.186)    | 0 (0.000) |     9.60 | clax, gr1ks, KENSi, Norwi, Patsi |
|           38 |      114 | 2025-02-25 | Iberian Soul         | W   | 0.777      | 0.143        | 0.014 (0.002)    | 0.620 (0.083)    | 0 (0.000) |    12.14 | clax, gr1ks, KENSi, Norwi, Patsi |
|           37 |      139 | 2025-02-24 | Wild Lotus           | W   | 0.771      | 0.143        | -                | 0.334 (0.044)    | 0 (0.000) |     6.15 | clax, gr1ks, KENSi, Norwi, Patsi |
|           36 |      169 | 2025-02-23 | BC.Game Esports      | L   | 0.766      | -            | -                | -                | -         |    -4.63 | clax, gr1ks, KENSi, Norwi, Patsi |
|           35 |      243 | 2025-02-22 | EYEBALLERS           | W   | 0.758      | 0.143        | 0.018 (0.002)    | 0.262 (0.034)    | 0 (0.000) |     9.36 | clax, gr1ks, KENSi, Norwi, Patsi |
|           34 |      289 | 2025-02-21 | OG                   | L   | 0.754      | -            | -                | -                | -         |    -8.74 | clax, gr1ks, KENSi, Norwi, Patsi |
|           33 |      357 | 2025-02-19 | FAVBET Team          | W   | 0.744      | 0.500        | 0.023 (0.010)    | 0.790 (0.352)    | 0 (0.000) |    12.37 | clax, gr1ks, KENSi, Norwi, Patsi |
|           32 |      747 | 2025-02-09 | ALASKA               | L   | 0.686      | -            | -                | -                | -         |    -5.19 | clax, gr1ks, KENSi, Norwi, Patsi |
|           31 |      796 | 2025-02-08 | BC.Game Esports      | L   | 0.682      | -            | -                | -                | -         |    -5.22 | clax, gr1ks, KENSi, Norwi, Patsi |
|           30 |      857 | 2025-02-07 | K27                  | W   | 0.678      | 0.143        | 0.009 (0.001)    | 0.652 (0.076)    | 0 (0.000) |    12.42 | clax, gr1ks, KENSi, Norwi, Patsi |
|           29 |      992 | 2025-02-05 | UNiTY esports        | W   | 0.665      | 0.143        | 0.019 (0.002)    | -                | 0 (0.000) |     8.85 | clax, gr1ks, KENSi, Norwi, Patsi |
|           28 |     1035 | 2025-02-04 | Ninjas in Pyjamas    | W   | 0.660      | 0.143        | -                | 0.649 (0.073)    | 0 (0.000) |     5.75 | clax, gr1ks, KENSi, Norwi, Patsi |
|           27 |     1061 | 2025-02-04 | PARIVISION           | L   | 0.659      | -            | -                | -                | -         |   -13.21 | clax, gr1ks, KENSi, Norwi, Patsi |
|           26 |     1091 | 2025-02-04 | Partizan Esports     | W   | 0.659      | 0.143        | 0.082 (0.009)    | 0.618 (0.070)    | 0 (0.000) |    16.15 | clax, gr1ks, KENSi, Norwi, Patsi |
|           25 |     1097 | 2025-02-04 | The Suspect          | W   | 0.659      | -            | -                | -                | -         |     7.42 | clax, gr1ks, KENSi, Norwi, Patsi |
|           24 |     1236 | 2025-01-28 | GUN5 Esports         | L   | 0.622      | -            | -                | -                | -         |    -5.29 | clax, gr1ks, KENSi, Norwi, Patsi |
|           23 |     1239 | 2025-01-28 | Ninjas in Pyjamas    | L   | 0.621      | -            | -                | -                | -         |   -15.27 | clax, gr1ks, KENSi, Norwi, Patsi |
|           22 |     1274 | 2025-01-27 | FAVBET Team          | L   | 0.615      | -            | -                | -                | -         |    -7.45 | clax, gr1ks, KENSi, Norwi, Patsi |
|           21 |     1284 | 2025-01-26 | Ninjas in Pyjamas    | W   | 0.608      | 0.143        | -                | 0.649 (0.068)    | -         |     3.75 | clax, gr1ks, KENSi, Norwi, Patsi |
|           20 |     1323 | 2025-01-24 | Natus Vincere Junior | L   | 0.599      | -            | -                | -                | -         |    -5.20 | clax, gr1ks, KENSi, Norwi, Patsi |
|           19 |     1392 | 2025-01-22 | GameAgents           | W   | 0.588      | -            | -                | -                | -         |     6.60 | clax, gr1ks, KENSi, Norwi, Patsi |
|           18 |     2102 | 2024-12-11 | GUN5 Esports         | L   | 0.355      | -            | -                | -                | -         |    -3.23 | clax, gr1ks, KENSi, Norwi, Patsi |
|           17 |     2151 | 2024-12-10 | Monte                | L   | 0.349      | -            | -                | -                | -         |    -5.65 | clax, gr1ks, KENSi, Norwi, Patsi |
|           16 |     2172 | 2024-12-09 | Sashi Esport         | W   | 0.344      | 0.435        | 0.007 (0.001)    | 0.535 (0.096)    | -         |     7.66 | clax, gr1ks, KENSi, Norwi, Patsi |
|           15 |     3041 | 2024-11-22 | 9Pandas              | L   | 0.251      | -            | -                | -                | -         |    -2.04 | clax, deko, KENSi, Lack1, Norwi  |
|           14 |     3120 | 2024-11-21 | Team Spirit          | L   | 0.246      | -            | -                | -                | -         |    -0.01 | clax, deko, KENSi, Lack1, Norwi  |
|           13 |     3169 | 2024-11-21 | B8                   | W   | 0.242      | 0.143        | 0.134 (0.006)    | -                | 1 (0.290) |     6.42 | clax, deko, KENSi, Lack1, Norwi  |
|           12 |     3185 | 2024-11-20 | Eternal Fire         | L   | 0.241      | -            | -                | -                | -         |    -0.01 | clax, deko, KENSi, Lack1, Norwi  |
|           11 |     3863 | 2024-11-08 | Natus Vincere Junior | L   | 0.170      | -            | -                | -                | -         |    -1.48 | clax, deko, KENSi, Lack1, Norwi  |
|           10 |     3900 | 2024-11-07 | 9Pandas              | W   | 0.165      | 0.143        | 0.084 (0.002)    | -                | -         |     3.83 | clax, deko, KENSi, Lack1, Norwi  |
|            9 |     4014 | 2024-11-05 | 9INE                 | W   | 0.153      | -            | -                | -                | -         |     1.55 | clax, deko, KENSi, Lack1, Norwi  |
|            8 |     4713 | 2024-10-24 | M80                  | L   | 0.087      | -            | -                | -                | -         |    -1.20 | clax, deko, KENSi, Lack1, Norwi  |
|            7 |     4725 | 2024-10-24 | BIG                  | L   | 0.086      | -            | -                | -                | -         |    -0.09 | clax, deko, KENSi, Lack1, Norwi  |
|            6 |     5071 | 2024-10-17 | Nemiga Gaming        | L   | 0.047      | -            | -                | -                | -         |    -0.45 | clax, deko, KENSi, Lack1, Norwi  |
|            5 |     5159 | 2024-10-16 | Fluxo                | L   | 0.041      | -            | -                | -                | -         |    -0.44 | clax, deko, KENSi, Lack1, Norwi  |
|            4 |     5194 | 2024-10-15 | PARIVISION           | L   | 0.037      | -            | -                | -                | -         |    -0.83 | clax, deko, KENSi, Lack1, Norwi  |
|            3 |     5282 | 2024-10-13 | FAVBET Team          | L   | 0.026      | -            | -                | -                | -         |    -0.34 | clax, deko, KENSi, Lack1, Norwi  |
|            2 |     5370 | 2024-10-12 | Metizport            | W   | 0.020      | -            | -                | -                | -         |     0.46 | clax, deko, KENSi, Lack1, Norwi  |
|            1 |     5448 | 2024-10-10 | Zero Tenacity        | W   | 0.008      | -            | -                | -                | -         |     0.14 | clax, deko, KENSi, Lack1, Norwi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,569.95)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.211 | $5,030.36      | $1,062.43       |
| 2024-10-20 |      0.078 | $4,500.00      | $350.00         |
| 2024-10-13 |      0.032 | $5,000.00      | $157.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
