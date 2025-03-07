### Roster Details<br />
Team Name: TYLOO<br />
Roster: Attacker, JamYoung, Jee, Mercury, Moseyuh<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [3]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1187.7<br />
<br />
Final Rank Value (1187.7) = Starting Rank Value (1193.7) + Head To Head Adjustments (-6.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.438[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.529[<sup>2</sup>](#table1)

The average of these factors is 0.360<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1193.7
- 400 + ( ( 0.360 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1193.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |        0 | 2025-03-05 | FlyQuest             | W   | 0.820      | 0.415        | 0.096 (0.039)    | 0.190 (0.078)    | 1 (0.984) |    11.18 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           12 |        1 | 2025-03-04 | MIBR                 | L   | 0.815      | -            | -                | -                | -         |   -11.92 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           11 |        6 | 2025-03-03 | GamerLegion          | L   | 0.812      | -            | -                | -                | -         |    -2.80 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           10 |        8 | 2025-03-02 | Eternal Fire         | W   | 0.807      | 0.415        | 0.731 (0.294)    | 0.557 (0.224)    | 1 (0.968) |    24.94 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|            9 |       11 | 2025-03-01 | 3DMAX                | W   | 0.801      | 0.415        | 0.261 (0.104)    | 0.383 (0.153)    | 1 (0.961) |    22.59 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|            8 |      661 | 2025-02-11 | Lynn Vision Gaming   | L   | 0.698      | -            | -                | -                | -         |   -17.16 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|            7 |      668 | 2025-02-11 | ATOX Esports         | L   | 0.697      | -            | -                | -                | -         |   -14.66 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|            6 |      670 | 2025-02-10 | Rare Atom            | L   | 0.697      | -            | -                | -                | -         |   -19.18 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|            5 |     4154 | 2024-11-03 | Lynn Vision Gaming   | W   | 0.141      | 0.417        | 0.028 (0.002)    | 0.303 (0.021)    | 1 (0.170) |     0.87 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            4 |     4214 | 2024-11-02 | ATOX Esports         | W   | 0.136      | 0.417        | 0.005 (0.000)    | 0.012 (0.001)    | 1 (0.164) |     0.23 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            3 |     5145 | 2024-10-16 | Unsettled Resentment | W   | 0.042      | 0.417        | 0.013 (0.000)    | 0.198 (0.004)    | 0 (0.000) |     0.09 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            2 |     5508 | 2024-10-09 | Lynn Vision Gaming   | L   | 0.003      | -            | -                | -                | -         |    -0.08 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            1 |     5514 | 2024-10-09 | Lynn Vision Gaming   | L   | 0.003      | -            | -                | -                | -         |    -0.08 | JamYoung, Jee, Mercury, Moseyuh, Starry   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,912.99)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-05 |      0.984 | $8,500.00      | $8,367.86       |
| 2024-11-03 |      0.170 | $15,000.00     | $2,545.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
