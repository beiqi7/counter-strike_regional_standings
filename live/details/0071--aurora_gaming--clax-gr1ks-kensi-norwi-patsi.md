### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: clax, gr1ks, KENSi, Norwi, Patsi<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  930.0<br />
<br />
Final Rank Value (930.0) = Starting Rank Value (876.5) + Head To Head Adjustments (53.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.5
- 400 + ( ( 0.229 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 876.5


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
|           46 |       64 | 2025-02-26 | Rebels Gaming        | W   | 1.000      | 0.500        | 0.010 (0.005)    | 0.445 (0.223)    | 0 (0.000) |    11.51 | clax, gr1ks, KENSi, Norwi, Patsi |
|           45 |      106 | 2025-02-25 | Iberian Soul         | W   | 1.000      | 0.143        | -                | 0.615 (0.088)    | 0 (0.000) |    14.78 | clax, gr1ks, KENSi, Norwi, Patsi |
|           44 |      131 | 2025-02-24 | Wild Lotus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.88 | clax, gr1ks, KENSi, Norwi, Patsi |
|           43 |      161 | 2025-02-23 | BC.Game Esports      | L   | 1.000      | -            | -                | -                | -         |    -4.91 | clax, gr1ks, KENSi, Norwi, Patsi |
|           42 |      235 | 2025-02-22 | EYEBALLERS           | W   | 1.000      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    11.34 | clax, gr1ks, KENSi, Norwi, Patsi |
|           41 |      281 | 2025-02-21 | OG                   | L   | 1.000      | -            | -                | -                | -         |   -10.75 | clax, gr1ks, KENSi, Norwi, Patsi |
|           40 |      344 | 2025-02-19 | FAVBET Team          | W   | 1.000      | 0.500        | 0.037 (0.018)    | 0.952 (0.476)    | 0 (0.000) |    15.23 | clax, gr1ks, KENSi, Norwi, Patsi |
|           39 |      723 | 2025-02-09 | ALASKA               | L   | 1.000      | -            | -                | -                | -         |   -13.39 | clax, gr1ks, KENSi, Norwi, Patsi |
|           38 |      772 | 2025-02-08 | BC.Game Esports      | L   | 1.000      | -            | -                | -                | -         |    -7.14 | clax, gr1ks, KENSi, Norwi, Patsi |
|           37 |      833 | 2025-02-07 | K27                  | W   | 1.000      | 0.143        | -                | 0.787 (0.112)    | 0 (0.000) |    13.18 | clax, gr1ks, KENSi, Norwi, Patsi |
|           36 |      969 | 2025-02-05 | UNiTY esports        | W   | 1.000      | 0.143        | 0.030 (0.004)    | -                | 0 (0.000) |    13.70 | clax, gr1ks, KENSi, Norwi, Patsi |
|           35 |     1013 | 2025-02-04 | Ninjas in Pyjamas    | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     8.50 | clax, gr1ks, KENSi, Norwi, Patsi |
|           34 |     1039 | 2025-02-04 | PARIVISION           | L   | 1.000      | -            | -                | -                | -         |   -20.18 | clax, gr1ks, KENSi, Norwi, Patsi |
|           33 |     1069 | 2025-02-04 | Partizan Esports     | W   | 1.000      | 0.143        | 0.097 (0.014)    | 0.819 (0.117)    | 0 (0.000) |    23.96 | clax, gr1ks, KENSi, Norwi, Patsi |
|           32 |     1075 | 2025-02-04 | The Suspect          | W   | 1.000      | -            | -                | -                | -         |    10.08 | clax, gr1ks, KENSi, Norwi, Patsi |
|           31 |     1201 | 2025-01-28 | GUN5 Esports         | L   | 0.971      | -            | -                | -                | -         |    -8.49 | clax, gr1ks, KENSi, Norwi, Patsi |
|           30 |     1204 | 2025-01-28 | Ninjas in Pyjamas    | L   | 0.970      | -            | -                | -                | -         |   -24.59 | clax, gr1ks, KENSi, Norwi, Patsi |
|           29 |     1223 | 2025-01-27 | FAVBET Team          | L   | 0.964      | -            | -                | -                | -         |   -11.72 | clax, gr1ks, KENSi, Norwi, Patsi |
|           28 |     1231 | 2025-01-26 | Ninjas in Pyjamas    | W   | 0.955      | 0.143        | -                | 0.628 (0.086)    | -         |     4.58 | clax, gr1ks, KENSi, Norwi, Patsi |
|           27 |     1248 | 2025-01-24 | Natus Vincere Junior | L   | 0.944      | -            | -                | -                | -         |    -8.06 | clax, gr1ks, KENSi, Norwi, Patsi |
|           26 |     1286 | 2025-01-22 | GameAgents           | W   | 0.931      | 0.500        | -                | 0.156 (0.073)    | -         |     8.31 | clax, gr1ks, KENSi, Norwi, Patsi |
|           25 |     1980 | 2024-12-11 | GUN5 Esports         | L   | 0.651      | -            | -                | -                | -         |    -6.81 | clax, gr1ks, KENSi, Norwi, Patsi |
|           24 |     2027 | 2024-12-10 | Monte                | L   | 0.644      | -            | -                | -                | -         |    -9.31 | clax, gr1ks, KENSi, Norwi, Patsi |
|           23 |     2047 | 2024-12-09 | Sashi Esport         | W   | 0.638      | 0.435        | 0.015 (0.004)    | 0.606 (0.168)    | -         |    14.04 | clax, gr1ks, KENSi, Norwi, Patsi |
|           22 |     2918 | 2024-11-22 | 9Pandas              | L   | 0.527      | -            | -                | -                | -         |    -3.69 | clax, deko, KENSi, Lack1, Norwi  |
|           21 |     3000 | 2024-11-21 | Team Spirit          | L   | 0.520      | -            | -                | -                | -         |    -0.04 | clax, deko, KENSi, Lack1, Norwi  |
|           20 |     3048 | 2024-11-21 | B8                   | W   | 0.516      | 0.143        | 0.148 (0.011)    | -                | 1 (0.516) |    14.28 | clax, deko, KENSi, Lack1, Norwi  |
|           19 |     3064 | 2024-11-20 | Eternal Fire         | L   | 0.514      | -            | -                | -                | -         |    -0.05 | clax, deko, KENSi, Lack1, Norwi  |
|           18 |     3728 | 2024-11-08 | Natus Vincere Junior | L   | 0.429      | -            | -                | -                | -         |    -3.67 | clax, deko, KENSi, Lack1, Norwi  |
|           17 |     3764 | 2024-11-07 | 9Pandas              | W   | 0.423      | 0.143        | 0.104 (0.006)    | -                | -         |    10.20 | clax, deko, KENSi, Lack1, Norwi  |
|           16 |     3873 | 2024-11-05 | 9INE                 | W   | 0.409      | -            | -                | -                | -         |     5.59 | clax, deko, KENSi, Lack1, Norwi  |
|           15 |     4543 | 2024-10-24 | M80                  | L   | 0.330      | -            | -                | -                | -         |    -3.69 | clax, deko, KENSi, Lack1, Norwi  |
|           14 |     4553 | 2024-10-24 | BIG                  | L   | 0.328      | -            | -                | -                | -         |    -0.37 | clax, deko, KENSi, Lack1, Norwi  |
|           13 |     4874 | 2024-10-17 | Nemiga Gaming        | L   | 0.281      | -            | -                | -                | -         |    -1.74 | clax, deko, KENSi, Lack1, Norwi  |
|           12 |     4943 | 2024-10-16 | Fluxo                | L   | 0.274      | -            | -                | -                | -         |    -2.96 | clax, deko, KENSi, Lack1, Norwi  |
|           11 |     4976 | 2024-10-15 | PARIVISION           | L   | 0.270      | -            | -                | -                | -         |    -5.88 | clax, deko, KENSi, Lack1, Norwi  |
|           10 |     5059 | 2024-10-13 | FAVBET Team          | L   | 0.256      | -            | -                | -                | -         |    -3.59 | clax, deko, KENSi, Lack1, Norwi  |
|            9 |     5146 | 2024-10-12 | Metizport            | W   | 0.249      | 0.435        | 0.087 (0.009)    | -                | -         |     6.33 | clax, deko, KENSi, Lack1, Norwi  |
|            8 |     5216 | 2024-10-10 | Zero Tenacity        | W   | 0.234      | 0.435        | 0.032 (0.003)    | 0.843 (0.086)    | -         |     4.40 | clax, deko, KENSi, Lack1, Norwi  |
|            7 |     5586 | 2024-10-04 | Passion UA           | L   | 0.196      | -            | -                | -                | -         |    -2.42 | clax, deko, KENSi, Lack1, Norwi  |
|            6 |     5947 | 2024-09-28 | GamerLegion          | L   | 0.156      | -            | -                | -                | -         |    -3.50 | clax, deko, KENSi, Lack1, Norwi  |
|            5 |     6030 | 2024-09-27 | ECSTATIC             | W   | 0.150      | -            | -                | -                | -         |     2.66 | clax, deko, KENSi, Lack1, Norwi  |
|            4 |     6103 | 2024-09-26 | 3DMAX                | L   | 0.143      | -            | -                | -                | -         |    -0.07 | clax, deko, KENSi, Lack1, Norwi  |
|            3 |     6118 | 2024-09-26 | Wild Lotus           | W   | 0.142      | -            | -                | -                | -         |     1.58 | clax, deko, KENSi, Lack1, Norwi  |
|            2 |     6187 | 2024-09-25 | Endpoint             | W   | 0.137      | -            | -                | -                | -         |     1.64 | clax, deko, KENSi, Lack1, Norwi  |
|            1 |     6273 | 2024-09-24 | AMKAL ESPORTS        | W   | 0.130      | -            | -                | -                | -         |     1.77 | clax, deko, KENSi, Lack1, Norwi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,129.97)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.436 | $5,030.36      | $2,195.68       |
| 2024-10-20 |      0.303 | $4,500.00      | $1,363.77       |
| 2024-10-13 |      0.257 | $5,000.00      | $1,283.93       |
| 2024-09-28 |      0.157 | $5,000.00      | $785.55         |
| 2024-09-26 |      0.143 | $3,500.00      | $501.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
