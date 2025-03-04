### Roster Details<br />
Team Name: Aurora Gaming<br />
Roster: clax, gr1ks, KENSi, Norwi, Patsi<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.9<br />
<br />
Final Rank Value (929.9) = Starting Rank Value (876.4) + Head To Head Adjustments (53.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.4
- 400 + ( ( 0.229 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 876.4


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
|           46 |       66 | 2025-02-26 | Rebels Gaming        | W   | 1.000      | 0.500        | 0.010 (0.005)    | 0.445 (0.223)    | 0 (0.000) |    11.51 | clax, gr1ks, KENSi, Norwi, Patsi |
|           45 |      108 | 2025-02-25 | Iberian Soul         | W   | 1.000      | 0.143        | -                | 0.615 (0.088)    | 0 (0.000) |    14.78 | clax, gr1ks, KENSi, Norwi, Patsi |
|           44 |      133 | 2025-02-24 | Wild Lotus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.88 | clax, gr1ks, KENSi, Norwi, Patsi |
|           43 |      163 | 2025-02-23 | BC.Game Esports      | L   | 1.000      | -            | -                | -                | -         |    -4.91 | clax, gr1ks, KENSi, Norwi, Patsi |
|           42 |      237 | 2025-02-22 | EYEBALLERS           | W   | 1.000      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    11.34 | clax, gr1ks, KENSi, Norwi, Patsi |
|           41 |      283 | 2025-02-21 | OG                   | L   | 1.000      | -            | -                | -                | -         |   -10.75 | clax, gr1ks, KENSi, Norwi, Patsi |
|           40 |      346 | 2025-02-19 | FAVBET Team          | W   | 1.000      | 0.500        | 0.037 (0.018)    | 0.952 (0.476)    | 0 (0.000) |    15.23 | clax, gr1ks, KENSi, Norwi, Patsi |
|           39 |      725 | 2025-02-09 | ALASKA               | L   | 1.000      | -            | -                | -                | -         |   -13.38 | clax, gr1ks, KENSi, Norwi, Patsi |
|           38 |      774 | 2025-02-08 | BC.Game Esports      | L   | 1.000      | -            | -                | -                | -         |    -7.14 | clax, gr1ks, KENSi, Norwi, Patsi |
|           37 |      835 | 2025-02-07 | K27                  | W   | 1.000      | 0.143        | -                | 0.787 (0.112)    | 0 (0.000) |    13.19 | clax, gr1ks, KENSi, Norwi, Patsi |
|           36 |      971 | 2025-02-05 | UNiTY esports        | W   | 1.000      | 0.143        | 0.030 (0.004)    | -                | 0 (0.000) |    13.70 | clax, gr1ks, KENSi, Norwi, Patsi |
|           35 |     1015 | 2025-02-04 | Ninjas in Pyjamas    | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | 0 (0.000) |     8.50 | clax, gr1ks, KENSi, Norwi, Patsi |
|           34 |     1041 | 2025-02-04 | PARIVISION           | L   | 1.000      | -            | -                | -                | -         |   -20.18 | clax, gr1ks, KENSi, Norwi, Patsi |
|           33 |     1071 | 2025-02-04 | Partizan Esports     | W   | 1.000      | 0.143        | 0.097 (0.014)    | 0.819 (0.117)    | 0 (0.000) |    23.97 | clax, gr1ks, KENSi, Norwi, Patsi |
|           32 |     1077 | 2025-02-04 | The Suspect          | W   | 1.000      | -            | -                | -                | -         |    10.08 | clax, gr1ks, KENSi, Norwi, Patsi |
|           31 |     1203 | 2025-01-28 | GUN5 Esports         | L   | 0.971      | -            | -                | -                | -         |    -8.49 | clax, gr1ks, KENSi, Norwi, Patsi |
|           30 |     1206 | 2025-01-28 | Ninjas in Pyjamas    | L   | 0.970      | -            | -                | -                | -         |   -24.58 | clax, gr1ks, KENSi, Norwi, Patsi |
|           29 |     1225 | 2025-01-27 | FAVBET Team          | L   | 0.963      | -            | -                | -                | -         |   -11.72 | clax, gr1ks, KENSi, Norwi, Patsi |
|           28 |     1233 | 2025-01-26 | Ninjas in Pyjamas    | W   | 0.955      | 0.143        | -                | 0.628 (0.086)    | -         |     4.58 | clax, gr1ks, KENSi, Norwi, Patsi |
|           27 |     1250 | 2025-01-24 | Natus Vincere Junior | L   | 0.944      | -            | -                | -                | -         |    -8.06 | clax, gr1ks, KENSi, Norwi, Patsi |
|           26 |     1288 | 2025-01-22 | GameAgents           | W   | 0.931      | 0.500        | -                | 0.156 (0.073)    | -         |     8.31 | clax, gr1ks, KENSi, Norwi, Patsi |
|           25 |     1982 | 2024-12-11 | GUN5 Esports         | L   | 0.651      | -            | -                | -                | -         |    -6.80 | clax, gr1ks, KENSi, Norwi, Patsi |
|           24 |     2029 | 2024-12-10 | Monte                | L   | 0.643      | -            | -                | -                | -         |    -9.30 | clax, gr1ks, KENSi, Norwi, Patsi |
|           23 |     2049 | 2024-12-09 | Sashi Esport         | W   | 0.637      | 0.435        | 0.015 (0.004)    | 0.606 (0.168)    | -         |    14.03 | clax, gr1ks, KENSi, Norwi, Patsi |
|           22 |     2920 | 2024-11-22 | 9Pandas              | L   | 0.527      | -            | -                | -                | -         |    -3.69 | clax, deko, KENSi, Lack1, Norwi  |
|           21 |     3002 | 2024-11-21 | Team Spirit          | L   | 0.520      | -            | -                | -                | -         |    -0.04 | clax, deko, KENSi, Lack1, Norwi  |
|           20 |     3050 | 2024-11-21 | B8                   | W   | 0.515      | 0.143        | 0.147 (0.011)    | -                | 1 (0.515) |    14.27 | clax, deko, KENSi, Lack1, Norwi  |
|           19 |     3066 | 2024-11-20 | Eternal Fire         | L   | 0.514      | -            | -                | -                | -         |    -0.05 | clax, deko, KENSi, Lack1, Norwi  |
|           18 |     3730 | 2024-11-08 | Natus Vincere Junior | L   | 0.428      | -            | -                | -                | -         |    -3.67 | clax, deko, KENSi, Lack1, Norwi  |
|           17 |     3766 | 2024-11-07 | 9Pandas              | W   | 0.423      | 0.143        | 0.104 (0.006)    | -                | -         |    10.19 | clax, deko, KENSi, Lack1, Norwi  |
|           16 |     3875 | 2024-11-05 | 9INE                 | W   | 0.409      | -            | -                | -                | -         |     5.59 | clax, deko, KENSi, Lack1, Norwi  |
|           15 |     4545 | 2024-10-24 | M80                  | L   | 0.329      | -            | -                | -                | -         |    -3.68 | clax, deko, KENSi, Lack1, Norwi  |
|           14 |     4555 | 2024-10-24 | BIG                  | L   | 0.328      | -            | -                | -                | -         |    -0.37 | clax, deko, KENSi, Lack1, Norwi  |
|           13 |     4876 | 2024-10-17 | Nemiga Gaming        | L   | 0.281      | -            | -                | -                | -         |    -1.74 | clax, deko, KENSi, Lack1, Norwi  |
|           12 |     4945 | 2024-10-16 | Fluxo                | L   | 0.274      | -            | -                | -                | -         |    -2.96 | clax, deko, KENSi, Lack1, Norwi  |
|           11 |     4978 | 2024-10-15 | PARIVISION           | L   | 0.270      | -            | -                | -                | -         |    -5.87 | clax, deko, KENSi, Lack1, Norwi  |
|           10 |     5061 | 2024-10-13 | FAVBET Team          | L   | 0.256      | -            | -                | -                | -         |    -3.58 | clax, deko, KENSi, Lack1, Norwi  |
|            9 |     5148 | 2024-10-12 | Metizport            | W   | 0.248      | 0.435        | 0.087 (0.009)    | -                | -         |     6.32 | clax, deko, KENSi, Lack1, Norwi  |
|            8 |     5218 | 2024-10-10 | Zero Tenacity        | W   | 0.234      | 0.435        | 0.032 (0.003)    | 0.843 (0.086)    | -         |     4.40 | clax, deko, KENSi, Lack1, Norwi  |
|            7 |     5588 | 2024-10-04 | Passion UA           | L   | 0.195      | -            | -                | -                | -         |    -2.41 | clax, deko, KENSi, Lack1, Norwi  |
|            6 |     5949 | 2024-09-28 | GamerLegion          | L   | 0.156      | -            | -                | -                | -         |    -3.49 | clax, deko, KENSi, Lack1, Norwi  |
|            5 |     6032 | 2024-09-27 | ECSTATIC             | W   | 0.149      | -            | -                | -                | -         |     2.65 | clax, deko, KENSi, Lack1, Norwi  |
|            4 |     6105 | 2024-09-26 | 3DMAX                | L   | 0.143      | -            | -                | -                | -         |    -0.07 | clax, deko, KENSi, Lack1, Norwi  |
|            3 |     6120 | 2024-09-26 | Wild Lotus           | W   | 0.142      | -            | -                | -                | -         |     1.57 | clax, deko, KENSi, Lack1, Norwi  |
|            2 |     6189 | 2024-09-25 | Endpoint             | W   | 0.137      | -            | -                | -                | -         |     1.63 | clax, deko, KENSi, Lack1, Norwi  |
|            1 |     6275 | 2024-09-24 | AMKAL ESPORTS        | W   | 0.130      | -            | -                | -                | -         |     1.77 | clax, deko, KENSi, Lack1, Norwi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,121.39)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.436 | $5,030.36      | $2,193.81       |
| 2024-10-20 |      0.303 | $4,500.00      | $1,362.09       |
| 2024-10-13 |      0.256 | $5,000.00      | $1,282.07       |
| 2024-09-28 |      0.157 | $5,000.00      | $783.69         |
| 2024-09-26 |      0.143 | $3,500.00      | $499.73         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
