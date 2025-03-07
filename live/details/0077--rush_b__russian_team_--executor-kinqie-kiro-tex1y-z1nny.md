### Roster Details<br />
Team Name: RUSH B (Russian team)<br />
Roster: executor, kinqie, KIRO, tex1y, z1Nny<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  886.5<br />
<br />
Final Rank Value (886.5) = Starting Rank Value (940.9) + Head To Head Adjustments (-54.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.146[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 940.9
- 400 + ( ( 0.245 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 940.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       13 | 2025-02-28 | FAVBET Team                | L   | 0.794      | -            | -                | -                | -         |   -12.86 | executor, kinqie, KIRO, tex1y, z1Nny |
|           54 |       35 | 2025-02-27 | ALASKA                     | W   | 0.787      | 0.143        | 0.033 (0.004)    | 0.737 (0.099)    | 0 (0.000) |    16.20 | executor, kinqie, KIRO, tex1y, z1Nny |
|           53 |       68 | 2025-02-26 | B8                         | L   | 0.783      | -            | -                | -                | -         |    -5.00 | executor, kinqie, KIRO, tex1y, z1Nny |
|           52 |       75 | 2025-02-26 | FAVBET Team                | L   | 0.782      | -            | -                | -                | -         |   -13.24 | executor, kinqie, KIRO, tex1y, z1Nny |
|           51 |      143 | 2025-02-24 | PARIVISION                 | L   | 0.771      | -            | -                | -                | -         |   -14.02 | executor, kinqie, KIRO, tex1y, z1Nny |
|           50 |      180 | 2025-02-23 | ESC Gaming                 | W   | 0.765      | -            | -                | -                | 0 (0.000) |     3.45 | executor, kinqie, KIRO, tex1y, z1Nny |
|           49 |      237 | 2025-02-22 | Rebels Gaming              | W   | 0.759      | 0.143        | -                | 0.396 (0.051)    | 0 (0.000) |     8.19 | executor, kinqie, KIRO, tex1y, z1Nny |
|           48 |      255 | 2025-02-21 | Fire Flux Esports          | L   | 0.755      | -            | -                | -                | -         |   -11.90 | executor, kinqie, KIRO, tex1y, z1Nny |
|           47 |      280 | 2025-02-21 | Astralis Talent            | L   | 0.754      | -            | -                | -                | -         |   -17.25 | executor, kinqie, KIRO, tex1y, z1Nny |
|           46 |      315 | 2025-02-20 | Benched                    | W   | 0.749      | -            | -                | -                | 0 (0.000) |     2.85 | executor, kinqie, KIRO, tex1y, z1Nny |
|           45 |      355 | 2025-02-19 | Zero Tenacity              | W   | 0.744      | 0.500        | 0.020 (0.009)    | 0.778 (0.347)    | 0 (0.000) |    10.50 | executor, kinqie, KIRO, tex1y, z1Nny |
|           44 |      395 | 2025-02-18 | Natus Vincere Junior       | L   | 0.738      | -            | -                | -                | -         |   -10.55 | executor, kinqie, KIRO, tex1y, z1Nny |
|           43 |      396 | 2025-02-18 | Team Spirit Academy        | L   | 0.738      | -            | -                | -                | -         |    -9.94 | executor, kinqie, KIRO, tex1y, z1Nny |
|           42 |      441 | 2025-02-17 | Fnatic                     | L   | 0.731      | -            | -                | -                | -         |    -8.89 | executor, kinqie, KIRO, tex1y, z1Nny |
|           41 |      537 | 2025-02-15 | KONO.ECF                   | L   | 0.721      | -            | -                | -                | -         |   -19.07 | executor, kinqie, KIRO, tex1y, z1Nny |
|           40 |      573 | 2025-02-14 | QUAZAR                     | W   | 0.716      | -            | -                | -                | 0 (0.000) |     4.12 | executor, kinqie, KIRO, tex1y, z1Nny |
|           39 |      588 | 2025-02-14 | GTZ.ESPORTS                | W   | 0.715      | 0.435        | 0.068 (0.025)    | 0.498 (0.186)    | 0 (0.000) |    16.08 | executor, kinqie, KIRO, tex1y, z1Nny |
|           38 |      621 | 2025-02-13 | GUN5 Esports               | L   | 0.708      | -            | -                | -                | -         |   -10.45 | executor, kinqie, KIRO, tex1y, z1Nny |
|           37 |      687 | 2025-02-10 | Sashi Esport               | W   | 0.694      | 0.435        | 0.007 (0.003)    | 0.535 (0.194)    | 0 (0.000) |    10.74 | executor, kinqie, KIRO, tex1y, z1Nny |
|           36 |      739 | 2025-02-09 | OG                         | W   | 0.687      | 0.143        | 0.041 (0.005)    | 0.989 (0.117)    | -         |    10.23 | executor, kinqie, KIRO, tex1y, z1Nny |
|           35 |      808 | 2025-02-08 | Natus Vincere Junior       | L   | 0.682      | -            | -                | -                | -         |    -9.53 | executor, kinqie, KIRO, tex1y, z1Nny |
|           34 |      818 | 2025-02-08 | Zero Tenacity              | W   | 0.681      | 0.143        | 0.020 (0.002)    | 0.778 (0.091)    | -         |     8.69 | executor, kinqie, KIRO, tex1y, z1Nny |
|           33 |      862 | 2025-02-07 | Heimo Esports              | W   | 0.678      | 0.143        | -                | 0.528 (0.061)    | -         |     4.99 | executor, kinqie, KIRO, tex1y, z1Nny |
|           32 |     1002 | 2025-02-05 | Adventurers                | W   | 0.664      | -            | -                | -                | -         |     4.62 | executor, kinqie, KIRO, tex1y, z1Nny |
|           31 |     1031 | 2025-02-04 | Zero Tenacity              | L   | 0.660      | -            | -                | -                | -         |   -11.96 | executor, kinqie, KIRO, tex1y, z1Nny |
|           30 |     1056 | 2025-02-04 | Monte                      | L   | 0.659      | -            | -                | -                | -         |   -10.07 | executor, kinqie, KIRO, tex1y, z1Nny |
|           29 |     1317 | 2025-01-24 | Iberian Soul               | L   | 0.599      | -            | -                | -                | -         |   -12.45 | executor, kinqie, KIRO, tex1y, z1Nny |
|           28 |     1394 | 2025-01-22 | ARCRED                     | W   | 0.588      | 0.500        | 0.017 (0.006)    | 0.526 (0.185)    | -         |     6.08 | executor, kinqie, KIRO, tex1y, z1Nny |
|           27 |     1627 | 2024-12-22 | Zero Tenacity              | W   | 0.416      | 0.143        | 0.020 (0.001)    | 0.778 (0.055)    | -         |     5.73 | executor, kinqie, KIRO, tex1y, z1Nny |
|           26 |     1645 | 2024-12-22 | P0RTUGAL                   | L   | 0.415      | -            | -                | -                | -         |    -8.90 | executor, kinqie, KIRO, tex1y, z1Nny |
|           25 |     1702 | 2024-12-21 | JANO Esports               | W   | 0.409      | 0.143        | 0.019 (0.001)    | -                | -         |     5.72 | executor, kinqie, KIRO, tex1y, z1Nny |
|           24 |     1866 | 2024-12-15 | FORZE Reload               | W   | 0.376      | 0.143        | 0.023 (0.001)    | -                | 1 (0.452) |     4.55 | executor, kinqie, KIRO, tex1y, z1Nny |
|           23 |     1954 | 2024-12-14 | K27                        | W   | 0.370      | -            | -                | -                | 1 (0.444) |     5.91 | executor, kinqie, KIRO, tex1y, z1Nny |
|           22 |     2198 | 2024-12-08 | 0to100                     | W   | 0.339      | -            | -                | -                | -         |     2.90 | executor, kinqie, KIRO, tex1y, z1Nny |
|           21 |     2205 | 2024-12-08 | Preasy Esport              | W   | 0.338      | -            | -                | -                | -         |     3.08 | executor, kinqie, KIRO, tex1y, z1Nny |
|           20 |     2224 | 2024-12-08 | Aimclub                    | W   | 0.338      | -            | -                | -                | -         |     0.50 | executor, kinqie, KIRO, tex1y, z1Nny |
|           19 |     2563 | 2024-12-01 | Zero Tenacity              | L   | 0.299      | -            | -                | -                | -         |    -5.24 | executor, kinqie, KIRO, tex1y, z1Nny |
|           18 |     2574 | 2024-12-01 | EYEBALLERS                 | W   | 0.299      | -            | -                | -                | -         |     2.94 | executor, kinqie, KIRO, tex1y, z1Nny |
|           17 |     2917 | 2024-11-24 | Premdesant                 | W   | 0.259      | -            | -                | -                | -         |     1.58 | executor, kinqie, KIRO, tex1y, z1Nny |
|           16 |     3381 | 2024-11-17 | INDINDA                    | W   | 0.220      | -            | -                | -                | -         |     0.59 | executor, kinqie, KIRO, tex1y, z1Nny |
|           15 |     3393 | 2024-11-17 | LEON Esports               | L   | 0.220      | -            | -                | -                | -         |    -4.99 | executor, kinqie, KIRO, tex1y, z1Nny |
|           14 |     3402 | 2024-11-17 | XP Academy                 | W   | 0.219      | -            | -                | -                | -         |     0.71 | executor, kinqie, KIRO, tex1y, z1Nny |
|           13 |     3820 | 2024-11-09 | Nuclear TigeRES            | W   | 0.175      | -            | -                | -                | -         |     2.26 | executor, kinqie, KIRO, tex1y, z1Nny |
|           12 |     3826 | 2024-11-09 | VOID GAMING (Russian team) | W   | 0.175      | -            | -                | -                | -         |     0.25 | executor, kinqie, KIRO, tex1y, z1Nny |
|           11 |     4102 | 2024-11-03 | ARCRED                     | L   | 0.144      | -            | -                | -                | -         |    -2.98 | executor, kinqie, KIRO, tex1y, z1Nny |
|           10 |     4177 | 2024-11-02 | 1win                       | W   | 0.138      | -            | -                | -                | -         |     1.01 | executor, kinqie, KIRO, tex1y, z1Nny |
|            9 |     4244 | 2024-11-01 | Nuclear TigeRES            | W   | 0.132      | -            | -                | -                | -         |     1.69 | executor, kinqie, KIRO, tex1y, z1Nny |
|            8 |     4550 | 2024-10-27 | K27                        | W   | 0.104      | -            | -                | -                | -         |     1.82 | executor, kinqie, KIRO, tex1y, z1Nny |
|            7 |     4590 | 2024-10-26 | ECSTATIC                   | L   | 0.099      | -            | -                | -                | -         |    -1.85 | executor, kinqie, KIRO, tex1y, z1Nny |
|            6 |     4715 | 2024-10-24 | NewBALLS                   | W   | 0.087      | -            | -                | -                | -         |     0.48 | executor, kinqie, KIRO, tex1y, z1Nny |
|            5 |     4849 | 2024-10-21 | ARCRED                     | L   | 0.070      | -            | -                | -                | -         |    -1.47 | executor, kinqie, KIRO, tex1y, z1Nny |
|            4 |     4873 | 2024-10-20 | Wu-Tang Clan               | L   | 0.066      | -            | -                | -                | -         |    -1.90 | executor, kinqie, KIRO, tex1y, z1Nny |
|            3 |     4887 | 2024-10-20 | GenOne                     | W   | 0.065      | -            | -                | -                | -         |     0.66 | executor, kinqie, KIRO, tex1y, z1Nny |
|            2 |     4965 | 2024-10-19 | GTZ.ESPORTS                | W   | 0.058      | -            | -                | -                | -         |     1.50 | executor, kinqie, KIRO, tex1y, z1Nny |
|            1 |     5294 | 2024-10-13 | FAVBET Team                | L   | 0.025      | -            | -                | -                | -         |    -0.46 | executor, kinqie, KIRO, tex1y, z1Nny |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,463.07)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $2,607.56      | $1,302.33       |
| 2024-12-15 |      0.452 | $7,263.25      | $3,280.90       |
| 2024-11-03 |      0.172 | $5,108.69      | $879.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
