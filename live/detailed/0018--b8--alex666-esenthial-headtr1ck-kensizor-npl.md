### Roster Details<br />
Team Name: B8<br />
Roster: alex666, esenthial, headtr1ck, kensizor, npl<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1226.2<br />
<br />
Final Rank Value (1226.2) = Starting Rank Value (1214.0) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.546[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.367[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.391<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1214.0
- 400 + ( ( 0.391 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1214.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |       62 | 2025-02-26 | RUSH B (Russian team) | W   | 1.000      | 0.500        | 0.032 (0.016)    | 0.984 (0.492)    | 0 (0.000) |     5.08 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           50 |      167 | 2025-02-23 | BC.Game Esports       | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.976 (0.424)    | 0 (0.000) |    15.15 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           49 |      185 | 2025-02-23 | 9Pandas               | W   | 1.000      | 0.435        | 0.104 (0.045)    | 0.628 (0.273)    | 0 (0.000) |    10.73 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           48 |      224 | 2025-02-22 | CYBERSHOKE Esports    | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     6.90 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           47 |      312 | 2025-02-20 | Monte                 | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.866 (0.376)    | 0 (0.000) |     8.00 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           46 |      341 | 2025-02-19 | Iberian Soul          | W   | 1.000      | 0.500        | -                | 0.615 (0.307)    | -         |     3.70 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           45 |      518 | 2025-02-15 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -17.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           44 |      560 | 2025-02-14 | Nemiga Gaming         | W   | 1.000      | 0.435        | 0.204 (0.089)    | -                | -         |    10.10 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           43 |      617 | 2025-02-12 | GUN5 Esports          | W   | 1.000      | 0.435        | 0.123 (0.053)    | -                | -         |     8.44 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           42 |      839 | 2025-02-07 | Benched               | L   | 1.000      | -            | -                | -                | -         |   -30.60 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           41 |      874 | 2025-02-07 | PARIVISION            | L   | 1.000      | -            | -                | -                | -         |   -27.94 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           40 |      901 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |     4.80 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           39 |      970 | 2025-02-05 | PARIVISION            | W   | 1.000      | -            | -                | -                | -         |     2.85 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           38 |      985 | 2025-02-05 | Nemiga Gaming         | W   | 1.000      | 0.143        | 0.204 (0.029)    | -                | -         |    10.09 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           37 |     1008 | 2025-02-04 | Fire Flux Esports     | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     7.00 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           36 |     1109 | 2025-02-02 | Sashi Esport          | W   | 1.000      | 0.435        | -                | 0.606 (0.263)    | -         |     8.11 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           35 |     1199 | 2025-01-28 | Zero Tenacity         | W   | 0.971      | 0.500        | -                | 0.843 (0.409)    | -         |     6.48 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           34 |     1243 | 2025-01-24 | ARCRED                | W   | 0.944      | 0.500        | -                | 0.541 (0.255)    | -         |     3.81 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           33 |     1284 | 2025-01-22 | Team Spirit Academy   | L   | 0.931      | -            | -                | -                | -         |   -19.68 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           32 |     1322 | 2025-01-17 | G2 Esports            | L   | 0.899      | -            | -                | -                | -         |    -1.43 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           31 |     1953 | 2024-12-12 | ECSTATIC              | L   | 0.655      | -            | -                | -                | -         |   -17.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2989 | 2024-11-22 | Astralis              | L   | 0.522      | -            | -                | -                | -         |    -0.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     3048 | 2024-11-21 | Aurora Gaming         | L   | 0.516      | -            | -                | -                | -         |   -14.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     3067 | 2024-11-20 | Team Spirit           | L   | 0.514      | -            | -                | -                | -         |    -0.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     4378 | 2024-10-27 | SAW                   | L   | 0.351      | -            | -                | -                | -         |    -3.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     4392 | 2024-10-27 | PaiN Gaming           | W   | 0.350      | 0.500        | 0.333 (0.058)    | -                | 1 (0.350) |     8.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |     4435 | 2024-10-26 | Eternal Fire          | W   | 0.343      | 0.500        | 0.708 (0.121)    | -                | 1 (0.343) |    10.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     4517 | 2024-10-25 | SAW                   | L   | 0.336      | -            | -                | -                | -         |    -2.89 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           23 |     4529 | 2024-10-25 | Eternal Fire          | W   | 0.335      | 0.500        | 0.708 (0.119)    | -                | 1 (0.335) |    10.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           22 |     4750 | 2024-10-19 | Team Falcons          | L   | 0.297      | -            | -                | -                | -         |    -0.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           21 |     4815 | 2024-10-18 | JANO Esports          | W   | 0.289      | -            | -                | -                | 1 (0.289) |     1.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           20 |     4925 | 2024-10-16 | The MongolZ           | L   | 0.276      | -            | -                | -                | -         |    -0.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           19 |     4928 | 2024-10-16 | Ninjas in Pyjamas     | W   | 0.276      | -            | -                | -                | 1 (0.276) |     1.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           18 |     5482 | 2024-10-05 | GamerLegion           | L   | 0.204      | -            | -                | -                | -         |    -0.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           17 |     5630 | 2024-10-03 | ALTERNATE aTTaX       | W   | 0.189      | -            | -                | -                | -         |     1.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           16 |     5917 | 2024-09-28 | 3DMAX                 | W   | 0.157      | -            | -                | -                | -         |     4.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           15 |     6012 | 2024-09-27 | SAW                   | W   | 0.151      | -            | -                | -                | -         |     3.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           14 |     6035 | 2024-09-27 | OG                    | W   | 0.149      | -            | -                | -                | -         |     0.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           13 |     6043 | 2024-09-27 | GamerLegion           | L   | 0.149      | -            | -                | -                | -         |    -4.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           12 |     6090 | 2024-09-26 | Fire Flux Esports     | W   | 0.144      | -            | -                | -                | -         |     0.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           11 |     6096 | 2024-09-26 | Illuminar Gaming      | W   | 0.143      | -            | -                | -                | -         |     0.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           10 |     6129 | 2024-09-26 | Insilio               | W   | 0.141      | -            | -                | -                | -         |     0.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            9 |     6174 | 2024-09-25 | BC.Game Esports       | W   | 0.138      | -            | -                | -                | -         |     0.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            8 |     6800 | 2024-09-16 | Team Sampi            | L   | 0.074      | -            | -                | -                | -         |    -2.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            7 |     7043 | 2024-09-12 | AMKAL ESPORTS         | L   | 0.048      | -            | -                | -                | -         |    -1.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            6 |     7228 | 2024-09-08 | GamerLegion           | W   | 0.023      | -            | -                | -                | -         |     0.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            5 |     7238 | 2024-09-08 | Zero Tenacity         | W   | 0.023      | -            | -                | -                | -         |     0.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            4 |     7307 | 2024-09-07 | BC.Game Esports       | W   | 0.016      | -            | -                | -                | -         |     0.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            3 |     7378 | 2024-09-06 | 9Pandas               | L   | 0.011      | -            | -                | -                | -         |    -0.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            2 |     7457 | 2024-09-05 | SINNERS Esports       | W   | 0.004      | -            | -                | -                | -         |     0.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            1 |     7498 | 2024-09-05 | 9INE                  | W   | 0.002      | -            | -                | -                | -         |     0.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,869.38)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $22,000.00     | $22,000.00      |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-10-27 |      0.351 | $20,000.00     | $7,014.90       |
| 2024-10-20 |      0.303 | $3,500.00      | $1,060.71       |
| 2024-10-20 |      0.303 | $15,000.00     | $4,544.86       |
| 2024-10-06 |      0.211 | $2,000.00      | $421.26         |
| 2024-09-28 |      0.157 | $2,000.00      | $314.22         |
| 2024-09-08 |      0.023 | $22,000.00     | $513.43         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
