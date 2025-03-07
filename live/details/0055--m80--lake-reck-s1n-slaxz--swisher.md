### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
<br />
Final Rank Value:  940.0<br />
<br />
Final Rank Value (940.0) = Starting Rank Value (865.2) + Head To Head Adjustments (74.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.157[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.2
- 400 + ( ( 0.211 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 865.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       10 | 2025-03-01 | FlyQuest           | W   | 0.801      | 0.415        | 0.096 (0.038)    | 0.190 (0.076)    | 1 (0.961) |    18.73 | Lake, reck, s1n, slaxz-, Swisher |
|           20 |      562 | 2025-02-14 | BLUEJAYS           | W   | 0.717      | 0.143        | 0.006 (0.001)    | 0.287 (0.035)    | 0 (0.000) |     9.94 | Lake, reck, s1n, slaxz-, Swisher |
|           19 |      584 | 2025-02-14 | NRG                | W   | 0.716      | 0.143        | 0.038 (0.005)    | 0.643 (0.079)    | 0 (0.000) |    14.63 | Lake, reck, s1n, slaxz-, Swisher |
|           18 |      608 | 2025-02-13 | Nouns Esports      | W   | 0.710      | 0.143        | 0.008 (0.001)    | 0.649 (0.079)    | 0 (0.000) |    10.54 | Lake, reck, s1n, slaxz-, Swisher |
|           17 |      674 | 2025-02-10 | Marsborne          | W   | 0.695      | 0.143        | -                | 0.579 (0.069)    | 0 (0.000) |     5.67 | Lake, reck, s1n, slaxz-, Swisher |
|           16 |      718 | 2025-02-09 | Marsborne          | W   | 0.689      | 0.143        | -                | 0.579 (0.068)    | 0 (0.000) |     5.65 | Lake, reck, s1n, slaxz-, Swisher |
|           15 |      779 | 2025-02-08 | Bad News Capybaras | W   | 0.683      | 0.143        | 0.000 (0.000)    | 0.257 (0.030)    | 0 (0.000) |     5.25 | Lake, reck, s1n, slaxz-, Swisher |
|           14 |      907 | 2025-02-06 | Zomblers           | W   | 0.673      | -            | -                | -                | 0 (0.000) |     1.44 | Lake, reck, s1n, slaxz-, Swisher |
|           13 |      912 | 2025-02-06 | Lumen              | W   | 0.672      | -            | -                | -                | 0 (0.000) |     1.42 | Lake, reck, s1n, slaxz-, Swisher |
|           12 |     1455 | 2025-01-16 | FaZe Clan          | L   | 0.554      | -            | -                | -                | -         |    -0.08 | k1to, Lake, s1n, slaxz-, Swisher |
|           11 |     4658 | 2024-10-25 | BESTIA             | L   | 0.093      | -            | -                | -                | -         |    -1.46 | Lake, reck, s1n, slaxz-, Swisher |
|           10 |     4713 | 2024-10-24 | Aurora Gaming      | W   | 0.087      | 0.934        | 0.007 (0.001)    | 0.633 (0.062)    | 0 (0.000) |     1.20 | Lake, reck, s1n, slaxz-, Swisher |
|            9 |     4720 | 2024-10-24 | BESTIA             | L   | 0.086      | -            | -                | -                | -         |    -1.36 | Lake, reck, s1n, slaxz-, Swisher |
|            8 |     4864 | 2024-10-20 | NRG                | W   | 0.067      | 0.477        | 0.038 (0.001)    | 0.643 (0.025)    | -         |     1.49 | Lake, reck, s1n, slaxz-, Swisher |
|            7 |     5020 | 2024-10-17 | Legacy             | W   | 0.051      | 0.477        | 0.032 (0.001)    | -                | -         |     0.77 | Lake, reck, s1n, slaxz-, Swisher |
|            6 |     5074 | 2024-10-16 | NRG                | W   | 0.045      | 0.477        | 0.038 (0.001)    | 0.643 (0.017)    | -         |     1.00 | Lake, reck, s1n, slaxz-, Swisher |
|            5 |     5450 | 2024-10-09 | BLUEJAYS           | W   | 0.006      | 0.477        | 0.006 (0.000)    | -                | -         |     0.10 | Lake, reck, s1n, slaxz-, Swisher |
|            4 |     5456 | 2024-10-09 | BLUEJAYS           | L   | 0.006      | -            | -                | -                | -         |    -0.10 | Lake, reck, s1n, slaxz-, Swisher |
|            3 |     5529 | 2024-10-08 | Legacy             | W   | 0.001      | -            | -                | -                | -         |     0.01 | Lake, reck, s1n, slaxz-, Swisher |
|            2 |     5535 | 2024-10-08 | Legacy             | L   | 0.000      | -            | -                | -                | -         |    -0.01 | Lake, reck, s1n, slaxz-, Swisher |
|            1 |     5542 | 2024-10-08 | Wildcard           | W   | 0.000      | -            | -                | -                | -         |     0.00 | Lake, reck, s1n, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,000.00)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.080 | $25,000.00     | $2,000.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
