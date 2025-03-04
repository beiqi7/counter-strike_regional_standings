### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, draken, hampus, Ro1f, spooke<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  962.5<br />
<br />
Final Rank Value (962.5) = Starting Rank Value (924.6) + Head To Head Adjustments (37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.200[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.6
- 400 + ( ( 0.252 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 924.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |     2867 | 2024-11-23 | Alliance             | W   | 0.530      | 0.143        | 0.018 (0.001)    | -                | 1 (0.530) |     7.57 | bobeksde, draken, hampus, Ro1f, spooke |
|           44 |     2884 | 2024-11-23 | Monte                | L   | 0.530      | -            | -                | -                | -         |    -9.39 | bobeksde, draken, hampus, Ro1f, spooke |
|           43 |     3008 | 2024-11-21 | Kappa Bar            | W   | 0.518      | -            | -                | -                | 1 (0.518) |     3.72 | bobeksde, draken, hampus, Ro1f, spooke |
|           42 |     3037 | 2024-11-21 | Alliance             | W   | 0.516      | -            | -                | -                | 1 (0.516) |     7.41 | bobeksde, draken, hampus, Ro1f, spooke |
|           41 |     3597 | 2024-11-10 | OG                   | W   | 0.444      | 0.143        | 0.072 (0.005)    | 0.984 (0.062)    | 0 (0.000) |     7.18 | bobeksde, draken, hampus, Ro1f, spooke |
|           40 |     3700 | 2024-11-08 | Metizport            | L   | 0.431      | -            | -                | -                | -         |    -3.58 | bobeksde, draken, hampus, Ro1f, spooke |
|           39 |     3726 | 2024-11-08 | Zero Tenacity        | L   | 0.429      | -            | -                | -                | -         |    -7.09 | bobeksde, draken, hampus, Ro1f, spooke |
|           38 |     3825 | 2024-11-06 | Dynamo Eclot         | L   | 0.415      | -            | -                | -                | -         |    -3.73 | bobeksde, draken, hampus, Ro1f, spooke |
|           37 |     3863 | 2024-11-05 | Showmakerz           | W   | 0.411      | -            | -                | -                | 0 (0.000) |     1.66 | bobeksde, draken, hampus, Ro1f, spooke |
|           36 |     3926 | 2024-11-04 | HOTU                 | W   | 0.403      | 0.384        | -                | 0.785 (0.122)    | 0 (0.000) |     2.65 | bobeksde, draken, hampus, Ro1f, spooke |
|           35 |     3965 | 2024-11-03 | Insilio              | W   | 0.397      | -            | -                | -                | 0 (0.000) |     1.95 | bobeksde, draken, hampus, Ro1f, spooke |
|           34 |     4122 | 2024-11-01 | OG                   | W   | 0.383      | 0.384        | 0.072 (0.011)    | 0.984 (0.145)    | 0 (0.000) |     6.22 | bobeksde, draken, hampus, Ro1f, spooke |
|           33 |     4158 | 2024-10-31 | ECSTATIC             | L   | 0.378      | -            | -                | -                | -         |    -6.23 | bobeksde, draken, hampus, Ro1f, spooke |
|           32 |     4169 | 2024-10-31 | Metizport            | W   | 0.377      | 0.333        | 0.087 (0.011)    | 0.517 (0.065)    | 0 (0.000) |     8.84 | bobeksde, draken, hampus, Ro1f, spooke |
|           31 |     4246 | 2024-10-30 | 9Pandas              | L   | 0.369      | -            | -                | -                | -         |    -4.04 | bobeksde, draken, hampus, Ro1f, spooke |
|           30 |     4272 | 2024-10-29 | Endpoint             | W   | 0.365      | 0.333        | -                | 0.382 (0.047)    | 0 (0.000) |     3.77 | bobeksde, draken, hampus, Ro1f, spooke |
|           29 |     4283 | 2024-10-29 | Tricked Esport       | L   | 0.364      | -            | -                | -                | -         |    -6.71 | bobeksde, draken, hampus, Ro1f, spooke |
|           28 |     4295 | 2024-10-29 | Rare Atom            | W   | 0.364      | -            | -                | -                | -         |     4.03 | bobeksde, draken, hampus, Ro1f, spooke |
|           27 |     4449 | 2024-10-26 | Nexus Gaming         | W   | 0.343      | 0.143        | 0.219 (0.011)    | -                | -         |     8.57 | bobeksde, draken, hampus, Ro1f, spooke |
|           26 |     4666 | 2024-10-21 | UNiTY esports        | W   | 0.309      | 0.384        | 0.030 (0.004)    | 0.408 (0.048)    | -         |     4.16 | bobeksde, draken, hampus, Ro1f, spooke |
|           25 |     4706 | 2024-10-20 | Wild Lotus           | L   | 0.303      | -            | -                | -                | -         |    -6.85 | bobeksde, draken, hampus, Ro1f, spooke |
|           24 |     4934 | 2024-10-16 | WW Team              | W   | 0.275      | -            | -                | -                | -         |     0.72 | bobeksde, draken, hampus, Ro1f, spooke |
|           23 |     5409 | 2024-10-07 | Preasy Esport        | W   | 0.215      | 0.384        | -                | 0.714 (0.059)    | -         |     2.36 | bobeksde, draken, hampus, Ro1f, spooke |
|           22 |     5434 | 2024-10-06 | EYEBALLERS           | W   | 0.210      | -            | -                | -                | -         |     2.39 | bobeksde, draken, hampus, Ro1f, spooke |
|           21 |     5446 | 2024-10-06 | Fightclub            | W   | 0.209      | -            | -                | -                | -         |     0.48 | bobeksde, draken, hampus, Ro1f, spooke |
|           20 |     5461 | 2024-10-06 | GTZ.ESPORTS          | W   | 0.208      | 0.143        | 0.094 (0.003)    | -                | -         |     5.86 | bobeksde, draken, hampus, Ro1f, spooke |
|           19 |     5515 | 2024-10-05 | Metizport X          | W   | 0.203      | -            | -                | -                | -         |     1.25 | bobeksde, draken, hampus, Ro1f, spooke |
|           18 |     5524 | 2024-10-05 | ENCE Academy         | W   | 0.202      | 0.333        | -                | 0.665 (0.045)    | -         |     2.48 | bobeksde, draken, hampus, Ro1f, spooke |
|           17 |     5582 | 2024-10-04 | Natus Vincere Junior | W   | 0.196      | 0.333        | 0.106 (0.007)    | 1.000 (0.065)    | -         |     4.01 | bobeksde, draken, hampus, Ro1f, spooke |
|           16 |     5621 | 2024-10-03 | Partizan Esports     | W   | 0.190      | 0.333        | 0.097 (0.006)    | 0.819 (0.052)    | -         |     4.70 | bobeksde, draken, hampus, Ro1f, spooke |
|           15 |     5775 | 2024-10-01 | Los kogutos          | L   | 0.174      | -            | -                | -                | -         |    -1.87 | bobeksde, draken, hampus, Ro1f, spooke |
|           14 |     5810 | 2024-09-30 | MOUZ NXT             | W   | 0.170      | -            | -                | -                | -         |     0.66 | bobeksde, draken, hampus, Ro1f, spooke |
|           13 |     5828 | 2024-09-30 | Tricked Esport       | L   | 0.169      | -            | -                | -                | -         |    -3.11 | bobeksde, draken, hampus, Ro1f, spooke |
|           12 |     5935 | 2024-09-28 | ARCRED               | W   | 0.157      | -            | -                | -                | -         |     1.83 | bobeksde, draken, hampus, Ro1f, spooke |
|           11 |     5969 | 2024-09-28 | Wild Lotus           | L   | 0.155      | -            | -                | -                | -         |    -3.43 | bobeksde, draken, hampus, Ro1f, spooke |
|           10 |     6167 | 2024-09-25 | Lazer Cats           | L   | 0.138      | -            | -                | -                | -         |    -3.20 | bobeksde, draken, hampus, Ro1f, spooke |
|            9 |     6358 | 2024-09-23 | Nemiga Gaming        | L   | 0.124      | -            | -                | -                | -         |    -0.98 | bobeksde, draken, hampus, Ro1f, spooke |
|            8 |     6374 | 2024-09-23 | 9INE                 | L   | 0.123      | -            | -                | -                | -         |    -2.71 | bobeksde, draken, hampus, Ro1f, spooke |
|            7 |     6381 | 2024-09-23 | GameAgents           | W   | 0.122      | -            | -                | -                | -         |     1.06 | bobeksde, draken, hampus, Ro1f, spooke |
|            6 |     6538 | 2024-09-20 | Devils.one           | W   | 0.102      | -            | -                | -                | -         |     0.60 | bobeksde, draken, hampus, Ro1f, spooke |
|            5 |     6578 | 2024-09-19 | CYBERSHOKE Esports   | W   | 0.097      | -            | -                | -                | -         |     1.47 | bobeksde, draken, hampus, Ro1f, spooke |
|            4 |     6604 | 2024-09-19 | Alliance             | W   | 0.095      | -            | -                | -                | -         |     1.56 | bobeksde, draken, hampus, Ro1f, spooke |
|            3 |     6834 | 2024-09-15 | 9Pandas              | W   | 0.069      | 0.443        | 0.104 (0.003)    | -                | -         |     1.46 | bobeksde, draken, hampus, Ro1f, spooke |
|            2 |     6844 | 2024-09-15 | K27                  | W   | 0.068      | -            | -                | -                | -         |     1.24 | bobeksde, draken, hampus, Ro1f, spooke |
|            1 |     6993 | 2024-09-13 | Rebels Gaming        | L   | 0.055      | -            | -                | -                | -         |    -1.10 | bobeksde, draken, hampus, Ro1f, spooke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,664.07)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.536 | $1,864.89      | $1,000.31       |
| 2024-11-23 |      0.530 | $10,873.30     | $5,768.18       |
| 2024-11-09 |      0.437 | $4,623.93      | $2,020.42       |
| 2024-10-31 |      0.378 | $2,000.00      | $755.84         |
| 2024-10-06 |      0.210 | $4,821.41      | $1,013.41       |
| 2024-10-05 |      0.202 | $5,000.00      | $1,011.13       |
| 2024-09-24 |      0.129 | $8,000.00      | $1,031.15       |
| 2024-09-14 |      0.064 | $1,000.00      | $63.62          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
