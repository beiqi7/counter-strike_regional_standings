### Roster Details<br />
Team Name: Team Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1959.5<br />
<br />
Final Rank Value (1959.5) = Starting Rank Value (2000.0) + Head To Head Adjustments (-40.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.696[<sup>2</sup>](#table1)
- Opponent Network: 0.381[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.769<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 2000.0
- 400 + ( ( 0.769 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 2000.0


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
|           32 |      715 | 2025-02-09 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -16.63 | chopper, donk, magixx, sh1ro, zont1x |
|           31 |      770 | 2025-02-08 | Natus Vincere     | W   | 1.000      | 1.000        | 0.602 (0.602)    | 0.434 (0.434)    | 1 (1.000) |     7.73 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      857 | 2025-02-07 | Virtus.pro        | W   | 1.000      | 1.000        | 0.299 (0.299)    | 0.419 (0.419)    | 1 (1.000) |     5.29 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |     1012 | 2025-02-04 | GamerLegion       | W   | 1.000      | 1.000        | -                | 0.475 (0.475)    | 1 (1.000) |     3.77 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |     1065 | 2025-02-04 | Team Liquid       | W   | 1.000      | 1.000        | 0.109 (0.109)    | 0.198 (0.198)    | 1 (1.000) |     0.63 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |     1093 | 2025-02-03 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -24.66 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |     1110 | 2025-02-02 | Astralis          | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |     8.57 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1230 | 2025-01-26 | Eternal Fire      | W   | 0.956      | 0.769        | 0.708 (0.520)    | 0.524 (0.385)    | 1 (0.956) |    12.94 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1235 | 2025-01-25 | Natus Vincere     | W   | 0.951      | 0.769        | 0.602 (0.440)    | 0.434 (0.317)    | 1 (0.951) |     6.58 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1275 | 2025-01-23 | HEROIC            | W   | 0.936      | 0.769        | 0.154 (0.111)    | 0.412 (0.297)    | 1 (0.936) |     0.32 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1315 | 2025-01-18 | FlyQuest          | W   | 0.904      | -            | -                | -                | -         |     0.44 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1342 | 2025-01-14 | Fnatic            | W   | 0.877      | 0.363        | -                | 0.508 (0.162)    | -         |     0.28 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     2798 | 2024-11-24 | Ninjas in Pyjamas | W   | 0.535      | -            | -                | -                | 1 (0.535) |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     2813 | 2024-11-24 | Sashi Esport      | W   | 0.534      | -            | -                | -                | 1 (0.534) |     0.10 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     2904 | 2024-11-23 | G2 Esports        | L   | 0.528      | -            | -                | -                | -         |   -13.18 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     3002 | 2024-11-21 | Aurora Gaming     | W   | 0.520      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     3054 | 2024-11-21 | Passion UA        | L   | 0.515      | -            | -                | -                | -         |   -16.17 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     3069 | 2024-11-20 | B8                | W   | 0.513      | -            | -                | -                | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     4012 | 2024-11-03 | G2 Esports        | L   | 0.395      | -            | -                | -                | -         |   -10.16 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     4068 | 2024-11-02 | Astralis          | W   | 0.389      | 1.000        | 0.734 (0.286)    | 0.811 (0.316)    | -         |     4.51 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     4132 | 2024-11-01 | FaZe Clan         | W   | 0.382      | 1.000        | 0.475 (0.181)    | -                | -         |     3.31 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     4175 | 2024-10-31 | G2 Esports        | L   | 0.376      | -            | -                | -                | -         |    -9.89 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     4245 | 2024-10-30 | Team Vitality     | W   | 0.369      | 1.000        | 1.000 (0.369)    | -                | -         |     4.55 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     6035 | 2024-09-27 | G2 Esports        | L   | 0.149      | -            | -                | -                | -         |    -3.96 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     6102 | 2024-09-26 | Astralis          | W   | 0.143      | -            | -                | -                | -         |     1.61 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     6190 | 2024-09-25 | Team Liquid       | L   | 0.137      | -            | -                | -                | -         |    -4.24 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     6535 | 2024-09-20 | Natus Vincere     | L   | 0.102      | -            | -                | -                | -         |    -2.73 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     6661 | 2024-09-18 | Imperial Esports  | W   | 0.089      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     6737 | 2024-09-17 | FURIA             | W   | 0.082      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     7384 | 2024-09-06 | 3DMAX             | W   | 0.010      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     7412 | 2024-09-06 | The MongolZ       | W   | 0.008      | -            | -                | -                | -         |     0.09 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     7501 | 2024-09-05 | MIBR              | L   | 0.002      | -            | -                | -                | -         |    -0.05 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($561,152.25)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $180,000.00    | $180,000.00     |
| 2025-01-26 |      0.956 | $288,125.00    | $275,533.47     |
| 2024-11-03 |      0.395 | $250,000.00    | $98,657.93      |
| 2024-09-29 |      0.162 | $20,000.00     | $3,248.19       |
| 2024-09-22 |      0.116 | $32,000.00     | $3,712.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
