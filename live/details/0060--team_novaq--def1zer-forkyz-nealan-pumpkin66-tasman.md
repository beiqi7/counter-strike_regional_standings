### Roster Details<br />
Team Name: Team Novaq<br />
Roster: def1zer, forkyz, neaLaN, Pumpkin66, tasman<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.1<br />
<br />
Final Rank Value (908.1) = Starting Rank Value (944.6) + Head To Head Adjustments (-36.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.275[<sup>2</sup>](#table1)

The average of these factors is 0.247<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.6
- 400 + ( ( 0.247 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 944.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      185 | 2025-02-23 | Roler Coaster   | L   | 0.765      | -            | -                | -                | -         |   -21.20 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           15 |      209 | 2025-02-22 | Openai chatgpt  | W   | 0.761      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.18 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           14 |      311 | 2025-02-20 | POLET           | L   | 0.749      | -            | -                | -                | -         |   -21.43 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           13 |      789 | 2025-02-08 | Little Red Door | L   | 0.682      | -            | -                | -                | -         |   -19.11 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           12 |      801 | 2025-02-08 | Fnatic          | W   | 0.682      | 0.143        | 0.025 (0.003)    | 0.471 (0.055)    | 0 (0.000) |    13.12 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           11 |      874 | 2025-02-07 | Iberian Soul    | W   | 0.677      | 0.143        | 0.014 (0.002)    | 0.620 (0.072)    | 0 (0.000) |     6.97 | def1zer, forkyz, neaLaN, Pumpkin66, tasman |
|           10 |     1883 | 2024-12-15 | AK BARS         | W   | 0.375      | 0.333        | 0.006 (0.001)    | 0.078 (0.012)    | 1 (0.450) |     2.12 | dako, def1zer, forkyz, Pumpkin66, tasman   |
|            9 |     2547 | 2024-12-01 | MYSKILL         | W   | 0.299      | 0.143        | 0.001 (0.000)    | 0.085 (0.004)    | 0 (0.000) |     1.50 | dako, def1zer, forkyz, Pumpkin66, tasman   |
|            8 |     2560 | 2024-12-01 | ALLINNERS       | L   | 0.299      | -            | -                | -                | -         |    -7.82 | dako, def1zer, forkyz, Pumpkin66, tasman   |
|            7 |     2579 | 2024-12-01 | Mix52           | W   | 0.299      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | -         |     0.49 | dako, def1zer, forkyz, Pumpkin66, tasman   |
|            6 |     3430 | 2024-11-16 | GTZ.ESPORTS     | L   | 0.216      | -            | -                | -                | -         |    -1.42 | dako, def1zer, demente, neaLaN, Pumpkin66  |
|            5 |     3497 | 2024-11-15 | KONO.ECF        | W   | 0.210      | 0.617        | 0.047 (0.007)    | 0.597 (0.093)    | 1 (0.252) |     2.98 | dako, def1zer, demente, neaLaN, Pumpkin66  |
|            4 |     3504 | 2024-11-15 | GnG x Amazigh   | W   | 0.209      | 0.617        | 0.000 (0.000)    | 0.015 (0.002)    | 1 (0.251) |     0.33 | dako, def1zer, demente, neaLaN, Pumpkin66  |
|            3 |     3544 | 2024-11-14 | Team USA        | W   | 0.205      | 0.617        | 0.000 (0.000)    | -                | 1 (0.246) |     0.28 | dako, def1zer, demente, neaLaN, Pumpkin66  |
|            2 |     3555 | 2024-11-14 | Team Latvia     | W   | 0.204      | 0.617        | -                | 0.045 (0.007)    | 1 (0.245) |     0.82 | dako, def1zer, demente, neaLaN, Pumpkin66  |
|            1 |     3563 | 2024-11-14 | Nexus Gaming    | W   | 0.204      | 0.617        | 0.161 (0.024)    | 0.539 (0.081)    | 1 (0.245) |     4.68 | dako, def1zer, demente, neaLaN, Pumpkin66  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,565.63)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.450 | $5,000.00      | $2,251.39       |
| 2024-11-17 |      0.265 | $12,500.00     | $3,314.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
