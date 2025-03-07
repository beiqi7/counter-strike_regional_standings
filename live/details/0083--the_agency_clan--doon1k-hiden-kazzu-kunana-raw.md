### Roster Details<br />
Team Name: The Agency Clan<br />
Roster: doon1k, hiden, kaZzu, Kunana, raW<br />
Global Rank: [83](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  868.6<br />
<br />
Final Rank Value (868.6) = Starting Rank Value (851.1) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.298[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 851.1
- 400 + ( ( 0.205 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 851.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1511 | 2024-12-30 | Energise Club                    | W   | 0.461      | 0.143        | 0.000 (0.000)    | 0.054 (0.004)    | 0 (0.000) |     1.92 | doon1k, hiden, kaZzu, Kunana, raW    |
|           17 |     1562 | 2024-12-28 | Rhyno Youngsters                 | W   | 0.449      | 0.143        | 0.002 (0.000)    | 0.076 (0.006)    | 0 (0.000) |     4.86 | doon1k, Hiden, kazzu, Kunana, raW    |
|           16 |     1566 | 2024-12-28 | Leça FC Esports                  | W   | 0.448      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     0.99 | doon1k, Hiden, kazzu, Kunana, raW    |
|           15 |     1625 | 2024-12-22 | GTZ.ESPORTS                      | L   | 0.416      | -            | -                | -                | -         |    -1.97 | doon1k, Hiden, kazzu, Kunana, raW    |
|           14 |     1633 | 2024-12-22 | Rhyno Youngsters                 | W   | 0.416      | 0.143        | 0.002 (0.000)    | 0.076 (0.005)    | 1 (0.499) |     4.52 | doon1k, Hiden, kazzu, Kunana, raW    |
|           13 |     1663 | 2024-12-22 | La Bombonera                     | W   | 0.414      | 0.143        | 0.000 (0.000)    | 0.030 (0.002)    | 1 (0.497) |     3.07 | doon1k, Hiden, kazzu, Kunana, raW    |
|           12 |     1685 | 2024-12-21 | Impulse GW                       | W   | 0.410      | 0.143        | 0.007 (0.000)    | 0.060 (0.004)    | 1 (0.492) |     4.38 | doon1k, Hiden, kazzu, Kunana, raW    |
|           11 |     1763 | 2024-12-19 | THE LAST DANCE (Portuguese team) | W   | 0.400      | 0.143        | 0.000 (0.000)    | 0.057 (0.004)    | 0 (0.000) |     3.04 | doon1k, hiden, kaZzu, Kunana, raW    |
|           10 |     2000 | 2024-12-13 | Macabrienz                       | W   | 0.366      | -            | -                | -                | 0 (0.000) |     0.87 | doon1k, hiden, kaZzu, Kunana, raW    |
|            9 |     3454 | 2024-11-16 | Rhyno Esports                    | L   | 0.214      | -            | -                | -                | -         |    -3.77 | Hiden, kaZzu, Kunana, raW, Werzaide  |
|            8 |     4096 | 2024-11-03 | GOOFYBOYZ                        | L   | 0.144      | -            | -                | -                | -         |    -2.90 | doon1k, Hiden, kazzu, Kunana, raW    |
|            7 |     4111 | 2024-11-03 | Impulse GW                       | W   | 0.143      | 0.143        | 0.007 (0.000)    | 0.060 (0.001)    | 1 (0.172) |     1.57 | doon1k, Hiden, kazzu, Kunana, raW    |
|            6 |     4130 | 2024-11-03 | 1bot +4                          | W   | 0.142      | -            | -                | -                | 1 (0.171) |     0.33 | doon1k, Hiden, kazzu, Kunana, raW    |
|            5 |     4486 | 2024-10-28 | Impulse GW                       | W   | 0.111      | 0.143        | 0.007 (0.000)    | 0.060 (0.001)    | -         |     1.23 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            4 |     4780 | 2024-10-22 | FALKE ESPORTS                    | W   | 0.077      | 0.143        | -                | 0.025 (0.000)    | -         |     0.18 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            3 |     4788 | 2024-10-22 | TGD Pro                          | W   | 0.077      | -            | -                | -                | -         |     0.18 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            2 |     4876 | 2024-10-20 | Energise Club                    | W   | 0.065      | 0.143        | 0.000 (0.000)    | 0.054 (0.001)    | -         |     0.29 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            1 |     4885 | 2024-10-20 | GOOFYBOYZ                        | L   | 0.065      | -            | -                | -                | -         |    -1.33 | doon1k, kaZzu, Kunana, raW, Werzaide |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,356.22)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.553 | $365.01        | $201.77         |
| 2024-12-28 |      0.538 | $730.00        | $392.90         |
| 2024-12-22 |      0.500 | $834.42        | $416.80         |
| 2024-11-17 |      0.264 | $1,054.46      | $278.85         |
| 2024-11-03 |      0.173 | $380.83        | $65.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
