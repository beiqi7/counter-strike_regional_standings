### Roster Details<br />
Team Name: The Huns Esports<br />
Roster: Bart4k, cobrazera, nin9, Veccil, xerolte<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  901.8<br />
<br />
Final Rank Value (901.8) = Starting Rank Value (934.1) + Head To Head Adjustments (-32.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.374[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.293[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.1
- 400 + ( ( 0.242 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 934.1


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
|           28 |       98 | 2025-02-25 | ATOX Esports              | L   | 0.779      | -            | -                | -                | -         |    -7.55 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           27 |      121 | 2025-02-25 | Chinggis Warriors         | L   | 0.775      | -            | -                | -                | -         |   -17.54 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           26 |      155 | 2025-02-24 | Eruption                  | W   | 0.769      | 0.143        | 0.016 (0.002)    | 0.406 (0.053)    | 0 (0.000) |    11.44 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           25 |      619 | 2025-02-13 | ATOX Esports              | L   | 0.709      | -            | -                | -                | -         |    -7.09 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           24 |      622 | 2025-02-12 | Lynn Vision Gaming        | W   | 0.708      | 0.143        | 0.028 (0.003)    | 0.303 (0.037)    | 0 (0.000) |    12.72 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           23 |      640 | 2025-02-12 | Lynn Vision Gaming        | L   | 0.703      | -            | -                | -                | -         |   -10.06 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           22 |      643 | 2025-02-11 | Chinggis Warriors         | W   | 0.701      | 0.143        | 0.011 (0.001)    | 0.397 (0.048)    | 0 (0.000) |     6.19 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           21 |      660 | 2025-02-11 | ATOX Esports              | L   | 0.698      | -            | -                | -                | -         |    -6.90 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           20 |      667 | 2025-02-11 | Lynn Vision Gaming        | W   | 0.697      | 0.143        | 0.028 (0.003)    | 0.303 (0.036)    | 0 (0.000) |    11.51 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           19 |     1575 | 2024-12-28 | ATOX Esports              | L   | 0.447      | -            | -                | -                | -         |    -4.89 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           18 |     1582 | 2024-12-27 | IHC Esports               | W   | 0.446      | 0.384        | 0.003 (0.001)    | 0.134 (0.027)    | 1 (0.535) |     3.37 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           17 |     1596 | 2024-12-27 | Rare Atom                 | L   | 0.442      | -            | -                | -                | -         |    -8.71 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           16 |     1599 | 2024-12-26 | Chinggis Warriors         | W   | 0.441      | 0.384        | 0.011 (0.002)    | 0.397 (0.081)    | 1 (0.529) |     3.61 | Bart4k, cobrazera, nin9, Veccil, xerolte    |
|           15 |     3108 | 2024-11-22 | IHC Esports               | L   | 0.247      | -            | -                | -                | -         |    -6.03 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           14 |     3176 | 2024-11-21 | Ex-GR Gaming              | W   | 0.241      | 0.333        | 0.008 (0.001)    | -                | 0 (0.000) |     1.72 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           13 |     3181 | 2024-11-20 | Just Swing (Chinese team) | L   | 0.241      | -            | -                | -                | -         |    -5.93 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|           12 |     3446 | 2024-11-16 | Metizport                 | L   | 0.215      | -            | -                | -                | -         |    -2.52 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           11 |     3512 | 2024-11-15 | Team Czech Republic       | L   | 0.209      | -            | -                | -                | -         |    -5.15 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|           10 |     3519 | 2024-11-15 | Kitsune Esports           | W   | 0.209      | 0.617        | -                | 0.069 (0.011)    | 1 (0.250) |     0.93 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|            9 |     3529 | 2024-11-14 | Dusty Roots               | W   | 0.205      | 0.617        | 0.009 (0.001)    | 0.257 (0.039)    | 1 (0.247) |     1.94 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|            8 |     3596 | 2024-11-13 | Partizan Esports          | L   | 0.199      | -            | -                | -                | -         |    -2.00 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|            7 |     3604 | 2024-11-13 | SINNERS Academy           | W   | 0.199      | 0.617        | 0.001 (0.000)    | 0.072 (0.011)    | 1 (0.238) |     1.53 | Bart4k, cobrazera, nin9, wndrz, xerolte     |
|            6 |     3869 | 2024-11-07 | IHC Esports               | L   | 0.168      | -            | -                | -                | -         |    -4.33 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|            5 |     3966 | 2024-11-05 | DEWA United               | W   | 0.158      | -            | -                | -                | -         |     0.38 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|            4 |     3968 | 2024-11-05 | Gods Reign                | W   | 0.157      | 0.333        | 0.023 (0.001)    | 0.390 (0.025)    | -         |     2.42 | Bart4k, cobrazera, nin9, wonderzce, xerolte |
|            3 |     5056 | 2024-10-17 | Lynn Vision Gaming        | L   | 0.047      | -            | -                | -                | -         |    -0.74 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            2 |     5147 | 2024-10-16 | SayGGTeam                 | W   | 0.042      | -            | -                | -                | -         |     0.25 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |
|            1 |     5210 | 2024-10-15 | Unsettled Resentment      | L   | 0.036      | -            | -                | -                | -         |    -0.87 | Bart4k, cobrazera, nin9, sk0R, Tamiraarita  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,467.96)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.543 | $1,500.00      | $814.38         |
| 2024-11-17 |      0.265 | $12,500.00     | $3,314.24       |
| 2024-11-03 |      0.170 | $2,000.00      | $339.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
