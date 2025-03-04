### Roster Details<br />
Team Name: Team Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1959.1<br />
<br />
Final Rank Value (1959.1) = Starting Rank Value (2000.0) + Head To Head Adjustments (-40.9)<br />

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
|           32 |      713 | 2025-02-09 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |   -16.61 | chopper, donk, magixx, sh1ro, zont1x |
|           31 |      768 | 2025-02-08 | Natus Vincere     | W   | 1.000      | 1.000        | 0.602 (0.602)    | 0.434 (0.434)    | 1 (1.000) |     7.67 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      855 | 2025-02-07 | Virtus.pro        | W   | 1.000      | 1.000        | 0.298 (0.298)    | 0.418 (0.418)    | 1 (1.000) |     5.30 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |     1010 | 2025-02-04 | GamerLegion       | W   | 1.000      | 1.000        | -                | 0.475 (0.475)    | 1 (1.000) |     3.78 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |     1063 | 2025-02-04 | Team Liquid       | W   | 1.000      | 1.000        | 0.109 (0.109)    | 0.198 (0.198)    | 1 (1.000) |     0.63 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |     1091 | 2025-02-03 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |   -24.73 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |     1108 | 2025-02-02 | Astralis          | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |     8.49 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1228 | 2025-01-26 | Eternal Fire      | W   | 0.957      | 0.769        | 0.708 (0.520)    | 0.524 (0.385)    | 1 (0.957) |    12.95 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1233 | 2025-01-25 | Natus Vincere     | W   | 0.951      | 0.769        | 0.602 (0.440)    | 0.434 (0.318)    | 1 (0.951) |     6.53 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1273 | 2025-01-23 | HEROIC            | W   | 0.937      | 0.769        | 0.154 (0.111)    | 0.412 (0.297)    | 1 (0.937) |     0.32 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1313 | 2025-01-18 | FlyQuest          | W   | 0.904      | -            | -                | -                | -         |     0.44 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1340 | 2025-01-14 | Fnatic            | W   | 0.878      | 0.363        | -                | 0.507 (0.162)    | -         |     0.28 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     2796 | 2024-11-24 | Ninjas in Pyjamas | W   | 0.536      | -            | -                | -                | 1 (0.536) |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     2811 | 2024-11-24 | Sashi Esport      | W   | 0.535      | -            | -                | -                | 1 (0.535) |     0.10 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     2902 | 2024-11-23 | G2 Esports        | L   | 0.529      | -            | -                | -                | -         |   -13.18 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     3000 | 2024-11-21 | Aurora Gaming     | W   | 0.520      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     3052 | 2024-11-21 | Passion UA        | L   | 0.515      | -            | -                | -                | -         |   -16.18 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     3067 | 2024-11-20 | B8                | W   | 0.514      | -            | -                | -                | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     4010 | 2024-11-03 | G2 Esports        | L   | 0.395      | -            | -                | -                | -         |   -10.16 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     4066 | 2024-11-02 | Astralis          | W   | 0.389      | 1.000        | 0.734 (0.286)    | 0.811 (0.316)    | -         |     4.47 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     4130 | 2024-11-01 | FaZe Clan         | W   | 0.382      | 1.000        | 0.475 (0.181)    | -                | -         |     3.31 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     4173 | 2024-10-31 | G2 Esports        | L   | 0.377      | -            | -                | -                | -         |    -9.89 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     4243 | 2024-10-30 | Team Vitality     | W   | 0.370      | 1.000        | 1.000 (0.370)    | -                | -         |     4.56 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     6033 | 2024-09-27 | G2 Esports        | L   | 0.149      | -            | -                | -                | -         |    -3.96 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     6100 | 2024-09-26 | Astralis          | W   | 0.143      | -            | -                | -                | -         |     1.60 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     6188 | 2024-09-25 | Team Liquid       | L   | 0.137      | -            | -                | -                | -         |    -4.25 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     6533 | 2024-09-20 | Natus Vincere     | L   | 0.103      | -            | -                | -                | -         |    -2.75 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     6659 | 2024-09-18 | Imperial Esports  | W   | 0.090      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     6735 | 2024-09-17 | FURIA             | W   | 0.083      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     7382 | 2024-09-06 | 3DMAX             | W   | 0.010      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     7410 | 2024-09-06 | The MongolZ       | W   | 0.009      | -            | -                | -                | -         |     0.09 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     7499 | 2024-09-05 | MIBR              | L   | 0.002      | -            | -                | -                | -         |    -0.07 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($561,372.18)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $180,000.00    | $180,000.00     |
| 2025-01-26 |      0.957 | $288,125.00    | $275,640.85     |
| 2024-11-03 |      0.395 | $250,000.00    | $98,751.10      |
| 2024-09-29 |      0.163 | $20,000.00     | $3,255.64       |
| 2024-09-22 |      0.116 | $32,000.00     | $3,724.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
