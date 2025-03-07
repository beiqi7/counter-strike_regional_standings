### Roster Details<br />
Team Name: P0RTUGAL<br />
Roster: danistzz, KaiR0N-, NickelBack, synyx, X5G7V<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  839.5<br />
<br />
Final Rank Value (839.5) = Starting Rank Value (793.6) + Head To Head Adjustments (45.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.6
- 400 + ( ( 0.178 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 793.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1626 | 2024-12-22 | Metizport                                 | W   | 0.416      | 0.143        | 0.062 (0.004)    | 0.367 (0.026)    | 0 (0.000) |     9.56 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           11 |     1645 | 2024-12-22 | RUSH B (Russian team)                     | W   | 0.415      | 0.143        | 0.026 (0.002)    | 0.901 (0.064)    | 0 (0.000) |     8.90 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           10 |     1703 | 2024-12-21 | Nexus Gaming                              | W   | 0.409      | 0.143        | 0.161 (0.011)    | 0.539 (0.038)    | 0 (0.000) |    10.57 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            9 |     2010 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.366      | -            | -                | -                | -         |    -5.91 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            8 |     2017 | 2024-12-13 | ROYALS                                    | W   | 0.366      | 0.143        | 0.001 (0.000)    | 0.099 (0.006)    | 0 (0.000) |     3.30 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            7 |     2025 | 2024-12-13 | VOLT (European team)                      | W   | 0.365      | 0.143        | 0.003 (0.000)    | 0.139 (0.009)    | 0 (0.000) |     4.15 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            6 |     2199 | 2024-12-08 | VOLT (European team)                      | W   | 0.339      | 0.143        | 0.003 (0.000)    | 0.139 (0.008)    | 0 (0.000) |     3.96 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            5 |     2206 | 2024-12-08 | AMKAL ESPORTS                             | W   | 0.338      | 0.143        | 0.018 (0.001)    | 0.300 (0.017)    | 0 (0.000) |     5.18 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            4 |     2222 | 2024-12-08 | Kubix Esports                             | W   | 0.338      | 0.143        | 0.039 (0.002)    | 0.316 (0.018)    | 0 (0.000) |     6.90 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            3 |     4107 | 2024-11-03 | Fire Flux Esports                         | L   | 0.143      | -            | -                | -                | -         |    -1.64 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            2 |     4211 | 2024-11-02 | Dynamo Eclot                              | L   | 0.136      | -            | -                | -                | -         |    -0.94 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            1 |     4694 | 2024-10-25 | Copenhagen Wolves (American organization) | W   | 0.092      | 0.384        | 0.017 (0.001)    | 1.000 (0.042)    | 0 (0.000) |     1.78 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,465.16)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $16,949.15     | $8,465.16       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
