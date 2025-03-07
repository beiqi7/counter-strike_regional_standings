### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: isak, jocab, MisteM, r1nkle, REZ<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.5<br />
<br />
Final Rank Value (855.5) = Starting Rank Value (842.8) + Head To Head Adjustments (12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.180[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.8
- 400 + ( ( 0.201 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 842.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2918 | 2024-11-24 | Team Spirit      | L   | 0.259      | -            | -                | -                | -         |    -0.02 | isak, jocab, MisteM, r1nkle, REZ |
|           14 |     2938 | 2024-11-23 | 9Pandas          | W   | 0.256      | 0.143        | 0.084 (0.004)    | 0.481 (0.021)    | 1 (0.308) |     5.83 | isak, jocab, MisteM, r1nkle, REZ |
|           13 |     3032 | 2024-11-22 | TSM              | W   | 0.252      | 0.143        | 0.002 (0.000)    | 0.065 (0.003)    | 1 (0.302) |     2.40 | isak, jocab, MisteM, r1nkle, REZ |
|           12 |     3117 | 2024-11-21 | Team Falcons     | L   | 0.246      | -            | -                | -                | -         |    -0.02 | isak, jocab, MisteM, r1nkle, REZ |
|           11 |     3174 | 2024-11-21 | PARIVISION       | W   | 0.242      | 0.143        | 0.002 (0.000)    | 0.018 (0.001)    | 1 (0.290) |     2.10 | isak, jocab, MisteM, r1nkle, REZ |
|           10 |     3187 | 2024-11-20 | G2 Esports       | L   | 0.240      | -            | -                | -                | -         |    -0.21 | isak, jocab, MisteM, r1nkle, REZ |
|            9 |     3651 | 2024-11-12 | BetBoom Team     | L   | 0.192      | -            | -                | -                | -         |    -1.81 | isak, jocab, MisteM, r1nkle, REZ |
|            8 |     3682 | 2024-11-11 | Zero Tenacity    | W   | 0.188      | 0.384        | 0.020 (0.002)    | 0.778 (0.067)    | 0 (0.000) |     3.45 | isak, jocab, MisteM, r1nkle, REZ |
|            7 |     3799 | 2024-11-09 | Metizport        | L   | 0.176      | -            | -                | -                | -         |    -1.51 | isak, jocab, MisteM, r1nkle, REZ |
|            6 |     3852 | 2024-11-08 | Alliance         | W   | 0.171      | 0.143        | 0.013 (0.000)    | 0.516 (0.015)    | 1 (0.205) |     3.05 | isak, jocab, MisteM, r1nkle, REZ |
|            5 |     4680 | 2024-10-25 | Imperial Esports | L   | 0.093      | -            | -                | -                | -         |    -1.28 | isak, jocab, MisteM, r1nkle, REZ |
|            4 |     4733 | 2024-10-23 | Team Falcons     | L   | 0.083      | -            | -                | -                | -         |    -0.01 | isak, jocab, MisteM, r1nkle, REZ |
|            3 |     4773 | 2024-10-23 | Imperial Esports | W   | 0.081      | 0.934        | 0.061 (0.006)    | 0.576 (0.052)    | 0 (0.000) |     1.44 | isak, jocab, MisteM, r1nkle, REZ |
|            2 |     5124 | 2024-10-16 | JANO Esports     | L   | 0.043      | -            | -                | -                | -         |    -0.47 | isak, jocab, MisteM, r1nkle, REZ |
|            1 |     5143 | 2024-10-16 | B8               | L   | 0.042      | -            | -                | -                | -         |    -0.23 | isak, jocab, MisteM, r1nkle, REZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,084.76)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-12 |      0.232 | $1,500.00      | $347.26         |
| 2024-11-09 |      0.212 | $11,097.44     | $2,348.96       |
| 2024-10-20 |      0.078 | $5,000.00      | $388.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
