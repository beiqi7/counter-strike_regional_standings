### Roster Details<br />
Team Name: Legacy<br />
Roster: dumau, latto, lux, n1ssim, saadzin<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  899.4<br />
<br />
Final Rank Value (899.4) = Starting Rank Value (854.8) + Head To Head Adjustments (44.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.401[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.8
- 400 + ( ( 0.206 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 854.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |       22 | 2025-02-27 | Akimbo Esports     | W   | 0.790      | 0.477        | -                | 0.512 (0.232)    | 0 (0.000) |     5.62 | dumau, latto, lux, n1ssim, saadzin   |
|           34 |       23 | 2025-02-27 | Akimbo Esports     | W   | 0.790      | 0.477        | -                | 0.512 (0.232)    | 0 (0.000) |     5.91 | dumau, latto, lux, n1ssim, saadzin   |
|           33 |       48 | 2025-02-26 | LAG Gaming         | W   | 0.784      | -            | -                | -                | 0 (0.000) |     3.19 | dumau, latto, lux, n1ssim, saadzin   |
|           32 |       53 | 2025-02-26 | LAG Gaming         | W   | 0.784      | -            | -                | -                | 0 (0.000) |     3.29 | dumau, latto, lux, n1ssim, saadzin   |
|           31 |      249 | 2025-02-21 | Imperial Esports   | L   | 0.756      | -            | -                | -                | -         |    -9.56 | dumau, latto, lux, n1ssim, saadzin   |
|           30 |      303 | 2025-02-20 | UNO MILLE          | W   | 0.751      | 0.371        | 0.008 (0.003)    | 0.527 (0.176)    | 0 (0.000) |     8.19 | dumau, latto, lux, n1ssim, saadzin   |
|           29 |      340 | 2025-02-19 | Vagrants           | L   | 0.746      | -            | -                | -                | -         |   -15.51 | dumau, latto, lux, n1ssim, saadzin   |
|           28 |      345 | 2025-02-19 | Vagrants           | L   | 0.745      | -            | -                | -                | -         |   -16.43 | dumau, latto, lux, n1ssim, saadzin   |
|           27 |      378 | 2025-02-18 | Chill Guys         | L   | 0.740      | -            | -                | -                | -         |   -13.62 | dumau, latto, lux, n1ssim, saadzin   |
|           26 |      383 | 2025-02-18 | Chill Guys         | L   | 0.740      | -            | -                | -                | -         |   -14.51 | dumau, latto, lux, n1ssim, saadzin   |
|           25 |      626 | 2025-02-12 | Fluxo              | W   | 0.706      | 0.143        | 0.050 (0.006)    | -                | 0 (0.000) |    12.16 | dumau, latto, lux, n1ssim, saadzin   |
|           24 |      647 | 2025-02-11 | Fluxo              | W   | 0.701      | 0.143        | 0.050 (0.006)    | -                | 0 (0.000) |    12.40 | dumau, latto, lux, n1ssim, saadzin   |
|           23 |      653 | 2025-02-11 | Sharks Esports     | W   | 0.700      | 0.143        | 0.051 (0.006)    | 0.636 (0.076)    | 0 (0.000) |    15.36 | dumau, latto, lux, n1ssim, saadzin   |
|           22 |      764 | 2025-02-08 | BESTIA             | W   | 0.683      | 0.143        | 0.057 (0.007)    | 0.459 (0.054)    | 0 (0.000) |    10.63 | dumau, latto, lux, n1ssim, saadzin   |
|           21 |      766 | 2025-02-08 | LaChampionsLiga    | W   | 0.683      | -            | -                | -                | -         |     4.23 | dumau, latto, lux, n1ssim, saadzin   |
|           20 |      785 | 2025-02-08 | MIBR               | L   | 0.683      | -            | -                | -                | -         |    -2.85 | dumau, latto, lux, n1ssim, saadzin   |
|           19 |      841 | 2025-02-07 | UNO MILLE          | W   | 0.678      | 0.143        | 0.008 (0.001)    | 0.527 (0.061)    | -         |     7.04 | dumau, latto, lux, n1ssim, saadzin   |
|           18 |      887 | 2025-02-07 | Team Solid         | W   | 0.677      | 0.143        | 0.023 (0.003)    | 0.624 (0.072)    | -         |    10.41 | dumau, latto, lux, n1ssim, saadzin   |
|           17 |      965 | 2025-02-05 | Team Solid         | W   | 0.666      | 0.143        | 0.023 (0.003)    | 0.624 (0.071)    | -         |    10.64 | dumau, latto, lux, n1ssim, saadzin   |
|           16 |      988 | 2025-02-05 | Familia Maquininha | W   | 0.666      | -            | -                | -                | -         |     5.68 | dumau, latto, lux, n1ssim, saadzin   |
|           15 |     1466 | 2025-01-12 | BESTIA             | L   | 0.533      | -            | -                | -                | -         |    -7.88 | dumau, latto, lux, n1ssim, saadzin   |
|           14 |     1468 | 2025-01-11 | Dusty Roots        | W   | 0.528      | 0.384        | 0.009 (0.002)    | 0.257 (0.063)    | -         |     6.55 | dumau, latto, lux, n1ssim, saadzin   |
|           13 |     1472 | 2025-01-10 | ShindeN            | W   | 0.522      | 0.384        | -                | 0.274 (0.066)    | -         |     4.49 | dumau, latto, lux, n1ssim, saadzin   |
|           12 |     4615 | 2024-10-26 | Monte              | L   | 0.098      | -            | -                | -                | -         |    -1.75 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           11 |     4675 | 2024-10-25 | PaiN Gaming        | L   | 0.093      | -            | -                | -                | -         |    -0.04 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           10 |     4689 | 2024-10-25 | MIBR               | W   | 0.092      | 0.500        | 0.105 (0.006)    | -                | 1 (0.111) |     2.59 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            9 |     4750 | 2024-10-23 | Imperial Esports   | L   | 0.082      | -            | -                | -                | -         |    -1.18 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            8 |     4776 | 2024-10-23 | Team Falcons       | L   | 0.080      | -            | -                | -                | -         |    -0.01 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            7 |     4933 | 2024-10-19 | NRG                | L   | 0.062      | -            | -                | -                | -         |    -0.54 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            6 |     5020 | 2024-10-17 | M80                | L   | 0.051      | -            | -                | -                | -         |    -0.77 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            5 |     5075 | 2024-10-16 | Nouns Esports      | W   | 0.045      | -            | -                | -                | -         |     0.80 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            4 |     5455 | 2024-10-09 | Familia Maquininha | W   | 0.006      | -            | -                | -                | -         |     0.05 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            3 |     5462 | 2024-10-09 | Familia Maquininha | W   | 0.006      | -            | -                | -                | -         |     0.05 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            2 |     5529 | 2024-10-08 | M80                | L   | 0.001      | -            | -                | -                | -         |    -0.01 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            1 |     5535 | 2024-10-08 | M80                | W   | 0.000      | -            | -                | -                | -         |     0.01 | b4rtiN, dumau, latto, NEKIZ, saadzin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,699.97)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.914 | $750.00        | $685.66         |
| 2025-01-12 |      0.640 | $7,500.00      | $4,797.92       |
| 2024-10-27 |      0.125 | $3,000.00      | $376.39         |
| 2024-10-20 |      0.080 | $10,500.00     | $840.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
