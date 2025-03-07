### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, Nicks, rdnzao<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1029.5<br />
<br />
Final Rank Value (1029.5) = Starting Rank Value (1079.0) + Head To Head Adjustments (-49.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.437[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.301[<sup>2</sup>](#table1)

The average of these factors is 0.308<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1079.0
- 400 + ( ( 0.308 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1079.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |       56 | 2025-02-26 | ODDIK                    | L   | 0.784      | -            | -                | -                | -         |   -16.00 | doc, gafolo, koala, Nicks, rdnzao |
|           48 |       59 | 2025-02-26 | ODDIK                    | L   | 0.784      | -            | -                | -                | -         |   -17.01 | doc, gafolo, koala, Nicks, rdnzao |
|           47 |      104 | 2025-02-25 | BESTIA                   | W   | 0.778      | 0.450        | 0.057 (0.024)    | 0.459 (0.193)    | 0 (0.000) |     6.05 | doc, gafolo, koala, Nicks, rdnzao |
|           46 |      106 | 2025-02-25 | BESTIA                   | W   | 0.778      | 0.450        | 0.057 (0.024)    | 0.459 (0.193)    | 0 (0.000) |     6.38 | doc, gafolo, koala, Nicks, rdnzao |
|           45 |      200 | 2025-02-22 | Imperial Esports         | L   | 0.762      | -            | -                | -                | -         |   -14.54 | doc, gafolo, koala, Nicks, rdnzao |
|           44 |      221 | 2025-02-22 | ODDIK                    | W   | 0.760      | 0.371        | 0.024 (0.008)    | 0.568 (0.192)    | 0 (0.000) |     7.26 | doc, gafolo, koala, Nicks, rdnzao |
|           43 |      270 | 2025-02-21 | Swingers                 | W   | 0.755      | 0.371        | -                | 0.210 (0.071)    | 0 (0.000) |     3.74 | doc, gafolo, koala, Nicks, rdnzao |
|           42 |      304 | 2025-02-20 | Bounty Hunters Esports   | W   | 0.750      | 0.371        | -                | 0.693 (0.231)    | -         |     3.93 | doc, gafolo, koala, Nicks, rdnzao |
|           41 |      347 | 2025-02-19 | Bounty Hunters Esports   | W   | 0.745      | 0.450        | 0.003 (0.001)    | 0.693 (0.279)    | -         |     4.05 | doc, gafolo, koala, Nicks, rdnzao |
|           40 |      349 | 2025-02-19 | Bounty Hunters Esports   | W   | 0.745      | 0.450        | 0.003 (0.001)    | 0.693 (0.279)    | -         |     4.21 | doc, gafolo, koala, Nicks, rdnzao |
|           39 |      629 | 2025-02-12 | Fluxo                    | L   | 0.705      | -            | -                | -                | -         |   -13.74 | doc, gafolo, koala, Nicks, rdnzao |
|           38 |      648 | 2025-02-11 | Imperial Esports         | W   | 0.701      | 0.143        | 0.061 (0.007)    | -                | -         |     8.20 | doc, gafolo, koala, Nicks, rdnzao |
|           37 |      653 | 2025-02-11 | Legacy                   | L   | 0.700      | -            | -                | -                | -         |   -15.36 | doc, gafolo, koala, Nicks, rdnzao |
|           36 |      733 | 2025-02-09 | MIBR                     | L   | 0.688      | -            | -                | -                | -         |    -6.20 | doc, gafolo, koala, Nicks, rdnzao |
|           35 |      795 | 2025-02-08 | BESTIA                   | W   | 0.682      | 0.143        | 0.057 (0.007)    | -                | -         |     5.84 | doc, gafolo, koala, Nicks, rdnzao |
|           34 |     1227 | 2025-01-28 | Floripa Stars            | W   | 0.623      | 0.450        | -                | 0.278 (0.093)    | -         |     1.41 | doc, gafolo, koala, Nicks, rdnzao |
|           33 |     1228 | 2025-01-28 | Floripa Stars            | W   | 0.622      | 0.450        | -                | 0.278 (0.093)    | -         |     1.43 | doc, gafolo, koala, Nicks, rdnzao |
|           32 |     1259 | 2025-01-27 | TROPA DO TACO            | W   | 0.617      | -            | -                | -                | -         |     0.47 | doc, gafolo, koala, Nicks, rdnzao |
|           31 |     1264 | 2025-01-27 | TROPA DO TACO            | W   | 0.617      | -            | -                | -                | -         |     0.47 | doc, gafolo, koala, Nicks, rdnzao |
|           30 |     2192 | 2024-12-08 | NRG                      | L   | 0.340      | -            | -                | -                | -         |    -5.75 | doc, gafolo, hoax, koala, rdnzao  |
|           29 |     2193 | 2024-12-08 | BLUEJAYS                 | W   | 0.339      | -            | -                | -                | 1 (0.407) |     2.74 | doc, gafolo, hoax, koala, rdnzao  |
|           28 |     2196 | 2024-12-08 | NRG                      | L   | 0.339      | -            | -                | -                | -         |    -5.86 | doc, gafolo, hoax, koala, rdnzao  |
|           27 |     2274 | 2024-12-07 | Nouns Esports            | W   | 0.334      | 0.384        | 0.008 (0.001)    | 0.649 (0.100)    | 1 (0.401) |     3.00 | doc, gafolo, hoax, koala, rdnzao  |
|           26 |     2288 | 2024-12-07 | Bad News Capybaras       | W   | 0.333      | -            | -                | -                | 1 (0.400) |     1.19 | doc, gafolo, hoax, koala, rdnzao  |
|           25 |     2345 | 2024-12-06 | MIGHT                    | W   | 0.328      | -            | -                | -                | 1 (0.394) |     1.22 | doc, gafolo, hoax, koala, rdnzao  |
|           24 |     2633 | 2024-11-30 | ODDIK                    | L   | 0.294      | -            | -                | -                | -         |    -6.65 | doc, gafolo, hoax, koala, rdnzao  |
|           23 |     2721 | 2024-11-29 | Nitro.GG                 | W   | 0.287      | -            | -                | -                | -         |     0.95 | doc, gafolo, hoax, koala, rdnzao  |
|           22 |     2755 | 2024-11-28 | 20/70                    | W   | 0.282      | -            | -                | -                | -         |     0.84 | doc, gafolo, hoax, koala, rdnzao  |
|           21 |     3048 | 2024-11-22 | Fluxo                    | L   | 0.251      | -            | -                | -                | -         |    -5.26 | doc, gafolo, hoax, koala, rdnzao  |
|           20 |     3770 | 2024-11-09 | Fluxo                    | L   | 0.178      | -            | -                | -                | -         |    -3.79 | doc, gafolo, hoax, koala, rdnzao  |
|           19 |     3795 | 2024-11-09 | Team Solid               | W   | 0.177      | 0.371        | 0.023 (0.002)    | -                | -         |     1.38 | doc, gafolo, hoax, koala, rdnzao  |
|           18 |     3842 | 2024-11-08 | Game Hunters             | W   | 0.171      | -            | -                | -                | -         |     0.74 | doc, gafolo, hoax, koala, rdnzao  |
|           17 |     3870 | 2024-11-07 | MIBR Academy             | W   | 0.167      | -            | -                | -                | -         |     0.52 | doc, gafolo, hoax, koala, rdnzao  |
|           16 |     3970 | 2024-11-05 | Intense Game             | W   | 0.156      | -            | -                | -                | -         |     0.47 | doc, gafolo, hoax, koala, rdnzao  |
|           15 |     3974 | 2024-11-05 | Bounty Hunters Esports   | W   | 0.156      | -            | -                | -                | -         |     0.73 | doc, gafolo, hoax, koala, rdnzao  |
|           14 |     4026 | 2024-11-04 | ODDIK                    | L   | 0.151      | -            | -                | -                | -         |    -3.48 | doc, gafolo, hoax, koala, rdnzao  |
|           13 |     4089 | 2024-11-03 | Team Solid               | L   | 0.145      | -            | -                | -                | -         |    -3.48 | doc, gafolo, hoax, koala, rdnzao  |
|           12 |     4222 | 2024-11-01 | Fluxo                    | W   | 0.134      | 0.143        | 0.050 (0.001)    | -                | -         |     1.32 | doc, gafolo, hoax, koala, rdnzao  |
|           11 |     4278 | 2024-10-31 | América eSports          | W   | 0.128      | -            | -                | -                | -         |     0.29 | doc, gafolo, hoax, koala, rdnzao  |
|           10 |     4385 | 2024-10-30 | AdalYamigos              | W   | 0.121      | -            | -                | -                | -         |     0.45 | doc, gafolo, hoax, koala, rdnzao  |
|            9 |     4416 | 2024-10-29 | Galorys Academy          | W   | 0.117      | -            | -                | -                | -         |     0.28 | doc, gafolo, hoax, koala, rdnzao  |
|            8 |     4475 | 2024-10-28 | UNO MILLE                | L   | 0.111      | -            | -                | -                | -         |    -2.96 | doc, gafolo, hoax, koala, rdnzao  |
|            7 |     4530 | 2024-10-27 | ODDIK                    | W   | 0.105      | -            | -                | -                | 1 (0.126) |     0.88 | doc, gafolo, hoax, koala, rdnzao  |
|            6 |     4581 | 2024-10-26 | Fluxo                    | W   | 0.100      | -            | -                | -                | 1 (0.120) |     0.98 | doc, gafolo, hoax, koala, rdnzao  |
|            5 |     5085 | 2024-10-16 | Imperial Esports         | L   | 0.044      | -            | -                | -                | -         |    -1.04 | doc, gafolo, hoax, koala, rdnzao  |
|            4 |     5169 | 2024-10-15 | Case Esports             | W   | 0.039      | -            | -                | -                | -         |     0.11 | doc, gafolo, hoax, koala, rdnzao  |
|            3 |     5468 | 2024-10-09 | Players (Brazilian team) | W   | 0.006      | -            | -                | -                | -         |     0.00 | doc, gafolo, hoax, koala, rdnzao  |
|            2 |     5477 | 2024-10-09 | Players (Brazilian team) | W   | 0.005      | -            | -                | -                | -         |     0.00 | doc, gafolo, hoax, koala, rdnzao  |
|            1 |     5549 | 2024-10-08 | Case Esports             | W   | 0.000      | -            | -                | -                | -         |     0.00 | doc, gafolo, hoax, koala, rdnzao  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,794.32)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.914 | $4,000.00      | $3,656.85       |
| 2024-12-08 |      0.408 | $7,500.00      | $3,058.85       |
| 2024-11-30 |      0.354 | $1,500.00      | $530.31         |
| 2024-11-24 |      0.313 | $3,878.61      | $1,212.52       |
| 2024-11-09 |      0.214 | $4,000.00      | $854.91         |
| 2024-10-27 |      0.126 | $10,512.48     | $1,322.82       |
| 2024-10-20 |      0.079 | $2,000.00      | $158.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
