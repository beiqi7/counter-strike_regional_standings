### Roster Details<br />
Team Name: Partizan Esports<br />
Roster: c0llins, Dragon, emi, Kind0, VLDN<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1037.2<br />
<br />
Final Rank Value (1037.2) = Starting Rank Value (1072.6) + Head To Head Adjustments (-35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.479[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.244[<sup>2</sup>](#table1)

The average of these factors is 0.305<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1072.6
- 400 + ( ( 0.305 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1072.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |       18 | 2025-02-28 | PARIVISION           | W   | 0.792      | 0.435        | -                | 0.910 (0.376)    | 0 (0.000) |     7.21 | c0llins, Dragon, emi, Kind0, VLDN   |
|           39 |       82 | 2025-02-26 | 500                  | L   | 0.781      | -            | -                | -                | -         |   -11.19 | c0llins, Dragon, emi, Kind0, VLDN   |
|           38 |      238 | 2025-02-22 | BC.Game Esports      | L   | 0.759      | -            | -                | -                | -         |    -9.79 | c0llins, Dragon, Kind0, maden, VLDN |
|           37 |      269 | 2025-02-21 | 9INE                 | W   | 0.755      | 0.435        | 0.039 (0.015)    | 0.876 (0.345)    | 0 (0.000) |     9.51 | c0llins, Dragon, Kind0, maden, VLDN |
|           36 |      523 | 2025-02-15 | 500                  | L   | 0.721      | -            | -                | -                | -         |    -9.98 | c0llins, Dragon, emi, Kind0, VLDN   |
|           35 |      540 | 2025-02-15 | ENCE                 | W   | 0.721      | 0.435        | 0.081 (0.031)    | 0.416 (0.156)    | 0 (0.000) |     8.15 | c0llins, Dragon, emi, Kind0, VLDN   |
|           34 |      596 | 2025-02-14 | Nexus Gaming         | W   | 0.714      | 0.435        | 0.161 (0.060)    | 0.539 (0.201)    | 0 (0.000) |    10.29 | c0llins, Dragon, emi, Kind0, VLDN   |
|           33 |      639 | 2025-02-12 | Fnatic               | W   | 0.703      | 0.435        | 0.025 (0.009)    | 0.471 (0.173)    | -         |    11.31 | c0llins, Dragon, emi, Kind0, VLDN   |
|           32 |      790 | 2025-02-08 | BC.Game Esports      | L   | 0.682      | -            | -                | -                | -         |   -10.10 | c0llins, Dragon, emi, Kind0, VLDN   |
|           31 |      797 | 2025-02-08 | SkyFury              | W   | 0.682      | -            | -                | -                | -         |     1.17 | c0llins, Dragon, emi, Kind0, VLDN   |
|           30 |      849 | 2025-02-07 | DDL                  | W   | 0.678      | -            | -                | -                | -         |     0.61 | c0llins, Dragon, emi, Kind0, VLDN   |
|           29 |     1091 | 2025-02-04 | Aurora Gaming        | L   | 0.659      | -            | -                | -                | -         |   -16.15 | c0llins, Dragon, emi, Kind0, VLDN   |
|           28 |     2216 | 2024-12-08 | VOLT (European team) | L   | 0.338      | -            | -                | -                | -         |    -9.37 | c0llins, Dragon, emi, Kind0, ROGA   |
|           27 |     2464 | 2024-12-03 | 500                  | L   | 0.310      | -            | -                | -                | -         |    -5.17 | c0llins, Dragon, emi, Kind0, ROGA   |
|           26 |     2494 | 2024-12-02 | Permitta Esports     | W   | 0.305      | 0.372        | 0.013 (0.002)    | 0.349 (0.048)    | -         |     1.96 | c0llins, Dragon, emi, Kind0, ROGA   |
|           25 |     2663 | 2024-11-30 | UNiTY esports        | W   | 0.293      | 0.372        | 0.019 (0.003)    | -                | -         |     1.68 | c0llins, Dragon, emi, Kind0, ROGA   |
|           24 |     2715 | 2024-11-29 | CYBERSHOKE Esports   | L   | 0.287      | -            | -                | -                | -         |    -6.71 | c0llins, Dragon, emi, Kind0, ROGA   |
|           23 |     2794 | 2024-11-27 | Lazer Cats           | W   | 0.276      | -            | -                | -                | -         |     1.14 | c0llins, Dragon, emi, Kind0, ROGA   |
|           22 |     2986 | 2024-11-23 | Anonymo Esports      | W   | 0.254      | -            | -                | -                | -         |     0.35 | c0llins, Dragon, emi, Kind0, ROGA   |
|           21 |     3000 | 2024-11-23 | RUSTEC               | W   | 0.254      | -            | -                | -                | -         |     0.41 | c0llins, Dragon, emi, Kind0, ROGA   |
|           20 |     3070 | 2024-11-22 | Leo Team             | L   | 0.249      | -            | -                | -                | -         |    -6.12 | c0llins, Dragon, emi, Kind0, ROGA   |
|           19 |     3082 | 2024-11-22 | QUAZAR               | W   | 0.249      | -            | -                | -                | -         |     0.90 | c0llins, Dragon, emi, Kind0, ROGA   |
|           18 |     3378 | 2024-11-17 | Metizport            | W   | 0.220      | 0.617        | 0.062 (0.010)    | 0.367 (0.060)    | 1 (0.264) |     3.04 | c0llins, choiv7, Dragon, emi, Kind0 |
|           17 |     3398 | 2024-11-17 | GTZ.ESPORTS          | L   | 0.219      | -            | -                | -                | -         |    -2.28 | c0llins, choiv7, Dragon, emi, Kind0 |
|           16 |     3445 | 2024-11-16 | Los kogutos          | W   | 0.215      | 0.617        | 0.022 (0.003)    | 0.257 (0.041)    | 1 (0.258) |     1.69 | c0llins, choiv7, Dragon, emi, Kind0 |
|           15 |     3513 | 2024-11-15 | Kitsune Esports      | W   | 0.209      | -            | -                | -                | 1 (0.251) |     0.48 | c0llins, choiv7, Dragon, emi, Kind0 |
|           14 |     3521 | 2024-11-15 | SINNERS Academy      | L   | 0.209      | -            | -                | -                | -         |    -5.73 | c0llins, choiv7, Dragon, emi, Kind0 |
|           13 |     3527 | 2024-11-14 | Team Czech Republic  | W   | 0.206      | -            | -                | -                | 1 (0.247) |     0.75 | c0llins, choiv7, Dragon, emi, Kind0 |
|           12 |     3596 | 2024-11-13 | The Huns Esports     | W   | 0.199      | 0.617        | 0.021 (0.003)    | 0.280 (0.041)    | 1 (0.239) |     2.00 | c0llins, choiv7, Dragon, emi, Kind0 |
|           11 |     3607 | 2024-11-13 | Dusty Roots          | W   | 0.199      | 0.617        | 0.009 (0.001)    | 0.257 (0.038)    | 1 (0.238) |     1.04 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     3884 | 2024-11-07 | Flame Sharks         | W   | 0.166      | -            | -                | -                | -         |     0.30 | c0llins, Dragon, emi, Kind0, ROGA   |
|            9 |     3896 | 2024-11-07 | RUSTEC               | W   | 0.166      | -            | -                | -                | -         |     0.53 | c0llins, Dragon, emi, Kind0, ROGA   |
|            8 |     4043 | 2024-11-04 | GameAgents           | L   | 0.149      | -            | -                | -                | -         |    -4.27 | c0llins, Dragon, emi, Kind0, ROGA   |
|            7 |     4384 | 2024-10-30 | MOUZ NXT             | L   | 0.121      | -            | -                | -                | -         |    -3.63 | c0llins, Dragon, emi, Kind0, ROGA   |
|            6 |     4434 | 2024-10-29 | Grindas              | W   | 0.116      | -            | -                | -                | -         |     0.18 | c0llins, Dragon, emi, Kind0, ROGA   |
|            5 |     4452 | 2024-10-29 | Los kogutos          | W   | 0.115      | -            | -                | -                | -         |     0.92 | c0llins, Dragon, emi, Kind0, ROGA   |
|            4 |     5117 | 2024-10-16 | ADEPTS               | W   | 0.043      | -            | -                | -                | -         |     0.07 | c0llins, Dragon, emi, Kind0, ROGA   |
|            3 |     5197 | 2024-10-15 | Fire Flux Esports    | L   | 0.037      | -            | -                | -                | -         |    -0.86 | c0llins, Dragon, emi, Kind0, ROGA   |
|            2 |     5231 | 2024-10-14 | Underrated           | W   | 0.032      | -            | -                | -                | -         |     0.12 | c0llins, Dragon, emi, Kind0, ROGA   |
|            1 |     5241 | 2024-10-14 | TEAM NEXT LEVEL      | W   | 0.031      | -            | -                | -                | -         |     0.11 | c0llins, Dragon, emi, Kind0, ROGA   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,123.29)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $2,000.00      | $1,837.41       |
| 2025-02-15 |      0.866 | $10,000.00     | $8,657.41       |
| 2024-11-17 |      0.265 | $25,000.00     | $6,628.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
