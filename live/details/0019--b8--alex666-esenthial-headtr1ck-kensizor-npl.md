### Roster Details<br />
Team Name: B8<br />
Roster: alex666, esenthial, headtr1ck, kensizor, npl<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1226.3<br />
<br />
Final Rank Value (1226.3) = Starting Rank Value (1213.8) + Head To Head Adjustments (12.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.546[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.367[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.391<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1213.8
- 400 + ( ( 0.391 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1213.8


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
|           51 |       64 | 2025-02-26 | RUSH B (Russian team) | W   | 1.000      | 0.500        | 0.032 (0.016)    | 0.985 (0.492)    | 0 (0.000) |     5.07 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           50 |      169 | 2025-02-23 | BC.Game Esports       | W   | 1.000      | 0.435        | 0.091 (0.039)    | 0.976 (0.424)    | 0 (0.000) |    15.14 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           49 |      187 | 2025-02-23 | 9Pandas               | W   | 1.000      | 0.435        | 0.104 (0.045)    | 0.628 (0.273)    | 0 (0.000) |    10.72 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           48 |      226 | 2025-02-22 | CYBERSHOKE Esports    | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     6.90 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           47 |      314 | 2025-02-20 | Monte                 | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.866 (0.376)    | 0 (0.000) |     7.99 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           46 |      343 | 2025-02-19 | Iberian Soul          | W   | 1.000      | 0.500        | -                | 0.615 (0.307)    | -         |     3.70 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           45 |      520 | 2025-02-15 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -17.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           44 |      562 | 2025-02-14 | Nemiga Gaming         | W   | 1.000      | 0.435        | 0.204 (0.088)    | -                | -         |    10.18 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           43 |      619 | 2025-02-12 | GUN5 Esports          | W   | 1.000      | 0.435        | 0.123 (0.053)    | -                | -         |     8.44 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           42 |      841 | 2025-02-07 | Benched               | L   | 1.000      | -            | -                | -                | -         |   -30.60 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           41 |      876 | 2025-02-07 | PARIVISION            | L   | 1.000      | -            | -                | -                | -         |   -27.94 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           40 |      903 | 2025-02-06 | Alliance              | W   | 1.000      | -            | -                | -                | -         |     4.79 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           39 |      972 | 2025-02-05 | PARIVISION            | W   | 1.000      | -            | -                | -                | -         |     2.85 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           38 |      987 | 2025-02-05 | Nemiga Gaming         | W   | 1.000      | 0.143        | 0.204 (0.029)    | -                | -         |    10.20 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           37 |     1010 | 2025-02-04 | Fire Flux Esports     | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     7.00 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           36 |     1111 | 2025-02-02 | Sashi Esport          | W   | 1.000      | 0.435        | -                | 0.606 (0.263)    | -         |     8.11 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           35 |     1201 | 2025-01-28 | Zero Tenacity         | W   | 0.971      | 0.500        | -                | 0.843 (0.409)    | -         |     6.48 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           34 |     1245 | 2025-01-24 | ARCRED                | W   | 0.944      | 0.500        | -                | 0.541 (0.255)    | -         |     3.81 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           33 |     1286 | 2025-01-22 | Team Spirit Academy   | L   | 0.931      | -            | -                | -                | -         |   -19.67 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           32 |     1324 | 2025-01-17 | G2 Esports            | L   | 0.898      | -            | -                | -                | -         |    -1.43 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           31 |     1955 | 2024-12-12 | ECSTATIC              | L   | 0.655      | -            | -                | -                | -         |   -17.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2991 | 2024-11-22 | Astralis              | L   | 0.521      | -            | -                | -                | -         |    -0.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     3050 | 2024-11-21 | Aurora Gaming         | L   | 0.515      | -            | -                | -                | -         |   -14.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     3069 | 2024-11-20 | Team Spirit           | L   | 0.513      | -            | -                | -                | -         |    -0.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     4380 | 2024-10-27 | SAW                   | L   | 0.350      | -            | -                | -                | -         |    -3.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     4394 | 2024-10-27 | PaiN Gaming           | W   | 0.349      | 0.500        | 0.333 (0.058)    | -                | 1 (0.349) |     8.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |     4437 | 2024-10-26 | Eternal Fire          | W   | 0.343      | 0.500        | 0.708 (0.121)    | -                | 1 (0.343) |    10.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     4519 | 2024-10-25 | SAW                   | L   | 0.336      | -            | -                | -                | -         |    -2.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           23 |     4531 | 2024-10-25 | Eternal Fire          | W   | 0.335      | 0.500        | 0.708 (0.118)    | -                | 1 (0.335) |    10.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           22 |     4752 | 2024-10-19 | Team Falcons          | L   | 0.297      | -            | -                | -                | -         |    -0.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           21 |     4817 | 2024-10-18 | JANO Esports          | W   | 0.289      | -            | -                | -                | 1 (0.289) |     1.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           20 |     4927 | 2024-10-16 | The MongolZ           | L   | 0.276      | -            | -                | -                | -         |    -0.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           19 |     4930 | 2024-10-16 | Ninjas in Pyjamas     | W   | 0.275      | -            | -                | -                | 1 (0.275) |     1.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           18 |     5484 | 2024-10-05 | GamerLegion           | L   | 0.204      | -            | -                | -                | -         |    -0.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           17 |     5632 | 2024-10-03 | ALTERNATE aTTaX       | W   | 0.189      | -            | -                | -                | -         |     1.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           16 |     5919 | 2024-09-28 | 3DMAX                 | W   | 0.157      | -            | -                | -                | -         |     4.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           15 |     6014 | 2024-09-27 | SAW                   | W   | 0.150      | -            | -                | -                | -         |     3.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           14 |     6037 | 2024-09-27 | OG                    | W   | 0.149      | -            | -                | -                | -         |     0.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           13 |     6045 | 2024-09-27 | GamerLegion           | L   | 0.148      | -            | -                | -                | -         |    -4.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           12 |     6092 | 2024-09-26 | Fire Flux Esports     | W   | 0.143      | -            | -                | -                | -         |     0.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           11 |     6098 | 2024-09-26 | Illuminar Gaming      | W   | 0.143      | -            | -                | -                | -         |     0.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           10 |     6131 | 2024-09-26 | Insilio               | W   | 0.141      | -            | -                | -                | -         |     0.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            9 |     6176 | 2024-09-25 | BC.Game Esports       | W   | 0.137      | -            | -                | -                | -         |     0.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            8 |     6802 | 2024-09-16 | Team Sampi            | L   | 0.074      | -            | -                | -                | -         |    -2.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            7 |     7045 | 2024-09-12 | AMKAL ESPORTS         | L   | 0.047      | -            | -                | -                | -         |    -1.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            6 |     7230 | 2024-09-08 | GamerLegion           | W   | 0.023      | -            | -                | -                | -         |     0.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            5 |     7240 | 2024-09-08 | Zero Tenacity         | W   | 0.022      | -            | -                | -                | -         |     0.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            4 |     7309 | 2024-09-07 | BC.Game Esports       | W   | 0.016      | -            | -                | -                | -         |     0.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            3 |     7380 | 2024-09-06 | 9Pandas               | L   | 0.010      | -            | -                | -                | -         |    -0.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            2 |     7459 | 2024-09-05 | SINNERS Esports       | W   | 0.004      | -            | -                | -                | -         |     0.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            1 |     7500 | 2024-09-05 | 9INE                  | W   | 0.002      | -            | -                | -                | -         |     0.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,845.34)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $22,000.00     | $22,000.00      |
| 2025-02-15 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-10-27 |      0.350 | $20,000.00     | $7,007.45       |
| 2024-10-20 |      0.303 | $3,500.00      | $1,059.41       |
| 2024-10-20 |      0.303 | $15,000.00     | $4,539.27       |
| 2024-10-06 |      0.210 | $2,000.00      | $420.51         |
| 2024-09-28 |      0.157 | $2,000.00      | $313.48         |
| 2024-09-08 |      0.023 | $22,000.00     | $505.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
