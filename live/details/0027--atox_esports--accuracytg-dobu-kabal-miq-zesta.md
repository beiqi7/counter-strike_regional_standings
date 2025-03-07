### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: AccuracyTG, dobu, kabal, MiQ, Zesta<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1066.7<br />
<br />
Final Rank Value (1066.7) = Starting Rank Value (1032.2) + Head To Head Adjustments (34.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.352[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1032.2
- 400 + ( ( 0.287 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1032.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |       37 | 2025-02-27 | HOTU                      | W   | 0.786      | 0.143        | -                | 0.588 (0.079)    | 0 (0.000) |     3.88 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           24 |       43 | 2025-02-26 | Eruption                  | W   | 0.785      | 0.143        | 0.016 (0.002)    | 0.406 (0.055)    | 0 (0.000) |     7.07 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           23 |       98 | 2025-02-25 | The Huns Esports          | W   | 0.779      | 0.143        | 0.021 (0.003)    | -                | 0 (0.000) |     7.55 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           22 |      134 | 2025-02-24 | Gods Reign                | W   | 0.773      | 0.143        | 0.023 (0.003)    | 0.390 (0.052)    | 0 (0.000) |     7.27 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           21 |      162 | 2025-02-23 | HOTU                      | L   | 0.768      | -            | -                | -                | -         |   -20.29 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           20 |      619 | 2025-02-13 | The Huns Esports          | W   | 0.709      | 0.143        | 0.021 (0.003)    | -                | 0 (0.000) |     7.09 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           19 |      623 | 2025-02-12 | Rare Atom                 | W   | 0.707      | -            | -                | -                | 0 (0.000) |     5.54 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           18 |      636 | 2025-02-12 | Lynn Vision Gaming        | L   | 0.704      | -            | -                | -                | -         |   -14.03 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           17 |      660 | 2025-02-11 | The Huns Esports          | W   | 0.698      | 0.143        | 0.021 (0.003)    | -                | -         |     6.90 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           16 |      668 | 2025-02-11 | TYLOO                     | W   | 0.697      | 0.143        | 0.052 (0.006)    | -                | -         |    14.66 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           15 |      671 | 2025-02-10 | Rooster                   | W   | 0.696      | 0.143        | -                | 0.366 (0.044)    | -         |     3.48 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           14 |     1534 | 2024-12-29 | Eruption                  | W   | 0.452      | 0.384        | 0.016 (0.003)    | 0.406 (0.085)    | 1 (0.543) |     4.75 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           13 |     1535 | 2024-12-28 | Rare Atom                 | W   | 0.452      | 0.384        | 0.008 (0.002)    | 0.339 (0.071)    | 1 (0.542) |     3.44 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           12 |     1575 | 2024-12-28 | The Huns Esports          | W   | 0.447      | 0.384        | 0.021 (0.004)    | 0.280 (0.058)    | 1 (0.536) |     4.89 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           11 |     1580 | 2024-12-27 | Chinggis Warriors         | W   | 0.446      | 0.384        | 0.011 (0.002)    | 0.397 (0.082)    | 1 (0.536) |     2.25 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|           10 |     1598 | 2024-12-26 | Eruption                  | L   | 0.441      | -            | -                | -                | -         |    -9.39 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            9 |     2363 | 2024-12-06 | Chinggis Warriors         | W   | 0.326      | 0.333        | -                | 0.397 (0.052)    | -         |     1.63 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            8 |     2370 | 2024-12-06 | DogEvil                   | W   | 0.325      | 0.333        | -                | 0.521 (0.068)    | -         |     0.64 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            7 |     2429 | 2024-12-04 | Just Swing (Chinese team) | W   | 0.314      | -            | -                | -                | -         |     1.40 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            6 |     2432 | 2024-12-04 | Nomads (Mongolian team)   | W   | 0.314      | -            | -                | -                | -         |     0.57 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            5 |     2437 | 2024-12-03 | IHC Esports               | L   | 0.313      | -            | -                | -                | -         |    -8.53 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            4 |     3024 | 2024-11-23 | Just Swing (Chinese team) | W   | 0.253      | -            | -                | -                | -         |     1.11 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            3 |     3033 | 2024-11-22 | CatEvil                   | W   | 0.252      | -            | -                | -                | -         |     0.45 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            2 |     3254 | 2024-11-19 | IHC Esports               | W   | 0.236      | -            | -                | -                | -         |     0.99 | AccuracyTG, dobu, kabal, MiQ, Zesta |
|            1 |     3255 | 2024-11-19 | Chinggis Warriors         | W   | 0.235      | -            | -                | -                | -         |     1.22 | AccuracyTG, dobu, kabal, MiQ, Zesta |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,993.75)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.543 | $12,500.00     | $6,786.46       |
| 2024-12-06 |      0.391 | $7,500.00      | $2,932.29       |
| 2024-11-23 |      0.303 | $7,500.00      | $2,275.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
