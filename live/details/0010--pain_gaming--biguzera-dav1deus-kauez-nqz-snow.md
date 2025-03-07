### Roster Details<br />
Team Name: PaiN Gaming<br />
Roster: biguzera, dav1deuS, kauez, nqz, snow<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1627.5<br />
<br />
Final Rank Value (1627.5) = Starting Rank Value (1637.7) + Head To Head Adjustments (-10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.691[<sup>1</sup>](#table2)
- Bounty Collected: 0.605[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.742[<sup>2</sup>](#table1)

The average of these factors is 0.561<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1637.7
- 400 + ( ( 0.561 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1637.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |        3 | 2025-03-04 | Lynn Vision Gaming | W   | 0.815      | 0.415        | 0.028 (0.011)    | 0.303 (0.123)    | 1 (0.978) |     0.56 | biguzera, dav1deuS, kauez, nqz, snow |
|           23 |        5 | 2025-03-03 | FlyQuest           | L   | 0.812      | -            | -                | -                | -         |   -24.26 | biguzera, dav1deuS, kauez, nqz, snow |
|           22 |      294 | 2025-02-21 | MOUZ               | L   | 0.752      | -            | -                | -                | -         |    -4.34 | biguzera, dav1deuS, kauez, nqz, snow |
|           21 |      421 | 2025-02-17 | Virtus.pro         | W   | 0.732      | 1.000        | 0.320 (0.281)    | 0.352 (0.309)    | 1 (0.879) |    11.22 | biguzera, dav1deuS, kauez, nqz, snow |
|           20 |      470 | 2025-02-16 | The MongolZ        | L   | 0.726      | -            | -                | -                | -         |    -5.35 | biguzera, dav1deuS, kauez, nqz, snow |
|           19 |      529 | 2025-02-15 | Team Falcons       | W   | 0.721      | 1.000        | 1.000 (0.865)    | 0.495 (0.428)    | 1 (0.865) |    18.13 | biguzera, dav1deuS, kauez, nqz, snow |
|           18 |      590 | 2025-02-14 | Astralis           | W   | 0.715      | 1.000        | 0.788 (0.676)    | 0.807 (0.692)    | 1 (0.858) |    17.05 | biguzera, dav1deuS, kauez, nqz, snow |
|           17 |      738 | 2025-02-09 | Imperial Esports   | L   | 0.687      | -            | -                | -                | -         |   -21.21 | biguzera, dav1deuS, kauez, nqz, snow |
|           16 |      774 | 2025-02-08 | RED Canids         | W   | 0.683      | 0.143        | -                | 0.196 (0.023)    | 0 (0.000) |     0.17 | biguzera, dav1deuS, kauez, nqz, snow |
|           15 |     1183 | 2025-01-31 | Astralis           | L   | 0.638      | -            | -                | -                | -         |    -4.29 | biguzera, dav1deuS, kauez, nqz, snow |
|           14 |     1195 | 2025-01-30 | GamerLegion        | L   | 0.631      | -            | -                | -                | -         |   -12.76 | biguzera, dav1deuS, kauez, nqz, snow |
|           13 |     1209 | 2025-01-29 | Virtus.pro         | W   | 0.625      | 1.000        | 0.320 (0.240)    | 0.352 (0.264)    | 1 (0.750) |     9.74 | biguzera, dav1deuS, kauez, nqz, snow |
|           12 |     1325 | 2025-01-24 | Natus Vincere      | L   | 0.599      | -            | -                | -                | -         |   -11.32 | biguzera, dav1deuS, kauez, nqz, snow |
|           11 |     1442 | 2025-01-18 | FaZe Clan          | W   | 0.565      | 0.363        | 0.498 (0.122)    | 0.354 (0.087)    | 0 (0.000) |    13.06 | biguzera, dav1deuS, kauez, nqz, snow |
|           10 |     1453 | 2025-01-17 | GamerLegion        | W   | 0.559      | 0.363        | 0.094 (0.023)    | 0.415 (0.101)    | 0 (0.000) |     6.48 | biguzera, dav1deuS, kauez, nqz, snow |
|            9 |     4553 | 2024-10-27 | B8                 | L   | 0.104      | -            | -                | -                | -         |    -3.10 | biguzera, kauez, lux, nqz, snow      |
|            8 |     4675 | 2024-10-25 | Legacy             | W   | 0.093      | 0.500        | 0.032 (0.002)    | 0.556 (0.031)    | 1 (0.112) |     0.04 | biguzera, kauez, lux, nqz, snow      |
|            7 |     4692 | 2024-10-25 | Monte              | W   | 0.092      | -            | -                | -                | 1 (0.110) |     0.03 | biguzera, kauez, lux, nqz, snow      |
|            6 |     4866 | 2024-10-20 | MIBR               | W   | 0.066      | 0.450        | 0.105 (0.004)    | 0.265 (0.009)    | -         |     0.19 | biguzera, kauez, lux, nqz, snow      |
|            5 |     5025 | 2024-10-17 | MIBR               | W   | 0.050      | 0.450        | 0.105 (0.003)    | -                | -         |     0.14 | biguzera, kauez, lux, nqz, snow      |
|            4 |     5083 | 2024-10-16 | InSanitY Sports    | W   | 0.044      | -            | -                | -                | -         |     0.01 | biguzera, kauez, lux, nqz, snow      |
|            3 |     5463 | 2024-10-09 | InSanitY Sports    | L   | 0.006      | -            | -                | -                | -         |    -0.17 | biguzera, kauez, lux, nqz, snow      |
|            2 |     5472 | 2024-10-09 | InSanitY Sports    | L   | 0.005      | -            | -                | -                | -         |    -0.17 | biguzera, kauez, lux, nqz, snow      |
|            1 |     5548 | 2024-10-08 | Imperial Esports   | L   | 0.000      | -            | -                | -                | -         |     0.00 | biguzera, kauez, lux, nqz, snow      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74,946.18)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.36) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $62,500.00     | $57,427.66      |
| 2025-02-09 |      0.825 | $4,500.00      | $3,712.50       |
| 2025-01-26 |      0.731 | $15,000.00     | $10,970.83      |
| 2024-10-27 |      0.125 | $10,000.00     | $1,254.63       |
| 2024-10-20 |      0.079 | $20,000.00     | $1,580.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
