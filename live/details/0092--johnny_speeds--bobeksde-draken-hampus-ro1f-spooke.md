### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, draken, hampus, Ro1f, spooke<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  857.7<br />
<br />
Final Rank Value (857.7) = Starting Rank Value (845.5) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.145[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.5
- 400 + ( ( 0.202 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 845.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     2989 | 2024-11-23 | Alliance       | W   | 0.254      | 0.143        | 0.013 (0.001)    | 0.516 (0.023)    | 1 (0.305) |     4.35 | bobeksde, draken, hampus, Ro1f, spooke |
|           22 |     3006 | 2024-11-23 | Monte          | L   | 0.254      | -            | -                | -                | -         |    -4.47 | bobeksde, draken, hampus, Ro1f, spooke |
|           21 |     3130 | 2024-11-21 | Kappa Bar      | W   | 0.244      | 0.143        | 0.006 (0.000)    | -                | 1 (0.292) |     2.44 | bobeksde, draken, hampus, Ro1f, spooke |
|           20 |     3158 | 2024-11-21 | Alliance       | W   | 0.243      | 0.143        | 0.013 (0.001)    | 0.516 (0.021)    | 1 (0.291) |     4.18 | bobeksde, draken, hampus, Ro1f, spooke |
|           19 |     3732 | 2024-11-10 | OG             | W   | 0.183      | 0.143        | 0.041 (0.001)    | 0.989 (0.031)    | 0 (0.000) |     3.22 | bobeksde, draken, hampus, Ro1f, spooke |
|           18 |     3835 | 2024-11-08 | Metizport      | L   | 0.172      | -            | -                | -                | -         |    -1.51 | bobeksde, draken, hampus, Ro1f, spooke |
|           17 |     3861 | 2024-11-08 | Zero Tenacity  | L   | 0.170      | -            | -                | -                | -         |    -2.35 | bobeksde, draken, hampus, Ro1f, spooke |
|           16 |     3964 | 2024-11-06 | Dynamo Eclot   | L   | 0.158      | -            | -                | -                | -         |    -1.38 | bobeksde, draken, hampus, Ro1f, spooke |
|           15 |     4003 | 2024-11-05 | Showmakerz     | W   | 0.154      | -            | -                | -                | 0 (0.000) |     0.69 | bobeksde, draken, hampus, Ro1f, spooke |
|           14 |     4069 | 2024-11-04 | HOTU           | W   | 0.148      | 0.384        | -                | 0.588 (0.040)    | 0 (0.000) |     1.48 | bobeksde, draken, hampus, Ro1f, spooke |
|           13 |     4108 | 2024-11-03 | Insilio        | W   | 0.143      | 0.143        | -                | 0.433 (0.011)    | 0 (0.000) |     0.88 | bobeksde, draken, hampus, Ro1f, spooke |
|           12 |     4261 | 2024-11-01 | OG             | W   | 0.132      | 0.384        | 0.041 (0.002)    | 0.989 (0.060)    | 0 (0.000) |     2.33 | bobeksde, draken, hampus, Ro1f, spooke |
|           11 |     4298 | 2024-10-31 | ECSTATIC       | L   | 0.127      | -            | -                | -                | -         |    -1.86 | bobeksde, draken, hampus, Ro1f, spooke |
|           10 |     4311 | 2024-10-31 | Metizport      | W   | 0.126      | 0.333        | 0.062 (0.003)    | 0.367 (0.019)    | 0 (0.000) |     2.89 | bobeksde, draken, hampus, Ro1f, spooke |
|            9 |     4396 | 2024-10-30 | 9Pandas        | L   | 0.120      | -            | -                | -                | -         |    -1.15 | bobeksde, draken, hampus, Ro1f, spooke |
|            8 |     4423 | 2024-10-29 | Endpoint       | W   | 0.116      | 0.333        | 0.007 (0.000)    | 0.225 (0.010)    | 0 (0.000) |     1.42 | bobeksde, draken, hampus, Ro1f, spooke |
|            7 |     4436 | 2024-10-29 | Tricked Esport | L   | 0.116      | -            | -                | -                | -         |    -1.91 | bobeksde, draken, hampus, Ro1f, spooke |
|            6 |     4450 | 2024-10-29 | Rare Atom      | W   | 0.115      | 0.333        | 0.008 (0.000)    | 0.339 (0.016)    | -         |     1.70 | bobeksde, draken, hampus, Ro1f, spooke |
|            5 |     4612 | 2024-10-26 | Nexus Gaming   | W   | 0.098      | 0.143        | 0.161 (0.003)    | 0.539 (0.009)    | -         |     2.59 | bobeksde, draken, hampus, Ro1f, spooke |
|            4 |     4855 | 2024-10-21 | UNiTY esports  | W   | 0.070      | 0.384        | 0.019 (0.001)    | -                | -         |     0.93 | bobeksde, draken, hampus, Ro1f, spooke |
|            3 |     4895 | 2024-10-20 | Wild Lotus     | L   | 0.065      | -            | -                | -                | -         |    -1.66 | bobeksde, draken, hampus, Ro1f, spooke |
|            2 |     5149 | 2024-10-16 | WW Team        | W   | 0.042      | -            | -                | -                | -         |     0.10 | bobeksde, draken, hampus, Ro1f, spooke |
|            1 |     5273 | 2024-10-13 | Insilio        | L   | 0.026      | -            | -                | -                | -         |    -0.71 | bobeksde, draken, hampus, Ro1f, spooke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,182.82)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.311 | $1,864.89      | $580.19         |
| 2024-11-23 |      0.305 | $10,873.30     | $3,318.62       |
| 2024-11-09 |      0.212 | $4,623.93      | $978.73         |
| 2024-10-31 |      0.153 | $2,000.00      | $305.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
