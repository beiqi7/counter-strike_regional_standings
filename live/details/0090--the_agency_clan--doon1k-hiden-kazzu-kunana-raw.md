### Roster Details<br />
Team Name: The Agency Clan<br />
Roster: doon1k, hiden, kaZzu, Kunana, raW<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  903.0<br />
<br />
Final Rank Value (903.0) = Starting Rank Value (880.1) + Head To Head Adjustments (22.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 880.1
- 400 + ( ( 0.231 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 880.1


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
|           18 |     1392 | 2024-12-30 | Energise Club                    | W   | 0.778      | 0.143        | 0.000 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     2.65 | doon1k, hiden, kaZzu, Kunana, raW    |
|           17 |     1444 | 2024-12-28 | Rhyno Youngsters                 | W   | 0.763      | 0.143        | 0.004 (0.000)    | 0.120 (0.013)    | 0 (0.000) |     7.50 | doon1k, Hiden, kazzu, Kunana, raW    |
|           16 |     1448 | 2024-12-28 | Leça FC Esports                  | W   | 0.763      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.43 | doon1k, Hiden, kazzu, Kunana, raW    |
|           15 |     1506 | 2024-12-22 | GTZ.ESPORTS                      | L   | 0.724      | -            | -                | -                | -         |    -3.53 | doon1k, Hiden, kazzu, Kunana, raW    |
|           14 |     1514 | 2024-12-22 | Rhyno Youngsters                 | W   | 0.724      | 0.143        | 0.004 (0.000)    | 0.120 (0.012)    | 1 (0.724) |     7.10 | doon1k, Hiden, kazzu, Kunana, raW    |
|           13 |     1544 | 2024-12-22 | La Bombonera                     | W   | 0.722      | 0.143        | 0.000 (0.000)    | 0.035 (0.004)    | 1 (0.722) |     4.66 | doon1k, Hiden, kazzu, Kunana, raW    |
|           12 |     1566 | 2024-12-21 | Impulse GW                       | W   | 0.717      | 0.143        | 0.008 (0.001)    | 0.171 (0.018)    | 1 (0.717) |     6.96 | doon1k, Hiden, kazzu, Kunana, raW    |
|           11 |     1643 | 2024-12-19 | THE LAST DANCE (Portuguese team) | W   | 0.705      | 0.143        | 0.000 (0.000)    | 0.067 (0.007)    | 0 (0.000) |     4.74 | doon1k, hiden, kaZzu, Kunana, raW    |
|           10 |     1875 | 2024-12-13 | Macabrienz                       | W   | 0.664      | -            | -                | -                | 0 (0.000) |     1.40 | doon1k, hiden, kaZzu, Kunana, raW    |
|            9 |     3325 | 2024-11-16 | Rhyno Esports                    | L   | 0.482      | -            | -                | -                | -         |    -7.13 | Hiden, kaZzu, Kunana, raW, Werzaide  |
|            8 |     3955 | 2024-11-03 | GOOFYBOYZ                        | L   | 0.398      | -            | -                | -                | -         |    -7.82 | doon1k, Hiden, kazzu, Kunana, raW    |
|            7 |     3970 | 2024-11-03 | Impulse GW                       | W   | 0.397      | 0.143        | 0.008 (0.000)    | 0.171 (0.010)    | 1 (0.397) |     4.05 | doon1k, Hiden, kazzu, Kunana, raW    |
|            6 |     3988 | 2024-11-03 | 1bot +4                          | W   | 0.396      | -            | -                | -                | 1 (0.396) |     0.79 | doon1k, Hiden, kazzu, Kunana, raW    |
|            5 |     4330 | 2024-10-28 | Impulse GW                       | W   | 0.358      | 0.143        | 0.008 (0.000)    | 0.171 (0.009)    | -         |     3.83 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            4 |     4604 | 2024-10-22 | FALKE ESPORTS                    | W   | 0.318      | -            | -                | -                | -         |     0.67 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            3 |     4611 | 2024-10-22 | TGD Pro                          | W   | 0.317      | 0.143        | -                | 0.046 (0.002)    | -         |     0.66 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            2 |     4689 | 2024-10-20 | Energise Club                    | W   | 0.303      | 0.143        | 0.000 (0.000)    | 0.065 (0.003)    | -         |     1.12 | doon1k, kaZzu, Kunana, raW, Werzaide |
|            1 |     4698 | 2024-10-20 | GOOFYBOYZ                        | L   | 0.303      | -            | -                | -                | -         |    -6.18 | doon1k, kaZzu, Kunana, raW, Werzaide |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,112.98)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.778 | $365.01        | $283.86         |
| 2024-12-28 |      0.763 | $730.00        | $557.08         |
| 2024-12-22 |      0.724 | $834.42        | $604.47         |
| 2024-11-17 |      0.489 | $1,054.46      | $516.01         |
| 2024-11-03 |      0.398 | $380.83        | $151.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
