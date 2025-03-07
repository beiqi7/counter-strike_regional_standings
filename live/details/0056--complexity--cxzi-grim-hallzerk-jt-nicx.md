### Roster Details<br />
Team Name: Complexity<br />
Roster: Cxzi, Grim, hallzerk, JT, nicx<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [13]( ../standings_americas.md)<br />
<br />
Final Rank Value:  936.3<br />
<br />
Final Rank Value (936.3) = Starting Rank Value (946.9) + Head To Head Adjustments (-10.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.142[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 946.9
- 400 + ( ( 0.248 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 946.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |      419 | 2025-02-17 | SAW             | L   | 0.733      | -            | -                | -                | -         |    -2.60 | Cxzi, Grim, hallzerk, JT, nicx |
|            8 |      477 | 2025-02-16 | Imperial Female | W   | 0.726      | 1.000        | 0.146 (0.127)    | 0.159 (0.138)    | 1 (0.871) |    13.68 | Cxzi, Grim, hallzerk, JT, nicx |
|            7 |      545 | 2025-02-15 | Virtus.pro      | L   | 0.720      | -            | -                | -                | -         |    -0.40 | Cxzi, Grim, hallzerk, JT, nicx |
|            6 |      592 | 2025-02-14 | The MongolZ     | L   | 0.714      | -            | -                | -                | -         |    -0.12 | Cxzi, Grim, hallzerk, JT, nicx |
|            5 |      811 | 2025-02-08 | Betera Esports  | L   | 0.682      | -            | -                | -                | -         |   -17.07 | Cxzi, Grim, hallzerk, JT, nicx |
|            4 |      856 | 2025-02-07 | SIUUUUUU        | W   | 0.678      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.89 | Cxzi, Grim, hallzerk, JT, nicx |
|            3 |     1188 | 2025-01-31 | Team Liquid     | L   | 0.637      | -            | -                | -                | -         |    -4.62 | Cxzi, Grim, hallzerk, JT, nicx |
|            2 |     1201 | 2025-01-29 | Eternal Fire    | L   | 0.627      | -            | -                | -                | -         |    -0.08 | Cxzi, Grim, hallzerk, JT, nicx |
|            1 |     1457 | 2025-01-16 | Virtus.pro      | L   | 0.553      | -            | -                | -                | -         |    -0.34 | Cxzi, Grim, hallzerk, JT, nicx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,290.80)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $18,750.00     | $17,228.30      |
| 2025-02-09 |      0.825 | $2,500.00      | $2,062.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
