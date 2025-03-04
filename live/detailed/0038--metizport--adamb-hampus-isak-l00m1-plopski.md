### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, hampus, isak, L00m1, Plopski<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1056.9<br />
<br />
Final Rank Value (1056.9) = Starting Rank Value (1143.8) + Head To Head Adjustments (-86.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.486[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.467[<sup>2</sup>](#table1)

The average of these factors is 0.358<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1143.8
- 400 + ( ( 0.358 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1143.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      636 | 2025-02-11 | HEROIC                      | L   | 1.000      | -            | -                | -                | -         |   -10.77 | adamb, hampus, isak, L00m1, Plopski |
|           40 |      645 | 2025-02-11 | Nemiga Gaming               | W   | 1.000      | 0.143        | 0.204 (0.029)    | -                | 0 (0.000) |    15.55 | adamb, hampus, isak, L00m1, Plopski |
|           39 |      663 | 2025-02-10 | GamerLegion                 | L   | 1.000      | -            | -                | -                | -         |    -1.62 | adamb, hampus, isak, L00m1, Plopski |
|           38 |      674 | 2025-02-10 | Nexus Gaming                | W   | 1.000      | 0.143        | 0.219 (0.031)    | 0.808 (0.115)    | 0 (0.000) |    14.32 | adamb, hampus, isak, L00m1, Plopski |
|           37 |      978 | 2025-02-05 | Ninjas in Pyjamas           | L   | 1.000      | -            | -                | -                | -         |   -27.89 | adamb, hampus, isak, L00m1, Plopski |
|           36 |      987 | 2025-02-05 | Passion UA                  | L   | 1.000      | -            | -                | -                | -         |   -20.18 | adamb, hampus, isak, L00m1, Plopski |
|           35 |     1336 | 2025-01-15 | Team Vitality               | L   | 0.884      | -            | -                | -                | -         |    -0.27 | adamb, hampus, isak, L00m1, Plopski |
|           34 |     1505 | 2024-12-22 | P0RTUGAL                    | L   | 0.725      | -            | -                | -                | -         |   -17.71 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           33 |     1510 | 2024-12-22 | Zero Tenacity               | W   | 0.724      | 0.143        | 0.032 (0.003)    | 0.843 (0.087)    | -         |     7.45 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           32 |     1562 | 2024-12-21 | Insilio                     | W   | 0.717      | -            | -                | -                | -         |     2.29 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           31 |     1815 | 2024-12-14 | 9INE                        | L   | 0.670      | -            | -                | -                | -         |   -14.71 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           30 |     1910 | 2024-12-13 | Monte                       | W   | 0.663      | 0.435        | 0.034 (0.010)    | -                | -         |     5.84 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           29 |     1997 | 2024-12-11 | Insilio                     | W   | 0.649      | 0.435        | -                | 0.513 (0.145)    | -         |     1.96 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           28 |     2032 | 2024-12-10 | Chimera Esports             | L   | 0.642      | -            | -                | -                | -         |   -14.46 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           27 |     2122 | 2024-12-08 | FLuffy Gangsters            | W   | 0.628      | 0.435        | 0.016 (0.004)    | 0.924 (0.252)    | -         |     4.32 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           26 |     2246 | 2024-12-05 | Fire Flux Esports           | W   | 0.609      | 0.435        | -                | 1.000 (0.265)    | -         |     6.29 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           25 |     2346 | 2024-12-03 | Wild Lotus                  | L   | 0.595      | -            | -                | -                | -         |   -15.92 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           24 |     3246 | 2024-11-17 | Partizan Esports            | L   | 0.489      | -            | -                | -                | -         |    -7.72 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           23 |     3267 | 2024-11-17 | Nexus Gaming                | L   | 0.488      | -            | -                | -                | -         |    -7.13 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           22 |     3315 | 2024-11-16 | The Huns Esports            | W   | 0.483      | 0.617        | 0.029 (0.009)    | 0.387 (0.115)    | 1 (0.483) |     4.09 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           21 |     3385 | 2024-11-15 | Homyno                      | W   | 0.476      | -            | -                | -                | 1 (0.476) |     1.31 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           20 |     3392 | 2024-11-15 | Team Norway                 | W   | 0.476      | -            | -                | -                | 1 (0.476) |     0.90 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           19 |     3403 | 2024-11-14 | Los kogutos                 | W   | 0.471      | 0.617        | 0.037 (0.011)    | 0.520 (0.151)    | 1 (0.471) |     3.90 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           18 |     3478 | 2024-11-13 | PCIFIC Espor                | L   | 0.463      | -            | -                | -                | -         |   -12.81 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           17 |     3484 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.463      | -            | -                | -                | 1 (0.463) |     1.51 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           16 |     3664 | 2024-11-09 | Ninjas in Pyjamas           | W   | 0.437      | -            | -                | -                | 1 (0.437) |     3.01 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           15 |     3700 | 2024-11-08 | Johnny Speeds               | W   | 0.431      | 0.143        | 0.046 (0.003)    | -                | 1 (0.431) |     3.58 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           14 |     3739 | 2024-11-07 | Kappa Bar                   | W   | 0.425      | -            | -                | -                | 1 (0.425) |     1.33 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           13 |     4169 | 2024-10-31 | Johnny Speeds               | L   | 0.377      | -            | -                | -                | -         |    -8.84 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           12 |     4225 | 2024-10-30 | ECSTATIC                    | W   | 0.371      | 0.333        | 0.039 (0.005)    | 0.809 (0.100)    | -         |     2.75 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           11 |     4238 | 2024-10-30 | Iberian Soul                | W   | 0.370      | 0.333        | -                | 0.615 (0.076)    | -         |     2.20 | adamb, L00m1, nilo, Plopski, SHiNE  |
|           10 |     5146 | 2024-10-12 | Aurora Gaming               | L   | 0.249      | -            | -                | -                | -         |    -6.33 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            9 |     5210 | 2024-10-10 | Fnatic                      | W   | 0.235      | 0.435        | 0.059 (0.006)    | -                | -         |     3.53 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            8 |     5357 | 2024-10-08 | ALTERNATE aTTaX             | W   | 0.222      | -            | -                | -                | -         |     1.87 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            7 |     5413 | 2024-10-07 | Monte                       | L   | 0.215      | -            | -                | -                | -         |    -5.45 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            6 |     5572 | 2024-10-04 | CYBERSHOKE Esports          | W   | 0.197      | 0.435        | -                | 1.000 (0.086)    | -         |     1.31 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            5 |     5742 | 2024-10-01 | G2 Ares                     | W   | 0.177      | -            | -                | -                | -         |     0.45 | adamb, L00m1, nilo, Plopski, SHiNE  |
|            4 |     6387 | 2024-09-23 | Wild Lotus                  | L   | 0.121      | -            | -                | -                | -         |    -3.41 | adamb, L00m1, nilo, Plopski, Sapec  |
|            3 |     6795 | 2024-09-16 | 9INE                        | W   | 0.075      | -            | -                | -                | -         |     0.27 | adamb, L00m1, nilo, Plopski, Sapec  |
|            2 |     7084 | 2024-09-11 | Zero Tenacity               | L   | 0.043      | -            | -                | -                | -         |    -1.00 | adamb, L00m1, nilo, Plopski, Sapec  |
|            1 |     7196 | 2024-09-09 | Zero Tenacity               | L   | 0.029      | -            | -                | -                | -         |    -0.68 | adamb, L00m1, nilo, Plopski, Sapec  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,153.99)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.725 | $6,518.90      | $4,724.42       |
| 2024-12-15 |      0.677 | $2,000.00      | $1,354.18       |
| 2024-11-17 |      0.490 | $15,000.00     | $7,356.32       |
| 2024-11-09 |      0.437 | $23,119.67     | $10,102.11      |
| 2024-10-13 |      0.257 | $2,000.00      | $513.57         |
| 2024-09-26 |      0.143 | $500.00        | $71.58          |
| 2024-09-14 |      0.064 | $500.00        | $31.81          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
