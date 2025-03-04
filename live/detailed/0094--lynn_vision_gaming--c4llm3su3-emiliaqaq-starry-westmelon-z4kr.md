### Roster Details<br />
Team Name: Lynn Vision Gaming<br />
Roster: C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  897.9<br />
<br />
Final Rank Value (897.9) = Starting Rank Value (865.9) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.216[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.9
- 400 + ( ( 0.224 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 865.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |        2 | 2025-03-02 | FlyQuest                | L   | 1.000      | -            | -                | -                | -         |    -5.79 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           33 |      602 | 2025-02-12 | The Huns Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.89 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           32 |      616 | 2025-02-12 | ATOX Esports            | W   | 1.000      | 0.143        | 0.069 (0.010)    | 0.525 (0.075)    | 0 (0.000) |    23.37 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           31 |      620 | 2025-02-12 | The Huns Esports        | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.387 (0.055)    | 0 (0.000) |    16.68 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           30 |      622 | 2025-02-11 | Unsettled Resentment    | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.228 (0.033)    | 0 (0.000) |    11.34 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           29 |      640 | 2025-02-11 | TYLOO                   | W   | 1.000      | 0.143        | 0.021 (0.003)    | 0.198 (0.028)    | 0 (0.000) |    22.29 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           28 |      646 | 2025-02-11 | The Huns Esports        | L   | 1.000      | -            | -                | -                | -         |   -13.37 | C4LLM3SU3, EmiliaQAQ, Starry, westmelon, z4kr |
|           27 |     3489 | 2024-11-13 | FlyQuest                | L   | 0.462      | -            | -                | -                | -         |    -1.90 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           26 |     3495 | 2024-11-12 | TALON                   | W   | 0.461      | -            | -                | -                | 1 (0.461) |     2.54 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           25 |     3531 | 2024-11-11 | Alter Ego               | W   | 0.453      | -            | -                | -                | 1 (0.453) |     1.02 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           24 |     3577 | 2024-11-11 | Adventurers             | L   | 0.449      | -            | -                | -                | -         |    -7.36 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           23 |     4011 | 2024-11-03 | TYLOO                   | L   | 0.395      | -            | -                | -                | -         |    -3.17 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           22 |     4014 | 2024-11-02 | ATOX Esports            | W   | 0.394      | -            | -                | -                | 1 (0.394) |     3.99 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           21 |     4080 | 2024-11-02 | Unsettled Resentment    | W   | 0.388      | 0.417        | 0.016 (0.003)    | 0.228 (0.037)    | 1 (0.388) |     4.21 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           20 |     4860 | 2024-10-17 | The Huns Esports        | W   | 0.282      | 0.417        | 0.029 (0.003)    | 0.387 (0.045)    | 0 (0.000) |     5.87 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           19 |     4926 | 2024-10-16 | ATOX Esports            | L   | 0.276      | -            | -                | -                | -         |    -5.85 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           18 |     5269 | 2024-10-09 | TYLOO                   | W   | 0.229      | 0.417        | 0.021 (0.002)    | -                | 0 (0.000) |     5.48 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           17 |     5275 | 2024-10-09 | TYLOO                   | W   | 0.229      | 0.417        | 0.021 (0.002)    | -                | -         |     5.55 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           16 |     5346 | 2024-10-08 | SayGGTeam               | L   | 0.223      | -            | -                | -                | -         |    -4.64 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           15 |     5352 | 2024-10-08 | SayGGTeam               | L   | 0.222      | -            | -                | -                | -         |    -4.72 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           14 |     5682 | 2024-10-02 | The QUBE Esports        | W   | 0.183      | -            | -                | -                | -         |     0.73 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           13 |     5687 | 2024-10-02 | The QUBE Esports        | W   | 0.182      | -            | -                | -                | -         |     0.73 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           12 |     5755 | 2024-10-01 | Chinggis Warriors       | W   | 0.176      | 0.417        | -                | 0.449 (0.033)    | -         |     2.67 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           11 |     5761 | 2024-10-01 | Chinggis Warriors       | W   | 0.176      | 0.417        | -                | 0.449 (0.033)    | -         |     2.71 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|           10 |     6198 | 2024-09-25 | Nomads (Mongolian team) | L   | 0.136      | -            | -                | -                | -         |    -3.27 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            9 |     6204 | 2024-09-25 | Nomads (Mongolian team) | L   | 0.136      | -            | -                | -                | -         |    -3.29 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            8 |     6292 | 2024-09-24 | DEWA United             | L   | 0.129      | -            | -                | -                | -         |    -3.51 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            7 |     6299 | 2024-09-24 | DEWA United             | L   | 0.129      | -            | -                | -                | -         |    -3.52 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            6 |     6365 | 2024-09-23 | Passion UA              | L   | 0.123      | -            | -                | -                | -         |    -1.50 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            5 |     6418 | 2024-09-22 | Insilio                 | L   | 0.116      | -            | -                | -                | -         |    -2.60 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            4 |     6540 | 2024-09-20 | ECSTATIC                | W   | 0.102      | 0.435        | 0.039 (0.002)    | 0.809 (0.036)    | -         |     1.84 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            3 |     6750 | 2024-09-17 | Nexus Gaming            | W   | 0.081      | 0.435        | 0.219 (0.008)    | 0.808 (0.029)    | -         |     2.30 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            2 |     6824 | 2024-09-15 | FAVBET Team             | L   | 0.070      | -            | -                | -                | -         |    -0.92 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |
|            1 |     7400 | 2024-09-06 | FlyQuest                | L   | 0.010      | -            | -                | -                | -         |    -0.04 | afufu, EmiliaQAQ, flying, westmelon, z4kr     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,567.04)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.395 | $8,000.00      | $3,159.66       |
| 2024-09-22 |      0.116 | $3,500.00      | $407.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
