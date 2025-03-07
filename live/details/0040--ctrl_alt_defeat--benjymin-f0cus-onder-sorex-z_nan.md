### Roster Details<br />
Team Name: Ctrl Alt Defeat<br />
Roster: BENJYMIN, f0cus, onder, Sorex, z_nan<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  986.8<br />
<br />
Final Rank Value (986.8) = Starting Rank Value (990.2) + Head To Head Adjustments (-3.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.594[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.2
- 400 + ( ( 0.268 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 990.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      195 | 2025-02-23 | ALASKA                    | L   | 0.764      | -            | -                | -                | -         |   -11.50 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            5 |      201 | 2025-02-22 | DUSTY                     | W   | 0.761      | 0.143        | 0.002 (0.000)    | 0.166 (0.022)    | 1 (0.913) |     8.73 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            4 |      227 | 2025-02-22 | ANTARCTICA (British team) | W   | 0.760      | 0.143        | 0.002 (0.000)    | 0.110 (0.014)    | 1 (0.912) |     4.61 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            3 |      235 | 2025-02-22 | The Last Resort           | W   | 0.759      | 0.143        | 0.001 (0.000)    | 0.116 (0.015)    | 1 (0.911) |     4.50 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            2 |      240 | 2025-02-22 | Proqfanclub               | W   | 0.758      | 0.143        | 0.000 (0.000)    | 0.055 (0.007)    | 1 (0.910) |     1.45 | BENJYMIN, f0cus, onder, Sorex, z_nan |
|            1 |      260 | 2025-02-21 | ALASKA                    | L   | 0.755      | -            | -                | -                | -         |   -11.20 | BENJYMIN, f0cus, onder, Sorex, z_nan |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($550.49)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.918 | $599.95        | $550.49         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
