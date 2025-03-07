### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  894.4<br />
<br />
Final Rank Value (894.4) = Starting Rank Value (897.8) + Head To Head Adjustments (-3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.138[<sup>2</sup>](#table1)
- LAN Wins: 0.085[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 897.8
- 400 + ( ( 0.226 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 897.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |       16 | 2025-02-28 | Sashi Esport               | W   | 0.793      | 0.435        | 0.007 (0.003)    | 0.535 (0.221)    | 0 (0.000) |    13.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |       34 | 2025-02-27 | Team Spirit Academy        | L   | 0.787      | -            | -                | -                | -         |    -9.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |       67 | 2025-02-26 | ARCRED                     | W   | 0.783      | 0.500        | 0.017 (0.008)    | 0.526 (0.247)    | 0 (0.000) |    10.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |      355 | 2025-02-19 | RUSH B (Russian team)      | L   | 0.744      | -            | -                | -                | -         |   -10.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |      663 | 2025-02-11 | Astralis                   | L   | 0.698      | -            | -                | -                | -         |    -0.11 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |      686 | 2025-02-10 | NEVERMORE (Ukrainian team) | W   | 0.694      | 0.143        | -                | 0.803 (0.095)    | 0 (0.000) |     9.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |      698 | 2025-02-10 | HEROIC                     | L   | 0.692      | -            | -                | -                | -         |    -5.92 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |      765 | 2025-02-08 | Little Red Door            | W   | 0.683      | -            | -                | -                | 0 (0.000) |     3.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |      781 | 2025-02-08 | BC.Game Esports            | L   | 0.683      | -            | -                | -                | -         |    -5.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |      786 | 2025-02-08 | ENCE                       | W   | 0.682      | 0.143        | 0.081 (0.010)    | 0.416 (0.049)    | 0 (0.000) |    12.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |      798 | 2025-02-08 | FORZE Reload               | W   | 0.682      | 0.143        | 0.023 (0.003)    | 0.413 (0.048)    | 0 (0.000) |    10.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |      818 | 2025-02-08 | RUSH B (Russian team)      | L   | 0.681      | -            | -                | -                | -         |    -8.69 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |      846 | 2025-02-07 | Arch Esports               | W   | 0.678      | -            | -                | -                | 0 (0.000) |     1.41 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |      968 | 2025-02-05 | KONO.ECF                   | L   | 0.666      | -            | -                | -                | -         |   -16.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     1031 | 2025-02-04 | RUSH B (Russian team)      | W   | 0.660      | 0.143        | 0.026 (0.003)    | 0.901 (0.102)    | 0 (0.000) |    11.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     1092 | 2025-02-04 | PARIVISION                 | L   | 0.659      | -            | -                | -                | -         |   -15.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     1100 | 2025-02-04 | Superior Esports           | W   | 0.659      | -            | -                | -                | -         |     1.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     1233 | 2025-01-28 | B8                         | L   | 0.622      | -            | -                | -                | -         |    -5.07 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     1238 | 2025-01-28 | Wild Lotus                 | L   | 0.622      | -            | -                | -                | -         |   -16.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     1276 | 2025-01-27 | Adventurers                | W   | 0.615      | -            | -                | -                | -         |     5.01 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     1279 | 2025-01-26 | AMKAL ESPORTS              | L   | 0.610      | -            | -                | -                | -         |   -13.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     1319 | 2025-01-24 | Team Spirit Academy        | W   | 0.599      | 0.500        | 0.053 (0.019)    | 0.682 (0.245)    | -         |    11.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     1389 | 2025-01-22 | Iberian Soul               | W   | 0.588      | 0.500        | 0.014 (0.005)    | 0.620 (0.219)    | -         |     8.05 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     1627 | 2024-12-22 | RUSH B (Russian team)      | L   | 0.416      | -            | -                | -                | -         |    -5.73 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     1631 | 2024-12-22 | Metizport                  | L   | 0.416      | -            | -                | -                | -         |    -4.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     1682 | 2024-12-21 | Alliance                   | W   | 0.410      | -            | -                | -                | -         |     5.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     1951 | 2024-12-14 | ECSTATIC                   | L   | 0.370      | -            | -                | -                | -         |    -6.21 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2061 | 2024-12-12 | AMKAL ESPORTS              | W   | 0.360      | 0.435        | -                | 0.588 (0.110)    | -         |     3.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2552 | 2024-12-01 | FORZE Reload               | W   | 0.299      | -            | -                | -                | -         |     4.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2563 | 2024-12-01 | RUSH B (Russian team)      | W   | 0.299      | -            | -                | -                | -         |     5.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2577 | 2024-12-01 | Los kogutos                | W   | 0.299      | -            | -                | -                | -         |     0.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2991 | 2024-11-23 | ENCE                       | L   | 0.254      | -            | -                | -                | -         |    -3.88 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     3358 | 2024-11-17 | 0to100                     | W   | 0.221      | -            | -                | -                | 1 (0.266) |     2.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     3462 | 2024-11-16 | Juggernauts                | W   | 0.214      | -            | -                | -                | 1 (0.256) |     1.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           14 |     3682 | 2024-11-11 | Ninjas in Pyjamas          | L   | 0.188      | -            | -                | -                | -         |    -3.45 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3733 | 2024-11-10 | Tricked Esport             | W   | 0.182      | 0.384        | 0.030 (0.003)    | 0.549 (0.046)    | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3793 | 2024-11-09 | GUN5 Esports               | W   | 0.177      | 0.143        | 0.105 (0.003)    | -                | -         |     3.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     3861 | 2024-11-08 | Johnny Speeds              | W   | 0.170      | 0.384        | 0.025 (0.002)    | -                | -         |     2.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3959 | 2024-11-06 | HOTU                       | W   | 0.159      | -            | -                | -                | -         |     1.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     4080 | 2024-11-04 | 500                        | L   | 0.148      | -            | -                | -                | -         |    -1.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     4196 | 2024-11-02 | Los kogutos                | W   | 0.138      | -            | -                | -                | -         |     2.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     4456 | 2024-10-29 | OG                         | L   | 0.115      | -            | -                | -                | -         |    -1.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     4502 | 2024-10-28 | 500                        | L   | 0.110      | -            | -                | -                | -         |    -1.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     4519 | 2024-10-28 | Dynamo Eclot               | L   | 0.109      | -            | -                | -                | -         |    -1.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     4523 | 2024-10-28 | Wu-Tang Clan               | W   | 0.109      | -            | -                | -                | -         |     0.34 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     4544 | 2024-10-27 | 0to100                     | W   | 0.104      | -            | -                | -                | -         |     0.19 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     5193 | 2024-10-15 | 9Pandas                    | L   | 0.037      | -            | -                | -                | -         |    -0.44 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     5448 | 2024-10-10 | Aurora Gaming              | L   | 0.008      | -            | -                | -                | -         |    -0.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,204.88)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.452 | $2,000.00      | $903.61         |
| 2024-11-24 |      0.311 | $1,864.89      | $580.19         |
| 2024-11-17 |      0.266 | $7,908.47      | $2,100.69       |
| 2024-11-12 |      0.232 | $1,000.00      | $231.50         |
| 2024-10-20 |      0.078 | $5,000.00      | $388.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
