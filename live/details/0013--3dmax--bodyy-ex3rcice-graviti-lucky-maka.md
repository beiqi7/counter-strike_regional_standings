### Roster Details<br />
Team Name: 3DMAX<br />
Roster: bodyy, Ex3rcice, Graviti, Lucky, Maka<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1521.5<br />
<br />
Final Rank Value (1521.5) = Starting Rank Value (1553.8) + Head To Head Adjustments (-32.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.631[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.825[<sup>2</sup>](#table1)

The average of these factors is 0.523<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1553.8
- 400 + ( ( 0.523 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1553.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       11 | 2025-03-01 | TYLOO                      | L   | 0.801      | -            | -                | -                | -         |   -22.59 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           28 |      401 | 2025-02-18 | SAW                        | L   | 0.736      | -            | -                | -                | -         |   -18.41 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           27 |      437 | 2025-02-17 | Eternal Fire               | L   | 0.732      | -            | -                | -                | -         |    -2.99 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           26 |      497 | 2025-02-16 | MIBR                       | W   | 0.725      | 1.000        | 0.105 (0.091)    | 0.265 (0.231)    | 1 (0.869) |     2.72 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           25 |      549 | 2025-02-15 | MOUZ                       | L   | 0.719      | -            | -                | -                | -         |    -2.45 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           24 |      599 | 2025-02-14 | Virtus.pro                 | W   | 0.714      | 1.000        | 0.320 (0.274)    | 0.352 (0.301)    | 1 (0.856) |    14.14 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           23 |      685 | 2025-02-10 | HEROIC                     | W   | 0.694      | 0.143        | 0.120 (0.014)    | 0.372 (0.044)    | 0 (0.000) |     1.35 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           22 |      696 | 2025-02-10 | NEVERMORE (Ukrainian team) | W   | 0.692      | 0.143        | -                | 0.803 (0.095)    | -         |     0.38 | bodyy, Ex3rcice, Graviti, Lucky, Maka |
|           21 |     1106 | 2025-02-03 | Eternal Fire               | L   | 0.655      | -            | -                | -                | -         |    -2.32 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           20 |     1122 | 2025-02-02 | BIG                        | W   | 0.649      | 1.000        | 0.234 (0.182)    | 0.400 (0.312)    | 1 (0.779) |     5.98 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           19 |     1157 | 2025-02-01 | Team Vitality              | L   | 0.642      | -            | -                | -                | -         |    -2.95 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           18 |     1193 | 2025-01-30 | MIBR                       | W   | 0.632      | 1.000        | 0.105 (0.080)    | 0.265 (0.201)    | 1 (0.758) |     2.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           17 |     1210 | 2025-01-29 | FlyQuest                   | W   | 0.625      | 1.000        | 0.096 (0.072)    | 0.190 (0.143)    | 1 (0.750) |     1.84 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           16 |     1464 | 2025-01-14 | HEROIC                     | L   | 0.542      | -            | -                | -                | -         |   -16.20 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           15 |     3110 | 2024-11-22 | G2 Esports                 | W   | 0.247      | 0.143        | 0.528 (0.022)    | -                | 1 (0.296) |     3.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           14 |     3166 | 2024-11-21 | Eternal Fire               | W   | 0.242      | 0.143        | 0.731 (0.030)    | -                | 1 (0.291) |     6.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           13 |     3179 | 2024-11-20 | TSM                        | W   | 0.241      | -            | -                | -                | 1 (0.289) |     0.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           12 |     4132 | 2024-11-03 | OG                         | W   | 0.142      | 0.934        | 0.041 (0.007)    | 0.989 (0.158)    | 1 (0.171) |     0.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           11 |     4174 | 2024-11-02 | The MongolZ                | L   | 0.138      | -            | -                | -                | -         |    -0.64 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           10 |     4583 | 2024-10-26 | BESTIA                     | W   | 0.099      | 0.934        | -                | 0.459 (0.051)    | -         |     0.07 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            9 |     4820 | 2024-10-21 | OG                         | W   | 0.071      | 0.934        | -                | 0.989 (0.079)    | -         |     0.05 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            8 |     4859 | 2024-10-21 | Team Falcons               | W   | 0.069      | -            | -                | -                | -         |     0.02 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            7 |     4951 | 2024-10-19 | Nemiga Gaming              | L   | 0.059      | -            | -                | -                | -         |    -1.80 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            6 |     4997 | 2024-10-18 | SAW                        | W   | 0.054      | 0.500        | 0.316 (0.010)    | -                | -         |     0.44 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            5 |     5039 | 2024-10-17 | Sashi Esport               | W   | 0.049      | -            | -                | -                | -         |     0.06 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            4 |     5115 | 2024-10-16 | Nemiga Gaming              | L   | 0.043      | -            | -                | -                | -         |    -1.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            3 |     5191 | 2024-10-15 | TSM                        | W   | 0.037      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            2 |     5346 | 2024-10-12 | Team Spirit Academy        | L   | 0.020      | -            | -                | -                | -         |    -0.61 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|            1 |     5422 | 2024-10-10 | CYBERSHOKE Esports         | W   | 0.010      | -            | -                | -                | -         |     0.01 | Djoko, Ex3rcice, Graviti, Lucky, Maka |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,781.01)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $31,250.00     | $28,713.83      |
| 2025-02-09 |      0.825 | $16,000.00     | $13,200.00      |
| 2024-11-03 |      0.172 | $70,000.00     | $12,026.39      |
| 2024-10-20 |      0.078 | $10,000.00     | $777.78         |
| 2024-10-13 |      0.032 | $2,000.00      | $63.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
