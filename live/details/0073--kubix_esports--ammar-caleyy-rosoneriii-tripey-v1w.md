### Roster Details<br />
Team Name: Kubix Esports<br />
Roster: ammar, Caleyy, rosoneriii, tripey, v1w<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  929.7<br />
<br />
Final Rank Value (929.7) = Starting Rank Value (977.5) + Head To Head Adjustments (-47.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.439[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.358[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 977.5
- 400 + ( ( 0.278 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 977.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |     1450 | 2024-12-28 | KONO.ECF                    | L   | 0.762      | -            | -                | -                | -         |   -10.89 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           41 |     1488 | 2024-12-26 | BMTH (Ukrainian team)       | W   | 0.749      | -            | -                | -                | 0 (0.000) |     2.30 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           40 |     1510 | 2024-12-22 | M1X                         | W   | 0.724      | 0.143        | 0.009 (0.001)    | -                | 1 (0.724) |     7.63 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           39 |     1535 | 2024-12-22 | The Suspect                 | W   | 0.722      | 0.143        | 0.003 (0.000)    | 0.219 (0.023)    | 1 (0.722) |     5.67 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           38 |     1551 | 2024-12-21 | Onlineheroes                | W   | 0.718      | -            | -                | -                | 1 (0.718) |     2.29 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           37 |     2096 | 2024-12-08 | P0RTUGAL                    | L   | 0.630      | -            | -                | -                | -         |   -13.25 | ammar, Caleyy, rosoneriii, tripey, v1w    |
|           36 |     2446 | 2024-12-01 | Insilio                     | L   | 0.584      | -            | -                | -                | -         |   -15.17 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           35 |     2452 | 2024-12-01 | ADEPTS                      | W   | 0.584      | 0.143        | -                | 0.292 (0.024)    | 0 (0.000) |     2.76 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           34 |     2554 | 2024-11-30 | Permitta Esports            | L   | 0.576      | -            | -                | -                | -         |   -11.79 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           33 |     2648 | 2024-11-28 | Fire Flux Esports           | L   | 0.563      | -            | -                | -                | -         |    -8.37 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           32 |     2729 | 2024-11-26 | GenOne                      | W   | 0.550      | 0.372        | 0.014 (0.003)    | 0.853 (0.175)    | 0 (0.000) |     6.21 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           31 |     2790 | 2024-11-24 | FLuffy Gangsters            | L   | 0.536      | -            | -                | -                | -         |   -10.69 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           30 |     2892 | 2024-11-23 | PCIFIC Espor                | L   | 0.529      | -            | -                | -                | -         |   -12.79 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           29 |     2950 | 2024-11-22 | Underrated                  | W   | 0.524      | 0.372        | 0.002 (0.000)    | 0.273 (0.053)    | 0 (0.000) |     2.51 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           28 |     2973 | 2024-11-22 | Anonymo Esports             | W   | 0.523      | 0.372        | -                | 0.100 (0.019)    | 0 (0.000) |     1.26 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           27 |     3186 | 2024-11-18 | RUSTEC                      | W   | 0.497      | 0.372        | -                | 0.221 (0.041)    | -         |     1.35 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           26 |     3315 | 2024-11-16 | Dark Cloud Esports          | W   | 0.483      | 0.143        | 0.045 (0.003)    | 0.837 (0.058)    | 1 (0.483) |     5.68 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           25 |     3535 | 2024-11-11 | Daystar                     | W   | 0.451      | 0.372        | -                | 0.132 (0.022)    | -         |     1.90 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           24 |     3795 | 2024-11-06 | Permitta Esports            | W   | 0.417      | 0.372        | 0.015 (0.002)    | 0.497 (0.077)    | -         |     4.15 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           23 |     3860 | 2024-11-05 | Kyoto (European mix-team)   | W   | 0.410      | 0.143        | 0.016 (0.001)    | -                | -         |     2.35 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           22 |     3929 | 2024-11-04 | ROUNDS                      | W   | 0.403      | -            | -                | -                | -         |     1.03 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           21 |     3978 | 2024-11-03 | MADNESS (Kosovar team)      | W   | 0.396      | 0.143        | 0.003 (0.000)    | -                | -         |     1.11 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           20 |     4161 | 2024-10-31 | Grindas                     | W   | 0.377      | -            | -                | -                | -         |     1.03 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           19 |     4355 | 2024-10-28 | ENTERPRISE Genesis          | W   | 0.357      | -            | -                | -                | -         |     1.66 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           18 |     4398 | 2024-10-27 | Juggernauts                 | L   | 0.349      | -            | -                | -                | -         |    -9.27 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           17 |     4514 | 2024-10-25 | Nuclear TigeRES             | L   | 0.336      | -            | -                | -                | -         |    -6.77 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           16 |     4521 | 2024-10-25 | 500                         | L   | 0.336      | -            | -                | -                | -         |    -3.88 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           15 |     4563 | 2024-10-23 | Poslednii3ae3d              | W   | 0.324      | -            | -                | -                | -         |     1.38 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           14 |     5065 | 2024-10-13 | Baklava Gaming              | W   | 0.255      | -            | -                | -                | -         |     0.88 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           13 |     5749 | 2024-10-01 | Dynamo Eclot                | W   | 0.176      | 0.143        | 0.150 (0.004)    | 0.705 (0.018)    | -         |     3.95 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           12 |     5910 | 2024-09-28 | M1X                         | L   | 0.157      | -            | -                | -                | -         |    -3.62 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           11 |     5945 | 2024-09-28 | The Suspect                 | W   | 0.156      | -            | -                | -                | 1 (0.156) |     1.06 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|           10 |     6265 | 2024-09-24 | Los kogutos                 | W   | 0.130      | 0.143        | 0.037 (0.001)    | -                | -         |     2.44 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            9 |     6286 | 2024-09-24 | GameAgents                  | W   | 0.130      | -            | -                | -                | -         |     0.94 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            8 |     6706 | 2024-09-17 | Team Secret (Croatian team) | W   | 0.084      | -            | -                | -                | -         |     0.16 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            7 |     6715 | 2024-09-17 | SINNERS Academy             | W   | 0.084      | -            | -                | -                | -         |     0.61 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            6 |     6788 | 2024-09-16 | THE GENTLEMEN ESPORTS       | L   | 0.076      | -            | -                | -                | -         |    -1.97 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            5 |     6811 | 2024-09-15 | NOM Esports                 | W   | 0.070      | -            | -                | -                | -         |     0.09 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            4 |     6988 | 2024-09-13 | QUAZAR                      | L   | 0.055      | -            | -                | -                | -         |    -1.41 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            3 |     7183 | 2024-09-09 | XPERION NXT                 | W   | 0.030      | -            | -                | -                | -         |     0.14 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            2 |     7329 | 2024-09-07 | Grannys Knockers            | L   | 0.016      | -            | -                | -                | -         |    -0.43 | ammar, gejmzilla, rosoneriii, tripey, v1w |
|            1 |     7471 | 2024-09-05 | TOOMUCHVIDEOGAMES           | W   | 0.003      | -            | -                | -                | -         |     0.01 | ammar, gejmzilla, rosoneriii, tripey, v1w |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,625.29)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.724 | $5,736.64      | $4,154.03       |
| 2024-11-16 |      0.483 | $21,089.26     | $10,175.61      |
| 2024-09-28 |      0.157 | $1,675.22      | $262.77         |
| 2024-09-21 |      0.110 | $300.00        | $32.89          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
