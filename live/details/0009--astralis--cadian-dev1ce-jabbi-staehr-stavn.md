### Roster Details<br />
Team Name: Astralis<br />
Roster: cadiaN, dev1ce, jabbi, Staehr, stavn<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1723.5<br />
<br />
Final Rank Value (1723.5) = Starting Rank Value (1895.8) + Head To Head Adjustments (-172.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.882[<sup>1</sup>](#table2)
- Bounty Collected: 0.673[<sup>2</sup>](#table1)
- Opponent Network: 0.322[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.719<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1895.8
- 400 + ( ( 0.719 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1895.8


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
|           41 |      185 | 2025-02-23 | FaZe Clan       | W   | 1.000      | 1.000        | 0.475 (0.475)    | 0.399 (0.399)    | 1 (1.000) |    19.41 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           40 |      225 | 2025-02-22 | MOUZ            | L   | 1.000      | -            | -                | -                | -         |    -9.39 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           39 |      285 | 2025-02-21 | The MongolZ     | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.463 (0.463)    | 1 (1.000) |    22.42 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           38 |      322 | 2025-02-20 | HEROIC          | L   | 1.000      | -            | -                | -                | -         |   -29.77 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           37 |      382 | 2025-02-18 | BIG             | W   | 1.000      | 1.000        | 0.244 (0.244)    | 0.528 (0.528)    | 1 (1.000) |     3.70 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           36 |      415 | 2025-02-17 | MIBR            | W   | 1.000      | 1.000        | 0.118 (0.118)    | 0.285 (0.285)    | 1 (1.000) |     1.15 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           35 |      463 | 2025-02-16 | Team Falcons    | L   | 1.000      | -            | -                | -                | -         |   -10.99 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           34 |      508 | 2025-02-15 | SAW             | W   | 1.000      | 1.000        | 0.315 (0.315)    | 0.333 (0.333)    | 1 (1.000) |     2.73 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           33 |      567 | 2025-02-14 | PaiN Gaming     | L   | 1.000      | -            | -                | -                | -         |   -25.04 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           32 |      636 | 2025-02-11 | BetBoom Team    | W   | 1.000      | -            | -                | -                | -         |     0.90 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           31 |      644 | 2025-02-11 | Zero Tenacity   | W   | 1.000      | -            | -                | -                | -         |     0.34 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           30 |      671 | 2025-02-10 | BC.Game Esports | L   | 1.000      | -            | -                | -                | -         |   -30.45 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           29 |      680 | 2025-02-10 | OG              | W   | 1.000      | -            | -                | -                | -         |     0.36 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           28 |      714 | 2025-02-09 | PARIVISION      | W   | 1.000      | -            | -                | -                | -         |     0.25 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           27 |      719 | 2025-02-09 | 500             | W   | 1.000      | -            | -                | -                | -         |     0.82 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           26 |      794 | 2025-02-08 | 9INE            | W   | 1.000      | -            | -                | -                | -         |     0.34 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           25 |     1066 | 2025-02-04 | GamerLegion     | L   | 1.000      | -            | -                | -                | -         |   -23.55 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           24 |     1094 | 2025-02-03 | FURIA           | W   | 1.000      | 1.000        | -                | 0.228 (0.228)    | 1 (1.000) |     1.22 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           23 |     1110 | 2025-02-02 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -8.57 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           22 |     1159 | 2025-01-31 | PaiN Gaming     | W   | 0.990      | 1.000        | 0.333 (0.330)    | 0.406 (0.403)    | 1 (0.990) |     5.13 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           21 |     1170 | 2025-01-30 | FlyQuest        | W   | 0.983      | 1.000        | 0.099 (0.097)    | 0.267 (0.262)    | 1 (0.983) |     1.08 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           20 |     1181 | 2025-01-29 | MIBR            | L   | 0.975      | -            | -                | -                | -         |   -30.11 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           19 |     1314 | 2025-01-18 | Natus Vincere   | L   | 0.904      | -            | -                | -                | -         |   -19.00 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           18 |     1341 | 2025-01-15 | Wildcard        | W   | 0.882      | -            | -                | -                | -         |     0.51 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           17 |     2815 | 2024-11-23 | Passion UA      | L   | 0.534      | -            | -                | -                | -         |   -16.70 | br0, cadiaN, jabbi, Staehr, stavn    |
|           16 |     2905 | 2024-11-23 | Eternal Fire    | W   | 0.528      | -            | -                | -                | 1 (0.528) |     9.07 | br0, cadiaN, jabbi, Staehr, stavn    |
|           15 |     2991 | 2024-11-22 | B8              | W   | 0.521      | -            | -                | -                | 1 (0.521) |     0.47 | br0, cadiaN, jabbi, Staehr, stavn    |
|           14 |     3048 | 2024-11-21 | Sashi Esport    | L   | 0.516      | -            | -                | -                | -         |   -16.11 | br0, cadiaN, jabbi, Staehr, stavn    |
|           13 |     3063 | 2024-11-20 | 9Pandas         | L   | 0.514      | -            | -                | -                | -         |   -15.98 | br0, cadiaN, jabbi, Staehr, stavn    |
|           12 |     4068 | 2024-11-02 | Team Spirit     | L   | 0.389      | -            | -                | -                | -         |    -4.51 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           11 |     4185 | 2024-10-31 | MOUZ            | W   | 0.375      | 1.000        | 1.000 (0.375)    | 0.420 (0.157)    | -         |     7.19 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|           10 |     4257 | 2024-10-29 | Natus Vincere   | W   | 0.367      | 1.000        | 0.602 (0.221)    | 0.434 (0.159)    | -         |     3.24 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            9 |     5265 | 2024-10-09 | Virtus.pro      | L   | 0.229      | -            | -                | -                | -         |    -5.41 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            8 |     5333 | 2024-10-08 | Team Falcons    | L   | 0.223      | -            | -                | -                | -         |    -3.10 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            7 |     5387 | 2024-10-07 | Eternal Fire    | W   | 0.217      | 0.624        | 0.708 (0.096)    | -                | -         |     4.02 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            6 |     6102 | 2024-09-26 | Team Spirit     | L   | 0.143      | -            | -                | -                | -         |    -1.61 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            5 |     6193 | 2024-09-25 | Team Vitality   | L   | 0.136      | -            | -                | -                | -         |    -1.98 | cadiaN, dev1ce, jabbi, Staehr, stavn |
|            4 |     6897 | 2024-09-14 | Complexity      | L   | 0.063      | -            | -                | -                | -         |    -1.96 | br0, dev1ce, jabbi, Staehr, stavn    |
|            3 |     6985 | 2024-09-13 | Rooster         | W   | 0.056      | -            | -                | -                | -         |     0.00 | br0, dev1ce, jabbi, Staehr, stavn    |
|            2 |     7081 | 2024-09-11 | Complexity      | L   | 0.043      | -            | -                | -                | -         |    -1.33 | br0, dev1ce, jabbi, Staehr, stavn    |
|            1 |     7143 | 2024-09-10 | Fnatic          | L   | 0.035      | -            | -                | -                | -         |    -1.09 | br0, dev1ce, jabbi, Staehr, stavn    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($203,262.82)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.73) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $150,000.00    | $150,000.00     |
| 2025-02-09 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-11-03 |      0.395 | $85,000.00     | $33,543.70      |
| 2024-10-13 |      0.257 | $5,000.00      | $1,282.88       |
| 2024-09-29 |      0.162 | $10,000.00     | $1,624.09       |
| 2024-09-22 |      0.116 | $7,000.00      | $812.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
