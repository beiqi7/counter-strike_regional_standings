### Roster Details<br />
Team Name: 8Sins<br />
Roster: Dutchy, moz, Prime, wfn, Wolfie<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  976.6<br />
<br />
Final Rank Value (976.6) = Starting Rank Value (987.3) + Head To Head Adjustments (-10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.502[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 987.3
- 400 + ( ( 0.266 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 987.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      190 | 2025-02-23 | ALASKA                    | L   | 0.765      | -            | -                | -                | -         |   -10.78 | Dutchy, moz, Prime, wfn, Wolfie  |
|           18 |      226 | 2025-02-22 | ALASKA                    | W   | 0.760      | 0.143        | 0.033 (0.004)    | 0.737 (0.096)    | 1 (0.912) |    13.11 | Dutchy, moz, Prime, wfn, Wolfie  |
|           17 |      233 | 2025-02-22 | ANTARCTICA (British team) | W   | 0.759      | 0.143        | 0.002 (0.000)    | 0.110 (0.014)    | 1 (0.911) |     5.05 | Dutchy, moz, Prime, wfn, Wolfie  |
|           16 |      257 | 2025-02-21 | DUSTY                     | W   | 0.755      | 0.143        | 0.002 (0.000)    | 0.166 (0.022)    | 1 (0.906) |     9.43 | Dutchy, moz, Prime, wfn, Wolfie  |
|           15 |      872 | 2025-02-07 | RUBY                      | L   | 0.677      | -            | -                | -                | -         |   -19.70 | Dutchy, moz, Prime, wfn, Wolfie  |
|           14 |     3194 | 2024-11-20 | Belfast Storm             | L   | 0.239      | -            | -                | -                | -         |    -5.88 | coldpera, f0cus, moz, Prime, wfn |
|           13 |     3877 | 2024-11-07 | The Last Resort           | L   | 0.166      | -            | -                | -                | -         |    -4.21 | coldpera, f0cus, moz, Prime, wfn |
|           12 |     3922 | 2024-11-06 | Belfast Storm             | W   | 0.161      | 0.143        | 0.002 (0.000)    | 0.116 (0.003)    | 0 (0.000) |     1.06 | coldpera, f0cus, moz, Prime, wfn |
|           11 |     3923 | 2024-11-06 | Annex Esports             | W   | 0.161      | 0.143        | 0.000 (0.000)    | 0.032 (0.001)    | 0 (0.000) |     0.56 | coldpera, f0cus, moz, Prime, wfn |
|           10 |     3981 | 2024-11-05 | ROYALS                    | W   | 0.155      | 0.143        | 0.001 (0.000)    | 0.099 (0.003)    | 0 (0.000) |     0.64 | coldpera, f0cus, moz, Prime, wfn |
|            9 |     4295 | 2024-10-31 | Dreams To Legends         | W   | 0.127      | 0.143        | -                | 0.049 (0.001)    | 0 (0.000) |     0.24 | f0cus, moz, Prime, wfn           |
|            8 |     4369 | 2024-10-30 | ALASKA                    | W   | 0.121      | 0.143        | 0.033 (0.001)    | 0.737 (0.015)    | -         |     3.00 | f0cus, moz, Prime, wfn           |
|            7 |     4564 | 2024-10-27 | Verdant fe                | L   | 0.103      | -            | -                | -                | -         |    -2.77 | f0cus, Menace, moz, Prime, wfn   |
|            6 |     4582 | 2024-10-26 | The Last Resort           | W   | 0.099      | 0.143        | 0.001 (0.000)    | 0.116 (0.002)    | 1 (0.119) |     0.62 | f0cus, Menace, moz, Prime, wfn   |
|            5 |     4597 | 2024-10-26 | The Last Resort           | W   | 0.098      | 0.143        | 0.000 (0.000)    | -                | 1 (0.118) |     0.34 | f0cus, Menace, moz, Prime, wfn   |
|            4 |     4622 | 2024-10-26 | ALASKA                    | L   | 0.097      | -            | -                | -                | -         |    -0.66 | f0cus, Menace, moz, Prime, wfn   |
|            3 |     4666 | 2024-10-25 | Annex Esports             | W   | 0.093      | 0.143        | 0.000 (0.000)    | 0.032 (0.001)    | 1 (0.112) |     0.35 | f0cus, Menace, moz, Prime, wfn   |
|            2 |     5030 | 2024-10-17 | The Last Resort           | W   | 0.049      | -            | -                | -                | -         |     0.06 | f0cus, moz, Prime, wfn           |
|            1 |     5090 | 2024-10-16 | TRAXXXMANIA               | L   | 0.044      | -            | -                | -                | -         |    -1.20 | f0cus, moz, Prime, wfn           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,334.02)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.918 | $1,326.20      | $1,216.88       |
| 2024-10-27 |      0.125 | $939.67        | $117.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
