### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, history, kye, nicks, piriajr<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1014.5<br />
<br />
Final Rank Value (1014.5) = Starting Rank Value (989.9) + Head To Head Adjustments (24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.457[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.171[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.9
- 400 + ( ( 0.284 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 989.9


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
|           58 |      194 | 2025-02-22 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -15.38 | arT, history, kye, nicks, piriajr |
|           57 |      245 | 2025-02-21 | Team Solid             | W   | 1.000      | 0.371        | 0.027 (0.010)    | 0.616 (0.228)    | 0 (0.000) |    11.19 | arT, history, kye, nicks, piriajr |
|           56 |      606 | 2025-02-12 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.04 | arT, history, kye, nicks, piriajr |
|           55 |      609 | 2025-02-12 | Sharks Esports         | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.683 (0.098)    | 0 (0.000) |    17.37 | arT, history, kye, nicks, piriajr |
|           54 |      627 | 2025-02-11 | Legacy                 | L   | 1.000      | -            | -                | -                | -         |   -16.72 | arT, history, kye, nicks, piriajr |
|           53 |      632 | 2025-02-11 | Imperial Esports       | W   | 1.000      | 0.143        | 0.083 (0.012)    | -                | 0 (0.000) |    16.00 | arT, history, kye, nicks, piriajr |
|           52 |      788 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |   -18.22 | arT, history, kye, nicks, piriajr |
|           51 |     1193 | 2025-01-28 | UNO MILLE              | W   | 0.973      | 0.450        | -                | 0.628 (0.275)    | 0 (0.000) |     7.11 | arT, history, kye, nicks, piriajr |
|           50 |     1197 | 2025-01-28 | UNO MILLE              | L   | 0.972      | -            | -                | -                | -         |   -24.08 | arT, history, kye, nicks, piriajr |
|           49 |     1241 | 2025-01-24 | Yawara E-Sports        | W   | 0.946      | 0.450        | -                | 0.502 (0.214)    | 0 (0.000) |     3.08 | arT, history, kye, nicks, piriajr |
|           48 |     1242 | 2025-01-24 | Yawara E-Sports        | W   | 0.946      | 0.450        | -                | 0.502 (0.213)    | 0 (0.000) |     3.17 | arT, history, kye, nicks, piriajr |
|           47 |     1334 | 2025-01-16 | Eternal Fire           | L   | 0.890      | -            | -                | -                | -         |    -0.25 | arT, history, kye, nicks, piriajr |
|           46 |     2488 | 2024-11-30 | ODDIK                  | W   | 0.579      | 0.371        | 0.033 (0.007)    | 0.552 (0.118)    | 0 (0.000) |     6.17 | arT, kye, nicks, piriajr, zevy    |
|           45 |     2539 | 2024-11-30 | Team Solid             | W   | 0.577      | 0.371        | -                | 0.616 (0.132)    | -         |     5.89 | arT, kye, nicks, piriajr, zevy    |
|           44 |     2581 | 2024-11-29 | TROPA DO TACO          | W   | 0.572      | -            | -                | -                | -         |     3.73 | arT, kye, nicks, piriajr, zevy    |
|           43 |     2659 | 2024-11-27 | Yawara E-Sports        | W   | 0.559      | 0.371        | -                | 0.502 (0.104)    | -         |     2.76 | arT, kye, nicks, piriajr, zevy    |
|           42 |     2770 | 2024-11-24 | Team Solid             | W   | 0.538      | -            | -                | -                | 1 (0.538) |     5.64 | arT, kye, nicks, piriajr, zevy    |
|           41 |     2925 | 2024-11-22 | Sharks Esports         | W   | 0.526      | -            | -                | -                | 1 (0.526) |    10.07 | arT, kye, nicks, piriajr, zevy    |
|           40 |     3635 | 2024-11-09 | Sharks Esports         | W   | 0.439      | 0.371        | 0.064 (0.010)    | 0.683 (0.111)    | -         |     8.75 | arT, kye, nicks, piriajr, zevy    |
|           39 |     3642 | 2024-11-09 | ODDIK                  | W   | 0.438      | -            | -                | -                | -         |     5.30 | arT, kye, nicks, piriajr, zevy    |
|           38 |     3694 | 2024-11-08 | TROPA DO TACO          | W   | 0.432      | -            | -                | -                | -         |     2.77 | arT, kye, nicks, piriajr, zevy    |
|           37 |     3815 | 2024-11-06 | 9z Academy             | W   | 0.417      | -            | -                | -                | -         |     2.17 | arT, kye, nicks, piriajr, zevy    |
|           36 |     3839 | 2024-11-05 | Bounty Hunters Esports | W   | 0.412      | -            | -                | -                | -         |     2.87 | arT, kye, nicks, piriajr, zevy    |
|           35 |     3886 | 2024-11-04 | Galorys Academy        | W   | 0.406      | -            | -                | -                | -         |     1.50 | arT, kye, nicks, piriajr, zevy    |
|           34 |     3951 | 2024-11-03 | América eSports        | W   | 0.399      | -            | -                | -                | -         |     1.37 | arT, kye, nicks, piriajr, zevy    |
|           33 |     4022 | 2024-11-02 | AdalYamigos            | W   | 0.392      | -            | -                | -                | -         |     2.25 | arT, kye, nicks, piriajr, zevy    |
|           32 |     4084 | 2024-11-01 | Sharks Esports         | L   | 0.386      | -            | -                | -                | -         |    -4.07 | arT, kye, nicks, piriajr, zevy    |
|           31 |     4146 | 2024-10-31 | UNO MILLE              | W   | 0.379      | -            | -                | -                | -         |     3.01 | arT, kye, nicks, piriajr, zevy    |
|           30 |     4217 | 2024-10-30 | Intense Game           | W   | 0.371      | -            | -                | -                | -         |     1.90 | arT, kye, nicks, piriajr, zevy    |
|           29 |     4256 | 2024-10-29 | ODDIK                  | W   | 0.366      | -            | -                | -                | -         |     4.41 | arT, kye, nicks, piriajr, zevy    |
|           28 |     4309 | 2024-10-28 | Team Solid             | L   | 0.359      | -            | -                | -                | -         |    -7.53 | arT, kye, nicks, piriajr, zevy    |
|           27 |     4419 | 2024-10-26 | Sharks Esports         | L   | 0.345      | -            | -                | -                | -         |    -3.65 | arT, kye, nicks, piriajr, zevy    |
|           26 |     4821 | 2024-10-18 | Nemiga Gaming          | L   | 0.288      | -            | -                | -                | -         |    -2.95 | arT, kye, nicks, piriajr, zevy    |
|           25 |     4861 | 2024-10-17 | HEROIC                 | L   | 0.282      | -            | -                | -                | -         |    -3.00 | arT, kye, nicks, piriajr, zevy    |
|           24 |     4943 | 2024-10-16 | Aurora Gaming          | W   | 0.274      | 0.624        | -                | 0.671 (0.115)    | 1 (0.274) |     2.96 | arT, kye, nicks, piriajr, zevy    |
|           23 |     5304 | 2024-10-08 | InSanitY Sports        | L   | 0.225      | -            | -                | -                | -         |    -5.71 | arT, kye, nicks, piriajr, zevy    |
|           22 |     5312 | 2024-10-08 | InSanitY Sports        | L   | 0.225      | -            | -                | -                | -         |    -5.78 | arT, kye, nicks, piriajr, zevy    |
|           21 |     5556 | 2024-10-04 | MIBR                   | W   | 0.199      | 0.450        | 0.118 (0.011)    | -                | -         |     4.29 | arT, kye, nicks, piriajr, zevy    |
|           20 |     5558 | 2024-10-04 | MIBR                   | L   | 0.198      | -            | -                | -                | -         |    -1.99 | arT, kye, nicks, piriajr, zevy    |
|           19 |     5648 | 2024-10-02 | PaiN Gaming            | W   | 0.185      | 0.450        | 0.333 (0.028)    | -                | -         |     5.53 | arT, kye, nicks, piriajr, zevy    |
|           18 |     5654 | 2024-10-02 | PaiN Gaming            | W   | 0.185      | 0.450        | 0.333 (0.028)    | -                | -         |     5.54 | arT, kye, nicks, piriajr, zevy    |
|           17 |     5782 | 2024-09-30 | Imperial Esports       | W   | 0.172      | 0.450        | 0.083 (0.006)    | -                | -         |     2.20 | arT, kye, nicks, piriajr, zevy    |
|           16 |     5785 | 2024-09-30 | Imperial Esports       | W   | 0.172      | 0.450        | 0.083 (0.006)    | -                | -         |     2.23 | arT, kye, nicks, piriajr, zevy    |
|           15 |     5840 | 2024-09-29 | PaiN Gaming            | L   | 0.165      | -            | -                | -                | -         |    -0.24 | arT, kye, nicks, piriajr, zevy    |
|           14 |     5892 | 2024-09-28 | Team Solid             | W   | 0.159      | -            | -                | -                | -         |     1.76 | arT, kye, nicks, piriajr, zevy    |
|           13 |     5900 | 2024-09-28 | RED Canids             | W   | 0.158      | -            | -                | -                | -         |     1.52 | arT, kye, nicks, piriajr, zevy    |
|           12 |     5984 | 2024-09-27 | Dusty Roots            | W   | 0.152      | -            | -                | -                | -         |     1.37 | arT, kye, nicks, piriajr, zevy    |
|           11 |     5989 | 2024-09-27 | Hype Esports           | W   | 0.152      | -            | -                | -                | -         |     0.77 | arT, kye, nicks, piriajr, zevy    |
|           10 |     6000 | 2024-09-27 | Floripa Stars          | W   | 0.151      | -            | -                | -                | -         |     0.72 | arT, kye, nicks, piriajr, zevy    |
|            9 |     6149 | 2024-09-25 | RED Canids             | W   | 0.139      | -            | -                | -                | -         |     1.36 | arT, kye, nicks, piriajr, zevy    |
|            8 |     6155 | 2024-09-25 | RED Canids             | W   | 0.138      | -            | -                | -                | -         |     1.38 | arT, kye, nicks, piriajr, zevy    |
|            7 |     6242 | 2024-09-24 | KRÜ Esports            | L   | 0.132      | -            | -                | -                | -         |    -3.50 | arT, kye, nicks, piriajr, zevy    |
|            6 |     6248 | 2024-09-24 | KRÜ Esports            | L   | 0.132      | -            | -                | -                | -         |    -3.52 | arT, kye, nicks, piriajr, zevy    |
|            5 |     6268 | 2024-09-24 | RED Canids             | L   | 0.131      | -            | -                | -                | -         |    -3.39 | arT, kye, nicks, piriajr, zevy    |
|            4 |     6287 | 2024-09-24 | InSanitY Sports        | W   | 0.130      | -            | -                | -                | -         |     0.81 | arT, kye, nicks, piriajr, zevy    |
|            3 |     6327 | 2024-09-23 | ODDIK                  | W   | 0.125      | -            | -                | -                | -         |     1.48 | arT, kye, nicks, piriajr, zevy    |
|            2 |     6329 | 2024-09-23 | ODDIK                  | W   | 0.125      | -            | -                | -                | -         |     1.49 | arT, kye, nicks, piriajr, zevy    |
|            1 |     6361 | 2024-09-23 | RED Canids             | L   | 0.124      | -            | -                | -                | -         |    -3.22 | arT, kye, nicks, piriajr, zevy    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,037.59)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-11-30 |      0.579 | $10,000.00     | $5,788.24       |
| 2024-11-24 |      0.538 | $10,342.97     | $5,563.46       |
| 2024-11-09 |      0.439 | $10,000.00     | $4,390.09       |
| 2024-10-27 |      0.351 | $1,226.46      | $430.63         |
| 2024-10-20 |      0.304 | $1,200.00      | $365.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
