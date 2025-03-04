### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, FL4MUS, ICY<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1632.8<br />
<br />
Final Rank Value (1632.8) = Starting Rank Value (1695.4) + Head To Head Adjustments (-62.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.656[<sup>1</sup>](#table2)
- Bounty Collected: 0.634[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.990[<sup>2</sup>](#table1)

The average of these factors is 0.623<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.4
- 400 + ( ( 0.623 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1695.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      375 | 2025-02-18 | MOUZ          | L   | 1.000      | -            | -                | -                | -         |    -7.37 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           30 |      397 | 2025-02-17 | PaiN Gaming   | L   | 1.000      | -            | -                | -                | -         |   -20.44 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           29 |      464 | 2025-02-16 | Wildcard      | W   | 1.000      | 1.000        | 0.161 (0.161)    | 0.279 (0.279)    | 1 (1.000) |     1.71 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           28 |      519 | 2025-02-15 | Complexity    | W   | 1.000      | 1.000        | 0.091 (0.091)    | 0.118 (0.118)    | 1 (1.000) |     0.66 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           27 |      580 | 2025-02-14 | 3DMAX         | L   | 1.000      | -            | -                | -                | -         |   -19.16 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           26 |      855 | 2025-02-07 | Team Spirit   | L   | 1.000      | -            | -                | -                | -         |    -5.30 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           25 |     1023 | 2025-02-04 | Team Vitality | L   | 1.000      | -            | -                | -                | -         |    -6.60 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           24 |     1103 | 2025-02-02 | Eternal Fire  | W   | 1.000      | 1.000        | 0.708 (0.708)    | 0.524 (0.524)    | 1 (1.000) |    24.90 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           23 |     1129 | 2025-02-01 | G2 Esports    | W   | 0.997      | 1.000        | 0.971 (0.968)    | 0.310 (0.309)    | 1 (0.997) |    18.74 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           22 |     1159 | 2025-01-31 | MIBR          | W   | 0.990      | 1.000        | 0.118 (0.117)    | 0.285 (0.283)    | 1 (0.990) |     1.72 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           21 |     1170 | 2025-01-30 | SAW           | W   | 0.983      | 1.000        | 0.315 (0.309)    | 0.333 (0.327)    | 1 (0.983) |     5.33 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           20 |     1181 | 2025-01-29 | PaiN Gaming   | L   | 0.975      | -            | -                | -                | -         |   -20.67 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           19 |     1304 | 2025-01-19 | Team Vitality | L   | 0.911      | -            | -                | -                | -         |    -5.54 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           18 |     1335 | 2025-01-16 | Complexity    | W   | 0.889      | 0.363        | 0.091 (0.029)    | -                | -         |     0.67 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           17 |     2917 | 2024-11-22 | Sashi Esport  | W   | 0.527      | 0.143        | -                | 0.606 (0.046)    | 1 (0.527) |     0.49 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2999 | 2024-11-21 | 9Pandas       | W   | 0.520      | 0.143        | 0.104 (0.008)    | 0.628 (0.047)    | 1 (0.520) |     0.74 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     3040 | 2024-11-21 | TSM           | W   | 0.516      | -            | -                | -                | 1 (0.516) |     0.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           14 |     3065 | 2024-11-20 | Passion UA    | L   | 0.514      | -            | -                | -                | -         |   -15.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           13 |     4523 | 2024-10-25 | OG            | L   | 0.336      | -            | -                | -                | -         |   -10.41 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           12 |     4654 | 2024-10-21 | Team Falcons  | W   | 0.310      | -            | -                | -                | -         |     0.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           11 |     4665 | 2024-10-21 | OG            | L   | 0.309      | -            | -                | -                | -         |    -9.60 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           10 |     5176 | 2024-10-11 | Natus Vincere | L   | 0.243      | -            | -                | -                | -         |    -3.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            9 |     5248 | 2024-10-09 | The MongolZ   | W   | 0.231      | 0.624        | 1.000 (0.144)    | 0.463 (0.067)    | 1 (0.231) |     5.38 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            8 |     5263 | 2024-10-09 | Astralis      | W   | 0.229      | 0.624        | 0.734 (0.105)    | 0.811 (0.116)    | -         |     5.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            7 |     5342 | 2024-10-08 | 9z Team       | W   | 0.223      | -            | -                | -                | -         |     0.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            6 |     5386 | 2024-10-07 | The MongolZ   | L   | 0.217      | -            | -                | -                | -         |    -1.76 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            5 |     6742 | 2024-09-17 | Team Falcons  | L   | 0.082      | -            | -                | -                | -         |    -0.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            4 |     6953 | 2024-09-13 | FURIA         | W   | 0.057      | -            | -                | -                | -         |     0.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            3 |     6990 | 2024-09-13 | Team Falcons  | W   | 0.055      | -            | -                | -                | -         |     0.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            2 |     7035 | 2024-09-12 | Team Liquid   | L   | 0.049      | -            | -                | -                | -         |    -1.43 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            1 |     7124 | 2024-09-10 | RED Canids    | W   | 0.037      | -            | -                | -                | -         |     0.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,690.95)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.30) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $31,250.00     | $31,250.00      |
| 2025-02-09 |      1.000 | $40,000.00     | $40,000.00      |
| 2025-01-19 |      0.911 | $7,500.00      | $6,834.58       |
| 2024-10-13 |      0.257 | $10,000.00     | $2,569.49       |
| 2024-09-22 |      0.116 | $17,500.00     | $2,036.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
