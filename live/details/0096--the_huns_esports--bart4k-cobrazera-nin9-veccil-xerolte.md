### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, Veccil, xerolte<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  895.5<br />
<br />
Final Rank Value (895.5) = Starting Rank Value (986.2) + Head To Head Adjustments (-90.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.391[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.2
- 400 + ( ( 0.282 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 986.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       92 | 2025-02-25 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -8.26 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           46 |      113 | 2025-02-25 | Chinggis Warriors         | L   | 1.000      | -            | -                | -                | -         |   -19.76 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           45 |      147 | 2025-02-24 | Eruption                  | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.479 (0.068)    | 0 (0.000) |    15.42 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           44 |      600 | 2025-02-13 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -8.30 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           43 |      602 | 2025-02-12 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.284 (0.041)    | 0 (0.000) |    15.89 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           42 |      620 | 2025-02-12 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -16.68 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           41 |      623 | 2025-02-11 | Chinggis Warriors         | W   | 1.000      | 0.143        | 0.019 (0.003)    | 0.449 (0.064)    | 0 (0.000) |    11.56 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           40 |      639 | 2025-02-11 | ATOX Esports              | L   | 1.000      | -            | -                | -                | -         |    -7.95 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           39 |      646 | 2025-02-11 | Lynn Vision Gaming        | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.284 (0.041)    | 0 (0.000) |    13.37 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           38 |     1455 | 2024-12-28 | ATOX Esports              | L   | 0.762      | -            | -                | -                | -         |    -6.93 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           37 |     1462 | 2024-12-27 | IHC Esports               | W   | 0.760      | 0.384        | -                | 0.157 (0.046)    | 1 (0.760) |     6.23 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           36 |     1475 | 2024-12-27 | Rare Atom                 | L   | 0.755      | -            | -                | -                | -         |   -14.05 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           35 |     1478 | 2024-12-26 | Chinggis Warriors         | W   | 0.754      | 0.384        | 0.019 (0.005)    | 0.449 (0.130)    | 1 (0.754) |     8.38 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           34 |     2351 | 2024-12-03 | SayGGTeam                 | L   | 0.595      | -            | -                | -                | -         |   -14.14 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           33 |     2358 | 2024-12-02 | Flashback Gaming          | L   | 0.594      | -            | -                | -                | -         |   -11.74 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           32 |     2361 | 2024-12-02 | The QUBE Esports          | W   | 0.594      | -            | -                | -                | -         |     1.54 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           31 |     2988 | 2024-11-22 | IHC Esports               | L   | 0.522      | -            | -                | -                | -         |   -12.96 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           30 |     3055 | 2024-11-21 | Ex-GR Gaming              | W   | 0.515      | 0.333        | 0.013 (0.002)    | -                | -         |     3.81 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           29 |     3060 | 2024-11-20 | Just Swing (Chinese team) | L   | 0.514      | -            | -                | -                | -         |   -12.73 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           28 |     3315 | 2024-11-16 | Metizport                 | L   | 0.483      | -            | -                | -                | -         |    -4.09 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           27 |     3382 | 2024-11-15 | Team Czech Republic       | L   | 0.476      | -            | -                | -                | -         |   -11.59 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           26 |     3388 | 2024-11-15 | Kitsune Esports           | W   | 0.476      | -            | -                | -                | 1 (0.476) |     1.76 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           25 |     3398 | 2024-11-14 | Dusty Roots               | W   | 0.472      | 0.617        | 0.010 (0.003)    | 0.372 (0.108)    | 1 (0.472) |     3.87 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           24 |     3464 | 2024-11-13 | Partizan Esports          | L   | 0.464      | -            | -                | -                | -         |    -4.09 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           23 |     3471 | 2024-11-13 | SINNERS Academy           | W   | 0.464      | -            | -                | -                | 1 (0.464) |     3.37 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           22 |     3734 | 2024-11-07 | IHC Esports               | L   | 0.427      | -            | -                | -                | -         |   -11.29 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           21 |     3827 | 2024-11-05 | DEWA United               | W   | 0.415      | -            | -                | -                | -         |     1.20 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           20 |     3829 | 2024-11-05 | Gods Reign                | W   | 0.414      | 0.333        | 0.024 (0.003)    | 0.447 (0.062)    | -         |     4.87 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           19 |     4860 | 2024-10-17 | Lynn Vision Gaming        | L   | 0.282      | -            | -                | -                | -         |    -5.87 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           18 |     4932 | 2024-10-16 | SayGGTeam                 | W   | 0.276      | -            | -                | -                | -         |     1.77 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           17 |     4992 | 2024-10-15 | Unsettled Resentment      | L   | 0.269      | -            | -                | -                | -         |    -6.74 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           16 |     5679 | 2024-10-02 | SayGGTeam                 | L   | 0.183      | -            | -                | -                | -         |    -4.71 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           15 |     5684 | 2024-10-02 | SayGGTeam                 | L   | 0.182      | -            | -                | -                | -         |    -4.75 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           14 |     5756 | 2024-10-01 | Gods Reign                | W   | 0.176      | 0.417        | 0.024 (0.002)    | 0.447 (0.033)    | -         |     2.05 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           13 |     5762 | 2024-10-01 | Gods Reign                | W   | 0.176      | 0.417        | 0.024 (0.002)    | 0.447 (0.033)    | -         |     2.08 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           12 |     5956 | 2024-09-28 | ATOX Esports              | W   | 0.156      | -            | -                | -                | -         |     0.96 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           11 |     5959 | 2024-09-28 | ATOX Esports              | W   | 0.156      | -            | -                | -                | -         |     0.97 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|           10 |     6059 | 2024-09-26 | Chinggis Warriors         | L   | 0.147      | -            | -                | -                | -         |    -3.20 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            9 |     6121 | 2024-09-26 | ATOX Esports              | L   | 0.142      | -            | -                | -                | -         |    -1.70 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            8 |     6134 | 2024-09-25 | The QUBE Esports          | W   | 0.140      | -            | -                | -                | 1 (0.140) |     0.16 | Bart4k, cobrazera, ncl, nin9, wonderzce     |
|            7 |     6196 | 2024-09-25 | -72C                      | W   | 0.136      | -            | -                | -                | -         |     0.32 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            6 |     6202 | 2024-09-25 | -72C                      | W   | 0.136      | -            | -                | -                | -         |     0.32 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            5 |     6294 | 2024-09-24 | TYLOO                     | W   | 0.129      | -            | -                | -                | -         |     2.48 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            4 |     6302 | 2024-09-24 | TYLOO                     | L   | 0.129      | -            | -                | -                | -         |    -1.60 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            3 |     7332 | 2024-09-07 | HXG Esports               | W   | 0.016      | -            | -                | -                | -         |     0.02 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            2 |     7408 | 2024-09-06 | Gods Reign                | W   | 0.009      | -            | -                | -                | -         |     0.10 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            1 |     7496 | 2024-09-05 | Come Mid                  | W   | 0.002      | -            | -                | -                | -         |     0.00 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,072.48)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.768 | $1,500.00      | $1,152.30       |
| 2024-11-17 |      0.490 | $12,500.00     | $6,130.26       |
| 2024-11-03 |      0.395 | $2,000.00      | $789.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
