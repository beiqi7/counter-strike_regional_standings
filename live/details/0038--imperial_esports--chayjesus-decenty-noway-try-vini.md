### Roster Details<br />
Team Name: Imperial Esports<br />
Roster: chayJESUS, decenty, noway, try, VINI<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  991.4<br />
<br />
Final Rank Value (991.4) = Starting Rank Value (888.6) + Head To Head Adjustments (102.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 888.6
- 400 + ( ( 0.222 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 888.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      200 | 2025-02-22 | Sharks Esports    | W   | 0.762      | 0.371        | 0.051 (0.017)    | 0.636 (0.215)    | 0 (0.000) |    14.54 | chayJESUS, decenty, noway, try, VINI      |
|           24 |      202 | 2025-02-22 | Fluxo             | W   | 0.761      | 0.371        | 0.050 (0.017)    | 0.411 (0.139)    | 0 (0.000) |    12.02 | chayJESUS, decenty, noway, try, VINI      |
|           23 |      249 | 2025-02-21 | Legacy            | W   | 0.756      | 0.371        | 0.032 (0.011)    | 0.556 (0.187)    | 0 (0.000) |     9.56 | chayJESUS, decenty, noway, try, VINI      |
|           22 |      320 | 2025-02-20 | MIBR Academy      | W   | 0.749      | 0.371        | -                | 0.361 (0.120)    | 0 (0.000) |     4.69 | chayJESUS, decenty, noway, try, VINI, zqk |
|           21 |      648 | 2025-02-11 | Sharks Esports    | L   | 0.701      | -            | -                | -                | -         |    -8.20 | chayJESUS, decenty, noway, try, VINI      |
|           20 |      652 | 2025-02-11 | Fluxo             | L   | 0.700      | -            | -                | -                | -         |   -11.07 | chayJESUS, decenty, noway, try, VINI      |
|           19 |      717 | 2025-02-09 | MIBR              | W   | 0.689      | 0.143        | 0.105 (0.012)    | -                | 0 (0.000) |    17.77 | chayJESUS, decenty, noway, try, VINI      |
|           18 |      738 | 2025-02-09 | PaiN Gaming       | W   | 0.687      | 0.143        | 0.357 (0.042)    | 0.371 (0.044)    | 0 (0.000) |    21.21 | chayJESUS, decenty, noway, try, VINI      |
|           17 |      763 | 2025-02-08 | Nitro.GG          | W   | 0.683      | 0.143        | 0.001 (0.000)    | 0.387 (0.045)    | 0 (0.000) |     4.07 | chayJESUS, decenty, noway, try, VINI      |
|           16 |      769 | 2025-02-08 | KRÜ Esports       | W   | 0.683      | -            | -                | -                | 0 (0.000) |     5.34 | chayJESUS, decenty, noway, try, VINI      |
|           15 |      812 | 2025-02-08 | Fluxo             | W   | 0.682      | 0.143        | 0.050 (0.006)    | 0.411 (0.048)    | 0 (0.000) |    12.39 | chayJESUS, decenty, noway, try, VINI      |
|           14 |      842 | 2025-02-07 | ShindeN           | W   | 0.678      | -            | -                | -                | 0 (0.000) |     4.35 | chayJESUS, decenty, noway, try, VINI      |
|           13 |      886 | 2025-02-07 | AdalYamigos       | W   | 0.677      | 0.143        | -                | 0.484 (0.056)    | -         |     6.25 | chayJESUS, decenty, noway, try, VINI      |
|           12 |      964 | 2025-02-05 | AdalYamigos       | W   | 0.666      | 0.143        | -                | 0.484 (0.055)    | -         |     6.29 | chayJESUS, decenty, noway, try, VINI      |
|           11 |      986 | 2025-02-05 | Fake do Biru      | W   | 0.666      | -            | -                | -                | -         |     3.42 | chayJESUS, decenty, noway, try, VINI      |
|           10 |     4594 | 2024-10-26 | The MongolZ       | L   | 0.098      | -            | -                | -                | -         |    -0.01 | decenty, felps, noway, try, VINI          |
|            9 |     4680 | 2024-10-25 | Ninjas in Pyjamas | W   | 0.093      | 0.934        | 0.015 (0.002)    | -                | -         |     1.28 | decenty, felps, noway, try, VINI          |
|            8 |     4750 | 2024-10-23 | Legacy            | W   | 0.082      | 0.934        | 0.032 (0.003)    | 0.556 (0.051)    | -         |     1.18 | decenty, felps, noway, try, VINI          |
|            7 |     4773 | 2024-10-23 | Ninjas in Pyjamas | L   | 0.081      | -            | -                | -                | -         |    -1.44 | decenty, felps, noway, try, VINI          |
|            6 |     5027 | 2024-10-17 | RED Canids        | L   | 0.050      | -            | -                | -                | -         |    -1.07 | decenty, felps, noway, try, VINI          |
|            5 |     5085 | 2024-10-16 | Sharks Esports    | W   | 0.044      | 0.450        | 0.051 (0.001)    | -                | -         |     1.04 | decenty, felps, noway, try, VINI          |
|            4 |     5167 | 2024-10-15 | InSanitY Sports   | L   | 0.039      | -            | -                | -                | -         |    -0.95 | decenty, felps, noway, try, VINI          |
|            3 |     5465 | 2024-10-09 | Team Solid        | W   | 0.006      | -            | -                | -                | -         |     0.08 | decenty, felps, noway, try, VINI          |
|            2 |     5474 | 2024-10-09 | Team Solid        | W   | 0.005      | -            | -                | -                | -         |     0.08 | decenty, felps, noway, try, VINI          |
|            1 |     5548 | 2024-10-08 | PaiN Gaming       | W   | 0.000      | -            | -                | -                | -         |     0.00 | decenty, felps, noway, try, VINI          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,815.32)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      0.914 | $10,000.00     | $9,142.13       |
| 2024-11-03 |      0.172 | $20,000.00     | $3,436.11       |
| 2024-10-20 |      0.079 | $3,000.00      | $237.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
