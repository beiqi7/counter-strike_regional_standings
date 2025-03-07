### Roster Details<br />
Team Name: Passion UA<br />
Roster: jackasmo, jambo, Kvem, Topa, zeRRoFIX<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  905.5<br />
<br />
Final Rank Value (905.5) = Starting Rank Value (875.1) + Head To Head Adjustments (30.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.330[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.145[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 875.1
- 400 + ( ( 0.215 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 875.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      283 | 2025-02-21 | GUN5 Esports           | L   | 0.754      | -            | -                | -                | -         |    -9.90 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           33 |      575 | 2025-02-14 | ENCE                   | L   | 0.716      | -            | -                | -                | -         |   -10.76 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           32 |      613 | 2025-02-13 | Betclic Apogee Esports | W   | 0.710      | 0.435        | 0.012 (0.004)    | 0.528 (0.195)    | 0 (0.000) |    11.26 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           31 |      820 | 2025-02-08 | HEROIC                 | L   | 0.681      | -            | -                | -                | -         |    -6.37 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           30 |      896 | 2025-02-07 | BetBoom Team           | W   | 0.675      | 0.143        | 0.101 (0.012)    | 0.308 (0.036)    | 0 (0.000) |    13.86 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           29 |     1000 | 2025-02-05 | BetBoom Team           | W   | 0.665      | 0.143        | 0.101 (0.011)    | 0.308 (0.035)    | 0 (0.000) |    14.32 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           28 |     1010 | 2025-02-05 | Metizport              | W   | 0.664      | 0.143        | 0.062 (0.007)    | 0.367 (0.042)    | 0 (0.000) |    13.65 | jackasmo, jambo, Kvem, Topa, zeRRoFIX               |
|           27 |     2935 | 2024-11-23 | Astralis               | W   | 0.257      | 0.143        | 0.788 (0.035)    | 0.807 (0.036)    | 1 (0.309) |     8.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           26 |     3031 | 2024-11-22 | Team Falcons           | L   | 0.252      | -            | -                | -                | -         |    -0.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           25 |     3116 | 2024-11-21 | BIG                    | L   | 0.246      | -            | -                | -                | -         |    -0.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           24 |     3173 | 2024-11-21 | Team Spirit            | W   | 0.242      | 0.143        | 1.000 (0.041)    | 0.503 (0.021)    | 1 (0.290) |     7.60 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           23 |     3186 | 2024-11-20 | Virtus.pro             | W   | 0.241      | 0.143        | 0.320 (0.013)    | 0.352 (0.015)    | 1 (0.289) |     7.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           22 |     3216 | 2024-11-20 | Nexus Gaming           | L   | 0.238      | -            | -                | -                | -         |    -1.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           21 |     3541 | 2024-11-14 | Permitta Esports       | L   | 0.205      | -            | -                | -                | -         |    -3.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           20 |     3568 | 2024-11-14 | BC.Game Esports        | L   | 0.204      | -            | -                | -                | -         |    -3.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           19 |     3590 | 2024-11-13 | Lilmix                 | W   | 0.199      | -            | -                | -                | 0 (0.000) |     1.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           18 |     3939 | 2024-11-06 | Ex-Soul's Heart Esport | L   | 0.160      | -            | -                | -                | -         |    -4.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           17 |     3962 | 2024-11-06 | 500                    | L   | 0.158      | -            | -                | -                | -         |    -1.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           16 |     4047 | 2024-11-04 | THE SPELLS             | W   | 0.149      | -            | -                | -                | 0 (0.000) |     0.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           15 |     4359 | 2024-10-30 | XP Academy             | L   | 0.122      | -            | -                | -                | -         |    -3.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           14 |     4464 | 2024-10-29 | Los kogutos            | L   | 0.114      | -            | -                | -                | -         |    -1.77 | Burmylov, fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|           13 |     4556 | 2024-10-27 | Los kogutos            | L   | 0.104      | -            | -                | -                | -         |    -1.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           12 |     4687 | 2024-10-25 | ALTERNATE aTTaX        | W   | 0.092      | 0.372        | 0.018 (0.001)    | 0.298 (0.012)    | 0 (0.000) |     1.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           11 |     4699 | 2024-10-25 | 9INE                   | L   | 0.091      | -            | -                | -                | -         |    -2.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|           10 |     4745 | 2024-10-23 | HOTU                   | W   | 0.082      | 0.372        | 0.002 (0.000)    | 0.588 (0.022)    | -         |     0.76 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            9 |     4810 | 2024-10-22 | RUSTEC                 | W   | 0.075      | -            | -                | -                | -         |     0.15 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            8 |     4831 | 2024-10-21 | FORZE Reload           | W   | 0.071      | 0.372        | 0.023 (0.001)    | 0.413 (0.013)    | -         |     1.00 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            7 |     4850 | 2024-10-21 | Anonymo Esports        | W   | 0.070      | -            | -                | -                | -         |     0.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            6 |     5262 | 2024-10-13 | Mission Possible       | W   | 0.027      | -            | -                | -                | -         |     0.10 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            5 |     5275 | 2024-10-13 | Ex-ENTERPRISE esports  | W   | 0.026      | -            | -                | -                | -         |     0.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            4 |     5333 | 2024-10-12 | Mission Possible       | L   | 0.021      | -            | -                | -                | -         |    -0.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            3 |     5387 | 2024-10-12 | FAVBET Team            | L   | 0.019      | -            | -                | -                | -         |    -0.29 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            2 |     5417 | 2024-10-11 | Cloud9                 | W   | 0.013      | -            | -                | -                | -         |     0.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |
|            1 |     5435 | 2024-10-10 | RUBY                   | L   | 0.009      | -            | -                | -                | -         |    -0.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,950.10)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      0.866 | $2,000.00      | $1,731.48       |
| 2024-10-27 |      0.125 | $1,244.91      | $155.61         |
| 2024-10-13 |      0.032 | $2,000.00      | $63.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
