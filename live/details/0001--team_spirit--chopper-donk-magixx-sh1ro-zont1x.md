### Roster Details<br />
Team Name: Team Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1960.3<br />
<br />
Final Rank Value (1960.3) = Starting Rank Value (1984.0) + Head To Head Adjustments (-23.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.614[<sup>2</sup>](#table1)
- Opponent Network: 0.259[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.718<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1984.0
- 400 + ( ( 0.718 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1984.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      736 | 2025-02-09 | Team Vitality     | L   | 0.688      | -            | -                | -                | -         |   -13.08 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |      792 | 2025-02-08 | Natus Vincere     | W   | 0.682      | 1.000        | 0.420 (0.344)    | 0.321 (0.263)    | 1 (0.819) |     2.63 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |      879 | 2025-02-07 | Virtus.pro        | W   | 0.677      | 1.000        | 0.320 (0.260)    | 0.352 (0.286)    | 1 (0.812) |     3.18 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1032 | 2025-02-04 | GamerLegion       | W   | 0.660      | 1.000        | 0.094 (0.075)    | 0.415 (0.329)    | 1 (0.792) |     2.20 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1085 | 2025-02-04 | Team Liquid       | W   | 0.659      | 1.000        | -                | 0.180 (0.143)    | 1 (0.791) |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1116 | 2025-02-03 | Natus Vincere     | L   | 0.654      | -            | -                | -                | -         |   -18.47 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1133 | 2025-02-02 | Astralis          | W   | 0.648      | 1.000        | 0.788 (0.613)    | 0.807 (0.627)    | 1 (0.777) |     7.24 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     1280 | 2025-01-26 | Eternal Fire      | W   | 0.609      | 0.769        | 0.731 (0.411)    | 0.557 (0.313)    | 1 (0.731) |     8.58 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     1286 | 2025-01-25 | Natus Vincere     | W   | 0.605      | 0.769        | 0.420 (0.234)    | 0.321 (0.179)    | 1 (0.726) |     2.02 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     1364 | 2025-01-23 | HEROIC            | W   | 0.593      | 0.769        | 0.120 (0.065)    | 0.372 (0.203)    | 1 (0.711) |     0.12 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     1435 | 2025-01-18 | FlyQuest          | W   | 0.566      | -            | -                | -                | -         |     0.17 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     1462 | 2025-01-14 | Fnatic            | W   | 0.544      | 0.363        | -                | 0.471 (0.112)    | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     2918 | 2024-11-24 | Ninjas in Pyjamas | W   | 0.259      | -            | -                | -                | 1 (0.311) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     2933 | 2024-11-24 | Sashi Esport      | W   | 0.258      | -            | -                | -                | 1 (0.309) |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3025 | 2024-11-23 | G2 Esports        | L   | 0.253      | -            | -                | -                | -         |    -7.50 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3120 | 2024-11-21 | Aurora Gaming     | W   | 0.246      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3173 | 2024-11-21 | Passion UA        | L   | 0.242      | -            | -                | -                | -         |    -7.60 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     3188 | 2024-11-20 | B8                | W   | 0.240      | -            | -                | -                | -         |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4153 | 2024-11-03 | G2 Esports        | L   | 0.141      | -            | -                | -                | -         |    -4.22 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4207 | 2024-11-02 | Astralis          | W   | 0.137      | 1.000        | 0.788 (0.129)    | 0.807 (0.132)    | -         |     1.81 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4269 | 2024-11-01 | FaZe Clan         | W   | 0.131      | 1.000        | 0.498 (0.078)    | -                | -         |     1.25 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4315 | 2024-10-31 | G2 Esports        | L   | 0.126      | -            | -                | -                | -         |    -3.77 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4393 | 2024-10-30 | Team Vitality     | W   | 0.120      | 1.000        | 1.000 (0.144)    | -                | -         |     1.28 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($401,661.98)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      0.825 | $180,000.00    | $148,500.00     |
| 2025-01-26 |      0.731 | $288,125.00    | $210,731.42     |
| 2024-11-03 |      0.170 | $250,000.00    | $42,430.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
