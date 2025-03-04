### Roster Details<br />
Team Name: BC.Game Esports<br />
Roster: CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz<br />
Global Rank: [95](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  896.4<br />
<br />
Final Rank Value (896.4) = Starting Rank Value (862.0) + Head To Head Adjustments (34.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.351[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 862.0
- 400 + ( ( 0.222 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 862.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |     1661 | 2024-12-19 | AMKAL ESPORTS      | L   | 0.702      | -            | -                | -                | -         |   -11.96 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           53 |     1706 | 2024-12-16 | G2 Ares            | W   | 0.683      | -            | -                | -                | 0 (0.000) |     5.19 | CacaNito, GuardiaN, jkaem, Lekr0, sense       |
|           52 |     1912 | 2024-12-13 | Nexus Gaming       | W   | 0.662      | 0.333        | 0.219 (0.048)    | 0.808 (0.178)    | 0 (0.000) |    16.39 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           51 |     1989 | 2024-12-11 | Betera Esports     | L   | 0.650      | -            | -                | -                | -         |   -13.47 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           50 |     2061 | 2024-12-09 | K27                | L   | 0.635      | -            | -                | -                | -         |    -9.97 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           49 |     2253 | 2024-12-05 | GenOne             | W   | 0.608      | 0.333        | -                | 0.853 (0.173)    | 0 (0.000) |     9.74 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           48 |     2290 | 2024-12-04 | Illuminar Gaming   | W   | 0.603      | 0.333        | -                | 0.588 (0.118)    | 0 (0.000) |     8.60 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           47 |     2297 | 2024-12-04 | GenOne             | L   | 0.602      | -            | -                | -                | -         |    -9.05 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           46 |     2348 | 2024-12-03 | GenOne             | L   | 0.595      | -            | -                | -                | -         |    -9.65 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           45 |     2403 | 2024-12-02 | FLuffy Gangsters   | L   | 0.589      | -            | -                | -                | -         |   -10.07 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           44 |     2407 | 2024-12-02 | FORZE Reload       | L   | 0.589      | -            | -                | -                | -         |    -9.90 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           43 |     2463 | 2024-12-01 | KONO.ECF           | W   | 0.583      | 0.372        | 0.054 (0.012)    | 0.763 (0.166)    | 0 (0.000) |     7.98 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           42 |     2471 | 2024-12-01 | Illuminar Gaming   | W   | 0.582      | -            | -                | -                | 0 (0.000) |     7.90 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           41 |     2563 | 2024-11-30 | GUN5 Esports       | L   | 0.575      | -            | -                | -                | -         |    -7.06 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           40 |     2594 | 2024-11-29 | Dark Cloud Esports | W   | 0.570      | 0.333        | 0.045 (0.009)    | 0.837 (0.159)    | 0 (0.000) |     8.24 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           39 |     2605 | 2024-11-29 | KONO.ECF           | W   | 0.569      | 0.333        | 0.054 (0.010)    | 0.763 (0.145)    | 0 (0.000) |     8.63 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           38 |     2609 | 2024-11-29 | Tricked Esport     | W   | 0.568      | 0.333        | 0.039 (0.007)    | 0.702 (0.133)    | 0 (0.000) |     9.86 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           37 |     2638 | 2024-11-28 | 500                | L   | 0.564      | -            | -                | -                | -         |    -4.71 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           36 |     2653 | 2024-11-28 | JANO Esports       | W   | 0.563      | -            | -                | -                | 0 (0.000) |     9.61 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           35 |     2677 | 2024-11-27 | Viperio            | W   | 0.557      | -            | -                | -                | -         |     5.94 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           34 |     2684 | 2024-11-27 | Chimera Esports    | W   | 0.556      | 0.333        | 0.030 (0.006)    | -                | -         |     9.59 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           33 |     2734 | 2024-11-26 | Viperio            | L   | 0.550      | -            | -                | -                | -         |   -11.83 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           32 |     2738 | 2024-11-26 | ALASKA             | W   | 0.548      | 0.333        | 0.036 (0.007)    | 0.888 (0.162)    | -         |    11.92 | CacaNito, GuardiaN, Lekr0, M1key, pr1metapz   |
|           31 |     2760 | 2024-11-25 | Leo Team           | W   | 0.542      | 0.333        | -                | 0.763 (0.138)    | -         |    10.20 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           30 |     2791 | 2024-11-24 | G2 Ares            | W   | 0.536      | -            | -                | -                | -         |     5.05 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           29 |     2899 | 2024-11-23 | GenOne             | W   | 0.529      | 0.333        | -                | 0.853 (0.150)    | -         |     8.83 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           28 |     2965 | 2024-11-22 | UNiTY esports      | L   | 0.524      | -            | -                | -                | -         |    -7.93 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           27 |     2982 | 2024-11-22 | Lilmix             | W   | 0.523      | -            | -                | -                | -         |     3.23 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           26 |     3050 | 2024-11-21 | FORZE Reload       | L   | 0.515      | -            | -                | -                | -         |    -7.88 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           25 |     3212 | 2024-11-18 | Astralis Talent    | L   | 0.495      | -            | -                | -                | -         |    -9.27 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           24 |     3386 | 2024-11-15 | FLuffy Gangsters   | L   | 0.476      | -            | -                | -                | -         |    -8.69 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           23 |     3394 | 2024-11-15 | Preasy Esport      | W   | 0.475      | -            | -                | -                | -         |     5.36 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           22 |     3426 | 2024-11-14 | TEAM NEXT LEVEL    | W   | 0.470      | 0.372        | 0.047 (0.008)    | -                | -         |     7.16 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           21 |     3435 | 2024-11-14 | Passion UA         | W   | 0.470      | -            | -                | -                | -         |     8.92 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           20 |     3517 | 2024-11-12 | WW Team            | W   | 0.456      | -            | -                | -                | -         |     1.79 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           19 |     3565 | 2024-11-11 | Chimera Esports    | L   | 0.450      | -            | -                | -                | -         |    -6.77 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           18 |     3568 | 2024-11-11 | QUAZAR             | W   | 0.449      | -            | -                | -                | -         |     4.88 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           17 |     3765 | 2024-11-07 | Nuclear TigeRES    | L   | 0.423      | -            | -                | -                | -         |    -6.59 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           16 |     3865 | 2024-11-05 | Poslednii3ae3d     | W   | 0.410      | -            | -                | -                | -         |     2.73 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           15 |     3872 | 2024-11-05 | Ex-RUBY            | L   | 0.410      | -            | -                | -                | -         |   -11.11 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           14 |     4242 | 2024-10-30 | RUSTEC             | W   | 0.370      | -            | -                | -                | -         |     1.78 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           13 |     4296 | 2024-10-29 | Leo Team           | W   | 0.363      | -            | -                | -                | -         |     5.54 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           12 |     4303 | 2024-10-29 | GTZ.ESPORTS        | W   | 0.363      | 0.372        | 0.094 (0.013)    | -                | -         |    10.43 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           11 |     4306 | 2024-10-29 | RUSTEC             | L   | 0.362      | -            | -                | -                | -         |    -8.23 | CacaNito, GuardiaN, jkaem, Lekr0, pr1metapz   |
|           10 |     4619 | 2024-10-22 | Nexus Gaming       | L   | 0.317      | -            | -                | -                | -         |    -1.41 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            9 |     4704 | 2024-10-20 | K27                | L   | 0.303      | -            | -                | -                | -         |    -3.61 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            8 |     4778 | 2024-10-19 | Nexus Gaming       | W   | 0.295      | 0.333        | 0.219 (0.022)    | -                | -         |     8.07 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            7 |     4808 | 2024-10-18 | Kay Team           | W   | 0.290      | -            | -                | -                | -         |     1.20 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            6 |     4927 | 2024-10-16 | FLuffy Gangsters   | L   | 0.276      | -            | -                | -                | -         |    -4.86 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            5 |     4942 | 2024-10-16 | TEAM NEXT LEVEL    | L   | 0.274      | -            | -                | -                | -         |    -4.20 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            4 |     4991 | 2024-10-15 | K27                | W   | 0.269      | -            | -                | -                | -         |     5.39 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            3 |     5009 | 2024-10-14 | Viperio            | W   | 0.264      | -            | -                | -                | -         |     3.27 | CacaNito, GuardiaN, KWERTZZ, Lekr0, pr1metapz |
|            2 |     6174 | 2024-09-25 | B8                 | L   | 0.138      | -            | -                | -                | -         |    -0.54 | anarkez, CacaNito, KWERTZZ, Lekr0, pr1metapz  |
|            1 |     7232 | 2024-09-08 | K27                | L   | 0.023      | -            | -                | -                | -         |    -0.25 | anarkez, CacaNito, GuardiaN, Lekr0, pr1metapz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,060.05)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-05 |      0.608 | $6,000.00      | $3,650.03       |
| 2024-11-29 |      0.568 | $6,000.00      | $3,410.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
