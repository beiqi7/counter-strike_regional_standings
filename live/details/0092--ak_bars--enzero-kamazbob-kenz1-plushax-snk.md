### Roster Details<br />
Team Name: AK BARS<br />
Roster: enzero, kamazbob, kenz1, plushax, SNk<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  898.7<br />
<br />
Final Rank Value (898.7) = Starting Rank Value (875.2) + Head To Head Adjustments (23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.307[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 875.2
- 400 + ( ( 0.228 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 875.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1756 | 2024-12-15 | Team Novaq             | L   | 0.676      | -            | -                | -                | -         |    -3.94 | enzero, kamazbob, kenz1, plushax, SNk |
|           17 |     1827 | 2024-12-14 | AimAssassins           | W   | 0.669      | 0.333        | 0.005 (0.001)    | 0.243 (0.054)    | 1 (0.669) |    13.34 | enzero, kamazbob, kenz1, plushax, SNk |
|           16 |     1899 | 2024-12-13 | Team Novaq             | W   | 0.664      | 0.333        | 0.035 (0.008)    | 0.402 (0.089)    | 1 (0.664) |    17.43 | enzero, kamazbob, kenz1, plushax, SNk |
|           15 |     1908 | 2024-12-13 | GamePoint (Uzbek team) | W   | 0.663      | 0.333        | -                | 0.039 (0.009)    | 1 (0.663) |     4.55 | enzero, kamazbob, kenz1, plushax, SNk |
|           14 |     2425 | 2024-12-01 | RAGE (Kazakh team)     | W   | 0.585      | 0.143        | 0.006 (0.000)    | 0.183 (0.015)    | 0 (0.000) |     8.47 | enzero, kamazbob, kenz1, plushax, SNk |
|           13 |     2441 | 2024-12-01 | Mix52                  | W   | 0.584      | 0.143        | 0.002 (0.000)    | 0.065 (0.005)    | 0 (0.000) |     7.16 | enzero, kamazbob, kenz1, plushax, SNk |
|           12 |     2460 | 2024-12-01 | ALLINNERS              | L   | 0.584      | -            | -                | -                | -         |   -12.52 | enzero, kamazbob, kenz1, plushax, SNk |
|           11 |     3661 | 2024-11-09 | ALLINNERS              | L   | 0.437      | -            | -                | -                | -         |    -9.13 | arun, enzero, kamazbob, kenz1, Yaqk   |
|           10 |     3683 | 2024-11-09 | DEPO                   | W   | 0.436      | 0.143        | 0.007 (0.000)    | 0.295 (0.018)    | 0 (0.000) |     5.51 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            9 |     3716 | 2024-11-08 | ALLINNERS              | L   | 0.430      | -            | -                | -                | -         |    -9.21 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            8 |     3816 | 2024-11-06 | MYSKILL                | W   | 0.416      | 0.143        | 0.003 (0.000)    | 0.129 (0.008)    | 0 (0.000) |     3.40 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            7 |     4071 | 2024-11-02 | Yamato Esports         | W   | 0.389      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.50 | arun, enzero, kamazbob, kenz1, Yaqk   |
|            6 |     5452 | 2024-10-06 | RAGE (Kazakh team)     | L   | 0.209      | -            | -                | -                | -         |    -3.41 | enzero, kade0, kamazbob, kenz1, SNk   |
|            5 |     5463 | 2024-10-05 | MYSKILL                | W   | 0.208      | 0.333        | 0.003 (0.000)    | 0.129 (0.009)    | 1 (0.208) |     1.70 | enzero, kade0, kamazbob, kenz1, SNk   |
|            4 |     5532 | 2024-10-05 | DEPO                   | W   | 0.202      | 0.333        | 0.007 (0.000)    | 0.295 (0.020)    | 1 (0.202) |     2.52 | enzero, kade0, kamazbob, kenz1, SNk   |
|            3 |     5541 | 2024-10-04 | RAGE (Kazakh team)     | L   | 0.201      | -            | -                | -                | -         |    -3.32 | enzero, kade0, kamazbob, kenz1, SNk   |
|            2 |     6413 | 2024-09-22 | MYSKILL                | W   | 0.116      | 0.143        | 0.003 (0.000)    | 0.129 (0.002)    | -         |     0.95 | enzero, kade0, kamazbob, kenz1, SNk   |
|            1 |     6944 | 2024-09-13 | MYSKILL                | L   | 0.061      | -            | -                | -                | -         |    -1.43 | arun, enzero, kamazbob, kenz1, SNk    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,666.68)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.676 | $2,500.00      | $1,688.90       |
| 2024-11-09 |      0.437 | $1,044.04      | $456.24         |
| 2024-10-06 |      0.209 | $2,500.00      | $521.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
