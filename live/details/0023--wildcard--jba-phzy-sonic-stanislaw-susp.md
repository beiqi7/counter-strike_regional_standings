### Roster Details<br />
Team Name: Wildcard<br />
Roster: JBa, phzy, Sonic, stanislaw, susp<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1141.2<br />
<br />
Final Rank Value (1141.2) = Starting Rank Value (1152.3) + Head To Head Adjustments (-11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.558[<sup>1</sup>](#table2)
- Bounty Collected: 0.420[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.305[<sup>2</sup>](#table1)

The average of these factors is 0.362<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.3
- 400 + ( ( 0.362 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1152.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      414 | 2025-02-17 | BIG                | L   | 1.000      | -            | -                | -                | -         |    -7.37 | JBa, phzy, Sonic, stanislaw, susp  |
|           35 |      464 | 2025-02-16 | Virtus.pro         | L   | 1.000      | -            | -                | -                | -         |    -1.71 | JBa, phzy, Sonic, stanislaw, susp  |
|           34 |      520 | 2025-02-15 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -0.55 | JBa, phzy, Sonic, stanislaw, susp  |
|           33 |      564 | 2025-02-14 | MIBR               | W   | 1.000      | 1.000        | 0.118 (0.118)    | 0.285 (0.285)    | 1 (1.000) |    15.13 | JBa, phzy, Sonic, stanislaw, susp  |
|           32 |     1158 | 2025-01-31 | Team Liquid        | L   | 0.991      | -            | -                | -                | -         |   -11.89 | JBa, phzy, Sonic, stanislaw, susp  |
|           31 |     1161 | 2025-01-31 | FURIA              | L   | 0.989      | -            | -                | -                | -         |   -15.78 | JBa, phzy, Sonic, stanislaw, susp  |
|           30 |     1176 | 2025-01-29 | BIG                | W   | 0.977      | 1.000        | 0.244 (0.238)    | 0.528 (0.516)    | 1 (0.977) |    25.58 | JBa, phzy, Sonic, stanislaw, susp  |
|           29 |     1339 | 2025-01-15 | Astralis           | L   | 0.882      | -            | -                | -                | -         |    -0.51 | JBa, phzy, Sonic, stanislaw, susp  |
|           28 |     1345 | 2025-01-12 | 9Pandas            | W   | 0.863      | 0.417        | 0.104 (0.037)    | 0.628 (0.226)    | 0 (0.000) |    12.98 | JBa, phzy, Sonic, stanislaw, susp  |
|           27 |     1348 | 2025-01-11 | SINNERS Esports    | W   | 0.857      | 0.417        | 0.031 (0.011)    | 0.597 (0.213)    | 0 (0.000) |     8.50 | JBa, phzy, Sonic, stanislaw, susp  |
|           26 |     1352 | 2025-01-10 | Insilio            | W   | 0.851      | 0.417        | -                | 0.513 (0.182)    | 0 (0.000) |     3.36 | JBa, phzy, Sonic, stanislaw, susp  |
|           25 |     4828 | 2024-10-17 | NRG                | L   | 0.286      | -            | -                | -                | -         |    -5.08 | JBa, phzy, Sonic, stanislaw, susp  |
|           24 |     4880 | 2024-10-16 | BLUEJAYS           | W   | 0.279      | 0.477        | 0.016 (0.002)    | 0.360 (0.048)    | 0 (0.000) |     2.32 | JBa, phzy, Sonic, stanislaw, susp  |
|           23 |     4947 | 2024-10-15 | Nouns Esports      | L   | 0.273      | -            | -                | -                | -         |    -6.28 | JBa, phzy, Sonic, stanislaw, susp  |
|           22 |     5221 | 2024-10-09 | Party Astronauts   | L   | 0.233      | -            | -                | -                | -         |    -6.08 | JBa, phzy, Sonic, stanislaw, susp  |
|           21 |     5228 | 2024-10-09 | Party Astronauts   | L   | 0.233      | -            | -                | -                | -         |    -6.14 | JBa, phzy, Sonic, stanislaw, susp  |
|           20 |     5301 | 2024-10-08 | M80                | L   | 0.225      | -            | -                | -                | -         |    -5.13 | JBa, phzy, Sonic, stanislaw, susp  |
|           19 |     5309 | 2024-10-08 | M80                | L   | 0.225      | -            | -                | -                | -         |    -5.21 | JBa, phzy, Sonic, stanislaw, susp  |
|           18 |     5444 | 2024-10-06 | FlyQuest           | L   | 0.209      | -            | -                | -                | -         |    -2.69 | fr3nd, JBa, Sonic, stanislaw, susp |
|           17 |     5493 | 2024-10-05 | M80                | W   | 0.204      | 0.500        | 0.043 (0.004)    | 0.460 (0.047)    | 1 (0.204) |     1.70 | fr3nd, JBa, Sonic, stanislaw, susp |
|           16 |     5555 | 2024-10-04 | ODDIK              | W   | 0.199      | 0.500        | 0.033 (0.003)    | 0.552 (0.055)    | 1 (0.199) |     1.22 | fr3nd, JBa, Sonic, stanislaw, susp |
|           15 |     5567 | 2024-10-04 | M80                | L   | 0.197      | -            | -                | -                | -         |    -4.62 | fr3nd, JBa, Sonic, stanislaw, susp |
|           14 |     5708 | 2024-10-01 | BLUEJAYS           | W   | 0.179      | 0.477        | 0.016 (0.001)    | 0.360 (0.031)    | 0 (0.000) |     1.25 | JBa, phzy, Sonic, stanislaw, susp  |
|           13 |     5711 | 2024-10-01 | BLUEJAYS           | W   | 0.179      | 0.477        | 0.016 (0.001)    | 0.360 (0.031)    | -         |     1.26 | JBa, phzy, Sonic, stanislaw, susp  |
|           12 |     5837 | 2024-09-29 | Legacy             | L   | 0.166      | -            | -                | -                | -         |    -4.18 | JBa, phzy, Sonic, stanislaw, susp  |
|           11 |     5888 | 2024-09-28 | Legacy             | W   | 0.159      | 0.143        | 0.043 (0.001)    | -                | -         |     0.99 | JBa, phzy, Sonic, stanislaw, susp  |
|           10 |     5895 | 2024-09-28 | MarcaRegistrada    | W   | 0.158      | -            | -                | -                | -         |     0.25 | JBa, phzy, Sonic, stanislaw, susp  |
|            9 |     6561 | 2024-09-19 | NRG                | L   | 0.099      | -            | -                | -                | -         |    -1.79 | JBa, phzy, Sonic, stanislaw, susp  |
|            8 |     6565 | 2024-09-19 | NRG                | L   | 0.099      | -            | -                | -                | -         |    -1.80 | JBa, phzy, Sonic, stanislaw, susp  |
|            7 |     6614 | 2024-09-18 | Familia Maquininha | W   | 0.093      | -            | -                | -                | -         |     0.21 | JBa, phzy, Sonic, stanislaw, susp  |
|            6 |     6619 | 2024-09-18 | Familia Maquininha | W   | 0.093      | -            | -                | -                | -         |     0.21 | JBa, phzy, Sonic, stanislaw, susp  |
|            5 |     6626 | 2024-09-18 | Chill Guys         | W   | 0.092      | -            | -                | -                | -         |     0.44 | JBa, phzy, Sonic, stanislaw, susp  |
|            4 |     6630 | 2024-09-18 | Chill Guys         | W   | 0.092      | -            | -                | -                | -         |     0.44 | JBa, phzy, Sonic, stanislaw, susp  |
|            3 |     7309 | 2024-09-07 | 3DMAX              | L   | 0.016      | -            | -                | -                | -         |    -0.04 | JBa, phzy, Sonic, stanislaw, susp  |
|            2 |     7377 | 2024-09-06 | Iberian Soul       | W   | 0.011      | -            | -                | -                | 1 (0.011) |     0.06 | JBa, phzy, Sonic, stanislaw, susp  |
|            1 |     7484 | 2024-09-05 | 9z Team            | L   | 0.003      | -            | -                | -                | -         |    -0.08 | JBa, phzy, Sonic, stanislaw, susp  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,738.03)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $18,750.00     | $18,750.00      |
| 2025-02-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2025-01-12 |      0.863 | $20,000.00     | $17,261.20      |
| 2024-10-20 |      0.305 | $4,250.00      | $1,297.45       |
| 2024-10-06 |      0.211 | $10,000.00     | $2,114.63       |
| 2024-09-22 |      0.116 | $7,000.00      | $814.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
