### Roster Details<br />
Team Name: Chill Guys<br />
Roster: Evan, MagiC, MERL, NIGHT666LADE, TABEN<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [16]( ../standings_americas.md)<br />
<br />
Final Rank Value:  898.6<br />
<br />
Final Rank Value (898.6) = Starting Rank Value (832.7) + Head To Head Adjustments (65.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.196<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 832.7
- 400 + ( ( 0.196 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 832.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |       44 | 2025-02-26 | SUPER EVIL GANG    | W   | 0.784      | 0.477        | 0.008 (0.004)    | 0.345 (0.155)    | 0 (0.000) |     6.45 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           32 |       49 | 2025-02-26 | SUPER EVIL GANG    | W   | 0.784      | 0.477        | 0.008 (0.004)    | 0.345 (0.155)    | 0 (0.000) |     6.81 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           31 |       95 | 2025-02-25 | Getting Info       | W   | 0.779      | 0.477        | 0.009 (0.004)    | 0.604 (0.269)    | 0 (0.000) |    13.98 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           30 |      102 | 2025-02-25 | Getting Info       | L   | 0.779      | -            | -                | -                | -         |   -10.63 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           29 |      336 | 2025-02-19 | Akimbo Esports     | W   | 0.746      | 0.477        | -                | 0.512 (0.219)    | 0 (0.000) |     5.30 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           28 |      341 | 2025-02-19 | Akimbo Esports     | W   | 0.745      | 0.477        | -                | 0.512 (0.219)    | 0 (0.000) |     5.56 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           27 |      378 | 2025-02-18 | Legacy             | W   | 0.740      | 0.477        | 0.032 (0.014)    | 0.556 (0.236)    | 0 (0.000) |    13.62 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           26 |      383 | 2025-02-18 | Legacy             | W   | 0.740      | 0.477        | 0.032 (0.014)    | 0.556 (0.236)    | 0 (0.000) |    14.51 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           25 |      673 | 2025-02-10 | Exceritus          | L   | 0.695      | -            | -                | -                | -         |   -18.47 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           24 |      719 | 2025-02-09 | InControl          | W   | 0.688      | -            | -                | -                | 0 (0.000) |     3.31 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           23 |      760 | 2025-02-08 | Party Astronauts   | L   | 0.684      | -            | -                | -                | -         |   -10.85 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           22 |      777 | 2025-02-08 | Exceritus          | W   | 0.683      | -            | -                | -                | 0 (0.000) |     2.76 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           21 |      832 | 2025-02-07 | Immigrants Peek    | W   | 0.679      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     5.38 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           20 |     1212 | 2025-01-28 | Party Astronauts   | L   | 0.623      | -            | -                | -                | -         |   -10.49 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           19 |     1218 | 2025-01-28 | Party Astronauts   | W   | 0.623      | 0.477        | 0.003 (0.001)    | 0.459 (0.164)    | -         |     9.32 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           18 |     1251 | 2025-01-27 | Nouns Esports      | W   | 0.618      | 0.477        | 0.008 (0.003)    | 0.649 (0.230)    | -         |    10.39 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           17 |     1256 | 2025-01-27 | Nouns Esports      | W   | 0.618      | 0.477        | 0.008 (0.003)    | 0.649 (0.229)    | -         |    10.97 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           16 |     1336 | 2025-01-23 | NRG                | L   | 0.596      | -            | -                | -                | -         |    -4.52 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           15 |     1342 | 2025-01-23 | NRG                | L   | 0.595      | -            | -                | -                | -         |    -4.70 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           14 |     1403 | 2025-01-21 | InControl          | W   | 0.584      | -            | -                | -                | -         |     3.70 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           13 |     1408 | 2025-01-21 | InControl          | W   | 0.584      | -            | -                | -                | -         |     3.83 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           12 |     1910 | 2024-12-14 | Drugs n pugs       | W   | 0.372      | -            | -                | -                | -         |     0.89 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|           11 |     2606 | 2024-11-30 | Bad News Capybaras | W   | 0.295      | -            | -                | -                | -         |     2.89 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|           10 |     2940 | 2024-11-23 | NRG                | L   | 0.256      | -            | -                | -                | -         |    -2.10 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|            9 |     3045 | 2024-11-22 | Blahaj             | W   | 0.251      | -            | -                | -                | -         |     1.20 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|            8 |     3049 | 2024-11-22 | Diablos            | W   | 0.251      | -            | -                | -                | -         |     0.64 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|            7 |     3052 | 2024-11-22 | Hite Gaming        | W   | 0.251      | 0.143        | 0.005 (0.000)    | -                | -         |     2.25 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|            6 |     3352 | 2024-11-17 | Akimbo Esports     | W   | 0.223      | -            | -                | -                | -         |     2.01 | Evan, MagiC, Merl, NIGHT666LADE, TABEN    |
|            5 |     3419 | 2024-11-16 | Timbermen          | W   | 0.217      | -            | -                | -                | -         |     1.75 | Evan, MagiC, MERL, NIGHT666LADE, TABEN    |
|            4 |     5451 | 2024-10-09 | FLUFFY AIMERS      | W   | 0.006      | -            | -                | -                | -         |     0.08 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            3 |     5457 | 2024-10-09 | FLUFFY AIMERS      | W   | 0.006      | -            | -                | -                | -         |     0.07 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            2 |     5533 | 2024-10-08 | Party Astronauts   | L   | 0.001      | -            | -                | -                | -         |    -0.01 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |
|            1 |     5539 | 2024-10-08 | Party Astronauts   | L   | 0.000      | -            | -                | -                | -         |    -0.01 | Evan, HorizoN, MagiC, NIGHT666LADE, TABEN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($481.34)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.447 | $500.00        | $223.30         |
| 2024-11-16 |      0.260 | $500.00        | $130.05         |
| 2024-10-20 |      0.080 | $1,600.00      | $128.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
