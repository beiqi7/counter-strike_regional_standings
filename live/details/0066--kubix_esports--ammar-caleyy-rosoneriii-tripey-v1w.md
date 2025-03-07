### Roster Details<br />
Team Name: Kubix Esports<br />
Roster: ammar, Caleyy, rosoneriii, tripey, v1w<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  901.7<br />
<br />
Final Rank Value (901.7) = Starting Rank Value (925.5) + Head To Head Adjustments (-23.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.285[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.5
- 400 + ( ( 0.238 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 925.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     1568 | 2024-12-28 | KONO.ECF                  | L   | 0.448      | -            | -                | -                | -         |    -6.60 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           29 |     1607 | 2024-12-26 | BMTH (Ukrainian team)     | W   | 0.437      | 0.333        | -                | 0.061 (0.011)    | 0 (0.000) |     1.49 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           28 |     1629 | 2024-12-22 | M1X                       | W   | 0.416      | 0.143        | 0.006 (0.000)    | -                | 1 (0.499) |     4.17 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           27 |     1654 | 2024-12-22 | The Suspect               | W   | 0.414      | 0.143        | 0.002 (0.000)    | 0.132 (0.009)    | 1 (0.497) |     3.31 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           26 |     1670 | 2024-12-21 | Onlineheroes              | W   | 0.411      | 0.143        | 0.001 (0.000)    | -                | 1 (0.493) |     1.54 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           25 |     2222 | 2024-12-08 | P0RTUGAL                  | L   | 0.338      | -            | -                | -                | -         |    -6.90 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           24 |     2564 | 2024-12-01 | Insilio                   | L   | 0.299      | -            | -                | -                | -         |    -7.99 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           23 |     2570 | 2024-12-01 | ADEPTS                    | W   | 0.299      | 0.143        | -                | 0.180 (0.009)    | 0 (0.000) |     1.24 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           22 |     2673 | 2024-11-30 | Permitta Esports          | L   | 0.293      | -            | -                | -                | -         |    -5.93 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           21 |     2763 | 2024-11-28 | Fire Flux Esports         | L   | 0.282      | -            | -                | -                | -         |    -4.57 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           20 |     2846 | 2024-11-26 | GenOne                    | W   | 0.271      | 0.372        | 0.009 (0.001)    | 0.644 (0.078)    | 0 (0.000) |     2.98 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           19 |     2909 | 2024-11-24 | FLuffy Gangsters          | L   | 0.259      | -            | -                | -                | -         |    -5.46 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           18 |     3012 | 2024-11-23 | PCIFIC Espor              | L   | 0.253      | -            | -                | -                | -         |    -5.84 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           17 |     3069 | 2024-11-22 | Underrated                | W   | 0.249      | 0.372        | 0.002 (0.000)    | 0.219 (0.024)    | 0 (0.000) |     1.74 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           16 |     3091 | 2024-11-22 | Anonymo Esports           | W   | 0.248      | 0.372        | -                | 0.052 (0.006)    | 0 (0.000) |     0.67 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           15 |     3314 | 2024-11-18 | RUSTEC                    | W   | 0.227      | 0.372        | -                | 0.177 (0.018)    | 0 (0.000) |     0.71 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           14 |     3444 | 2024-11-16 | Dark Cloud Esports        | W   | 0.215      | 0.143        | 0.035 (0.001)    | 0.667 (0.025)    | 1 (0.258) |     2.62 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           13 |     3668 | 2024-11-11 | Daystar                   | W   | 0.188      | 0.372        | -                | 0.077 (0.006)    | -         |     0.57 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           12 |     3931 | 2024-11-06 | Permitta Esports          | W   | 0.160      | 0.372        | 0.013 (0.001)    | 0.349 (0.025)    | -         |     1.73 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           11 |     3998 | 2024-11-05 | Kyoto (European mix-team) | W   | 0.154      | 0.143        | 0.011 (0.000)    | -                | -         |     0.65 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           10 |     4070 | 2024-11-04 | ROUNDS                    | W   | 0.148      | -            | -                | -                | -         |     0.45 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            9 |     4119 | 2024-11-03 | MADNESS (Kosovar team)    | W   | 0.143      | 0.143        | 0.003 (0.000)    | -                | -         |     0.51 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            8 |     4299 | 2024-10-31 | Grindas                   | W   | 0.127      | -            | -                | -                | -         |     0.44 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            7 |     4512 | 2024-10-28 | ENTERPRISE Genesis        | W   | 0.110      | 0.143        | 0.001 (0.000)    | -                | -         |     0.64 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            6 |     4557 | 2024-10-27 | Juggernauts               | L   | 0.103      | -            | -                | -                | -         |    -2.64 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            5 |     4676 | 2024-10-25 | Nuclear TigeRES           | L   | 0.093      | -            | -                | -                | -         |    -1.67 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            4 |     4685 | 2024-10-25 | 500                       | L   | 0.092      | -            | -                | -                | -         |    -0.98 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            3 |     4734 | 2024-10-23 | Poslednii3ae3d            | W   | 0.082      | -            | -                | -                | -         |     0.45 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            2 |     5130 | 2024-10-16 | GameAgents                | L   | 0.043      | -            | -                | -                | -         |    -1.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            1 |     5286 | 2024-10-13 | Baklava Gaming            | W   | 0.025      | -            | -                | -                | -         |     0.04 | ammar, gejmzilla, rosoneriii, tripey, v1w |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,296.24)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.499 | $5,736.64      | $2,863.80       |
| 2024-11-16 |      0.258 | $21,089.26     | $5,432.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
