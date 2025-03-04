### Roster Details<br />
Team Name: Imperial Female<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1032.6<br />
<br />
Final Rank Value (1032.6) = Starting Rank Value (1098.9) + Head To Head Adjustments (-66.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.557[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.417[<sup>2</sup>](#table1)

The average of these factors is 0.336<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1098.9
- 400 + ( ( 0.336 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1098.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       23 | 2025-02-27 | Prototype Blaze       | W   | 1.000      | 0.338        | 0.068 (0.023)    | 0.234 (0.079)    | 0 (0.000) |     9.96 | ANa, Kat, tory, twenty3, zAAz   |
|           23 |      452 | 2025-02-16 | Complexity            | L   | 1.000      | -            | -                | -                | -         |   -18.01 | ANa, Kat, tory, twenty3, zAAz   |
|           22 |      515 | 2025-02-15 | MIBR                  | L   | 1.000      | -            | -                | -                | -         |   -12.24 | ANa, Kat, tory, twenty3, zAAz   |
|           21 |      559 | 2025-02-14 | Eternal Fire          | L   | 1.000      | -            | -                | -                | -         |    -0.28 | ANa, Kat, tory, twenty3, zAAz   |
|           20 |      976 | 2025-02-05 | Nemiga Gaming         | L   | 1.000      | -            | -                | -                | -         |   -14.47 | ANa, Kat, tory, twenty3, zAAz   |
|           19 |      986 | 2025-02-05 | PARIVISION            | L   | 1.000      | -            | -                | -                | -         |   -26.00 | ANa, Kat, tory, twenty3, zAAz   |
|           18 |     1165 | 2025-01-30 | BIG                   | L   | 0.984      | -            | -                | -                | -         |    -4.27 | ANa, bubble, Kat, twenty3, zAAz |
|           17 |     1175 | 2025-01-29 | FURIA                 | L   | 0.977      | -            | -                | -                | -         |   -14.05 | ANa, bubble, Kat, twenty3, zAAz |
|           16 |     1332 | 2025-01-16 | Natus Vincere         | L   | 0.891      | -            | -                | -                | -         |    -0.97 | ANa, Kat, tory, twenty3, zAAz   |
|           15 |     2424 | 2024-12-01 | FURIA Female          | L   | 0.585      | -            | -                | -                | -         |   -12.42 | ANa, Kat, tory, twenty3, zAAz   |
|           14 |     2489 | 2024-11-30 | FURIA Female          | W   | 0.579      | 0.143        | 0.075 (0.006)    | 0.269 (0.022)    | 1 (0.579) |     5.86 | ANa, Kat, tory, twenty3, zAAz   |
|           13 |     2590 | 2024-11-29 | Tak tak queota        | W   | 0.571      | 0.143        | 0.003 (0.000)    | 0.095 (0.008)    | 1 (0.571) |     1.34 | ANa, Kat, tory, twenty3, zAAz   |
|           12 |     2783 | 2024-11-24 | FURIA Female          | W   | 0.537      | 0.524        | 0.075 (0.021)    | 0.269 (0.075)    | 1 (0.537) |     5.60 | ANa, Kat, tory, twenty3, zAAz   |
|           11 |     2808 | 2024-11-24 | BIG EQUIPA            | W   | 0.535      | 0.524        | 0.025 (0.007)    | 0.057 (0.016)    | 1 (0.535) |     2.63 | ANa, Kat, tory, twenty3, zAAz   |
|           10 |     2968 | 2024-11-22 | MIBR Female           | W   | 0.524      | 0.524        | 0.019 (0.005)    | 0.197 (0.054)    | 1 (0.524) |     2.59 | ANa, Kat, tory, twenty3, zAAz   |
|            9 |     2992 | 2024-11-22 | NAVI Javelins         | W   | 0.522      | 0.524        | 0.145 (0.040)    | 0.202 (0.055)    | 1 (0.522) |     7.50 | ANa, Kat, tory, twenty3, zAAz   |
|            8 |     4800 | 2024-10-18 | Nomercy (Female team) | W   | 0.290      | 0.328        | 0.005 (0.000)    | 0.350 (0.033)    | 0 (0.000) |     0.84 | ANa, Kat, tory, twenty3, zAAz   |
|            7 |     5668 | 2024-10-02 | Permitta W            | W   | 0.184      | 0.328        | 0.003 (0.000)    | 0.172 (0.010)    | 0 (0.000) |     0.46 | ANa, Kat, tory, twenty3, zAAz   |
|            6 |     6588 | 2024-09-19 | HSG                   | W   | 0.097      | 0.328        | -                | 0.046 (0.001)    | 0 (0.000) |     0.23 | ANa, Kat, tory, twenty3, zAAz   |
|            5 |     6839 | 2024-09-15 | NAVI Javelins         | L   | 0.069      | -            | -                | -                | -         |    -1.18 | ANa, Kat, tory, twenty3, zAAz   |
|            4 |     6909 | 2024-09-14 | K27 Female            | W   | 0.062      | -            | -                | -                | -         |     0.23 | ANa, Kat, tory, twenty3, zAAz   |
|            3 |     6932 | 2024-09-14 | HSG                   | W   | 0.062      | -            | -                | -                | -         |     0.15 | ANa, Kat, tory, twenty3, zAAz   |
|            2 |     7070 | 2024-09-11 | BIG EQUIPA            | W   | 0.044      | 0.328        | 0.025 (0.000)    | -                | -         |     0.22 | ANa, Kat, tory, twenty3, zAAz   |
|            1 |     7319 | 2024-09-07 | XRayG                 | W   | 0.016      | -            | -                | -                | -         |     0.03 | ANa, Kat, tory, twenty3, zAAz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,357.77)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2025-02-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-12-01 |      0.585 | $4,184.56      | $2,448.56       |
| 2024-11-24 |      0.537 | $50,000.00     | $26,840.50      |
| 2024-09-15 |      0.069 | $1,000.00      | $68.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
