### Roster Details<br />
Team Name: Imperial Esports<br />
Roster: chayJESUS, decenty, noway, try, VINI<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1055.4<br />
<br />
Final Rank Value (1055.4) = Starting Rank Value (918.9) + Head To Head Adjustments (136.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.481[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.127[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.249<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.9
- 400 + ( ( 0.249 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 918.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      192 | 2025-02-22 | Sharks Esports    | W   | 1.000      | 0.371        | 0.064 (0.024)    | 0.683 (0.253)    | 0 (0.000) |    17.19 | chayJESUS, decenty, noway, try, VINI |
|           45 |      194 | 2025-02-22 | Fluxo             | W   | 1.000      | 0.371        | 0.065 (0.024)    | 0.479 (0.177)    | 0 (0.000) |    15.38 | chayJESUS, decenty, noway, try, VINI |
|           44 |      241 | 2025-02-21 | Legacy            | W   | 1.000      | 0.371        | 0.043 (0.016)    | 0.628 (0.233)    | 0 (0.000) |    12.68 | chayJESUS, decenty, noway, try, VINI |
|           43 |      628 | 2025-02-11 | Sharks Esports    | L   | 1.000      | -            | -                | -                | -         |   -13.65 | chayJESUS, decenty, noway, try, VINI |
|           42 |      632 | 2025-02-11 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -16.00 | chayJESUS, decenty, noway, try, VINI |
|           41 |      694 | 2025-02-09 | MIBR              | W   | 1.000      | 0.143        | 0.118 (0.017)    | -                | 0 (0.000) |    20.78 | chayJESUS, decenty, noway, try, VINI |
|           40 |      714 | 2025-02-09 | PaiN Gaming       | W   | 1.000      | 0.143        | 0.333 (0.048)    | 0.406 (0.058)    | 0 (0.000) |    29.65 | chayJESUS, decenty, noway, try, VINI |
|           39 |      739 | 2025-02-08 | Nitro.GG          | W   | 1.000      | 0.143        | -                | 0.524 (0.075)    | 0 (0.000) |     5.02 | chayJESUS, decenty, noway, try, VINI |
|           38 |      745 | 2025-02-08 | KRÜ Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.41 | chayJESUS, decenty, noway, try, VINI |
|           37 |      788 | 2025-02-08 | Fluxo             | W   | 1.000      | 0.143        | 0.065 (0.009)    | 0.479 (0.068)    | 0 (0.000) |    18.22 | chayJESUS, decenty, noway, try, VINI |
|           36 |      818 | 2025-02-07 | ShindeN           | W   | 1.000      | -            | -                | -                | -         |     6.17 | chayJESUS, decenty, noway, try, VINI |
|           35 |      862 | 2025-02-07 | AdalYamigos       | W   | 1.000      | -            | -                | -                | -         |     7.63 | chayJESUS, decenty, noway, try, VINI |
|           34 |      941 | 2025-02-05 | AdalYamigos       | W   | 1.000      | -            | -                | -                | -         |     7.76 | chayJESUS, decenty, noway, try, VINI |
|           33 |      963 | 2025-02-05 | Fake do Biru      | W   | 1.000      | -            | -                | -                | -         |     4.86 | chayJESUS, decenty, noway, try, VINI |
|           32 |     4431 | 2024-10-26 | The MongolZ       | L   | 0.343      | -            | -                | -                | -         |    -0.06 | decenty, felps, noway, try, VINI     |
|           31 |     4516 | 2024-10-25 | Ninjas in Pyjamas | W   | 0.337      | -            | -                | -                | -         |     4.92 | decenty, felps, noway, try, VINI     |
|           30 |     4575 | 2024-10-23 | Legacy            | W   | 0.324      | 0.934        | 0.043 (0.013)    | 0.628 (0.190)    | -         |     4.98 | decenty, felps, noway, try, VINI     |
|           29 |     4596 | 2024-10-23 | Ninjas in Pyjamas | L   | 0.323      | -            | -                | -                | -         |    -5.48 | decenty, felps, noway, try, VINI     |
|           28 |     4833 | 2024-10-17 | RED Canids        | L   | 0.285      | -            | -                | -                | -         |    -5.58 | decenty, felps, noway, try, VINI     |
|           27 |     4887 | 2024-10-16 | Sharks Esports    | W   | 0.278      | 0.450        | -                | 0.683 (0.086)    | -         |     6.49 | decenty, felps, noway, try, VINI     |
|           26 |     4951 | 2024-10-15 | InSanitY Sports   | L   | 0.272      | -            | -                | -                | -         |    -6.16 | decenty, felps, noway, try, VINI     |
|           25 |     5233 | 2024-10-09 | Team Solid        | W   | 0.232      | 0.450        | -                | 0.616 (0.064)    | -         |     3.05 | decenty, felps, noway, try, VINI     |
|           24 |     5241 | 2024-10-09 | Team Solid        | W   | 0.232      | 0.450        | -                | 0.616 (0.064)    | -         |     3.11 | decenty, felps, noway, try, VINI     |
|           23 |     5307 | 2024-10-08 | PaiN Gaming       | W   | 0.225      | 0.450        | 0.333 (0.034)    | -                | -         |     6.83 | decenty, felps, noway, try, VINI     |
|           22 |     5315 | 2024-10-08 | PaiN Gaming       | L   | 0.225      | -            | -                | -                | -         |    -0.27 | decenty, felps, noway, try, VINI     |
|           21 |     5369 | 2024-10-07 | Complexity        | L   | 0.218      | -            | -                | -                | -         |    -2.72 | decenty, felps, noway, try, VINI     |
|           20 |     5401 | 2024-10-07 | Natus Vincere     | L   | 0.216      | -            | -                | -                | -         |    -0.09 | decenty, felps, noway, try, VINI     |
|           19 |     5417 | 2024-10-06 | MIBR              | L   | 0.212      | -            | -                | -                | -         |    -1.61 | decenty, felps, noway, try, VINI     |
|           18 |     5419 | 2024-10-06 | MIBR              | W   | 0.212      | 0.450        | 0.118 (0.011)    | -                | -         |     5.12 | decenty, felps, noway, try, VINI     |
|           17 |     5564 | 2024-10-04 | RED Canids        | L   | 0.198      | -            | -                | -                | -         |    -3.82 | decenty, felps, noway, try, VINI     |
|           16 |     5647 | 2024-10-02 | Hype Esports      | W   | 0.185      | -            | -                | -                | -         |     1.21 | decenty, felps, noway, try, VINI     |
|           15 |     5653 | 2024-10-02 | Hype Esports      | W   | 0.185      | -            | -                | -                | -         |     1.22 | decenty, felps, noway, try, VINI     |
|           14 |     5717 | 2024-10-01 | Sharks Esports    | W   | 0.179      | -            | -                | -                | -         |     4.26 | decenty, felps, noway, try, VINI     |
|           13 |     5722 | 2024-10-01 | Sharks Esports    | L   | 0.178      | -            | -                | -                | -         |    -1.37 | decenty, felps, noway, try, VINI     |
|           12 |     5782 | 2024-09-30 | Fluxo             | L   | 0.172      | -            | -                | -                | -         |    -2.20 | decenty, felps, noway, try, VINI     |
|           11 |     5785 | 2024-09-30 | Fluxo             | L   | 0.172      | -            | -                | -                | -         |    -2.23 | decenty, felps, noway, try, VINI     |
|           10 |     6106 | 2024-09-26 | Sharks Esports    | W   | 0.143      | -            | -                | -                | -         |     3.43 | decenty, felps, noway, try, VINI     |
|            9 |     6152 | 2024-09-25 | BESTIA            | L   | 0.139      | -            | -                | -                | -         |    -2.42 | decenty, felps, noway, try, VINI     |
|            8 |     6158 | 2024-09-25 | BESTIA            | W   | 0.138      | -            | -                | -                | -         |     1.96 | decenty, felps, noway, try, VINI     |
|            7 |     6184 | 2024-09-25 | BESTIA            | W   | 0.137      | -            | -                | -                | -         |     1.97 | decenty, felps, noway, try, VINI     |
|            6 |     6659 | 2024-09-18 | Team Spirit       | L   | 0.090      | -            | -                | -                | -         |    -0.01 | decenty, felps, noway, try, VINI     |
|            5 |     6872 | 2024-09-14 | M80               | L   | 0.064      | -            | -                | -                | -         |    -0.92 | decenty, felps, noway, try, VINI     |
|            4 |     7068 | 2024-09-11 | MOUZ              | W   | 0.044      | 0.889        | 1.000 (0.039)    | -                | 1 (0.044) |     1.38 | decenty, felps, noway, try, VINI     |
|            3 |     7133 | 2024-09-10 | BIG               | W   | 0.036      | -            | -                | -                | 1 (0.036) |     1.10 | decenty, felps, noway, try, VINI     |
|            2 |     7366 | 2024-09-06 | ODDIK             | W   | 0.012      | -            | -                | -                | -         |     0.18 | decenty, felps, noway, try, VINI     |
|            1 |     7368 | 2024-09-06 | ODDIK             | W   | 0.011      | -            | -                | -                | -         |     0.17 | decenty, felps, noway, try, VINI     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,990.57)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-11-03 |      0.397 | $20,000.00     | $7,941.75       |
| 2024-10-20 |      0.304 | $3,000.00      | $912.93         |
| 2024-10-13 |      0.257 | $4,000.00      | $1,027.80       |
| 2024-10-05 |      0.203 | $1,832.41      | $372.85         |
| 2024-09-22 |      0.116 | $23,500.00     | $2,735.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
