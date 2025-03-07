### Roster Details<br />
Team Name: Imperial Female<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1000.1<br />
<br />
Final Rank Value (1000.1) = Starting Rank Value (1046.7) + Head To Head Adjustments (-46.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.545[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.312[<sup>2</sup>](#table1)

The average of these factors is 0.293<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.7
- 400 + ( ( 0.293 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1046.7


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
|           17 |       29 | 2025-02-27 | Prototype Blaze       | W   | 0.788      | 0.338        | 0.047 (0.015)    | 0.197 (0.063)    | 0 (0.000) |     7.42 | ANa, Kat, tory, twenty3, zAAz   |
|           16 |      477 | 2025-02-16 | Complexity            | L   | 0.726      | -            | -                | -                | -         |   -13.68 | ANa, Kat, tory, twenty3, zAAz   |
|           15 |      541 | 2025-02-15 | MIBR                  | L   | 0.720      | -            | -                | -                | -         |    -5.72 | ANa, Kat, tory, twenty3, zAAz   |
|           14 |      585 | 2025-02-14 | Eternal Fire          | L   | 0.715      | -            | -                | -                | -         |    -0.14 | ANa, Kat, tory, twenty3, zAAz   |
|           13 |      999 | 2025-02-05 | Nemiga Gaming         | L   | 0.665      | -            | -                | -                | -         |   -12.39 | ANa, Kat, tory, twenty3, zAAz   |
|           12 |     1009 | 2025-02-05 | PARIVISION            | L   | 0.664      | -            | -                | -                | -         |   -17.49 | ANa, Kat, tory, twenty3, zAAz   |
|           11 |     1191 | 2025-01-30 | BIG                   | L   | 0.632      | -            | -                | -                | -         |    -2.52 | ANa, bubble, Kat, twenty3, zAAz |
|           10 |     1203 | 2025-01-29 | FURIA                 | L   | 0.626      | -            | -                | -                | -         |    -8.68 | ANa, bubble, Kat, twenty3, zAAz |
|            9 |     1454 | 2025-01-16 | Natus Vincere         | L   | 0.555      | -            | -                | -                | -         |    -0.98 | ANa, Kat, tory, twenty3, zAAz   |
|            8 |     2544 | 2024-12-01 | FURIA Female          | L   | 0.300      | -            | -                | -                | -         |    -5.99 | ANa, Kat, tory, twenty3, zAAz   |
|            7 |     2610 | 2024-11-30 | FURIA Female          | W   | 0.294      | 0.143        | 0.055 (0.003)    | 0.170 (0.009)    | 1 (0.353) |     3.41 | ANa, Kat, tory, twenty3, zAAz   |
|            6 |     2709 | 2024-11-29 | Tak tak queota        | W   | 0.288      | 0.143        | 0.003 (0.000)    | 0.060 (0.003)    | 1 (0.345) |     0.86 | ANa, Kat, tory, twenty3, zAAz   |
|            5 |     2904 | 2024-11-24 | FURIA Female          | W   | 0.260      | 0.524        | 0.055 (0.009)    | 0.170 (0.028)    | 1 (0.312) |     3.06 | ANa, Kat, tory, twenty3, zAAz   |
|            4 |     2930 | 2024-11-24 | BIG EQUIPA            | W   | 0.258      | 0.524        | 0.019 (0.003)    | 0.023 (0.004)    | 1 (0.310) |     1.50 | ANa, Kat, tory, twenty3, zAAz   |
|            3 |     3088 | 2024-11-22 | MIBR Female           | W   | 0.249      | 0.524        | 0.013 (0.002)    | 0.133 (0.021)    | 1 (0.298) |     1.35 | ANa, Kat, tory, twenty3, zAAz   |
|            2 |     3112 | 2024-11-22 | NAVI Javelins         | W   | 0.247      | 0.524        | 0.101 (0.016)    | 0.113 (0.018)    | 1 (0.296) |     3.23 | ANa, Kat, tory, twenty3, zAAz   |
|            1 |     4992 | 2024-10-18 | Nomercy (Female team) | W   | 0.054      | 0.328        | 0.003 (0.000)    | 0.290 (0.006)    | 0 (0.000) |     0.18 | ANa, Kat, tory, twenty3, zAAz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,630.28)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $12,500.00     | $11,485.53      |
| 2025-02-09 |      0.825 | $2,500.00      | $2,062.50       |
| 2024-12-01 |      0.360 | $4,184.56      | $1,505.86       |
| 2024-11-24 |      0.312 | $50,000.00     | $15,576.39      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
