### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, history, kye, nicks, piriajr<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1014.4<br />
<br />
Final Rank Value (1014.4) = Starting Rank Value (989.8) + Head To Head Adjustments (24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.457[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.171[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.8
- 400 + ( ( 0.284 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 989.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |      196 | 2025-02-22 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -15.38 | arT, history, kye, nicks, piriajr |
|           57 |      247 | 2025-02-21 | Team Solid             | W   | 1.000      | 0.371        | 0.027 (0.010)    | 0.616 (0.228)    | 0 (0.000) |    11.20 | arT, history, kye, nicks, piriajr |
|           56 |      608 | 2025-02-12 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.04 | arT, history, kye, nicks, piriajr |
|           55 |      611 | 2025-02-12 | Sharks Esports         | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.683 (0.098)    | 0 (0.000) |    17.37 | arT, history, kye, nicks, piriajr |
|           54 |      629 | 2025-02-11 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.72 | arT, history, kye, nicks, piriajr |
|           53 |      634 | 2025-02-11 | Imperial Esports       | W   | 1.000      | 0.143        | 0.083 (0.012)    | -                | 0 (0.000) |    16.00 | arT, history, kye, nicks, piriajr |
|           52 |      790 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -18.23 | arT, history, kye, nicks, piriajr |
|           51 |     1195 | 2025-01-28 | UNO MILLE              | W   | 0.972      | 0.450        | -                | 0.628 (0.275)    | 0 (0.000) |     7.11 | arT, history, kye, nicks, piriajr |
|           50 |     1199 | 2025-01-28 | UNO MILLE              | L   | 0.972      | -            | -                | -                | -         |   -24.06 | arT, history, kye, nicks, piriajr |
|           49 |     1243 | 2025-01-24 | Yawara E-Sports        | W   | 0.945      | 0.450        | -                | 0.502 (0.213)    | 0 (0.000) |     3.08 | arT, history, kye, nicks, piriajr |
|           48 |     1244 | 2025-01-24 | Yawara E-Sports        | W   | 0.945      | 0.450        | -                | 0.502 (0.213)    | 0 (0.000) |     3.18 | arT, history, kye, nicks, piriajr |
|           47 |     1336 | 2025-01-16 | Eternal Fire           | L   | 0.889      | -            | -                | -                | -         |    -0.25 | arT, history, kye, nicks, piriajr |
|           46 |     2490 | 2024-11-30 | ODDIK                  | W   | 0.578      | 0.371        | 0.033 (0.007)    | 0.552 (0.118)    | 0 (0.000) |     6.17 | arT, kye, nicks, piriajr, zevy    |
|           45 |     2541 | 2024-11-30 | Team Solid             | W   | 0.577      | 0.371        | -                | 0.616 (0.132)    | -         |     5.89 | arT, kye, nicks, piriajr, zevy    |
|           44 |     2583 | 2024-11-29 | TROPA DO TACO          | W   | 0.571      | -            | -                | -                | -         |     3.73 | arT, kye, nicks, piriajr, zevy    |
|           43 |     2661 | 2024-11-27 | Yawara E-Sports        | W   | 0.559      | 0.371        | -                | 0.502 (0.104)    | -         |     2.76 | arT, kye, nicks, piriajr, zevy    |
|           42 |     2772 | 2024-11-24 | Team Solid             | W   | 0.538      | -            | -                | -                | 1 (0.538) |     5.64 | arT, kye, nicks, piriajr, zevy    |
|           41 |     2927 | 2024-11-22 | Sharks Esports         | W   | 0.526      | -            | -                | -                | 1 (0.526) |    10.07 | arT, kye, nicks, piriajr, zevy    |
|           40 |     3637 | 2024-11-09 | Sharks Esports         | W   | 0.439      | 0.371        | 0.064 (0.010)    | 0.683 (0.111)    | -         |     8.74 | arT, kye, nicks, piriajr, zevy    |
|           39 |     3644 | 2024-11-09 | ODDIK                  | W   | 0.438      | -            | -                | -                | -         |     5.30 | arT, kye, nicks, piriajr, zevy    |
|           38 |     3696 | 2024-11-08 | TROPA DO TACO          | W   | 0.432      | -            | -                | -                | -         |     2.77 | arT, kye, nicks, piriajr, zevy    |
|           37 |     3817 | 2024-11-06 | 9z Academy             | W   | 0.416      | -            | -                | -                | -         |     2.17 | arT, kye, nicks, piriajr, zevy    |
|           36 |     3841 | 2024-11-05 | Bounty Hunters Esports | W   | 0.411      | -            | -                | -                | -         |     2.87 | arT, kye, nicks, piriajr, zevy    |
|           35 |     3888 | 2024-11-04 | Galorys Academy        | W   | 0.405      | -            | -                | -                | -         |     1.50 | arT, kye, nicks, piriajr, zevy    |
|           34 |     3953 | 2024-11-03 | América eSports        | W   | 0.398      | -            | -                | -                | -         |     1.37 | arT, kye, nicks, piriajr, zevy    |
|           33 |     4024 | 2024-11-02 | AdalYamigos            | W   | 0.392      | -            | -                | -                | -         |     2.25 | arT, kye, nicks, piriajr, zevy    |
|           32 |     4086 | 2024-11-01 | Sharks Esports         | L   | 0.386      | -            | -                | -                | -         |    -4.07 | arT, kye, nicks, piriajr, zevy    |
|           31 |     4148 | 2024-10-31 | UNO MILLE              | W   | 0.379      | -            | -                | -                | -         |     3.01 | arT, kye, nicks, piriajr, zevy    |
|           30 |     4219 | 2024-10-30 | Intense Game           | W   | 0.371      | -            | -                | -                | -         |     1.90 | arT, kye, nicks, piriajr, zevy    |
|           29 |     4258 | 2024-10-29 | ODDIK                  | W   | 0.366      | -            | -                | -                | -         |     4.40 | arT, kye, nicks, piriajr, zevy    |
|           28 |     4311 | 2024-10-28 | Team Solid             | L   | 0.359      | -            | -                | -                | -         |    -7.52 | arT, kye, nicks, piriajr, zevy    |
|           27 |     4421 | 2024-10-26 | Sharks Esports         | L   | 0.345      | -            | -                | -                | -         |    -3.65 | arT, kye, nicks, piriajr, zevy    |
|           26 |     4823 | 2024-10-18 | Nemiga Gaming          | L   | 0.288      | -            | -                | -                | -         |    -2.95 | arT, kye, nicks, piriajr, zevy    |
|           25 |     4863 | 2024-10-17 | HEROIC                 | L   | 0.282      | -            | -                | -                | -         |    -3.00 | arT, kye, nicks, piriajr, zevy    |
|           24 |     4945 | 2024-10-16 | Aurora Gaming          | W   | 0.274      | 0.624        | -                | 0.671 (0.115)    | 1 (0.274) |     2.96 | arT, kye, nicks, piriajr, zevy    |
|           23 |     5306 | 2024-10-08 | InSanitY Sports        | L   | 0.225      | -            | -                | -                | -         |    -5.70 | arT, kye, nicks, piriajr, zevy    |
|           22 |     5314 | 2024-10-08 | InSanitY Sports        | L   | 0.225      | -            | -                | -                | -         |    -5.77 | arT, kye, nicks, piriajr, zevy    |
|           21 |     5558 | 2024-10-04 | MIBR                   | W   | 0.198      | 0.450        | 0.118 (0.011)    | -                | -         |     4.28 | arT, kye, nicks, piriajr, zevy    |
|           20 |     5560 | 2024-10-04 | MIBR                   | L   | 0.198      | -            | -                | -                | -         |    -1.98 | arT, kye, nicks, piriajr, zevy    |
|           19 |     5650 | 2024-10-02 | PaiN Gaming            | W   | 0.185      | 0.450        | 0.333 (0.028)    | -                | -         |     5.52 | arT, kye, nicks, piriajr, zevy    |
|           18 |     5656 | 2024-10-02 | PaiN Gaming            | W   | 0.185      | 0.450        | 0.333 (0.028)    | -                | -         |     5.53 | arT, kye, nicks, piriajr, zevy    |
|           17 |     5784 | 2024-09-30 | Imperial Esports       | W   | 0.172      | 0.450        | 0.083 (0.006)    | -                | -         |     2.20 | arT, kye, nicks, piriajr, zevy    |
|           16 |     5787 | 2024-09-30 | Imperial Esports       | W   | 0.171      | 0.450        | 0.083 (0.006)    | -                | -         |     2.22 | arT, kye, nicks, piriajr, zevy    |
|           15 |     5842 | 2024-09-29 | PaiN Gaming            | L   | 0.165      | -            | -                | -                | -         |    -0.24 | arT, kye, nicks, piriajr, zevy    |
|           14 |     5894 | 2024-09-28 | Team Solid             | W   | 0.158      | -            | -                | -                | -         |     1.75 | arT, kye, nicks, piriajr, zevy    |
|           13 |     5902 | 2024-09-28 | RED Canids             | W   | 0.157      | -            | -                | -                | -         |     1.51 | arT, kye, nicks, piriajr, zevy    |
|           12 |     5986 | 2024-09-27 | Dusty Roots            | W   | 0.152      | -            | -                | -                | -         |     1.37 | arT, kye, nicks, piriajr, zevy    |
|           11 |     5991 | 2024-09-27 | Hype Esports           | W   | 0.151      | -            | -                | -                | -         |     0.77 | arT, kye, nicks, piriajr, zevy    |
|           10 |     6002 | 2024-09-27 | Floripa Stars          | W   | 0.151      | -            | -                | -                | -         |     0.72 | arT, kye, nicks, piriajr, zevy    |
|            9 |     6151 | 2024-09-25 | RED Canids             | W   | 0.138      | -            | -                | -                | -         |     1.36 | arT, kye, nicks, piriajr, zevy    |
|            8 |     6157 | 2024-09-25 | RED Canids             | W   | 0.138      | -            | -                | -                | -         |     1.37 | arT, kye, nicks, piriajr, zevy    |
|            7 |     6244 | 2024-09-24 | KRÜ Esports            | L   | 0.132      | -            | -                | -                | -         |    -3.49 | arT, kye, nicks, piriajr, zevy    |
|            6 |     6250 | 2024-09-24 | KRÜ Esports            | L   | 0.131      | -            | -                | -                | -         |    -3.51 | arT, kye, nicks, piriajr, zevy    |
|            5 |     6270 | 2024-09-24 | RED Canids             | L   | 0.130      | -            | -                | -                | -         |    -3.38 | arT, kye, nicks, piriajr, zevy    |
|            4 |     6289 | 2024-09-24 | InSanitY Sports        | W   | 0.129      | -            | -                | -                | -         |     0.81 | arT, kye, nicks, piriajr, zevy    |
|            3 |     6329 | 2024-09-23 | ODDIK                  | W   | 0.125      | -            | -                | -                | -         |     1.48 | arT, kye, nicks, piriajr, zevy    |
|            2 |     6331 | 2024-09-23 | ODDIK                  | W   | 0.125      | -            | -                | -                | -         |     1.49 | arT, kye, nicks, piriajr, zevy    |
|            1 |     6363 | 2024-09-23 | RED Canids             | L   | 0.123      | -            | -                | -                | -         |    -3.21 | arT, kye, nicks, piriajr, zevy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,025.38)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-11-30 |      0.578 | $10,000.00     | $5,784.51       |
| 2024-11-24 |      0.538 | $10,342.97     | $5,559.61       |
| 2024-11-09 |      0.439 | $10,000.00     | $4,386.36       |
| 2024-10-27 |      0.351 | $1,226.46      | $430.17         |
| 2024-10-20 |      0.304 | $1,200.00      | $364.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
