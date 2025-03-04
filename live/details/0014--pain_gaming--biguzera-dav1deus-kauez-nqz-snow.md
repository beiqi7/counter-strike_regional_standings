### Roster Details<br />
Team Name: PaiN Gaming<br />
Roster: biguzera, dav1deuS, kauez, nqz, snow<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1518.9<br />
<br />
Final Rank Value (1518.9) = Starting Rank Value (1529.1) + Head To Head Adjustments (-10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.677[<sup>1</sup>](#table2)
- Bounty Collected: 0.629[<sup>2</sup>](#table1)
- Opponent Network: 0.273[<sup>2</sup>](#table1)
- LAN Wins: 0.593[<sup>2</sup>](#table1)

The average of these factors is 0.543<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1529.1
- 400 + ( ( 0.543 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1529.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |        0 | 2025-03-03 | FlyQuest         | L   | 1.000      | -            | -                | -                | -         |   -27.62 | biguzera, dav1deuS, kauez, nqz, snow |
|           48 |      286 | 2025-02-21 | MOUZ             | L   | 1.000      | -            | -                | -                | -         |    -4.83 | biguzera, dav1deuS, kauez, nqz, snow |
|           47 |      397 | 2025-02-17 | Virtus.pro       | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.418 (0.418)    | 1 (1.000) |    20.44 | biguzera, dav1deuS, kauez, nqz, snow |
|           46 |      445 | 2025-02-16 | The MongolZ      | L   | 1.000      | -            | -                | -                | -         |    -4.10 | biguzera, dav1deuS, kauez, nqz, snow |
|           45 |      504 | 2025-02-15 | Team Falcons     | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.565 (0.565)    | 1 (1.000) |    27.01 | biguzera, dav1deuS, kauez, nqz, snow |
|           44 |      565 | 2025-02-14 | Astralis         | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |    24.98 | biguzera, dav1deuS, kauez, nqz, snow |
|           43 |      714 | 2025-02-09 | Imperial Esports | L   | 1.000      | -            | -                | -                | -         |   -29.65 | biguzera, dav1deuS, kauez, nqz, snow |
|           42 |      750 | 2025-02-08 | RED Canids       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.67 | biguzera, dav1deuS, kauez, nqz, snow |
|           41 |     1157 | 2025-01-31 | Astralis         | L   | 0.991      | -            | -                | -                | -         |    -5.18 | biguzera, dav1deuS, kauez, nqz, snow |
|           40 |     1169 | 2025-01-30 | GamerLegion      | L   | 0.983      | -            | -                | -                | -         |   -14.20 | biguzera, dav1deuS, kauez, nqz, snow |
|           39 |     1181 | 2025-01-29 | Virtus.pro       | W   | 0.975      | 1.000        | 0.298 (0.291)    | 0.418 (0.408)    | 1 (0.975) |    20.67 | biguzera, dav1deuS, kauez, nqz, snow |
|           38 |     1250 | 2025-01-24 | Natus Vincere    | L   | 0.944      | -            | -                | -                | -         |    -6.86 | biguzera, dav1deuS, kauez, nqz, snow |
|           37 |     1320 | 2025-01-18 | FaZe Clan        | W   | 0.903      | 0.363        | 0.475 (0.155)    | 0.398 (0.131)    | 0 (0.000) |    23.78 | biguzera, dav1deuS, kauez, nqz, snow |
|           36 |     1331 | 2025-01-17 | GamerLegion      | W   | 0.896      | 0.363        | 0.103 (0.034)    | 0.475 (0.154)    | 0 (0.000) |    16.57 | biguzera, dav1deuS, kauez, nqz, snow |
|           35 |     4392 | 2024-10-27 | B8               | L   | 0.350      | -            | -                | -                | -         |    -8.78 | biguzera, kauez, lux, nqz, snow      |
|           34 |     4511 | 2024-10-25 | Legacy           | W   | 0.337      | 0.500        | -                | 0.628 (0.106)    | 1 (0.337) |     0.43 | biguzera, kauez, lux, nqz, snow      |
|           33 |     4524 | 2024-10-25 | Monte            | W   | 0.336      | -            | -                | -                | 1 (0.336) |     0.36 | biguzera, kauez, lux, nqz, snow      |
|           32 |     4677 | 2024-10-20 | MIBR             | W   | 0.304      | 0.450        | 0.118 (0.016)    | -                | 0 (0.000) |     1.21 | biguzera, kauez, lux, nqz, snow      |
|           31 |     4831 | 2024-10-17 | MIBR             | W   | 0.285      | 0.450        | 0.118 (0.015)    | -                | -         |     1.13 | biguzera, kauez, lux, nqz, snow      |
|           30 |     4885 | 2024-10-16 | InSanitY Sports  | W   | 0.278      | -            | -                | -                | -         |     0.16 | biguzera, kauez, lux, nqz, snow      |
|           29 |     5231 | 2024-10-09 | InSanitY Sports  | L   | 0.232      | -            | -                | -                | -         |    -7.18 | biguzera, kauez, lux, nqz, snow      |
|           28 |     5239 | 2024-10-09 | InSanitY Sports  | L   | 0.232      | -            | -                | -                | -         |    -7.19 | biguzera, kauez, lux, nqz, snow      |
|           27 |     5307 | 2024-10-08 | Imperial Esports | L   | 0.225      | -            | -                | -                | -         |    -6.83 | biguzera, kauez, lux, nqz, snow      |
|           26 |     5315 | 2024-10-08 | Imperial Esports | W   | 0.225      | 0.450        | -                | 0.533 (0.054)    | -         |     0.27 | biguzera, kauez, lux, nqz, snow      |
|           25 |     5325 | 2024-10-08 | MIBR             | W   | 0.224      | 0.450        | 0.118 (0.012)    | -                | -         |     0.79 | biguzera, kauez, lux, nqz, snow      |
|           24 |     5330 | 2024-10-08 | MIBR             | W   | 0.224      | 0.450        | 0.118 (0.012)    | -                | -         |     0.80 | biguzera, kauez, lux, nqz, snow      |
|           23 |     5376 | 2024-10-07 | FaZe Clan        | L   | 0.217      | -            | -                | -                | -         |    -1.02 | biguzera, kauez, lux, nqz, snow      |
|           22 |     5404 | 2024-10-07 | MOUZ             | L   | 0.216      | -            | -                | -                | -         |    -0.46 | biguzera, kauez, lux, nqz, snow      |
|           21 |     5575 | 2024-10-04 | BESTIA           | L   | 0.197      | -            | -                | -                | -         |    -6.00 | biguzera, kauez, lux, nqz, snow      |
|           20 |     5648 | 2024-10-02 | Fluxo            | L   | 0.185      | -            | -                | -                | -         |    -5.53 | biguzera, kauez, lux, nqz, snow      |
|           19 |     5654 | 2024-10-02 | Fluxo            | L   | 0.185      | -            | -                | -                | -         |    -5.54 | biguzera, kauez, lux, nqz, snow      |
|           18 |     5660 | 2024-10-02 | RED Canids       | W   | 0.184      | -            | -                | -                | -         |     0.13 | biguzera, kauez, lux, nqz, snow      |
|           17 |     5664 | 2024-10-02 | RED Canids       | L   | 0.184      | -            | -                | -                | -         |    -5.67 | biguzera, kauez, lux, nqz, snow      |
|           16 |     5720 | 2024-10-01 | Hype Esports     | W   | 0.179      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |
|           15 |     5724 | 2024-10-01 | Hype Esports     | W   | 0.178      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |
|           14 |     5840 | 2024-09-29 | Fluxo            | W   | 0.165      | -            | -                | -                | -         |     0.24 | biguzera, kauez, lux, nqz, snow      |
|           13 |     5843 | 2024-09-29 | Team Solid       | W   | 0.164      | -            | -                | -                | -         |     0.13 | biguzera, kauez, lux, nqz, snow      |
|           12 |     5893 | 2024-09-28 | RED Canids       | W   | 0.159      | -            | -                | -                | -         |     0.10 | biguzera, kauez, lux, nqz, snow      |
|           11 |     5901 | 2024-09-28 | Team Solid       | L   | 0.158      | -            | -                | -                | -         |    -4.84 | biguzera, kauez, lux, nqz, snow      |
|           10 |     6146 | 2024-09-25 | ODDIK            | W   | 0.139      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, snow      |
|            9 |     6153 | 2024-09-25 | ODDIK            | W   | 0.138      | -            | -                | -                | -         |     0.12 | biguzera, kauez, lux, nqz, snow      |
|            8 |     6240 | 2024-09-24 | Sharks Esports   | W   | 0.132      | 0.450        | -                | 0.683 (0.041)    | -         |     0.40 | biguzera, kauez, lux, nqz, snow      |
|            7 |     6246 | 2024-09-24 | Sharks Esports   | W   | 0.132      | 0.450        | -                | 0.683 (0.040)    | -         |     0.40 | biguzera, kauez, lux, nqz, snow      |
|            6 |     6334 | 2024-09-23 | RED Canids       | W   | 0.125      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            5 |     6372 | 2024-09-23 | InSanitY Sports  | W   | 0.123      | -            | -                | -                | -         |     0.05 | biguzera, kauez, lux, nqz, snow      |
|            4 |     6566 | 2024-09-19 | KRÜ Esports      | W   | 0.099      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, snow      |
|            3 |     6569 | 2024-09-19 | KRÜ Esports      | W   | 0.098      | -            | -                | -                | -         |     0.03 | biguzera, kauez, lux, nqz, snow      |
|            2 |     6627 | 2024-09-18 | BESTIA           | W   | 0.092      | -            | -                | -                | -         |     0.08 | biguzera, kauez, lux, nqz, snow      |
|            1 |     6631 | 2024-09-18 | BESTIA           | W   | 0.092      | -            | -                | -                | -         |     0.08 | biguzera, kauez, lux, nqz, snow      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92,344.36)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.33) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $62,500.00     | $62,500.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-26 |      0.957 | $15,000.00     | $14,350.07      |
| 2024-10-27 |      0.351 | $10,000.00     | $3,507.45       |
| 2024-10-20 |      0.304 | $20,000.00     | $6,086.20       |
| 2024-10-13 |      0.257 | $4,000.00      | $1,027.80       |
| 2024-10-05 |      0.203 | $1,832.41      | $372.85         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
