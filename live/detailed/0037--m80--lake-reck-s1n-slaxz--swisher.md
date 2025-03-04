### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1057.0<br />
<br />
Final Rank Value (1057.0) = Starting Rank Value (951.0) + Head To Head Adjustments (106.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.423[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.171[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 951.0
- 400 + ( ( 0.265 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 951.0


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
|           41 |        4 | 2025-03-01 | FlyQuest           | W   | 1.000      | 0.889        | 0.099 (0.088)    | 0.267 (0.237)    | 1 (1.000) |    21.20 | Lake, reck, s1n, slaxz-, Swisher |
|           40 |      536 | 2025-02-14 | BLUEJAYS           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.65 | Lake, reck, s1n, slaxz-, Swisher |
|           39 |      558 | 2025-02-14 | NRG                | W   | 1.000      | 0.143        | 0.057 (0.008)    | 0.516 (0.074)    | 0 (0.000) |    17.74 | Lake, reck, s1n, slaxz-, Swisher |
|           38 |      589 | 2025-02-13 | Nouns Esports      | W   | 1.000      | 0.143        | -                | 0.601 (0.086)    | 0 (0.000) |    12.08 | Lake, reck, s1n, slaxz-, Swisher |
|           37 |      653 | 2025-02-10 | Marsborne          | W   | 1.000      | 0.143        | -                | 0.385 (0.055)    | 0 (0.000) |     5.24 | Lake, reck, s1n, slaxz-, Swisher |
|           36 |      695 | 2025-02-09 | Marsborne          | W   | 1.000      | 0.143        | -                | 0.385 (0.055)    | 0 (0.000) |     5.17 | Lake, reck, s1n, slaxz-, Swisher |
|           35 |      755 | 2025-02-08 | Bad News Capybaras | W   | 1.000      | -            | -                | -                | -         |     4.35 | Lake, reck, s1n, slaxz-, Swisher |
|           34 |      883 | 2025-02-06 | Zomblers           | W   | 1.000      | -            | -                | -                | -         |     1.21 | Lake, reck, s1n, slaxz-, Swisher |
|           33 |      888 | 2025-02-06 | Lumen              | W   | 1.000      | -            | -                | -                | -         |     1.17 | Lake, reck, s1n, slaxz-, Swisher |
|           32 |     1333 | 2025-01-16 | FaZe Clan          | L   | 0.890      | -            | -                | -                | -         |    -0.27 | k1to, Lake, s1n, slaxz-, Swisher |
|           31 |     4495 | 2024-10-25 | BESTIA             | L   | 0.337      | -            | -                | -                | -         |    -6.16 | Lake, reck, s1n, slaxz-, Swisher |
|           30 |     4543 | 2024-10-24 | Aurora Gaming      | W   | 0.330      | 0.934        | 0.022 (0.007)    | 0.671 (0.207)    | -         |     3.69 | Lake, reck, s1n, slaxz-, Swisher |
|           29 |     4549 | 2024-10-24 | BESTIA             | L   | 0.329      | -            | -                | -                | -         |    -6.12 | Lake, reck, s1n, slaxz-, Swisher |
|           28 |     4675 | 2024-10-20 | NRG                | W   | 0.305      | 0.477        | 0.057 (0.008)    | 0.516 (0.075)    | -         |     6.11 | Lake, reck, s1n, slaxz-, Swisher |
|           27 |     4826 | 2024-10-17 | Legacy             | W   | 0.286      | 0.477        | 0.043 (0.006)    | 0.628 (0.086)    | -         |     3.85 | Lake, reck, s1n, slaxz-, Swisher |
|           26 |     4877 | 2024-10-16 | NRG                | W   | 0.279      | 0.477        | 0.057 (0.008)    | 0.516 (0.069)    | -         |     5.65 | Lake, reck, s1n, slaxz-, Swisher |
|           25 |     5218 | 2024-10-09 | BLUEJAYS           | W   | 0.233      | -            | -                | -                | -         |     3.32 | Lake, reck, s1n, slaxz-, Swisher |
|           24 |     5224 | 2024-10-09 | BLUEJAYS           | L   | 0.233      | -            | -                | -                | -         |    -4.08 | Lake, reck, s1n, slaxz-, Swisher |
|           23 |     5288 | 2024-10-08 | Legacy             | W   | 0.226      | 0.477        | -                | 0.628 (0.068)    | -         |     3.08 | Lake, reck, s1n, slaxz-, Swisher |
|           22 |     5294 | 2024-10-08 | Legacy             | L   | 0.226      | -            | -                | -                | -         |    -4.10 | Lake, reck, s1n, slaxz-, Swisher |
|           21 |     5301 | 2024-10-08 | Wildcard           | W   | 0.225      | 0.477        | 0.161 (0.017)    | -                | -         |     5.13 | Lake, reck, s1n, slaxz-, Swisher |
|           20 |     5309 | 2024-10-08 | Wildcard           | W   | 0.225      | 0.477        | 0.161 (0.017)    | -                | -         |     5.21 | Lake, reck, s1n, slaxz-, Swisher |
|           19 |     5493 | 2024-10-05 | Wildcard           | L   | 0.204      | -            | -                | -                | -         |    -1.70 | Lake, reck, s1n, slaxz-, Swisher |
|           18 |     5560 | 2024-10-04 | BIG                | L   | 0.198      | -            | -                | -                | -         |    -0.35 | Lake, reck, s1n, slaxz-, Swisher |
|           17 |     5567 | 2024-10-04 | Wildcard           | W   | 0.197      | 0.500        | 0.161 (0.016)    | -                | 1 (0.197) |     4.62 | Lake, reck, s1n, slaxz-, Swisher |
|           16 |     5707 | 2024-10-01 | Party Astronauts   | W   | 0.179      | -            | -                | -                | -         |     1.90 | Lake, reck, s1n, slaxz-, Swisher |
|           15 |     5713 | 2024-10-01 | Party Astronauts   | L   | 0.179      | -            | -                | -                | -         |    -3.80 | Lake, reck, s1n, slaxz-, Swisher |
|           14 |     5716 | 2024-10-01 | Nouns Esports      | W   | 0.179      | -            | -                | -                | -         |     2.64 | Lake, reck, s1n, slaxz-, Swisher |
|           13 |     5721 | 2024-10-01 | Nouns Esports      | L   | 0.178      | -            | -                | -                | -         |    -3.02 | Lake, reck, s1n, slaxz-, Swisher |
|           12 |     5781 | 2024-09-30 | Chill Guys         | W   | 0.172      | -            | -                | -                | -         |     1.85 | Lake, reck, s1n, slaxz-, Swisher |
|           11 |     5783 | 2024-09-30 | Chill Guys         | W   | 0.172      | -            | -                | -                | -         |     1.87 | Lake, reck, s1n, slaxz-, Swisher |
|           10 |     5887 | 2024-09-28 | Bad News Capybaras | W   | 0.159      | -            | -                | -                | -         |     0.93 | Lake, reck, s1n, slaxz-, Swisher |
|            9 |     5890 | 2024-09-28 | Bad News Capybaras | W   | 0.159      | -            | -                | -                | -         |     0.94 | Lake, reck, s1n, slaxz-, Swisher |
|            8 |     6060 | 2024-09-26 | Timbermen          | W   | 0.146      | -            | -                | -                | -         |     0.72 | Lake, reck, s1n, slaxz-, Swisher |
|            7 |     6061 | 2024-09-26 | Timbermen          | W   | 0.146      | -            | -                | -                | -         |     0.72 | Lake, reck, s1n, slaxz-, Swisher |
|            6 |     6139 | 2024-09-25 | NRG                | W   | 0.139      | -            | -                | -                | -         |     3.08 | Lake, reck, s1n, slaxz-, Swisher |
|            5 |     6144 | 2024-09-25 | NRG                | L   | 0.139      | -            | -                | -                | -         |    -1.33 | Lake, reck, s1n, slaxz-, Swisher |
|            4 |     6599 | 2024-09-19 | MIBR               | L   | 0.096      | -            | -                | -                | -         |    -0.75 | Lake, reck, s1n, slaxz-, Swisher |
|            3 |     6872 | 2024-09-14 | Imperial Esports   | W   | 0.064      | 0.889        | 0.083 (0.005)    | -                | 1 (0.064) |     0.92 | Lake, reck, s1n, slaxz-, Swisher |
|            2 |     7072 | 2024-09-11 | Fnatic             | W   | 0.044      | -            | -                | -                | 1 (0.044) |     1.00 | Lake, reck, s1n, slaxz-, Swisher |
|            1 |     7126 | 2024-09-10 | Complexity         | W   | 0.037      | -            | -                | -                | 1 (0.037) |     0.65 | Lake, reck, s1n, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,991.03)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.305 | $25,000.00     | $7,632.05       |
| 2024-10-06 |      0.211 | $3,000.00      | $634.39         |
| 2024-09-22 |      0.116 | $32,000.00     | $3,724.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
