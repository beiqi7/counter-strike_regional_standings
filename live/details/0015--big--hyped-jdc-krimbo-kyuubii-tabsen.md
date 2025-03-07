### Roster Details<br />
Team Name: BIG<br />
Roster: hyped, JDC, Krimbo, kyuubii, tabseN<br />
Global Rank: [15](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1340.7<br />
<br />
Final Rank Value (1340.7) = Starting Rank Value (1414.5) + Head To Head Adjustments (-73.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.613[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.675[<sup>2</sup>](#table1)

The average of these factors is 0.460<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.5
- 400 + ( ( 0.460 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1414.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      404 | 2025-02-18 | Astralis         | L   | 0.736      | -            | -                | -                | -         |    -1.60 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           31 |      439 | 2025-02-17 | Wildcard         | W   | 0.731      | 1.000        | 0.162 (0.142)    | 0.216 (0.190)    | 1 (0.877) |     5.58 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           30 |      498 | 2025-02-16 | Eternal Fire     | L   | 0.725      | -            | -                | -                | -         |    -0.93 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           29 |      548 | 2025-02-15 | FlyQuest         | W   | 0.719      | 1.000        | 0.096 (0.083)    | 0.190 (0.164)    | 1 (0.863) |     5.59 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           28 |      600 | 2025-02-14 | MOUZ             | L   | 0.713      | -            | -                | -                | -         |    -0.72 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           27 |      665 | 2025-02-11 | HEROIC           | L   | 0.697      | -            | -                | -                | -         |   -18.07 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           26 |      689 | 2025-02-10 | OG               | W   | 0.693      | 0.143        | 0.041 (0.005)    | 0.989 (0.118)    | 0 (0.000) |     1.75 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           25 |      702 | 2025-02-10 | BC.Game Esports  | L   | 0.692      | -            | -                | -                | -         |   -18.24 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           24 |      817 | 2025-02-08 | 500              | L   | 0.681      | -            | -                | -                | -         |   -18.50 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           23 |     1122 | 2025-02-02 | 3DMAX            | L   | 0.649      | -            | -                | -                | -         |    -5.98 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           22 |     1153 | 2025-02-01 | FaZe Clan        | L   | 0.643      | -            | -                | -                | -         |    -1.72 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           21 |     1186 | 2025-01-31 | HEROIC           | W   | 0.637      | 1.000        | 0.120 (0.091)    | 0.372 (0.284)    | 1 (0.765) |     2.88 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           20 |     1191 | 2025-01-30 | Imperial Female  | W   | 0.632      | 1.000        | 0.146 (0.111)    | 0.159 (0.121)    | 1 (0.759) |     2.52 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           19 |     1204 | 2025-01-29 | Wildcard         | L   | 0.626      | -            | -                | -                | -         |   -16.07 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           18 |     1424 | 2025-01-19 | G2 Esports       | L   | 0.572      | -            | -                | -                | -         |    -7.12 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           17 |     1460 | 2025-01-15 | SAW              | W   | 0.548      | 0.363        | 0.316 (0.075)    | 0.260 (0.062)    | 0 (0.000) |     7.30 | hyped, JDC, Krimbo, kyuubii, tabseN |
|           16 |     1934 | 2024-12-14 | Permitta Esports | L   | 0.371      | -            | -                | -                | -         |   -11.29 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           15 |     3116 | 2024-11-21 | Passion UA       | W   | 0.246      | -            | -                | -                | 1 (0.296) |     0.35 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           14 |     3159 | 2024-11-21 | Team Falcons     | W   | 0.243      | 0.143        | 1.000 (0.042)    | 0.495 (0.021)    | 1 (0.291) |     7.26 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           13 |     3180 | 2024-11-20 | Sashi Esport     | W   | 0.241      | 0.143        | -                | 0.535 (0.022)    | 1 (0.289) |     0.59 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           12 |     3718 | 2024-11-11 | GUN5 Esports     | L   | 0.186      | -            | -                | -                | -         |    -5.36 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           11 |     4187 | 2024-11-02 | ALTERNATE aTTaX  | W   | 0.138      | 0.143        | 0.018 (0.000)    | -                | 0 (0.000) |     0.22 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           10 |     4251 | 2024-11-01 | XPERION NXT      | W   | 0.132      | -            | -                | -                | -         |     0.06 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            9 |     4377 | 2024-10-30 | MYinsanity       | W   | 0.121      | -            | -                | -                | -         |     0.04 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            8 |     4443 | 2024-10-29 | SNOGARD Dragons  | W   | 0.116      | -            | -                | -                | -         |     0.04 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            7 |     4510 | 2024-10-28 | XPERION NXT      | W   | 0.110      | -            | -                | -                | -         |     0.05 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            6 |     4520 | 2024-10-28 | ALTERNATE aTTaX  | W   | 0.109      | -            | -                | -                | -         |     0.17 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            5 |     4637 | 2024-10-26 | OG               | L   | 0.097      | -            | -                | -                | -         |    -2.90 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            4 |     4706 | 2024-10-24 | BESTIA           | W   | 0.088      | 0.934        | 0.057 (0.006)    | 0.459 (0.045)    | -         |     0.13 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            3 |     4725 | 2024-10-24 | Aurora Gaming    | W   | 0.086      | 0.934        | 0.007 (0.001)    | 0.633 (0.061)    | -         |     0.09 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            2 |     4844 | 2024-10-21 | ESports Cologne  | W   | 0.071      | -            | -                | -                | -         |     0.01 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|            1 |     5131 | 2024-10-16 | Wave Esports     | W   | 0.043      | -            | -                | -                | -         |     0.02 | JDC, Krimbo, rigoN, syrsoN, tabseN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($49,128.79)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $31,250.00     | $28,713.83      |
| 2025-02-09 |      0.825 | $10,000.00     | $8,250.00       |
| 2025-01-19 |      0.686 | $10,000.00     | $6,859.95       |
| 2024-12-14 |      0.445 | $3,676.66      | $1,637.39       |
| 2024-11-12 |      0.232 | $1,000.00      | $231.50         |
| 2024-11-03 |      0.172 | $20,000.00     | $3,436.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
