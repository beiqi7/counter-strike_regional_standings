### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: AccuracyTG, dobu, kabal, MiQ, Zesta<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1103.6<br />
<br />
Final Rank Value (1103.6) = Starting Rank Value (1075.7) + Head To Head Adjustments (27.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.462[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.433[<sup>2</sup>](#table1)

The average of these factors is 0.325<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.7
- 400 + ( ( 0.325 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1075.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       33 | 2025-02-27 | HOTU                      | W   | 1.000      | 0.143        | -                | 0.785 (0.112)    | 0 (0.000) |     4.92 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           30 |       39 | 2025-02-26 | Eruption                  | W   | 1.000      | 0.143        | -                | 0.479 (0.068)    | 0 (0.000) |     8.02 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           29 |       94 | 2025-02-25 | The Huns Esports          | W   | 1.000      | 0.143        | 0.029 (0.004)    | -                | 0 (0.000) |     8.42 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           28 |      128 | 2025-02-24 | Gods Reign                | W   | 1.000      | 0.143        | 0.024 (0.003)    | 0.447 (0.064)    | -         |     6.54 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           27 |      156 | 2025-02-23 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -26.40 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           26 |      602 | 2025-02-13 | The Huns Esports          | W   | 1.000      | 0.143        | 0.029 (0.004)    | -                | -         |     8.49 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           25 |      605 | 2025-02-12 | Rare Atom                 | W   | 1.000      | -            | -                | -                | -         |     7.45 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           24 |      618 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -21.48 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           23 |      641 | 2025-02-11 | The Huns Esports          | W   | 1.000      | 0.143        | 0.029 (0.004)    | -                | -         |     8.07 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           22 |      649 | 2025-02-11 | TYLOO                     | W   | 1.000      | -            | -                | -                | -         |    13.18 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           21 |      652 | 2025-02-10 | Rooster                   | W   | 1.000      | -            | -                | -                | -         |     5.00 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           20 |     1418 | 2024-12-29 | Eruption                  | W   | 0.768      | 0.384        | 0.017 (0.005)    | 0.479 (0.141)    | 1 (0.768) |     6.58 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           19 |     1419 | 2024-12-28 | Rare Atom                 | W   | 0.767      | 0.384        | -                | 0.342 (0.101)    | 1 (0.767) |     5.20 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           18 |     1457 | 2024-12-28 | The Huns Esports          | W   | 0.761      | 0.384        | 0.029 (0.009)    | 0.387 (0.113)    | 1 (0.761) |     6.96 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           17 |     1462 | 2024-12-27 | Chinggis Warriors         | W   | 0.761      | 0.384        | 0.019 (0.006)    | 0.449 (0.131)    | 1 (0.761) |     4.43 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           16 |     1479 | 2024-12-26 | Eruption                  | L   | 0.754      | -            | -                | -                | -         |   -17.57 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           15 |     2228 | 2024-12-06 | Chinggis Warriors         | W   | 0.616      | 0.333        | 0.019 (0.004)    | 0.449 (0.092)    | -         |     3.57 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           14 |     2235 | 2024-12-06 | DogEvil                   | W   | 0.614      | 0.333        | -                | 0.554 (0.113)    | -         |     1.32 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           13 |     2294 | 2024-12-04 | Just Swing (Chinese team) | W   | 0.602      | -            | -                | -                | -         |     2.52 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           12 |     2297 | 2024-12-04 | Nomads (Mongolian team)   | W   | 0.601      | -            | -                | -                | -         |     0.85 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           11 |     2302 | 2024-12-03 | IHC Esports               | L   | 0.600      | -            | -                | -                | -         |   -16.77 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|           10 |     2903 | 2024-11-23 | Just Swing (Chinese team) | W   | 0.528      | -            | -                | -                | -         |     2.15 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|            9 |     2912 | 2024-11-22 | CatEvil                   | W   | 0.527      | -            | -                | -                | -         |     0.89 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|            8 |     3131 | 2024-11-19 | IHC Esports               | W   | 0.508      | -            | -                | -                | -         |     1.73 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|            7 |     3132 | 2024-11-19 | Chinggis Warriors         | W   | 0.507      | 0.333        | 0.019 (0.003)    | 0.449 (0.076)    | -         |     3.23 | AccuracyTG, dobu, kabal, MiQ, Zesta  |
|            6 |     6123 | 2024-09-26 | The Huns Esports          | W   | 0.141      | -            | -                | -                | 1 (0.141) |     1.70 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            5 |     6135 | 2024-09-25 | The QUBE Esports          | W   | 0.140      | -            | -                | -                | 1 (0.140) |     0.10 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            4 |     6896 | 2024-09-14 | FURIA                     | L   | 0.063      | -            | -                | -                | -         |    -0.68 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            3 |     6971 | 2024-09-13 | ENCE                      | W   | 0.057      | 0.889        | 0.158 (0.008)    | -                | 1 (0.057) |     0.80 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            2 |     7038 | 2024-09-12 | Team Falcons              | L   | 0.048      | -            | -                | -                | -         |    -1.31 | ANNIHILATION, dobu, kabal, MiQ, yAmi |
|            1 |     7090 | 2024-09-11 | Team Vitality             | L   | 0.042      | -            | -                | -                | -         |    -0.01 | ANNIHILATION, dobu, kabal, MiQ, yAmi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,990.91)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.768 | $12,500.00     | $9,597.83       |
| 2024-12-06 |      0.616 | $7,500.00      | $4,619.11       |
| 2024-11-23 |      0.528 | $7,500.00      | $3,961.82       |
| 2024-09-22 |      0.116 | $7,000.00      | $812.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
