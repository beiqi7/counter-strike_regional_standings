### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, hampus, isak, L00m1, Plopski<br />
Global Rank: [42](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  982.5<br />
<br />
Final Rank Value (982.5) = Starting Rank Value (1018.9) + Head To Head Adjustments (-36.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.303[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1018.9
- 400 + ( ( 0.281 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1018.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      657 | 2025-02-11 | HEROIC                      | L   | 0.699      | -            | -                | -                | -         |    -8.08 | adamb, hampus, isak, L00m1, Plopski |
|           32 |      666 | 2025-02-11 | Nemiga Gaming               | W   | 0.697      | 0.143        | 0.074 (0.009)    | 0.313 (0.037)    | 0 (0.000) |     9.63 | adamb, hampus, isak, L00m1, Plopski |
|           31 |      684 | 2025-02-10 | GamerLegion                 | L   | 0.694      | -            | -                | -                | -         |    -0.81 | adamb, hampus, isak, L00m1, Plopski |
|           30 |      697 | 2025-02-10 | Nexus Gaming                | W   | 0.692      | 0.143        | 0.161 (0.019)    | 0.539 (0.064)    | 0 (0.000) |    12.51 | adamb, hampus, isak, L00m1, Plopski |
|           29 |     1001 | 2025-02-05 | Ninjas in Pyjamas           | L   | 0.665      | -            | -                | -                | -         |   -18.25 | adamb, hampus, isak, L00m1, Plopski |
|           28 |     1010 | 2025-02-05 | Passion UA                  | L   | 0.664      | -            | -                | -                | -         |   -13.65 | adamb, hampus, isak, L00m1, Plopski |
|           27 |     1458 | 2025-01-15 | Team Vitality               | L   | 0.549      | -            | -                | -                | -         |    -0.14 | adamb, hampus, isak, L00m1, Plopski |
|           26 |     1626 | 2024-12-22 | P0RTUGAL                    | L   | 0.416      | -            | -                | -                | -         |    -9.56 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           25 |     1631 | 2024-12-22 | Zero Tenacity               | W   | 0.416      | 0.143        | 0.020 (0.001)    | 0.778 (0.055)    | -         |     4.85 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           24 |     1683 | 2024-12-21 | Insilio                     | W   | 0.410      | 0.143        | -                | 0.433 (0.030)    | -         |     1.39 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           23 |     1943 | 2024-12-14 | 9INE                        | L   | 0.371      | -            | -                | -                | -         |    -7.29 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           22 |     2035 | 2024-12-13 | Monte                       | W   | 0.364      | 0.435        | 0.023 (0.004)    | -                | -         |     3.06 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           21 |     2120 | 2024-12-11 | Insilio                     | W   | 0.353      | 0.435        | -                | 0.433 (0.080)    | -         |     1.16 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           20 |     2157 | 2024-12-10 | Chimera Esports             | L   | 0.347      | -            | -                | -                | -         |    -7.63 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           19 |     2252 | 2024-12-08 | FLuffy Gangsters            | W   | 0.336      | 0.435        | 0.011 (0.002)    | 0.635 (0.111)    | -         |     2.50 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           18 |     2383 | 2024-12-05 | Fire Flux Esports           | W   | 0.320      | 0.435        | 0.008 (0.001)    | 1.000 (0.167)    | -         |     3.66 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           17 |     2480 | 2024-12-03 | Wild Lotus                  | L   | 0.308      | -            | -                | -                | -         |    -8.82 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           16 |     3378 | 2024-11-17 | Partizan Esports            | L   | 0.220      | -            | -                | -                | -         |    -3.04 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           15 |     3399 | 2024-11-17 | Nexus Gaming                | L   | 0.219      | -            | -                | -                | -         |    -2.52 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           14 |     3446 | 2024-11-16 | The Huns Esports            | W   | 0.215      | 0.617        | 0.021 (0.003)    | 0.280 (0.044)    | 1 (0.258) |     2.52 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           13 |     3515 | 2024-11-15 | Homyno                      | W   | 0.209      | 0.617        | 0.008 (0.001)    | -                | 1 (0.251) |     1.01 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           12 |     3523 | 2024-11-15 | Team Norway                 | W   | 0.209      | -            | -                | -                | 1 (0.250) |     0.55 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           11 |     3534 | 2024-11-14 | Los kogutos                 | W   | 0.205      | 0.617        | 0.022 (0.003)    | 0.257 (0.039)    | 1 (0.246) |     1.94 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           10 |     3611 | 2024-11-13 | PCIFIC Espor                | L   | 0.198      | -            | -                | -                | -         |    -5.10 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            9 |     3617 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.198      | -            | -                | -                | 1 (0.237) |     0.82 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            8 |     3799 | 2024-11-09 | Ninjas in Pyjamas           | W   | 0.176      | -            | -                | -                | 1 (0.212) |     1.51 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            7 |     3835 | 2024-11-08 | Johnny Speeds               | W   | 0.172      | -            | -                | -                | 1 (0.206) |     1.51 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            6 |     3874 | 2024-11-07 | Kappa Bar                   | W   | 0.167      | -            | -                | -                | 1 (0.200) |     0.81 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            5 |     4311 | 2024-10-31 | Johnny Speeds               | L   | 0.126      | -            | -                | -                | -         |    -2.89 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            4 |     4373 | 2024-10-30 | ECSTATIC                    | W   | 0.121      | 0.333        | 0.027 (0.001)    | 0.659 (0.032)    | -         |     1.16 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            3 |     4388 | 2024-10-30 | Iberian Soul                | W   | 0.121      | -            | -                | -                | -         |     1.10 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            2 |     5370 | 2024-10-12 | Aurora Gaming               | L   | 0.020      | -            | -                | -                | -         |    -0.46 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            1 |     5440 | 2024-10-10 | Fnatic                      | W   | 0.008      | -            | -                | -                | -         |     0.13 | adamb, L00m1, nilo, Plopski, SHiNE  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,093.20)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $6,518.90      | $3,255.83       |
| 2024-12-15 |      0.452 | $2,000.00      | $903.61         |
| 2024-11-17 |      0.265 | $15,000.00     | $3,977.08       |
| 2024-11-09 |      0.212 | $23,119.67     | $4,893.66       |
| 2024-10-13 |      0.032 | $2,000.00      | $63.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
