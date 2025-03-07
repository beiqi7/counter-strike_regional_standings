### Roster Details<br />
Team Name: Astralis<br />
Roster: cadiaN, dev1ce, jabbi, Staehr, stavn<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1803.0<br />
<br />
Final Rank Value (1803.0) = Starting Rank Value (1922.4) + Head To Head Adjustments (-119.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.906[<sup>1</sup>](#table2)
- Bounty Collected: 0.626[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.690<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1922.4
- 400 + ( ( 0.690 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1922.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      191 | 2025-02-23 | FaZe Clan       | W   | 0.765      | 1.000        | 0.498 (0.457)    | 0.354 (0.325)    | 1 (0.917) |    12.98 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           32 |      231 | 2025-02-22 | MOUZ            | L   | 0.759      | -            | -                | -                | -         |    -7.74 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           31 |      291 | 2025-02-21 | The MongolZ     | W   | 0.753      | 1.000        | 1.000 (0.904)    | 0.374 (0.338)    | 1 (0.904) |    14.11 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           30 |      329 | 2025-02-20 | HEROIC          | L   | 0.748      | -            | -                | -                | -         |   -23.10 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           29 |      404 | 2025-02-18 | BIG             | W   | 0.736      | 1.000        | 0.234 (0.206)    | 0.400 (0.353)    | 1 (0.883) |     1.60 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           28 |      438 | 2025-02-17 | MIBR            | W   | 0.731      | 1.000        | 0.105 (0.092)    | 0.265 (0.233)    | 1 (0.878) |     0.77 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           27 |      486 | 2025-02-16 | Team Falcons    | L   | 0.725      | -            | -                | -                | -         |    -9.36 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           26 |      531 | 2025-02-15 | SAW             | W   | 0.721      | 1.000        | 0.316 (0.273)    | 0.260 (0.225)    | 1 (0.865) |     1.22 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           25 |      590 | 2025-02-14 | PaiN Gaming     | L   | 0.715      | -            | -                | -                | -         |   -17.05 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           24 |      654 | 2025-02-11 | BetBoom Team    | W   | 0.699      | -            | -                | -                | -         |     0.24 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           23 |      663 | 2025-02-11 | Zero Tenacity   | W   | 0.698      | -            | -                | -                | -         |     0.11 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           22 |      690 | 2025-02-10 | BC.Game Esports | L   | 0.693      | -            | -                | -                | -         |   -21.54 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           21 |      701 | 2025-02-10 | OG              | W   | 0.692      | 0.143        | -                | 0.989 (0.117)    | -         |     0.12 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           20 |      735 | 2025-02-09 | PARIVISION      | W   | 0.688      | -            | -                | -                | -         |     0.07 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           19 |      741 | 2025-02-09 | 500             | W   | 0.687      | 0.143        | -                | 1.000 (0.118)    | -         |     0.27 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           18 |      816 | 2025-02-08 | 9INE            | W   | 0.681      | -            | -                | -                | -         |     0.12 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           17 |     1086 | 2025-02-04 | GamerLegion     | L   | 0.659      | -            | -                | -                | -         |   -17.31 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           16 |     1117 | 2025-02-03 | FURIA           | W   | 0.654      | 1.000        | -                | 0.192 (0.150)    | 1 (0.785) |     0.29 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           15 |     1133 | 2025-02-02 | Team Spirit     | L   | 0.648      | -            | -                | -                | -         |    -7.24 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           14 |     1183 | 2025-01-31 | PaiN Gaming     | W   | 0.638      | 1.000        | 0.357 (0.273)    | 0.371 (0.284)    | 1 (0.766) |     4.29 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           13 |     1194 | 2025-01-30 | FlyQuest        | W   | 0.632      | 1.000        | 0.096 (0.073)    | 0.190 (0.144)    | 1 (0.758) |     0.32 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           12 |     1207 | 2025-01-29 | MIBR            | L   | 0.625      | -            | -                | -                | -         |   -19.24 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           11 |     1434 | 2025-01-18 | Natus Vincere   | L   | 0.566      | -            | -                | -                | -         |   -15.48 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           10 |     1461 | 2025-01-15 | Wildcard        | W   | 0.547      | 0.363        | 0.162 (0.039)    | -                | -         |     0.22 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            9 |     2935 | 2024-11-23 | Passion UA      | L   | 0.257      | -            | -                | -                | -         |    -8.08 | br0, cadiaN, jabbi, Staehr, stavn    |
|            8 |     3026 | 2024-11-23 | Eternal Fire    | W   | 0.253      | -            | -                | -                | 1 (0.303) |     4.11 | br0, cadiaN, jabbi, Staehr, stavn    |
|            7 |     3109 | 2024-11-22 | B8              | W   | 0.247      | -            | -                | -                | 1 (0.296) |     0.09 | br0, cadiaN, jabbi, Staehr, stavn    |
|            6 |     3167 | 2024-11-21 | Sashi Esport    | L   | 0.242      | -            | -                | -                | -         |    -7.59 | br0, cadiaN, jabbi, Staehr, stavn    |
|            5 |     3182 | 2024-11-20 | 9Pandas         | L   | 0.241      | -            | -                | -                | -         |    -7.54 | br0, cadiaN, jabbi, Staehr, stavn    |
|            4 |     4207 | 2024-11-02 | Team Spirit     | L   | 0.137      | -            | -                | -                | -         |    -1.81 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            3 |     4325 | 2024-10-31 | MOUZ            | W   | 0.125      | 1.000        | 1.000 (0.150)    | -                | -         |     2.39 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            2 |     4405 | 2024-10-29 | Natus Vincere   | W   | 0.119      | 1.000        | 0.420 (0.060)    | -                | -         |     0.43 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            1 |     5502 | 2024-10-09 | Virtus.pro      | L   | 0.003      | -            | -                | -                | -         |    -0.09 | cadiaN, dev1ce, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($165,611.11)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.79) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $150,000.00    | $137,826.39     |
| 2025-02-09 |      0.825 | $16,000.00     | $13,200.00      |
| 2024-11-03 |      0.170 | $85,000.00     | $14,426.39      |
| 2024-10-13 |      0.032 | $5,000.00      | $158.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
