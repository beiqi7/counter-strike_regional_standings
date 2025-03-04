### Roster Details<br />
Team Name: Partizan Esports<br />
Roster: c0llins, Dragon, emi, Kind0, VLDN<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1087.4<br />
<br />
Final Rank Value (1087.4) = Starting Rank Value (1162.1) + Head To Head Adjustments (-74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.497[<sup>1</sup>](#table2)
- Bounty Collected: 0.390[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.363[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1162.1
- 400 + ( ( 0.366 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1162.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |       12 | 2025-02-28 | PARIVISION            | W   | 1.000      | 0.435        | -                | 0.869 (0.378)    | 0 (0.000) |    10.67 | c0llins, Dragon, emi, Kind0, VLDN   |
|           71 |       76 | 2025-02-26 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -13.77 | c0llins, Dragon, emi, Kind0, VLDN   |
|           70 |      230 | 2025-02-22 | BC.Game Esports       | L   | 1.000      | -            | -                | -                | -         |   -10.61 | c0llins, Dragon, Kind0, maden, VLDN |
|           69 |      261 | 2025-02-21 | 9INE                  | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.862 (0.375)    | 0 (0.000) |    12.40 | c0llins, Dragon, Kind0, maden, VLDN |
|           68 |      498 | 2025-02-15 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -12.89 | c0llins, Dragon, emi, Kind0, VLDN   |
|           67 |      514 | 2025-02-15 | ENCE                  | W   | 1.000      | 0.435        | 0.158 (0.069)    | 0.423 (0.184)    | 0 (0.000) |    14.00 | c0llins, Dragon, emi, Kind0, VLDN   |
|           66 |      577 | 2025-02-14 | Nexus Gaming          | W   | 1.000      | 0.435        | 0.219 (0.095)    | 0.808 (0.351)    | 0 (0.000) |    11.93 | c0llins, Dragon, emi, Kind0, VLDN   |
|           65 |      619 | 2025-02-12 | Fnatic                | W   | 1.000      | 0.435        | 0.059 (0.026)    | 0.507 (0.221)    | -         |    19.40 | c0llins, Dragon, emi, Kind0, VLDN   |
|           64 |      766 | 2025-02-08 | BC.Game Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.99 | c0llins, Dragon, emi, Kind0, VLDN   |
|           63 |      773 | 2025-02-08 | SkyFury               | W   | 1.000      | -            | -                | -                | -         |     1.52 | c0llins, Dragon, emi, Kind0, VLDN   |
|           62 |      825 | 2025-02-07 | DDL                   | W   | 1.000      | -            | -                | -                | -         |     0.73 | c0llins, Dragon, emi, Kind0, VLDN   |
|           61 |     1069 | 2025-02-04 | Aurora Gaming         | L   | 1.000      | -            | -                | -                | -         |   -23.96 | c0llins, Dragon, emi, Kind0, VLDN   |
|           60 |     2088 | 2024-12-08 | VOLT (European team)  | L   | 0.631      | -            | -                | -                | -         |   -17.95 | c0llins, Dragon, emi, Kind0, ROGA   |
|           59 |     2327 | 2024-12-03 | 500                   | L   | 0.598      | -            | -                | -                | -         |   -10.46 | c0llins, Dragon, emi, Kind0, ROGA   |
|           58 |     2374 | 2024-12-02 | Permitta Esports      | W   | 0.591      | 0.372        | -                | 0.497 (0.109)    | -         |     3.47 | c0llins, Dragon, emi, Kind0, ROGA   |
|           57 |     2542 | 2024-11-30 | UNiTY esports         | W   | 0.577      | 0.372        | 0.030 (0.006)    | -                | -         |     3.65 | c0llins, Dragon, emi, Kind0, ROGA   |
|           56 |     2596 | 2024-11-29 | CYBERSHOKE Esports    | L   | 0.570      | -            | -                | -                | -         |   -14.04 | c0llins, Dragon, emi, Kind0, ROGA   |
|           55 |     2676 | 2024-11-27 | Lazer Cats            | W   | 0.557      | -            | -                | -                | -         |     2.17 | c0llins, Dragon, emi, Kind0, ROGA   |
|           54 |     2864 | 2024-11-23 | Anonymo Esports       | W   | 0.531      | -            | -                | -                | -         |     0.63 | c0llins, Dragon, emi, Kind0, ROGA   |
|           53 |     2878 | 2024-11-23 | RUSTEC                | W   | 0.530      | -            | -                | -                | -         |     0.75 | c0llins, Dragon, emi, Kind0, ROGA   |
|           52 |     2949 | 2024-11-22 | Leo Team              | L   | 0.524      | -            | -                | -                | -         |   -12.54 | c0llins, Dragon, emi, Kind0, ROGA   |
|           51 |     2962 | 2024-11-22 | QUAZAR                | W   | 0.524      | -            | -                | -                | -         |     1.75 | c0llins, Dragon, emi, Kind0, ROGA   |
|           50 |     3246 | 2024-11-17 | Metizport             | W   | 0.489      | 0.617        | 0.087 (0.026)    | 0.517 (0.156)    | 1 (0.489) |     7.72 | c0llins, choiv7, Dragon, emi, Kind0 |
|           49 |     3266 | 2024-11-17 | GTZ.ESPORTS           | L   | 0.488      | -            | -                | -                | -         |    -5.33 | c0llins, choiv7, Dragon, emi, Kind0 |
|           48 |     3314 | 2024-11-16 | Los kogutos           | W   | 0.483      | 0.617        | 0.037 (0.011)    | 0.520 (0.155)    | 1 (0.483) |     4.06 | c0llins, choiv7, Dragon, emi, Kind0 |
|           47 |     3383 | 2024-11-15 | Kitsune Esports       | W   | 0.476      | -            | -                | -                | 1 (0.476) |     0.77 | c0llins, choiv7, Dragon, emi, Kind0 |
|           46 |     3390 | 2024-11-15 | SINNERS Academy       | L   | 0.476      | -            | -                | -                | -         |   -13.46 | c0llins, choiv7, Dragon, emi, Kind0 |
|           45 |     3396 | 2024-11-14 | Team Czech Republic   | W   | 0.472      | -            | -                | -                | 1 (0.472) |     1.53 | c0llins, choiv7, Dragon, emi, Kind0 |
|           44 |     3464 | 2024-11-13 | The Huns Esports      | W   | 0.464      | 0.617        | 0.029 (0.008)    | 0.387 (0.111)    | 1 (0.464) |     4.09 | c0llins, choiv7, Dragon, emi, Kind0 |
|           43 |     3474 | 2024-11-13 | Dusty Roots           | W   | 0.464      | 0.617        | -                | 0.372 (0.107)    | 1 (0.464) |     1.74 | c0llins, choiv7, Dragon, emi, Kind0 |
|           42 |     3760 | 2024-11-07 | RUSTEC                | W   | 0.424      | -            | -                | -                | -         |     1.03 | c0llins, Dragon, emi, Kind0, ROGA   |
|           41 |     4234 | 2024-10-30 | MOUZ NXT              | L   | 0.370      | -            | -                | -                | -         |   -11.17 | c0llins, Dragon, emi, Kind0, ROGA   |
|           40 |     4281 | 2024-10-29 | Grindas               | W   | 0.364      | -            | -                | -                | -         |     0.39 | c0llins, Dragon, emi, Kind0, ROGA   |
|           39 |     4297 | 2024-10-29 | Los kogutos           | W   | 0.363      | 0.372        | 0.037 (0.005)    | -                | -         |     3.40 | c0llins, Dragon, emi, Kind0, ROGA   |
|           38 |     4906 | 2024-10-16 | ADEPTS                | W   | 0.277      | -            | -                | -                | -         |     0.44 | c0llins, Dragon, emi, Kind0, ROGA   |
|           37 |     4979 | 2024-10-15 | Fire Flux Esports     | L   | 0.270      | -            | -                | -                | -         |    -6.39 | c0llins, Dragon, emi, Kind0, ROGA   |
|           36 |     5011 | 2024-10-14 | Underrated            | W   | 0.264      | -            | -                | -                | -         |     0.66 | c0llins, Dragon, emi, Kind0, ROGA   |
|           35 |     5020 | 2024-10-14 | TEAM NEXT LEVEL       | W   | 0.263      | -            | -                | -                | -         |     0.68 | c0llins, Dragon, emi, Kind0, ROGA   |
|           34 |     5621 | 2024-10-03 | Johnny Speeds         | L   | 0.190      | -            | -                | -                | -         |    -4.70 | c0llins, Dragon, emi, Kind0, ROGA   |
|           33 |     5625 | 2024-10-03 | GUN5 Esports          | W   | 0.190      | 0.384        | 0.123 (0.009)    | -                | -         |     1.81 | c0llins, Dragon, emi, Kind0, ROGA   |
|           32 |     5689 | 2024-10-02 | Natus Vincere Junior  | L   | 0.182      | -            | -                | -                | -         |    -3.79 | c0llins, Dragon, emi, Kind0, ROGA   |
|           31 |     5692 | 2024-10-02 | Insilio               | W   | 0.182      | -            | -                | -                | -         |     0.46 | c0llins, Dragon, emi, Kind0, ROGA   |
|           30 |     5768 | 2024-10-01 | UNiTY esports         | W   | 0.175      | -            | -                | -                | -         |     0.98 | c0llins, Dragon, emi, Kind0, ROGA   |
|           29 |     5776 | 2024-10-01 | Viperio               | W   | 0.174      | -            | -                | -                | -         |     0.60 | c0llins, Dragon, emi, Kind0, ROGA   |
|           28 |     5826 | 2024-09-30 | CYBERSHOKE Esports    | W   | 0.169      | -            | -                | -                | -         |     1.12 | c0llins, Dragon, emi, Kind0, ROGA   |
|           27 |     5909 | 2024-09-28 | RUBY                  | L   | 0.157      | -            | -                | -                | -         |    -4.54 | c0llins, Dragon, emi, Kind0, ROGA   |
|           26 |     6079 | 2024-09-26 | Viperio               | W   | 0.144      | -            | -                | -                | -         |     0.49 | c0llins, Dragon, emi, Kind0, ROGA   |
|           25 |     6101 | 2024-09-26 | Preasy Esport         | W   | 0.143      | -            | -                | -                | -         |     0.66 | c0llins, Dragon, emi, Kind0, ROGA   |
|           24 |     6116 | 2024-09-26 | GenOne                | L   | 0.142      | -            | -                | -                | -         |    -3.76 | c0llins, Dragon, emi, Kind0, ROGA   |
|           23 |     6125 | 2024-09-26 | FLuffy Gangsters      | L   | 0.142      | -            | -                | -                | -         |    -3.90 | c0llins, Dragon, emi, Kind0, ROGA   |
|           22 |     6225 | 2024-09-25 | Leo Team              | W   | 0.134      | -            | -                | -                | -         |     0.68 | c0llins, Dragon, emi, Kind0, ROGA   |
|           21 |     6258 | 2024-09-24 | TEAM NEXT LEVEL       | L   | 0.131      | -            | -                | -                | -         |    -3.39 | c0llins, Dragon, emi, Kind0, ROGA   |
|           20 |     6296 | 2024-09-24 | ALASKA                | W   | 0.129      | -            | -                | -                | -         |     2.41 | c0llins, Dragon, emi, Kind0, ROGA   |
|           19 |     6315 | 2024-09-24 | ADEPTS                | W   | 0.128      | -            | -                | -                | -         |     0.17 | c0llins, Dragon, emi, Kind0, ROGA   |
|           18 |     6346 | 2024-09-23 | Natus Vincere Youth   | W   | 0.124      | -            | -                | -                | -         |     0.09 | c0llins, Dragon, emi, Kind0, ROGA   |
|           17 |     6369 | 2024-09-23 | Alliance              | W   | 0.123      | -            | -                | -                | -         |     0.90 | c0llins, Dragon, emi, Kind0, ROGA   |
|           16 |     6406 | 2024-09-22 | Nemiga Academy        | W   | 0.117      | -            | -                | -                | -         |     0.10 | c0llins, Dragon, emi, Kind0, ROGA   |
|           15 |     6420 | 2024-09-22 | ADEPTS                | L   | 0.116      | -            | -                | -                | -         |    -3.49 | c0llins, Dragon, emi, Kind0, ROGA   |
|           14 |     6433 | 2024-09-22 | ROYALS                | L   | 0.114      | -            | -                | -                | -         |    -3.36 | c0llins, Dragon, emi, Kind0, ROGA   |
|           13 |     6478 | 2024-09-21 | GODSENT               | W   | 0.110      | -            | -                | -                | -         |     0.22 | c0llins, Dragon, emi, Kind0, ROGA   |
|           12 |     6534 | 2024-09-20 | Chimera Esports       | W   | 0.103      | -            | -                | -                | -         |     0.53 | c0llins, Dragon, emi, Kind0, ROGA   |
|           11 |     6545 | 2024-09-20 | RUBY                  | W   | 0.102      | -            | -                | -                | -         |     0.23 | c0llins, Dragon, emi, Kind0, ROGA   |
|           10 |     6582 | 2024-09-19 | Future (Russian team) | W   | 0.097      | -            | -                | -                | -         |     0.11 | c0llins, Dragon, emi, Kind0, ROGA   |
|            9 |     6610 | 2024-09-19 | ADEPTS                | W   | 0.094      | -            | -                | -                | -         |     0.12 | c0llins, Dragon, emi, Kind0, ROGA   |
|            8 |     6662 | 2024-09-18 | Leo Team              | W   | 0.090      | -            | -                | -                | -         |     0.44 | c0llins, Dragon, emi, Kind0, ROGA   |
|            7 |     6717 | 2024-09-17 | Team Novaq            | W   | 0.084      | -            | -                | -                | -         |     1.40 | c0llins, Dragon, emi, Kind0, ROGA   |
|            6 |     6785 | 2024-09-16 | Ex-9INE Academy       | W   | 0.076      | -            | -                | -                | -         |     0.11 | c0llins, Dragon, emi, Kind0, ROGA   |
|            5 |     6840 | 2024-09-15 | Los kogutos           | L   | 0.069      | -            | -                | -                | -         |    -1.39 | c0llins, Dragon, emi, Kind0, ROGA   |
|            4 |     6960 | 2024-09-13 | Fire Flux Esports     | W   | 0.057      | -            | -                | -                | -         |     0.39 | c0llins, Dragon, emi, Kind0, ROGA   |
|            3 |     7322 | 2024-09-07 | RUSH B (Russian team) | L   | 0.016      | -            | -                | -                | -         |    -0.38 | c0llins, Dragon, emi, Kind0, ROGA   |
|            2 |     7375 | 2024-09-06 | Wu-Tang Clan          | W   | 0.011      | -            | -                | -                | -         |     0.01 | c0llins, Dragon, emi, Kind0, ROGA   |
|            1 |     7383 | 2024-09-06 | Underrated            | W   | 0.010      | -            | -                | -                | -         |     0.03 | c0llins, Dragon, emi, Kind0, ROGA   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,979.08)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $2,000.00      | $2,000.00       |
| 2025-02-15 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-11-17 |      0.490 | $25,000.00     | $12,260.53      |
| 2024-10-03 |      0.190 | $12,500.00     | $2,371.00       |
| 2024-09-29 |      0.164 | $500.00        | $81.84          |
| 2024-09-27 |      0.149 | $1,000.00      | $148.75         |
| 2024-09-22 |      0.117 | $1,000.00      | $116.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
