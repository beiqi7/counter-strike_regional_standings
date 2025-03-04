### Roster Details<br />
Team Name: Chill Guys<br />
Roster: Evan, MagiC, MERL, NIGHT666LADE, TABEN<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  933.2<br />
<br />
Final Rank Value (933.2) = Starting Rank Value (848.1) + Head To Head Adjustments (85.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.249[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 848.1
- 400 + ( ( 0.215 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 848.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |       40 | 2025-02-26 | SUPER EVIL GANG            | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.409 (0.195)    | 0 (0.000) |     7.38 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           47 |       45 | 2025-02-26 | SUPER EVIL GANG            | W   | 1.000      | 0.477        | 0.011 (0.005)    | 0.409 (0.195)    | 0 (0.000) |     7.88 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           46 |       91 | 2025-02-25 | Getting Info               | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.600 (0.286)    | 0 (0.000) |    18.15 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           45 |       98 | 2025-02-25 | Getting Info               | L   | 1.000      | -            | -                | -                | -         |   -13.14 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           44 |      329 | 2025-02-19 | Akimbo Esports             | W   | 1.000      | 0.477        | 0.003 (0.002)    | 0.431 (0.206)    | 0 (0.000) |     6.14 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           43 |      333 | 2025-02-19 | Akimbo Esports             | W   | 1.000      | 0.477        | 0.003 (0.002)    | 0.431 (0.206)    | 0 (0.000) |     6.49 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           42 |      363 | 2025-02-18 | Legacy                     | W   | 1.000      | 0.477        | 0.043 (0.020)    | 0.628 (0.300)    | 0 (0.000) |    20.30 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           41 |      367 | 2025-02-18 | Legacy                     | W   | 1.000      | 0.477        | 0.043 (0.020)    | 0.628 (0.300)    | 0 (0.000) |    21.95 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           40 |      654 | 2025-02-10 | Exceritus                  | L   | 1.000      | -            | -                | -                | -         |   -23.46 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           39 |      698 | 2025-02-09 | InControl                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.06 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           38 |      738 | 2025-02-08 | Party Astronauts           | L   | 1.000      | -            | -                | -                | -         |   -16.00 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           37 |      755 | 2025-02-08 | Exceritus                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.29 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           36 |      810 | 2025-02-07 | Immigrants Peek            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           35 |     1186 | 2025-01-28 | Party Astronauts           | L   | 0.973      | -            | -                | -                | -         |   -17.00 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           34 |     1191 | 2025-01-28 | Party Astronauts           | W   | 0.973      | 0.477        | 0.009 (0.004)    | 0.528 (0.245)    | -         |    13.54 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           33 |     1215 | 2025-01-27 | Nouns Esports              | W   | 0.966      | 0.477        | 0.014 (0.006)    | 0.601 (0.277)    | -         |    17.88 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           32 |     1218 | 2025-01-27 | Nouns Esports              | W   | 0.966      | 0.477        | 0.014 (0.006)    | 0.601 (0.277)    | -         |    19.38 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           31 |     1259 | 2025-01-23 | NRG                        | L   | 0.940      | -            | -                | -                | -         |    -5.83 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           30 |     1261 | 2025-01-23 | NRG                        | L   | 0.939      | -            | -                | -                | -         |    -6.15 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           29 |     1784 | 2024-12-14 | Drugs n pugs               | W   | 0.672      | -            | -                | -                | -         |     1.47 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           28 |     2488 | 2024-11-30 | Bad News Capybaras         | W   | 0.579      | -            | -                | -                | -         |     4.77 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           27 |     2820 | 2024-11-23 | NRG                        | L   | 0.532      | -            | -                | -                | -         |    -3.71 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           26 |     2924 | 2024-11-22 | Blahaj                     | W   | 0.526      | -            | -                | -                | -         |     2.56 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           25 |     2928 | 2024-11-22 | Diablos                    | W   | 0.526      | -            | -                | -                | -         |     1.29 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           24 |     2931 | 2024-11-22 | Hite Gaming                | W   | 0.526      | -            | -                | -                | -         |     4.39 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           23 |     3222 | 2024-11-17 | Akimbo Esports             | W   | 0.492      | -            | -                | -                | -         |     5.04 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           22 |     3289 | 2024-11-16 | Timbermen                  | W   | 0.485      | -            | -                | -                | -         |     4.76 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           21 |     5221 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.232      | -            | -                | -                | -         |     3.73 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           20 |     5227 | 2024-10-09 | FLUFFY AIMERS              | W   | 0.232      | -            | -                | -                | -         |     3.80 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           19 |     5294 | 2024-10-08 | Party Astronauts           | L   | 0.226      | -            | -                | -                | -         |    -3.50 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           18 |     5300 | 2024-10-08 | Party Astronauts           | L   | 0.225      | -            | -                | -                | -         |    -3.56 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           17 |     5363 | 2024-10-07 | Familia Maquininha         | L   | 0.219      | -            | -                | -                | -         |    -4.72 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           16 |     5365 | 2024-10-07 | Familia Maquininha         | W   | 0.219      | -            | -                | -                | -         |     2.20 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           15 |     5598 | 2024-10-03 | LAG Gaming                 | W   | 0.192      | -            | -                | -                | -         |     1.40 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           14 |     5603 | 2024-10-03 | LAG Gaming                 | W   | 0.192      | -            | -                | -                | -         |     1.41 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           13 |     5716 | 2024-10-01 | FLUFFY AIMERS              | L   | 0.179      | -            | -                | -                | -         |    -2.80 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           12 |     5730 | 2024-10-01 | Nouns Esports              | L   | 0.178      | -            | -                | -                | -         |    -2.08 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           11 |     5734 | 2024-10-01 | Nouns Esports              | L   | 0.177      | -            | -                | -                | -         |    -2.11 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|           10 |     5783 | 2024-09-30 | M80                        | L   | 0.172      | -            | -                | -                | -         |    -1.85 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            9 |     5785 | 2024-09-30 | M80                        | L   | 0.172      | -            | -                | -                | -         |    -1.87 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            8 |     6233 | 2024-09-24 | Legacy                     | L   | 0.132      | -            | -                | -                | -         |    -1.85 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            7 |     6240 | 2024-09-24 | Legacy                     | L   | 0.132      | -            | -                | -                | -         |    -1.87 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            6 |     6323 | 2024-09-23 | InControl                  | W   | 0.126      | -            | -                | -                | -         |     0.96 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            5 |     6573 | 2024-09-19 | Vagrants                   | W   | 0.098      | -            | -                | -                | -         |     1.33 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            4 |     6628 | 2024-09-18 | Wildcard                   | L   | 0.092      | -            | -                | -                | -         |    -0.44 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            3 |     6632 | 2024-09-18 | Wildcard                   | L   | 0.091      | -            | -                | -                | -         |    -0.44 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            2 |     6859 | 2024-09-14 | Dangerous (Ukrainian team) | W   | 0.065      | -            | -                | -                | -         |     0.15 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            1 |     7010 | 2024-09-12 | Jahsdnmasjdm v2            | L   | 0.051      | -            | -                | -                | -         |    -1.42 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,066.11)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.672 | $500.00        | $335.75         |
| 2024-11-16 |      0.485 | $500.00        | $242.50         |
| 2024-10-20 |      0.305 | $1,600.00      | $487.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
