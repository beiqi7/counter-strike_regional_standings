### Roster Details<br />
Team Name: GamerLegion<br />
Roster: PR, REZ, sl3nd, Tauson, ztr<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1576.1<br />
<br />
Final Rank Value (1576.1) = Starting Rank Value (1575.0) + Head To Head Adjustments (1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.247[<sup>2</sup>](#table1)
- LAN Wins: 0.889[<sup>2</sup>](#table1)

The average of these factors is 0.565<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1575.0
- 400 + ( ( 0.565 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1575.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |        1 | 2025-03-03 | TYLOO           | W   | 1.000      | 0.889        | 0.021 (0.019)    | 0.198 (0.176)    | 1 (1.000) |     1.70 | PR, REZ, sl3nd, Tauson, ztr      |
|           21 |      663 | 2025-02-10 | Metizport       | W   | 1.000      | 0.143        | 0.087 (0.012)    | 0.517 (0.074)    | 0 (0.000) |     1.62 | PR, REZ, sl3nd, Tauson, ztr      |
|           20 |      676 | 2025-02-10 | Hesta           | W   | 1.000      | 0.143        | -                | 0.676 (0.097)    | -         |     0.45 | PR, REZ, sl3nd, Tauson, ztr      |
|           19 |      797 | 2025-02-08 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |   -30.87 | PR, REZ, sl3nd, Tauson, ztr      |
|           18 |     1010 | 2025-02-04 | Team Spirit     | L   | 1.000      | -            | -                | -                | -         |    -3.78 | PR, REZ, sl3nd, Tauson, ztr      |
|           17 |     1064 | 2025-02-04 | Astralis        | W   | 1.000      | 1.000        | 0.734 (0.734)    | 0.811 (0.811)    | 1 (1.000) |    23.47 | PR, REZ, sl3nd, Tauson, ztr      |
|           16 |     1094 | 2025-02-03 | The MongolZ     | L   | 1.000      | -            | -                | -                | -         |    -5.01 | PR, REZ, sl3nd, Tauson, ztr      |
|           15 |     1122 | 2025-02-01 | MOUZ            | W   | 0.997      | 1.000        | 1.000 (0.997)    | 0.420 (0.419)    | 1 (0.997) |    27.40 | PR, REZ, sl3nd, Tauson, ztr      |
|           14 |     1169 | 2025-01-30 | PaiN Gaming     | W   | 0.983      | 1.000        | 0.333 (0.328)    | 0.406 (0.399)    | 1 (0.983) |    14.20 | PR, REZ, sl3nd, Tauson, ztr      |
|           13 |     1178 | 2025-01-29 | SAW             | W   | 0.976      | 1.000        | 0.315 (0.307)    | 0.333 (0.325)    | 1 (0.976) |     8.40 | PR, REZ, sl3nd, Tauson, ztr      |
|           12 |     1331 | 2025-01-17 | PaiN Gaming     | L   | 0.896      | -            | -                | -                | -         |   -16.57 | PR, REZ, sl3nd, Tauson, ztr      |
|           11 |     3124 | 2024-11-20 | BetBoom Team    | W   | 0.510      | 0.143        | 0.122 (0.009)    | -                | 1 (0.510) |     1.12 | FL4MUS, sl3nd, Tauson, volt, ztr |
|           10 |     3127 | 2024-11-20 | SINNERS Esports | W   | 0.508      | -            | -                | -                | 1 (0.508) |     0.74 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            9 |     3168 | 2024-11-19 | Team Falcons    | W   | 0.501      | -            | -                | -                | 1 (0.501) |     0.19 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            8 |     3210 | 2024-11-18 | UNiTY esports   | W   | 0.495      | -            | -                | -                | 1 (0.495) |     0.33 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            7 |     3264 | 2024-11-17 | Dynamo Eclot    | L   | 0.488      | -            | -                | -                | -         |   -14.28 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            6 |     3281 | 2024-11-16 | Team Vitality   | L   | 0.487      | -            | -                | -                | -         |    -2.00 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            5 |     5175 | 2024-10-11 | GUN5 Esports    | L   | 0.243      | -            | -                | -                | -         |    -7.37 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            4 |     5425 | 2024-10-06 | Passion UA      | W   | 0.211      | 0.435        | 0.027 (0.002)    | 0.495 (0.045)    | -         |     0.22 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            3 |     5442 | 2024-10-06 | 9Pandas         | W   | 0.210      | 0.435        | 0.104 (0.009)    | 0.628 (0.057)    | -         |     0.33 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            2 |     5482 | 2024-10-05 | B8              | W   | 0.204      | 0.435        | 0.148 (0.013)    | 0.790 (0.070)    | -         |     0.77 | FL4MUS, sl3nd, Tauson, volt, ztr |
|            1 |     5568 | 2024-10-04 | Adventurers     | W   | 0.197      | -            | -                | -                | -         |     0.09 | FL4MUS, sl3nd, Tauson, volt, ztr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,633.85)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-09 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-10-06 |      0.211 | $22,000.00     | $4,633.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
