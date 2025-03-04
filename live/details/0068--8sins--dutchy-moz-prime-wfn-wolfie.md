### Roster Details<br />
Team Name: 8Sins<br />
Roster: Dutchy, moz, Prime, wfn, Wolfie<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  935.7<br />
<br />
Final Rank Value (935.7) = Starting Rank Value (962.5) + Head To Head Adjustments (-26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.513[<sup>2</sup>](#table1)

The average of these factors is 0.270<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 962.5
- 400 + ( ( 0.270 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 962.5


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
|           15 |      182 | 2025-02-23 | ALASKA                    | L   | 1.000      | -            | -                | -                | -         |   -15.96 | Dutchy, moz, Prime, wfn, Wolfie  |
|           14 |      218 | 2025-02-22 | ALASKA                    | W   | 1.000      | 0.143        | 0.036 (0.005)    | 0.888 (0.127)    | 1 (1.000) |    14.80 | Dutchy, moz, Prime, wfn, Wolfie  |
|           13 |      225 | 2025-02-22 | ANTARCTICA (British team) | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.125 (0.018)    | 1 (1.000) |     7.31 | Dutchy, moz, Prime, wfn, Wolfie  |
|           12 |      249 | 2025-02-21 | DUSTY                     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.146 (0.021)    | 1 (1.000) |    11.27 | Dutchy, moz, Prime, wfn, Wolfie  |
|           11 |      848 | 2025-02-07 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |   -23.33 | Dutchy, moz, Prime, wfn, Wolfie  |
|           10 |     3072 | 2024-11-20 | Belfast Storm             | L   | 0.512      | -            | -                | -                | -         |   -12.00 | coldpera, f0cus, moz, Prime, wfn |
|            9 |     3742 | 2024-11-07 | The Last Resort           | L   | 0.425      | -            | -                | -                | -         |   -10.35 | coldpera, f0cus, moz, Prime, wfn |
|            8 |     3786 | 2024-11-06 | Belfast Storm             | W   | 0.418      | 0.143        | 0.003 (0.000)    | 0.163 (0.010)    | 0 (0.000) |     3.04 | coldpera, f0cus, moz, Prime, wfn |
|            7 |     3787 | 2024-11-06 | Annex Esports             | W   | 0.418      | 0.143        | 0.000 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     1.63 | coldpera, f0cus, moz, Prime, wfn |
|            6 |     3842 | 2024-11-05 | ROYALS                    | W   | 0.411      | 0.143        | 0.005 (0.000)    | 0.202 (0.012)    | 0 (0.000) |     2.66 | coldpera, f0cus, moz, Prime, wfn |
|            5 |     4403 | 2024-10-27 | Verdant fe                | L   | 0.348      | -            | -                | -                | -         |    -8.78 | f0cus, Menace, moz, Prime, wfn   |
|            4 |     4420 | 2024-10-26 | The Last Resort           | W   | 0.344      | 0.143        | 0.001 (0.000)    | 0.162 (0.008)    | 1 (0.344) |     2.47 | f0cus, Menace, moz, Prime, wfn   |
|            3 |     4434 | 2024-10-26 | The Last Resort           | W   | 0.343      | 0.143        | 0.000 (0.000)    | 0.042 (0.002)    | 1 (0.343) |     1.53 | f0cus, Menace, moz, Prime, wfn   |
|            2 |     4459 | 2024-10-26 | ALASKA                    | L   | 0.342      | -            | -                | -                | -         |    -2.61 | f0cus, Menace, moz, Prime, wfn   |
|            1 |     4502 | 2024-10-25 | Annex Esports             | W   | 0.337      | 0.143        | 0.000 (0.000)    | 0.059 (0.003)    | 1 (0.337) |     1.51 | f0cus, Menace, moz, Prime, wfn   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,655.03)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $1,326.20      | $1,326.20       |
| 2024-10-27 |      0.350 | $939.67        | $328.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
