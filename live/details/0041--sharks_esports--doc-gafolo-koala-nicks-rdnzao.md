### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, Nicks, rdnzao<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1048.9<br />
<br />
Final Rank Value (1048.9) = Starting Rank Value (1133.2) + Head To Head Adjustments (-84.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.408[<sup>2</sup>](#table1)

The average of these factors is 0.353<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1133.2
- 400 + ( ( 0.353 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1133.2


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
|           71 |       50 | 2025-02-26 | ODDIK                    | L   | 1.000      | -            | -                | -                | -         |   -19.53 | doc, gafolo, koala, Nicks, rdnzao |
|           70 |       53 | 2025-02-26 | ODDIK                    | L   | 1.000      | -            | -                | -                | -         |   -21.18 | doc, gafolo, koala, Nicks, rdnzao |
|           69 |       98 | 2025-02-25 | BESTIA                   | W   | 1.000      | 0.450        | 0.081 (0.037)    | 0.433 (0.195)    | 0 (0.000) |     9.02 | doc, gafolo, koala, Nicks, rdnzao |
|           68 |      100 | 2025-02-25 | BESTIA                   | W   | 1.000      | 0.450        | 0.081 (0.037)    | 0.433 (0.195)    | 0 (0.000) |     9.71 | doc, gafolo, koala, Nicks, rdnzao |
|           67 |      192 | 2025-02-22 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -17.19 | doc, gafolo, koala, Nicks, rdnzao |
|           66 |      213 | 2025-02-22 | ODDIK                    | W   | 1.000      | 0.371        | 0.033 (0.012)    | 0.552 (0.205)    | 0 (0.000) |     9.97 | doc, gafolo, koala, Nicks, rdnzao |
|           65 |      262 | 2025-02-21 | Swingers                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.59 | doc, gafolo, koala, Nicks, rdnzao |
|           64 |      296 | 2025-02-20 | Bounty Hunters Esports   | W   | 1.000      | 0.371        | -                | 0.638 (0.236)    | -         |     6.08 | doc, gafolo, koala, Nicks, rdnzao |
|           63 |      336 | 2025-02-19 | Bounty Hunters Esports   | W   | 1.000      | 0.450        | -                | 0.638 (0.287)    | -         |     6.43 | doc, gafolo, koala, Nicks, rdnzao |
|           62 |      337 | 2025-02-19 | Bounty Hunters Esports   | W   | 1.000      | 0.450        | -                | 0.638 (0.287)    | -         |     6.82 | doc, gafolo, koala, Nicks, rdnzao |
|           61 |      609 | 2025-02-12 | Fluxo                    | L   | 1.000      | -            | -                | -                | -         |   -17.37 | doc, gafolo, koala, Nicks, rdnzao |
|           60 |      628 | 2025-02-11 | Imperial Esports         | W   | 1.000      | 0.143        | 0.083 (0.012)    | -                | -         |    13.65 | doc, gafolo, koala, Nicks, rdnzao |
|           59 |      633 | 2025-02-11 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |   -19.31 | doc, gafolo, koala, Nicks, rdnzao |
|           58 |      710 | 2025-02-09 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |   -12.80 | doc, gafolo, koala, Nicks, rdnzao |
|           57 |      771 | 2025-02-08 | BESTIA                   | W   | 1.000      | 0.143        | 0.081 (0.012)    | -                | -         |    10.77 | doc, gafolo, koala, Nicks, rdnzao |
|           56 |     1195 | 2025-01-28 | Floripa Stars            | W   | 0.972      | 0.450        | -                | 0.348 (0.152)    | -         |     2.22 | doc, gafolo, koala, Nicks, rdnzao |
|           55 |     1196 | 2025-01-28 | Floripa Stars            | W   | 0.972      | 0.450        | -                | 0.348 (0.152)    | -         |     2.28 | doc, gafolo, koala, Nicks, rdnzao |
|           54 |     2066 | 2024-12-08 | NRG                      | L   | 0.633      | -            | -                | -                | -         |    -9.62 | doc, gafolo, hoax, koala, rdnzao  |
|           53 |     2067 | 2024-12-08 | BLUEJAYS                 | W   | 0.633      | 0.384        | 0.016 (0.004)    | -                | 1 (0.633) |     6.42 | doc, gafolo, hoax, koala, rdnzao  |
|           52 |     2070 | 2024-12-08 | NRG                      | L   | 0.632      | -            | -                | -                | -         |    -9.97 | doc, gafolo, hoax, koala, rdnzao  |
|           51 |     2144 | 2024-12-07 | Nouns Esports            | W   | 0.626      | 0.384        | -                | 0.601 (0.145)    | 1 (0.626) |     6.82 | doc, gafolo, hoax, koala, rdnzao  |
|           50 |     2156 | 2024-12-07 | Bad News Capybaras       | W   | 0.625      | -            | -                | -                | 1 (0.625) |     1.77 | doc, gafolo, hoax, koala, rdnzao  |
|           49 |     2208 | 2024-12-06 | MIGHT                    | W   | 0.619      | -            | -                | -                | 1 (0.619) |     2.49 | doc, gafolo, hoax, koala, rdnzao  |
|           48 |     2512 | 2024-11-30 | ODDIK                    | L   | 0.578      | -            | -                | -                | -         |   -13.15 | doc, gafolo, hoax, koala, rdnzao  |
|           47 |     2602 | 2024-11-29 | Nitro.GG                 | W   | 0.570      | 0.371        | -                | 0.524 (0.111)    | -         |     2.07 | doc, gafolo, hoax, koala, rdnzao  |
|           46 |     2637 | 2024-11-28 | 20/70                    | W   | 0.564      | -            | -                | -                | -         |     1.60 | doc, gafolo, hoax, koala, rdnzao  |
|           45 |     2925 | 2024-11-22 | Fluxo                    | L   | 0.526      | -            | -                | -                | -         |   -10.07 | doc, gafolo, hoax, koala, rdnzao  |
|           44 |     3635 | 2024-11-09 | Fluxo                    | L   | 0.439      | -            | -                | -                | -         |    -8.75 | doc, gafolo, hoax, koala, rdnzao  |
|           43 |     3660 | 2024-11-09 | Team Solid               | W   | 0.437      | 0.371        | 0.027 (0.004)    | -                | -         |     3.30 | doc, gafolo, hoax, koala, rdnzao  |
|           42 |     3707 | 2024-11-08 | Game Hunters             | W   | 0.431      | -            | -                | -                | -         |     1.46 | doc, gafolo, hoax, koala, rdnzao  |
|           41 |     3735 | 2024-11-07 | MIBR Academy             | W   | 0.426      | -            | -                | -                | -         |     1.30 | doc, gafolo, hoax, koala, rdnzao  |
|           40 |     3831 | 2024-11-05 | Intense Game             | W   | 0.413      | -            | -                | -                | -         |     1.29 | doc, gafolo, hoax, koala, rdnzao  |
|           39 |     3835 | 2024-11-05 | Bounty Hunters Esports   | W   | 0.412      | -            | -                | -                | -         |     1.75 | doc, gafolo, hoax, koala, rdnzao  |
|           38 |     3885 | 2024-11-04 | ODDIK                    | L   | 0.406      | -            | -                | -                | -         |    -9.73 | doc, gafolo, hoax, koala, rdnzao  |
|           37 |     3946 | 2024-11-03 | Team Solid               | L   | 0.399      | -            | -                | -                | -         |    -9.92 | doc, gafolo, hoax, koala, rdnzao  |
|           36 |     4084 | 2024-11-01 | Fluxo                    | W   | 0.386      | 0.143        | 0.065 (0.004)    | -                | -         |     4.07 | doc, gafolo, hoax, koala, rdnzao  |
|           35 |     4139 | 2024-10-31 | América eSports          | W   | 0.379      | -            | -                | -                | -         |     0.71 | doc, gafolo, hoax, koala, rdnzao  |
|           34 |     4235 | 2024-10-30 | AdalYamigos              | W   | 0.370      | -            | -                | -                | -         |     1.27 | doc, gafolo, hoax, koala, rdnzao  |
|           33 |     4265 | 2024-10-29 | Galorys Academy          | W   | 0.365      | -            | -                | -                | -         |     0.82 | doc, gafolo, hoax, koala, rdnzao  |
|           32 |     4318 | 2024-10-28 | UNO MILLE                | L   | 0.359      | -            | -                | -                | -         |    -9.79 | doc, gafolo, hoax, koala, rdnzao  |
|           31 |     4371 | 2024-10-27 | ODDIK                    | W   | 0.351      | -            | -                | -                | 1 (0.351) |     2.50 | doc, gafolo, hoax, koala, rdnzao  |
|           30 |     4419 | 2024-10-26 | Fluxo                    | W   | 0.345      | -            | -                | -                | 1 (0.345) |     3.65 | doc, gafolo, hoax, koala, rdnzao  |
|           29 |     4887 | 2024-10-16 | Imperial Esports         | L   | 0.278      | -            | -                | -                | -         |    -6.49 | doc, gafolo, hoax, koala, rdnzao  |
|           28 |     4953 | 2024-10-15 | Case Esports             | W   | 0.272      | -            | -                | -                | -         |     0.75 | doc, gafolo, hoax, koala, rdnzao  |
|           27 |     5235 | 2024-10-09 | Players (Brazilian team) | W   | 0.232      | -            | -                | -                | -         |     0.13 | doc, gafolo, hoax, koala, rdnzao  |
|           26 |     5243 | 2024-10-09 | Players (Brazilian team) | W   | 0.232      | -            | -                | -                | -         |     0.13 | doc, gafolo, hoax, koala, rdnzao  |
|           25 |     5308 | 2024-10-08 | Case Esports             | W   | 0.225      | -            | -                | -                | -         |     0.63 | doc, gafolo, hoax, koala, rdnzao  |
|           24 |     5316 | 2024-10-08 | Case Esports             | W   | 0.225      | -            | -                | -                | -         |     0.63 | doc, gafolo, hoax, koala, rdnzao  |
|           23 |     5649 | 2024-10-02 | Team Solid               | W   | 0.185      | -            | -                | -                | -         |     1.21 | doc, gafolo, hoax, koala, rdnzao  |
|           22 |     5655 | 2024-10-02 | Team Solid               | L   | 0.185      | -            | -                | -                | -         |    -4.67 | doc, gafolo, hoax, koala, rdnzao  |
|           21 |     5717 | 2024-10-01 | Imperial Esports         | L   | 0.179      | -            | -                | -                | -         |    -4.26 | doc, gafolo, hoax, koala, rdnzao  |
|           20 |     5722 | 2024-10-01 | Imperial Esports         | W   | 0.178      | 0.450        | 0.083 (0.007)    | -                | -         |     1.37 | doc, gafolo, hoax, koala, rdnzao  |
|           19 |     5736 | 2024-10-01 | MIBR                     | W   | 0.178      | 0.450        | 0.118 (0.009)    | -                | -         |     3.01 | doc, gafolo, hoax, koala, rdnzao  |
|           18 |     5739 | 2024-10-01 | MIBR                     | L   | 0.177      | -            | -                | -                | -         |    -2.61 | doc, gafolo, hoax, koala, rdnzao  |
|           17 |     5848 | 2024-09-29 | Myth e-Sports            | W   | 0.164      | -            | -                | -                | -         |     0.27 | doc, gafolo, hoax, koala, rdnzao  |
|           16 |     5891 | 2024-09-28 | Patins da Ferrari        | W   | 0.159      | -            | -                | -                | -         |     0.17 | doc, gafolo, hoax, koala, rdnzao  |
|           15 |     5936 | 2024-09-28 | Nitro.GG                 | W   | 0.157      | -            | -                | -                | -         |     0.41 | doc, gafolo, hoax, koala, rdnzao  |
|           14 |     6075 | 2024-09-26 | BESTIA                   | L   | 0.145      | -            | -                | -                | -         |    -3.59 | doc, gafolo, hoax, koala, rdnzao  |
|           13 |     6106 | 2024-09-26 | Imperial Esports         | L   | 0.143      | -            | -                | -                | -         |    -3.43 | doc, gafolo, hoax, koala, rdnzao  |
|           12 |     6151 | 2024-09-25 | Hype Esports             | L   | 0.139      | -            | -                | -                | -         |    -4.04 | doc, gafolo, hoax, koala, rdnzao  |
|           11 |     6157 | 2024-09-25 | Hype Esports             | W   | 0.138      | -            | -                | -                | -         |     0.33 | doc, gafolo, hoax, koala, rdnzao  |
|           10 |     6192 | 2024-09-25 | MIBR                     | W   | 0.136      | -            | -                | -                | -         |     2.29 | doc, gafolo, hoax, koala, rdnzao  |
|            9 |     6240 | 2024-09-24 | PaiN Gaming              | L   | 0.132      | -            | -                | -                | -         |    -0.40 | doc, gafolo, hoax, koala, rdnzao  |
|            8 |     6246 | 2024-09-24 | PaiN Gaming              | L   | 0.132      | -            | -                | -                | -         |    -0.40 | doc, gafolo, hoax, koala, rdnzao  |
|            7 |     6864 | 2024-09-14 | Nitro.GG                 | W   | 0.064      | -            | -                | -                | -         |     0.16 | doc, gafolo, hoax, koala, rdnzao  |
|            6 |     6875 | 2024-09-14 | Team Solid               | L   | 0.064      | -            | -                | -                | -         |    -1.65 | doc, gafolo, hoax, koala, rdnzao  |
|            5 |     6883 | 2024-09-14 | Yawara E-Sports          | W   | 0.063      | -            | -                | -                | -         |     0.17 | doc, gafolo, hoax, koala, rdnzao  |
|            4 |     7105 | 2024-09-10 | InSanitY Sports          | L   | 0.039      | -            | -                | -                | -         |    -1.10 | doc, gafolo, hoax, koala, rdnzao  |
|            3 |     7109 | 2024-09-10 | InSanitY Sports          | W   | 0.038      | -            | -                | -                | -         |     0.12 | doc, gafolo, hoax, koala, rdnzao  |
|            2 |     7430 | 2024-09-05 | Dusty Roots              | W   | 0.005      | -            | -                | -                | -         |     0.02 | doc, gafolo, hoax, koala, rdnzao  |
|            1 |     7433 | 2024-09-05 | Dusty Roots              | W   | 0.005      | -            | -                | -                | -         |     0.02 | doc, gafolo, hoax, koala, rdnzao  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,815.66)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-12-08 |      0.633 | $7,500.00      | $4,748.47       |
| 2024-11-30 |      0.579 | $1,500.00      | $868.24         |
| 2024-11-24 |      0.538 | $3,878.61      | $2,086.30       |
| 2024-11-09 |      0.439 | $4,000.00      | $1,756.04       |
| 2024-10-27 |      0.351 | $10,512.48     | $3,691.09       |
| 2024-10-20 |      0.304 | $2,000.00      | $608.62         |
| 2024-09-29 |      0.164 | $276.04        | $45.24          |
| 2024-09-14 |      0.065 | $179.69        | $11.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
