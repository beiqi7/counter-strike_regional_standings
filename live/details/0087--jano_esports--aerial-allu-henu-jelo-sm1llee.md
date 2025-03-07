### Roster Details<br />
Team Name: JANO Esports<br />
Roster: Aerial, allu, HENU, jelo, Sm1llee<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  864.5<br />
<br />
Final Rank Value (864.5) = Starting Rank Value (956.2) + Head To Head Adjustments (-91.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.2
- 400 + ( ( 0.252 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 956.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      230 | 2025-02-22 | ENCE Academy          | W   | 0.760      | 0.143        | 0.008 (0.001)    | 0.566 (0.074)    | 1 (0.912) |    11.40 | Aerial, allu, HENU, jelo, Sm1llee |
|           29 |      275 | 2025-02-21 | Heimo Esports         | W   | 0.754      | 0.143        | 0.005 (0.001)    | 0.528 (0.068)    | 1 (0.905) |     7.96 | Aerial, allu, HENU, jelo, Sm1llee |
|           28 |      397 | 2025-02-18 | Ex-UHKA eSports       | W   | 0.737      | 0.143        | 0.000 (0.000)    | 0.246 (0.031)    | 0 (0.000) |     3.23 | Aerial, allu, HENU, jelo, Sm1llee |
|           27 |      577 | 2025-02-14 | Eternal premium       | L   | 0.716      | -            | -                | -                | -         |   -14.52 | Aerial, allu, HENU, jelo, Sm1llee |
|           26 |      694 | 2025-02-10 | Smuuttikusilkki       | W   | 0.693      | 0.143        | 0.000 (0.000)    | 0.222 (0.026)    | 0 (0.000) |     1.75 | Aerial, allu, HENU, jelo, Sm1llee |
|           25 |      933 | 2025-02-06 | SAUCEMEN              | W   | 0.671      | 0.143        | -                | 0.083 (0.010)    | 0 (0.000) |     1.44 | Aerial, allu, HENU, jelo, Sm1llee |
|           24 |     1060 | 2025-02-04 | Johnny Speeds         | L   | 0.659      | -            | -                | -                | -         |   -17.86 | Aerial, allu, HENU, jelo, Sm1llee |
|           23 |     1081 | 2025-02-04 | HAVU                  | W   | 0.659      | 0.143        | 0.002 (0.000)    | 0.366 (0.041)    | 0 (0.000) |     6.45 | Aerial, allu, HENU, jelo, Sm1llee |
|           22 |     1130 | 2025-02-02 | HAVU                  | L   | 0.648      | -            | -                | -                | -         |   -14.45 | Aerial, allu, HENU, jelo, Sm1llee |
|           21 |     1159 | 2025-02-01 | Heimo Esports         | L   | 0.642      | -            | -                | -                | -         |   -14.75 | Aerial, allu, HENU, jelo, Sm1llee |
|           20 |     1282 | 2025-01-26 | ENCE Academy          | L   | 0.609      | -            | -                | -                | -         |   -11.53 | Aerial, allu, HENU, jelo, Sm1llee |
|           19 |     1363 | 2025-01-23 | FCottoNd              | W   | 0.593      | 0.143        | -                | 0.176 (0.018)    | 0 (0.000) |     1.16 | Aerial, allu, HENU, jelo, Sm1llee |
|           18 |     1686 | 2024-12-21 | KONO.ECF              | L   | 0.410      | -            | -                | -                | -         |    -6.67 | Aerial, airax, allu, HENU, jelo   |
|           17 |     1702 | 2024-12-21 | RUSH B (Russian team) | L   | 0.409      | -            | -                | -                | -         |    -5.72 | Aerial, airax, allu, HENU, jelo   |
|           16 |     1760 | 2024-12-20 | 500                   | W   | 0.403      | 0.371        | 0.118 (0.021)    | 1.000 (0.179)    | 0 (0.000) |     8.67 | Aerial, airax, allu, HENU, jelo   |
|           15 |     1778 | 2024-12-19 | Monte                 | L   | 0.398      | -            | -                | -                | -         |    -5.38 | Aerial, airax, allu, HENU, jelo   |
|           14 |     1885 | 2024-12-15 | Dark Cloud Esports    | L   | 0.375      | -            | -                | -                | -         |    -7.53 | Aerial, airax, allu, HENU, jelo   |
|           13 |     2063 | 2024-12-12 | FORZE Reload          | L   | 0.360      | -            | -                | -                | -         |    -6.77 | Aerial, airax, allu, HENU, jelo   |
|           12 |     2150 | 2024-12-10 | K27                   | L   | 0.349      | -            | -                | -                | -         |    -5.13 | Aerial, airax, allu, HENU, jelo   |
|           11 |     2169 | 2024-12-09 | Betera Esports        | W   | 0.344      | 0.333        | 0.004 (0.001)    | 0.212 (0.029)    | -         |     2.71 | Aerial, airax, allu, HENU, jelo   |
|           10 |     2770 | 2024-11-28 | BC.Game Esports       | L   | 0.281      | -            | -                | -                | -         |    -5.66 | Aerial, airax, allu, HENU, jelo   |
|            9 |     2835 | 2024-11-26 | ADEPTS                | L   | 0.272      | -            | -                | -                | -         |    -7.59 | Aerial, airax, allu, HENU, jelo   |
|            8 |     2990 | 2024-11-23 | FORZE Reload          | L   | 0.254      | -            | -                | -                | -         |    -5.16 | Aerial, airax, allu, HENU, jelo   |
|            7 |     3087 | 2024-11-22 | Iberian Soul          | L   | 0.249      | -            | -                | -                | -         |    -4.98 | Aerial, airax, allu, HENU, jelo   |
|            6 |     3160 | 2024-11-21 | G2 Ares               | W   | 0.242      | 0.333        | 0.001 (0.000)    | 0.182 (0.018)    | -         |     1.38 | Aerial, airax, allu, HENU, jelo   |
|            5 |     3282 | 2024-11-19 | TEAM NEXT LEVEL       | L   | 0.232      | -            | -                | -                | -         |    -4.83 | Aerial, airax, allu, HENU, jelo   |
|            4 |     4916 | 2024-10-20 | ENCE Academy          | W   | 0.064      | 0.143        | 0.008 (0.000)    | -                | 1 (0.077) |     0.68 | Aerial, allu, HENU, juho, xseveN  |
|            3 |     5007 | 2024-10-18 | B8                    | L   | 0.053      | -            | -                | -                | -         |    -0.49 | Aerial, allu, HENU, juho, xseveN  |
|            2 |     5124 | 2024-10-16 | Ninjas in Pyjamas     | W   | 0.043      | 0.589        | 0.015 (0.000)    | -                | 1 (0.052) |     0.47 | Aerial, allu, HENU, juho, xseveN  |
|            1 |     5152 | 2024-10-16 | The MongolZ           | L   | 0.041      | -            | -                | -                | -         |    -0.01 | Aerial, allu, HENU, juho, xseveN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,888.81)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.912 | $3,139.38      | $2,861.85       |
| 2024-10-20 |      0.078 | $10,000.00     | $777.08         |
| 2024-10-20 |      0.077 | $3,262.27      | $249.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
