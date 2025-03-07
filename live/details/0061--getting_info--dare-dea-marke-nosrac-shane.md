### Roster Details<br />
Team Name: Getting Info<br />
Roster: dare, dea, MarKE, nosraC, shane<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  907.5<br />
<br />
Final Rank Value (907.5) = Starting Rank Value (852.4) + Head To Head Adjustments (55.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.194[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.4
- 400 + ( ( 0.205 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 852.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |       46 | 2025-02-26 | Vagrants             | L   | 0.784      | -            | -                | -                | -         |   -17.71 | dare, dea, MarKE, nosraC, shane    |
|           26 |       51 | 2025-02-26 | Vagrants             | W   | 0.784      | 0.477        | -                | 0.487 (0.218)    | 0 (0.000) |     6.85 | dare, dea, MarKE, nosraC, shane    |
|           25 |       95 | 2025-02-25 | Chill Guys           | L   | 0.779      | -            | -                | -                | -         |   -13.98 | dare, dea, MarKE, nosraC, shane    |
|           24 |      102 | 2025-02-25 | Chill Guys           | W   | 0.779      | 0.477        | 0.002 (0.001)    | 0.582 (0.260)    | 0 (0.000) |    10.63 | dare, dea, MarKE, nosraC, shane    |
|           23 |      299 | 2025-02-20 | LAG Gaming           | W   | 0.751      | -            | -                | -                | 0 (0.000) |     2.89 | dare, dea, MarKE, nosraC, shane    |
|           22 |      302 | 2025-02-20 | LAG Gaming           | W   | 0.751      | -            | -                | -                | 0 (0.000) |     2.98 | dare, dea, MarKE, nosraC, shane    |
|           21 |      337 | 2025-02-19 | Marsborne            | W   | 0.746      | 0.477        | -                | 0.579 (0.247)    | 0 (0.000) |     4.66 | dare, dea, MarKE, nosraC, shane    |
|           20 |      342 | 2025-02-19 | Marsborne            | W   | 0.745      | 0.477        | -                | 0.579 (0.247)    | 0 (0.000) |     4.86 | dare, dea, MarKE, nosraC, shane    |
|           19 |      375 | 2025-02-18 | SUPER EVIL GANG      | W   | 0.740      | 0.477        | 0.008 (0.004)    | 0.345 (0.146)    | 0 (0.000) |     6.00 | dare, dea, MarKE, nosraC, shane    |
|           18 |      380 | 2025-02-18 | SUPER EVIL GANG      | W   | 0.740      | 0.477        | 0.008 (0.004)    | 0.345 (0.146)    | 0 (0.000) |     6.31 | dare, dea, MarKE, nosraC, shane    |
|           17 |      574 | 2025-02-14 | BLUEJAYS             | L   | 0.716      | -            | -                | -                | -         |   -12.35 | dea, MarKE, nosraC, rayxts, vanity |
|           16 |      605 | 2025-02-13 | MIGHT                | W   | 0.711      | -            | -                | -                | 0 (0.000) |     6.00 | dea, MarKE, nosraC, rayxts, vanity |
|           15 |      759 | 2025-02-08 | Marsborne            | L   | 0.684      | -            | -                | -                | -         |   -17.22 | dea, MarKE, nosraC, slump, vanity  |
|           14 |      831 | 2025-02-07 | Fisher College       | W   | 0.679      | -            | -                | -                | 0 (0.000) |     5.42 | dea, MarKE, nosraC, slump, vanity  |
|           13 |     1213 | 2025-01-28 | Chicken Coop Esports | W   | 0.623      | 0.477        | 0.006 (0.002)    | -                | -         |     4.13 | dare, dea, MarKE, nosraC, shane    |
|           12 |     1219 | 2025-01-28 | Chicken Coop Esports | W   | 0.623      | 0.477        | 0.006 (0.002)    | -                | -         |     4.28 | dare, dea, MarKE, nosraC, shane    |
|           11 |     1298 | 2025-01-24 | NRG                  | W   | 0.601      | 0.477        | 0.038 (0.013)    | 0.643 (0.221)    | -         |    12.99 | dare, dea, MarKE, nosraC, shane    |
|           10 |     1304 | 2025-01-24 | NRG                  | W   | 0.601      | 0.477        | 0.038 (0.013)    | 0.643 (0.221)    | -         |    13.58 | dare, dea, MarKE, nosraC, shane    |
|            9 |     1371 | 2025-01-22 | Aetheris             | W   | 0.590      | 0.477        | -                | 0.346 (0.117)    | -         |     2.58 | dare, dea, MarKE, nosraC, shane    |
|            8 |     1377 | 2025-01-22 | Aetheris             | W   | 0.590      | 0.477        | -                | 0.346 (0.117)    | -         |     2.65 | dare, dea, MarKE, nosraC, shane    |
|            7 |     1845 | 2024-12-15 | NRG                  | W   | 0.379      | 0.303        | 0.038 (0.005)    | -                | -         |     8.74 | dare, dea, nosraC, shane, snav     |
|            6 |     1849 | 2024-12-15 | Nouns Esports        | W   | 0.378      | 0.303        | 0.008 (0.001)    | -                | -         |     6.65 | dare, dea, nosraC, shane, snav     |
|            5 |     1895 | 2024-12-14 | BLUEJAYS             | W   | 0.373      | 0.303        | 0.006 (0.001)    | -                | -         |     6.17 | dare, dea, nosraC, shane, snav     |
|            4 |     2814 | 2024-11-26 | Final Form           | W   | 0.273      | -            | -                | -                | -         |     0.64 | dare, dea, nosraC, shane, snav     |
|            3 |     2888 | 2024-11-24 | NRG                  | L   | 0.261      | -            | -                | -                | -         |    -2.23 | dare, dea, nosraC, shane, snav     |
|            2 |     2941 | 2024-11-23 | Party Astronauts     | W   | 0.256      | -            | -                | -                | -         |     3.83 | dare, dea, nosraC, shane, snav     |
|            1 |     3262 | 2024-11-19 | Undone               | L   | 0.234      | -            | -                | -                | -         |    -4.28 | dare, dea, nosraC, shane, snav     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,817.22)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.454 | $4,000.00      | $1,817.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
