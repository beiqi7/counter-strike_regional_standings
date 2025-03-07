### Roster Details<br />
Team Name: DUSTY<br />
Roster: EddezeNNN, PANDAZ, RavlE, TH0R, Vargur<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  888.0<br />
<br />
Final Rank Value (888.0) = Starting Rank Value (896.9) + Head To Head Adjustments (-9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.446[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 896.9
- 400 + ( ( 0.225 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 896.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      201 | 2025-02-22 | Ctrl Alt Defeat   | L   | 0.761      | -            | -                | -                | -         |    -8.73 | EddezeNNN, PANDAZ, RavlE, TH0R, Vargur |
|            5 |      228 | 2025-02-22 | Belfast Storm     | W   | 0.760      | 0.143        | 0.002 (0.000)    | 0.116 (0.015)    | 1 (0.912) |     7.35 | EddezeNNN, PANDAZ, RavlE, TH0R, Vargur |
|            4 |      236 | 2025-02-22 | Viperio Academy   | W   | 0.759      | 0.143        | 0.001 (0.000)    | 0.099 (0.013)    | 1 (0.911) |     4.42 | EddezeNNN, PANDAZ, RavlE, TH0R, Vargur |
|            3 |      241 | 2025-02-22 | Pigeons           | W   | 0.758      | 0.143        | 0.000 (0.000)    | 0.055 (0.007)    | 1 (0.910) |     2.37 | EddezeNNN, PANDAZ, RavlE, TH0R, Vargur |
|            2 |      257 | 2025-02-21 | 8Sins             | L   | 0.755      | -            | -                | -                | -         |    -9.43 | EddezeNNN, PANDAZ, RavlE, TH0R, Vargur |
|            1 |     3614 | 2024-11-13 | Ins (Polish team) | L   | 0.198      | -            | -                | -                | -         |    -4.93 | brnr, EddezeNNN, Midgard, PANDAZ, TH0R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($376.65)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.918 | $410.49        | $376.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
