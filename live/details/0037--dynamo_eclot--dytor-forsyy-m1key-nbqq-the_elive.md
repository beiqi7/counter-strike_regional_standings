### Roster Details<br />
Team Name: Dynamo Eclot<br />
Roster: Dytor, forsyy, M1key, nbqq, The eLiVe<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.1<br />
<br />
Final Rank Value (993.1) = Starting Rank Value (1020.7) + Head To Head Adjustments (-27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.515[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.098[<sup>2</sup>](#table1)
- LAN Wins: 0.188[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1020.7
- 400 + ( ( 0.281 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1020.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      244 | 2025-02-22 | 9Pandas                    | L   | 0.758      | -            | -                | -                | -         |   -11.87 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           45 |      327 | 2025-02-20 | Fnatic                     | W   | 0.748      | 0.435        | 0.025 (0.010)    | 0.471 (0.184)    | 0 (0.000) |    12.85 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           44 |      591 | 2025-02-14 | 500                        | L   | 0.715      | -            | -                | -                | -         |    -8.68 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           43 |      631 | 2025-02-12 | Team Spirit Academy        | W   | 0.705      | 0.435        | 0.053 (0.019)    | 0.682 (0.251)    | 0 (0.000) |    10.71 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           42 |      803 | 2025-02-08 | NEVERMORE (Ukrainian team) | L   | 0.682      | -            | -                | -                | -         |   -16.02 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           41 |      851 | 2025-02-07 | Ex-XI Esport               | W   | 0.678      | -            | -                | -                | 0 (0.000) |     0.69 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           40 |      939 | 2025-02-06 | 9INE                       | L   | 0.669      | -            | -                | -                | -         |   -13.21 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           39 |      995 | 2025-02-05 | Nexus Gaming               | W   | 0.665      | 0.143        | 0.161 (0.018)    | 0.539 (0.061)    | 0 (0.000) |    11.26 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           38 |     1004 | 2025-02-05 | ENCE                       | L   | 0.664      | -            | -                | -                | -         |   -13.01 | Dytor, forsyy, M1key, nbqq, The eLiVe |
|           37 |     1806 | 2024-12-17 | GUN5 Esports               | L   | 0.388      | -            | -                | -                | -         |    -6.50 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           36 |     1826 | 2024-12-16 | Monte                      | W   | 0.382      | 0.435        | 0.023 (0.005)    | -                | 0 (0.000) |     2.98 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           35 |     1935 | 2024-12-14 | ECSTATIC                   | W   | 0.371      | 0.435        | 0.027 (0.005)    | 0.659 (0.127)    | 0 (0.000) |     3.84 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           34 |     2028 | 2024-12-13 | Natus Vincere Junior       | L   | 0.365      | -            | -                | -                | -         |    -6.02 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           33 |     2064 | 2024-12-12 | ECSTATIC                   | W   | 0.360      | 0.435        | 0.027 (0.005)    | 0.659 (0.124)    | -         |     3.57 | Dytor, forsyy, kreaz, M1key, nbqq     |
|           32 |     2913 | 2024-11-24 | UNiTY esports              | W   | 0.259      | -            | -                | -                | 1 (0.311) |     1.76 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           31 |     3002 | 2024-11-23 | BRUTE                      | W   | 0.254      | -            | -                | -                | 1 (0.305) |     1.25 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           30 |     3257 | 2024-11-19 | Fnatic                     | L   | 0.235      | -            | -                | -                | -         |    -3.79 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           29 |     3306 | 2024-11-18 | HEROIC                     | W   | 0.229      | 0.143        | 0.120 (0.005)    | -                | 1 (0.274) |     3.77 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           28 |     3351 | 2024-11-17 | SINNERS Esports            | L   | 0.224      | -            | -                | -                | -         |    -4.31 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           27 |     3396 | 2024-11-17 | GamerLegion                | W   | 0.219      | 0.143        | 0.094 (0.004)    | -                | 1 (0.263) |     6.57 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           26 |     3408 | 2024-11-16 | Team Falcons               | L   | 0.219      | -            | -                | -                | -         |    -5.95 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           25 |     3698 | 2024-11-11 | BetBoom Team               | L   | 0.187      | -            | -                | -                | -         |    -3.20 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           24 |     3717 | 2024-11-11 | 9Pandas                    | L   | 0.186      | -            | -                | -                | -         |    -3.09 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           23 |     3738 | 2024-11-10 | 9Pandas                    | L   | 0.182      | -            | -                | -                | -         |    -3.08 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           22 |     3755 | 2024-11-10 | SINNERS Esports            | W   | 0.182      | 0.384        | -                | 0.494 (0.041)    | -         |     2.13 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           21 |     3768 | 2024-11-10 | Natus Vincere Junior       | W   | 0.180      | 0.371        | 0.078 (0.006)    | 0.786 (0.063)    | -         |     2.60 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           20 |     3817 | 2024-11-09 | Sashi Esport               | W   | 0.176      | 0.384        | -                | 0.535 (0.043)    | -         |     2.33 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           19 |     3828 | 2024-11-09 | Rebels Gaming              | W   | 0.175      | -            | -                | -                | -         |     1.14 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           18 |     3857 | 2024-11-08 | AMKAL ESPORTS              | W   | 0.170      | 0.384        | -                | 0.588 (0.046)    | -         |     0.97 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           17 |     3866 | 2024-11-08 | Wild Lotus                 | W   | 0.169      | -            | -                | -                | -         |     0.47 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           16 |     3910 | 2024-11-07 | 9Pandas                    | L   | 0.164      | -            | -                | -                | -         |    -2.75 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           15 |     3964 | 2024-11-06 | Johnny Speeds              | W   | 0.158      | -            | -                | -                | -         |     1.38 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           14 |     4020 | 2024-11-05 | SINNERS Esports            | W   | 0.153      | -            | -                | -                | -         |     1.87 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           13 |     4087 | 2024-11-04 | GUN5 Esports               | L   | 0.147      | -            | -                | -                | -         |    -2.55 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           12 |     4140 | 2024-11-03 | GUN5 Esports               | W   | 0.142      | 0.371        | 0.105 (0.007)    | -                | -         |     2.03 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           11 |     4211 | 2024-11-02 | P0RTUGAL                   | W   | 0.136      | -            | -                | -                | -         |     0.94 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|           10 |     4274 | 2024-11-01 | Wild Lotus                 | W   | 0.130      | -            | -                | -                | -         |     0.35 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            9 |     4389 | 2024-10-30 | Chimera Esports            | W   | 0.121      | -            | -                | -                | -         |     0.97 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            8 |     4519 | 2024-10-28 | Zero Tenacity              | W   | 0.109      | 0.384        | -                | 0.778 (0.039)    | -         |     1.16 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            7 |     4645 | 2024-10-26 | GUN5 Esports               | L   | 0.097      | -            | -                | -                | -         |    -1.66 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            6 |     4821 | 2024-10-21 | Dark Cloud Esports         | W   | 0.071      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            5 |     4914 | 2024-10-20 | 9Pandas                    | W   | 0.064      | -            | -                | -                | -         |     0.93 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            4 |     5062 | 2024-10-17 | Los kogutos                | L   | 0.047      | -            | -                | -                | -         |    -1.01 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            3 |     5219 | 2024-10-15 | ALASKA                     | L   | 0.035      | -            | -                | -                | -         |    -0.27 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            2 |     5246 | 2024-10-14 | GameAgents                 | W   | 0.031      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq     |
|            1 |     5379 | 2024-10-12 | Leo Team                   | W   | 0.019      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,984.90)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $2,000.00      | $1,837.41       |
| 2025-02-15 |      0.866 | $2,000.00      | $1,731.48       |
| 2024-12-17 |      0.466 | $10,000.00     | $4,655.56       |
| 2024-11-24 |      0.311 | $41,107.93     | $12,772.01      |
| 2024-11-12 |      0.232 | $1,000.00      | $231.50         |
| 2024-11-11 |      0.223 | $5,000.00      | $1,115.28       |
| 2024-11-10 |      0.219 | $7,500.00      | $1,641.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
