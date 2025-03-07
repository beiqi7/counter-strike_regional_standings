### Roster Details<br />
Team Name: BC.Game Esports<br />
Roster: CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  845.4<br />
<br />
Final Rank Value (845.4) = Starting Rank Value (817.7) + Head To Head Adjustments (27.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.373[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.7
- 400 + ( ( 0.189 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 817.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |     1783 | 2024-12-19 | AMKAL ESPORTS          | L   | 0.397      | -            | -                | -                | -         |    -6.95 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           58 |     1831 | 2024-12-16 | G2 Ares                | W   | 0.381      | -            | -                | -                | 0 (0.000) |     3.39 | CacaNito, GuardiaN, jkaem, Lekr0, sense       |
|           57 |     1886 | 2024-12-15 | Preasy Esport          | W   | 0.375      | 0.333        | -                | 0.647 (0.097)    | 0 (0.000) |     4.84 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           56 |     2037 | 2024-12-13 | Nexus Gaming           | W   | 0.364      | 0.333        | 0.161 (0.023)    | 0.539 (0.079)    | 0 (0.000) |     9.35 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           55 |     2112 | 2024-12-11 | Betera Esports         | L   | 0.354      | -            | -                | -                | -         |    -7.19 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           54 |     2187 | 2024-12-09 | K27                    | L   | 0.342      | -            | -                | -                | -         |    -3.83 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           53 |     2390 | 2024-12-05 | GenOne                 | W   | 0.319      | 0.333        | -                | 0.644 (0.082)    | 0 (0.000) |     4.95 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           52 |     2427 | 2024-12-04 | Illuminar Gaming       | W   | 0.315      | -            | -                | -                | 0 (0.000) |     4.33 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           51 |     2434 | 2024-12-04 | GenOne                 | L   | 0.314      | -            | -                | -                | -         |    -4.99 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           50 |     2482 | 2024-12-03 | GenOne                 | L   | 0.308      | -            | -                | -                | -         |    -5.11 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           49 |     2523 | 2024-12-02 | FLuffy Gangsters       | L   | 0.303      | -            | -                | -                | -         |    -5.44 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           48 |     2527 | 2024-12-02 | FORZE Reload           | L   | 0.303      | -            | -                | -                | -         |    -4.84 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           47 |     2583 | 2024-12-01 | KONO.ECF               | W   | 0.298      | 0.372        | 0.047 (0.006)    | 0.597 (0.080)    | 0 (0.000) |     5.13 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           46 |     2591 | 2024-12-01 | Illuminar Gaming       | W   | 0.298      | -            | -                | -                | 0 (0.000) |     3.97 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           45 |     2683 | 2024-11-30 | GUN5 Esports           | L   | 0.291      | -            | -                | -                | -         |    -2.97 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           44 |     2713 | 2024-11-29 | Dark Cloud Esports     | W   | 0.288      | 0.333        | 0.035 (0.004)    | 0.667 (0.077)    | 0 (0.000) |     4.50 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           43 |     2724 | 2024-11-29 | KONO.ECF               | W   | 0.287      | 0.333        | 0.047 (0.005)    | 0.597 (0.068)    | 0 (0.000) |     5.18 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           42 |     2728 | 2024-11-29 | Tricked Esport         | W   | 0.286      | 0.333        | 0.030 (0.003)    | 0.549 (0.063)    | 0 (0.000) |     4.75 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           41 |     2756 | 2024-11-28 | 500                    | L   | 0.282      | -            | -                | -                | -         |    -2.15 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           40 |     2770 | 2024-11-28 | JANO Esports           | W   | 0.281      | -            | -                | -                | -         |     5.66 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           39 |     2795 | 2024-11-27 | Viperio                | W   | 0.276      | -            | -                | -                | -         |     3.44 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           38 |     2802 | 2024-11-27 | Chimera Esports        | W   | 0.275      | 0.333        | 0.023 (0.003)    | -                | -         |     4.57 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           37 |     2853 | 2024-11-26 | Viperio                | L   | 0.270      | -            | -                | -                | -         |    -5.26 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           36 |     2858 | 2024-11-26 | ALASKA                 | W   | 0.269      | 0.333        | 0.033 (0.004)    | 0.737 (0.079)    | -         |     7.25 | CacaNito, GuardiaN, Lekr0, M1key, pr1metapz   |
|           35 |     2880 | 2024-11-25 | Leo Team               | W   | 0.264      | 0.333        | -                | 0.553 (0.058)    | -         |     4.51 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           34 |     2912 | 2024-11-24 | G2 Ares                | W   | 0.259      | -            | -                | -                | -         |     2.60 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           33 |     3021 | 2024-11-23 | GenOne                 | W   | 0.253      | 0.333        | -                | 0.644 (0.065)    | -         |     4.01 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           32 |     3085 | 2024-11-22 | UNiTY esports          | L   | 0.249      | -            | -                | -                | -         |    -4.21 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           31 |     3102 | 2024-11-22 | Lilmix                 | W   | 0.248      | -            | -                | -                | -         |     1.99 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           30 |     3171 | 2024-11-21 | FORZE Reload           | L   | 0.242      | -            | -                | -                | -         |    -3.63 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           29 |     3295 | 2024-11-19 | Betclic Apogee Esports | W   | 0.231      | -            | -                | -                | -         |     0.64 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           28 |     3344 | 2024-11-18 | Astralis Talent        | L   | 0.225      | -            | -                | -                | -         |    -4.00 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           27 |     3516 | 2024-11-15 | FLuffy Gangsters       | L   | 0.209      | -            | -                | -                | -         |    -3.78 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           26 |     3525 | 2024-11-15 | Preasy Esport          | W   | 0.208      | -            | -                | -                | -         |     2.84 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           25 |     3558 | 2024-11-14 | TEAM NEXT LEVEL        | W   | 0.204      | 0.372        | 0.041 (0.004)    | -                | -         |     3.37 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           24 |     3568 | 2024-11-14 | Passion UA             | W   | 0.204      | -            | -                | -                | -         |     3.65 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           23 |     3652 | 2024-11-12 | WW Team                | W   | 0.192      | -            | -                | -                | -         |     0.54 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           22 |     3700 | 2024-11-11 | Chimera Esports        | L   | 0.187      | -            | -                | -                | -         |    -2.86 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           21 |     3703 | 2024-11-11 | QUAZAR                 | W   | 0.187      | -            | -                | -                | -         |     2.05 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           20 |     3901 | 2024-11-07 | Nuclear TigeRES        | L   | 0.165      | -            | -                | -                | -         |    -2.21 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           19 |     4005 | 2024-11-05 | Poslednii3ae3d         | W   | 0.154      | -            | -                | -                | -         |     1.31 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           18 |     4013 | 2024-11-05 | Ex-RUBY                | L   | 0.154      | -            | -                | -                | -         |    -4.03 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           17 |     4392 | 2024-10-30 | RUSTEC                 | W   | 0.120      | -            | -                | -                | -         |     0.65 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           16 |     4451 | 2024-10-29 | Leo Team               | W   | 0.115      | -            | -                | -                | -         |     1.76 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           15 |     4459 | 2024-10-29 | GTZ.ESPORTS            | W   | 0.115      | 0.372        | 0.068 (0.003)    | -                | -         |     3.25 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           14 |     4462 | 2024-10-29 | RUSTEC                 | L   | 0.114      | -            | -                | -                | -         |    -2.46 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           13 |     4682 | 2024-10-25 | GamerLegion Academy    | W   | 0.093      | -            | -                | -                | -         |     0.46 | CacaNito, GuardiaN, Lekr0, pr1metapz          |
|           12 |     4690 | 2024-10-25 | FLuffy Gangsters       | W   | 0.092      | -            | -                | -                | -         |     1.28 | CacaNito, GuardiaN, Lekr0, pr1metapz          |
|           11 |     4721 | 2024-10-24 | Team Spirit Academy    | L   | 0.086      | -            | -                | -                | -         |    -0.86 | CacaNito, GuardiaN, Lekr0, pr1metapz          |
|           10 |     4801 | 2024-10-22 | Nexus Gaming           | L   | 0.076      | -            | -                | -                | -         |    -0.33 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            9 |     4854 | 2024-10-21 | RUSTEC                 | L   | 0.070      | -            | -                | -                | -         |    -1.82 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            8 |     4893 | 2024-10-20 | K27                    | L   | 0.065      | -            | -                | -                | -         |    -0.58 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            7 |     4969 | 2024-10-19 | Nexus Gaming           | W   | 0.058      | 0.333        | 0.161 (0.004)    | -                | -         |     1.57 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            6 |     5000 | 2024-10-18 | Kay Team               | W   | 0.054      | -            | -                | -                | -         |     0.25 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            5 |     5065 | 2024-10-17 | FORZE Reload           | L   | 0.047      | -            | -                | -                | -         |    -0.71 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            4 |     5142 | 2024-10-16 | FLuffy Gangsters       | L   | 0.042      | -            | -                | -                | -         |    -0.75 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            3 |     5158 | 2024-10-16 | TEAM NEXT LEVEL        | L   | 0.041      | -            | -                | -                | -         |    -0.59 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            2 |     5209 | 2024-10-15 | K27                    | W   | 0.036      | -            | -                | -                | -         |     0.83 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            1 |     5227 | 2024-10-14 | Viperio                | W   | 0.032      | -            | -                | -                | -         |     0.41 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,356.67)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-05 |      0.383 | $6,000.00      | $2,298.33       |
| 2024-11-29 |      0.343 | $6,000.00      | $2,058.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
