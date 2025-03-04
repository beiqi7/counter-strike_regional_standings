### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, gafolo, koala, Nicks, rdnzao<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1048.8<br />
<br />
Final Rank Value (1048.8) = Starting Rank Value (1133.1) + Head To Head Adjustments (-84.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.196[<sup>2</sup>](#table1)
- LAN Wins: 0.408[<sup>2</sup>](#table1)

The average of these factors is 0.352<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1133.1
- 400 + ( ( 0.352 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1133.1


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
|           71 |       52 | 2025-02-26 | ODDIK                    | L   | 1.000      | -            | -                | -                | -         |   -19.53 | doc, gafolo, koala, Nicks, rdnzao |
|           70 |       55 | 2025-02-26 | ODDIK                    | L   | 1.000      | -            | -                | -                | -         |   -21.18 | doc, gafolo, koala, Nicks, rdnzao |
|           69 |      100 | 2025-02-25 | BESTIA                   | W   | 1.000      | 0.450        | 0.081 (0.037)    | 0.433 (0.195)    | 0 (0.000) |     9.02 | doc, gafolo, koala, Nicks, rdnzao |
|           68 |      102 | 2025-02-25 | BESTIA                   | W   | 1.000      | 0.450        | 0.081 (0.037)    | 0.433 (0.195)    | 0 (0.000) |     9.71 | doc, gafolo, koala, Nicks, rdnzao |
|           67 |      194 | 2025-02-22 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -         |   -17.19 | doc, gafolo, koala, Nicks, rdnzao |
|           66 |      215 | 2025-02-22 | ODDIK                    | W   | 1.000      | 0.371        | 0.033 (0.012)    | 0.552 (0.205)    | 0 (0.000) |     9.97 | doc, gafolo, koala, Nicks, rdnzao |
|           65 |      264 | 2025-02-21 | Swingers                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.59 | doc, gafolo, koala, Nicks, rdnzao |
|           64 |      298 | 2025-02-20 | Bounty Hunters Esports   | W   | 1.000      | 0.371        | -                | 0.638 (0.236)    | -         |     6.08 | doc, gafolo, koala, Nicks, rdnzao |
|           63 |      338 | 2025-02-19 | Bounty Hunters Esports   | W   | 1.000      | 0.450        | -                | 0.638 (0.287)    | -         |     6.43 | doc, gafolo, koala, Nicks, rdnzao |
|           62 |      339 | 2025-02-19 | Bounty Hunters Esports   | W   | 1.000      | 0.450        | -                | 0.638 (0.287)    | -         |     6.82 | doc, gafolo, koala, Nicks, rdnzao |
|           61 |      611 | 2025-02-12 | Fluxo                    | L   | 1.000      | -            | -                | -                | -         |   -17.37 | doc, gafolo, koala, Nicks, rdnzao |
|           60 |      630 | 2025-02-11 | Imperial Esports         | W   | 1.000      | 0.143        | 0.083 (0.012)    | -                | -         |    13.65 | doc, gafolo, koala, Nicks, rdnzao |
|           59 |      635 | 2025-02-11 | Legacy                   | L   | 1.000      | -            | -                | -                | -         |   -19.31 | doc, gafolo, koala, Nicks, rdnzao |
|           58 |      712 | 2025-02-09 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |   -12.80 | doc, gafolo, koala, Nicks, rdnzao |
|           57 |      773 | 2025-02-08 | BESTIA                   | W   | 1.000      | 0.143        | 0.081 (0.012)    | -                | -         |    10.76 | doc, gafolo, koala, Nicks, rdnzao |
|           56 |     1197 | 2025-01-28 | Floripa Stars            | W   | 0.972      | 0.450        | -                | 0.348 (0.152)    | -         |     2.22 | doc, gafolo, koala, Nicks, rdnzao |
|           55 |     1198 | 2025-01-28 | Floripa Stars            | W   | 0.972      | 0.450        | -                | 0.348 (0.152)    | -         |     2.28 | doc, gafolo, koala, Nicks, rdnzao |
|           54 |     2068 | 2024-12-08 | NRG                      | L   | 0.633      | -            | -                | -                | -         |    -9.61 | doc, gafolo, hoax, koala, rdnzao  |
|           53 |     2069 | 2024-12-08 | BLUEJAYS                 | W   | 0.632      | 0.384        | 0.016 (0.004)    | -                | 1 (0.632) |     6.42 | doc, gafolo, hoax, koala, rdnzao  |
|           52 |     2072 | 2024-12-08 | NRG                      | L   | 0.631      | -            | -                | -                | -         |    -9.96 | doc, gafolo, hoax, koala, rdnzao  |
|           51 |     2146 | 2024-12-07 | Nouns Esports            | W   | 0.626      | 0.384        | -                | 0.601 (0.145)    | 1 (0.626) |     6.81 | doc, gafolo, hoax, koala, rdnzao  |
|           50 |     2158 | 2024-12-07 | Bad News Capybaras       | W   | 0.625      | -            | -                | -                | 1 (0.625) |     1.76 | doc, gafolo, hoax, koala, rdnzao  |
|           49 |     2210 | 2024-12-06 | MIGHT                    | W   | 0.619      | -            | -                | -                | 1 (0.619) |     2.49 | doc, gafolo, hoax, koala, rdnzao  |
|           48 |     2514 | 2024-11-30 | ODDIK                    | L   | 0.578      | -            | -                | -                | -         |   -13.14 | doc, gafolo, hoax, koala, rdnzao  |
|           47 |     2604 | 2024-11-29 | Nitro.GG                 | W   | 0.569      | 0.371        | -                | 0.524 (0.111)    | -         |     2.07 | doc, gafolo, hoax, koala, rdnzao  |
|           46 |     2639 | 2024-11-28 | 20/70                    | W   | 0.564      | -            | -                | -                | -         |     1.60 | doc, gafolo, hoax, koala, rdnzao  |
|           45 |     2927 | 2024-11-22 | Fluxo                    | L   | 0.526      | -            | -                | -                | -         |   -10.07 | doc, gafolo, hoax, koala, rdnzao  |
|           44 |     3637 | 2024-11-09 | Fluxo                    | L   | 0.439      | -            | -                | -                | -         |    -8.74 | doc, gafolo, hoax, koala, rdnzao  |
|           43 |     3662 | 2024-11-09 | Team Solid               | W   | 0.437      | 0.371        | 0.027 (0.004)    | -                | -         |     3.29 | doc, gafolo, hoax, koala, rdnzao  |
|           42 |     3709 | 2024-11-08 | Game Hunters             | W   | 0.431      | -            | -                | -                | -         |     1.46 | doc, gafolo, hoax, koala, rdnzao  |
|           41 |     3737 | 2024-11-07 | MIBR Academy             | W   | 0.425      | -            | -                | -                | -         |     1.30 | doc, gafolo, hoax, koala, rdnzao  |
|           40 |     3833 | 2024-11-05 | Intense Game             | W   | 0.412      | -            | -                | -                | -         |     1.29 | doc, gafolo, hoax, koala, rdnzao  |
|           39 |     3837 | 2024-11-05 | Bounty Hunters Esports   | W   | 0.412      | -            | -                | -                | -         |     1.75 | doc, gafolo, hoax, koala, rdnzao  |
|           38 |     3887 | 2024-11-04 | ODDIK                    | L   | 0.406      | -            | -                | -                | -         |    -9.72 | doc, gafolo, hoax, koala, rdnzao  |
|           37 |     3948 | 2024-11-03 | Team Solid               | L   | 0.399      | -            | -                | -                | -         |    -9.91 | doc, gafolo, hoax, koala, rdnzao  |
|           36 |     4086 | 2024-11-01 | Fluxo                    | W   | 0.386      | 0.143        | 0.065 (0.004)    | -                | -         |     4.07 | doc, gafolo, hoax, koala, rdnzao  |
|           35 |     4141 | 2024-10-31 | América eSports          | W   | 0.379      | -            | -                | -                | -         |     0.71 | doc, gafolo, hoax, koala, rdnzao  |
|           34 |     4237 | 2024-10-30 | AdalYamigos              | W   | 0.370      | -            | -                | -                | -         |     1.27 | doc, gafolo, hoax, koala, rdnzao  |
|           33 |     4267 | 2024-10-29 | Galorys Academy          | W   | 0.365      | -            | -                | -                | -         |     0.82 | doc, gafolo, hoax, koala, rdnzao  |
|           32 |     4320 | 2024-10-28 | UNO MILLE                | L   | 0.358      | -            | -                | -                | -         |    -9.77 | doc, gafolo, hoax, koala, rdnzao  |
|           31 |     4373 | 2024-10-27 | ODDIK                    | W   | 0.351      | -            | -                | -                | 1 (0.351) |     2.50 | doc, gafolo, hoax, koala, rdnzao  |
|           30 |     4421 | 2024-10-26 | Fluxo                    | W   | 0.345      | -            | -                | -                | 1 (0.345) |     3.65 | doc, gafolo, hoax, koala, rdnzao  |
|           29 |     4889 | 2024-10-16 | Imperial Esports         | L   | 0.278      | -            | -                | -                | -         |    -6.48 | doc, gafolo, hoax, koala, rdnzao  |
|           28 |     4955 | 2024-10-15 | Case Esports             | W   | 0.271      | -            | -                | -                | -         |     0.75 | doc, gafolo, hoax, koala, rdnzao  |
|           27 |     5237 | 2024-10-09 | Players (Brazilian team) | W   | 0.232      | -            | -                | -                | -         |     0.13 | doc, gafolo, hoax, koala, rdnzao  |
|           26 |     5245 | 2024-10-09 | Players (Brazilian team) | W   | 0.231      | -            | -                | -                | -         |     0.13 | doc, gafolo, hoax, koala, rdnzao  |
|           25 |     5310 | 2024-10-08 | Case Esports             | W   | 0.225      | -            | -                | -                | -         |     0.63 | doc, gafolo, hoax, koala, rdnzao  |
|           24 |     5318 | 2024-10-08 | Case Esports             | W   | 0.225      | -            | -                | -                | -         |     0.63 | doc, gafolo, hoax, koala, rdnzao  |
|           23 |     5651 | 2024-10-02 | Team Solid               | W   | 0.185      | -            | -                | -                | -         |     1.21 | doc, gafolo, hoax, koala, rdnzao  |
|           22 |     5657 | 2024-10-02 | Team Solid               | L   | 0.185      | -            | -                | -                | -         |    -4.66 | doc, gafolo, hoax, koala, rdnzao  |
|           21 |     5719 | 2024-10-01 | Imperial Esports         | L   | 0.178      | -            | -                | -                | -         |    -4.25 | doc, gafolo, hoax, koala, rdnzao  |
|           20 |     5724 | 2024-10-01 | Imperial Esports         | W   | 0.178      | 0.450        | 0.083 (0.007)    | -                | -         |     1.37 | doc, gafolo, hoax, koala, rdnzao  |
|           19 |     5738 | 2024-10-01 | MIBR                     | W   | 0.177      | 0.450        | 0.118 (0.009)    | -                | -         |     3.00 | doc, gafolo, hoax, koala, rdnzao  |
|           18 |     5741 | 2024-10-01 | MIBR                     | L   | 0.177      | -            | -                | -                | -         |    -2.61 | doc, gafolo, hoax, koala, rdnzao  |
|           17 |     5850 | 2024-09-29 | Myth e-Sports            | W   | 0.164      | -            | -                | -                | -         |     0.27 | doc, gafolo, hoax, koala, rdnzao  |
|           16 |     5893 | 2024-09-28 | Patins da Ferrari        | W   | 0.158      | -            | -                | -                | -         |     0.17 | doc, gafolo, hoax, koala, rdnzao  |
|           15 |     5938 | 2024-09-28 | Nitro.GG                 | W   | 0.156      | -            | -                | -                | -         |     0.41 | doc, gafolo, hoax, koala, rdnzao  |
|           14 |     6077 | 2024-09-26 | BESTIA                   | L   | 0.144      | -            | -                | -                | -         |    -3.58 | doc, gafolo, hoax, koala, rdnzao  |
|           13 |     6108 | 2024-09-26 | Imperial Esports         | L   | 0.143      | -            | -                | -                | -         |    -3.42 | doc, gafolo, hoax, koala, rdnzao  |
|           12 |     6153 | 2024-09-25 | Hype Esports             | L   | 0.138      | -            | -                | -                | -         |    -4.03 | doc, gafolo, hoax, koala, rdnzao  |
|           11 |     6159 | 2024-09-25 | Hype Esports             | W   | 0.138      | -            | -                | -                | -         |     0.33 | doc, gafolo, hoax, koala, rdnzao  |
|           10 |     6194 | 2024-09-25 | MIBR                     | W   | 0.136      | -            | -                | -                | -         |     2.28 | doc, gafolo, hoax, koala, rdnzao  |
|            9 |     6242 | 2024-09-24 | PaiN Gaming              | L   | 0.132      | -            | -                | -                | -         |    -0.40 | doc, gafolo, hoax, koala, rdnzao  |
|            8 |     6248 | 2024-09-24 | PaiN Gaming              | L   | 0.131      | -            | -                | -                | -         |    -0.40 | doc, gafolo, hoax, koala, rdnzao  |
|            7 |     6866 | 2024-09-14 | Nitro.GG                 | W   | 0.064      | -            | -                | -                | -         |     0.16 | doc, gafolo, hoax, koala, rdnzao  |
|            6 |     6877 | 2024-09-14 | Team Solid               | L   | 0.063      | -            | -                | -                | -         |    -1.64 | doc, gafolo, hoax, koala, rdnzao  |
|            5 |     6885 | 2024-09-14 | Yawara E-Sports          | W   | 0.063      | -            | -                | -                | -         |     0.17 | doc, gafolo, hoax, koala, rdnzao  |
|            4 |     7107 | 2024-09-10 | InSanitY Sports          | L   | 0.038      | -            | -                | -                | -         |    -1.09 | doc, gafolo, hoax, koala, rdnzao  |
|            3 |     7111 | 2024-09-10 | InSanitY Sports          | W   | 0.038      | -            | -                | -                | -         |     0.12 | doc, gafolo, hoax, koala, rdnzao  |
|            2 |     7432 | 2024-09-05 | Dusty Roots              | W   | 0.005      | -            | -                | -                | -         |     0.02 | doc, gafolo, hoax, koala, rdnzao  |
|            1 |     7435 | 2024-09-05 | Dusty Roots              | W   | 0.004      | -            | -                | -                | -         |     0.02 | doc, gafolo, hoax, koala, rdnzao  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,804.54)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-12-08 |      0.633 | $7,500.00      | $4,745.68       |
| 2024-11-30 |      0.578 | $1,500.00      | $867.68         |
| 2024-11-24 |      0.538 | $3,878.61      | $2,084.85       |
| 2024-11-09 |      0.439 | $4,000.00      | $1,754.55       |
| 2024-10-27 |      0.351 | $10,512.48     | $3,687.18       |
| 2024-10-20 |      0.304 | $2,000.00      | $607.87         |
| 2024-09-29 |      0.164 | $276.04        | $45.14          |
| 2024-09-14 |      0.065 | $179.69        | $11.60          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
