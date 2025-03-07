### Roster Details<br />
Team Name: Aimclub<br />
Roster: Blytz, lauNX, MoDo, s0und, zewts<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  858.8<br />
<br />
Final Rank Value (858.8) = Starting Rank Value (839.0) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.146[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 839.0
- 400 + ( ( 0.199 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 839.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1867 | 2024-12-15 | Nexus Gaming                | W   | 0.376      | 0.143        | 0.161 (0.010)    | 0.539 (0.035)    | 1 (0.451) |     9.42 | Blytz, lauNX, MoDo, s0und, zewts |
|            5 |     1931 | 2024-12-14 | JackBoyz                    | W   | 0.371      | 0.143        | 0.008 (0.001)    | 0.046 (0.003)    | 1 (0.445) |     3.38 | Blytz, lauNX, MoDo, s0und, zewts |
|            4 |     2706 | 2024-11-29 | DEVASTATION (Romanian team) | W   | 0.288      | 0.143        | 0.003 (0.000)    | 0.063 (0.003)    | 0 (0.000) |     2.37 | Blytz, lauNX, MoDo, s0und, zewts |
|            3 |     2718 | 2024-11-29 | HyperSpirit                 | W   | 0.287      | 0.143        | 0.000 (0.000)    | 0.071 (0.003)    | 0 (0.000) |     1.18 | Blytz, lauNX, MoDo, s0und, zewts |
|            2 |     2751 | 2024-11-28 | REDPack Esports             | W   | 0.282      | 0.143        | 0.002 (0.000)    | 0.067 (0.003)    | 0 (0.000) |     2.14 | Blytz, lauNX, MoDo, s0und, zewts |
|            1 |     2761 | 2024-11-28 | PORC CARTEL                 | W   | 0.282      | 0.143        | 0.001 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.35 | Blytz, lauNX, MoDo, s0und, zewts |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,927.16)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.451 | $13,130.94     | $5,927.16       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
