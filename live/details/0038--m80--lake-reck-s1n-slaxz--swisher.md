### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1056.9<br />
<br />
Final Rank Value (1056.9) = Starting Rank Value (950.8) + Head To Head Adjustments (106.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.423[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.171[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 950.8
- 400 + ( ( 0.265 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 950.8


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
|           41 |        6 | 2025-03-01 | FlyQuest           | W   | 1.000      | 0.889        | 0.099 (0.088)    | 0.267 (0.237)    | 1 (1.000) |    21.29 | Lake, reck, s1n, slaxz-, Swisher |
|           40 |      538 | 2025-02-14 | BLUEJAYS           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.65 | Lake, reck, s1n, slaxz-, Swisher |
|           39 |      560 | 2025-02-14 | NRG                | W   | 1.000      | 0.143        | 0.057 (0.008)    | 0.516 (0.074)    | 0 (0.000) |    17.74 | Lake, reck, s1n, slaxz-, Swisher |
|           38 |      591 | 2025-02-13 | Nouns Esports      | W   | 1.000      | 0.143        | -                | 0.601 (0.086)    | 0 (0.000) |    12.08 | Lake, reck, s1n, slaxz-, Swisher |
|           37 |      655 | 2025-02-10 | Marsborne          | W   | 1.000      | 0.143        | -                | 0.386 (0.055)    | 0 (0.000) |     5.25 | Lake, reck, s1n, slaxz-, Swisher |
|           36 |      697 | 2025-02-09 | Marsborne          | W   | 1.000      | 0.143        | -                | 0.386 (0.055)    | 0 (0.000) |     5.17 | Lake, reck, s1n, slaxz-, Swisher |
|           35 |      757 | 2025-02-08 | Bad News Capybaras | W   | 1.000      | -            | -                | -                | -         |     4.35 | Lake, reck, s1n, slaxz-, Swisher |
|           34 |      885 | 2025-02-06 | Zomblers           | W   | 1.000      | -            | -                | -                | -         |     1.21 | Lake, reck, s1n, slaxz-, Swisher |
|           33 |      890 | 2025-02-06 | Lumen              | W   | 1.000      | -            | -                | -                | -         |     1.17 | Lake, reck, s1n, slaxz-, Swisher |
|           32 |     1335 | 2025-01-16 | FaZe Clan          | L   | 0.890      | -            | -                | -                | -         |    -0.27 | k1to, Lake, s1n, slaxz-, Swisher |
|           31 |     4497 | 2024-10-25 | BESTIA             | L   | 0.337      | -            | -                | -                | -         |    -6.15 | Lake, reck, s1n, slaxz-, Swisher |
|           30 |     4545 | 2024-10-24 | Aurora Gaming      | W   | 0.329      | 0.934        | 0.022 (0.007)    | 0.671 (0.207)    | -         |     3.68 | Lake, reck, s1n, slaxz-, Swisher |
|           29 |     4551 | 2024-10-24 | BESTIA             | L   | 0.329      | -            | -                | -                | -         |    -6.12 | Lake, reck, s1n, slaxz-, Swisher |
|           28 |     4677 | 2024-10-20 | NRG                | W   | 0.305      | 0.477        | 0.057 (0.008)    | 0.516 (0.075)    | -         |     6.10 | Lake, reck, s1n, slaxz-, Swisher |
|           27 |     4828 | 2024-10-17 | Legacy             | W   | 0.286      | 0.477        | 0.043 (0.006)    | 0.628 (0.086)    | -         |     3.85 | Lake, reck, s1n, slaxz-, Swisher |
|           26 |     4879 | 2024-10-16 | NRG                | W   | 0.279      | 0.477        | 0.057 (0.008)    | 0.516 (0.069)    | -         |     5.64 | Lake, reck, s1n, slaxz-, Swisher |
|           25 |     5220 | 2024-10-09 | BLUEJAYS           | W   | 0.232      | -            | -                | -                | -         |     3.31 | Lake, reck, s1n, slaxz-, Swisher |
|           24 |     5226 | 2024-10-09 | BLUEJAYS           | L   | 0.232      | -            | -                | -                | -         |    -4.07 | Lake, reck, s1n, slaxz-, Swisher |
|           23 |     5290 | 2024-10-08 | Legacy             | W   | 0.226      | 0.477        | -                | 0.628 (0.068)    | -         |     3.08 | Lake, reck, s1n, slaxz-, Swisher |
|           22 |     5296 | 2024-10-08 | Legacy             | L   | 0.225      | -            | -                | -                | -         |    -4.09 | Lake, reck, s1n, slaxz-, Swisher |
|           21 |     5303 | 2024-10-08 | Wildcard           | W   | 0.225      | 0.477        | 0.161 (0.017)    | -                | -         |     5.13 | Lake, reck, s1n, slaxz-, Swisher |
|           20 |     5311 | 2024-10-08 | Wildcard           | W   | 0.225      | 0.477        | 0.161 (0.017)    | -                | -         |     5.20 | Lake, reck, s1n, slaxz-, Swisher |
|           19 |     5495 | 2024-10-05 | Wildcard           | L   | 0.203      | -            | -                | -                | -         |    -1.69 | Lake, reck, s1n, slaxz-, Swisher |
|           18 |     5562 | 2024-10-04 | BIG                | L   | 0.198      | -            | -                | -                | -         |    -0.35 | Lake, reck, s1n, slaxz-, Swisher |
|           17 |     5569 | 2024-10-04 | Wildcard           | W   | 0.197      | 0.500        | 0.161 (0.016)    | -                | 1 (0.197) |     4.61 | Lake, reck, s1n, slaxz-, Swisher |
|           16 |     5709 | 2024-10-01 | Party Astronauts   | W   | 0.179      | -            | -                | -                | -         |     1.89 | Lake, reck, s1n, slaxz-, Swisher |
|           15 |     5715 | 2024-10-01 | Party Astronauts   | L   | 0.179      | -            | -                | -                | -         |    -3.79 | Lake, reck, s1n, slaxz-, Swisher |
|           14 |     5718 | 2024-10-01 | Nouns Esports      | W   | 0.178      | -            | -                | -                | -         |     2.64 | Lake, reck, s1n, slaxz-, Swisher |
|           13 |     5723 | 2024-10-01 | Nouns Esports      | L   | 0.178      | -            | -                | -                | -         |    -3.02 | Lake, reck, s1n, slaxz-, Swisher |
|           12 |     5783 | 2024-09-30 | Chill Guys         | W   | 0.172      | -            | -                | -                | -         |     1.85 | Lake, reck, s1n, slaxz-, Swisher |
|           11 |     5785 | 2024-09-30 | Chill Guys         | W   | 0.172      | -            | -                | -                | -         |     1.87 | Lake, reck, s1n, slaxz-, Swisher |
|           10 |     5889 | 2024-09-28 | Bad News Capybaras | W   | 0.159      | -            | -                | -                | -         |     0.93 | Lake, reck, s1n, slaxz-, Swisher |
|            9 |     5892 | 2024-09-28 | Bad News Capybaras | W   | 0.159      | -            | -                | -                | -         |     0.94 | Lake, reck, s1n, slaxz-, Swisher |
|            8 |     6062 | 2024-09-26 | Timbermen          | W   | 0.146      | -            | -                | -                | -         |     0.72 | Lake, reck, s1n, slaxz-, Swisher |
|            7 |     6063 | 2024-09-26 | Timbermen          | W   | 0.145      | -            | -                | -                | -         |     0.72 | Lake, reck, s1n, slaxz-, Swisher |
|            6 |     6141 | 2024-09-25 | NRG                | W   | 0.139      | -            | -                | -                | -         |     3.07 | Lake, reck, s1n, slaxz-, Swisher |
|            5 |     6146 | 2024-09-25 | NRG                | L   | 0.139      | -            | -                | -                | -         |    -1.32 | Lake, reck, s1n, slaxz-, Swisher |
|            4 |     6601 | 2024-09-19 | MIBR               | L   | 0.096      | -            | -                | -                | -         |    -0.74 | Lake, reck, s1n, slaxz-, Swisher |
|            3 |     6874 | 2024-09-14 | Imperial Esports   | W   | 0.064      | 0.889        | 0.083 (0.005)    | -                | 1 (0.064) |     0.91 | Lake, reck, s1n, slaxz-, Swisher |
|            2 |     7074 | 2024-09-11 | Fnatic             | W   | 0.043      | -            | -                | -                | 1 (0.043) |     0.99 | Lake, reck, s1n, slaxz-, Swisher |
|            1 |     7128 | 2024-09-10 | Complexity         | W   | 0.037      | -            | -                | -                | 1 (0.037) |     0.65 | Lake, reck, s1n, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,968.67)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.305 | $25,000.00     | $7,622.74       |
| 2024-10-06 |      0.211 | $3,000.00      | $633.27         |
| 2024-09-22 |      0.116 | $32,000.00     | $3,712.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
