### Roster Details<br />
Team Name: B8<br />
Roster: alex666, esenthial, headtr1ck, kensizor, npl<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1133.7<br />
<br />
Final Rank Value (1133.7) = Starting Rank Value (1116.6) + Head To Head Adjustments (17.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.534[<sup>1</sup>](#table2)
- Bounty Collected: 0.388[<sup>2</sup>](#table1)
- Opponent Network: 0.302[<sup>2</sup>](#table1)
- LAN Wins: 0.076[<sup>2</sup>](#table1)

The average of these factors is 0.325<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1116.6
- 400 + ( ( 0.325 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1116.6


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
|           33 |       68 | 2025-02-26 | RUSH B (Russian team) | W   | 0.783      | 0.500        | 0.026 (0.012)    | 0.901 (0.423)    | 0 (0.000) |     5.00 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           32 |      175 | 2025-02-23 | BC.Game Esports       | W   | 0.766      | 0.435        | 0.061 (0.024)    | 1.000 (0.399)    | 0 (0.000) |    11.50 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           31 |      193 | 2025-02-23 | 9Pandas               | W   | 0.764      | 0.435        | 0.084 (0.034)    | 0.481 (0.192)    | 0 (0.000) |     8.59 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           30 |      232 | 2025-02-22 | CYBERSHOKE Esports    | W   | 0.759      | 0.435        | -                | 1.000 (0.396)    | 0 (0.000) |     5.95 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           29 |      321 | 2025-02-20 | Monte                 | W   | 0.749      | 0.435        | 0.036 (0.014)    | 0.766 (0.299)    | 0 (0.000) |     7.12 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           28 |      354 | 2025-02-19 | Iberian Soul          | W   | 0.744      | 0.500        | -                | 0.620 (0.277)    | -         |     3.73 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           27 |      544 | 2025-02-15 | 500                   | L   | 0.720      | -            | -                | -                | -         |   -11.95 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           26 |      586 | 2025-02-14 | Nemiga Gaming         | W   | 0.715      | 0.435        | 0.074 (0.028)    | -                | -         |     6.62 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           25 |      637 | 2025-02-12 | GUN5 Esports          | W   | 0.703      | 0.435        | 0.105 (0.038)    | 0.562 (0.206)    | -         |     7.67 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           24 |      863 | 2025-02-07 | Benched               | L   | 0.678      | -            | -                | -                | -         |   -20.39 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           23 |      898 | 2025-02-07 | PARIVISION            | L   | 0.675      | -            | -                | -                | -         |   -18.58 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           22 |      925 | 2025-02-06 | Alliance              | W   | 0.671      | -            | -                | -                | -         |     4.35 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           21 |      993 | 2025-02-05 | PARIVISION            | W   | 0.665      | -            | -                | -                | -         |     2.38 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           20 |     1008 | 2025-02-05 | Nemiga Gaming         | W   | 0.664      | 0.143        | 0.074 (0.008)    | -                | -         |     5.97 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           19 |     1030 | 2025-02-04 | Fire Flux Esports     | W   | 0.660      | 0.435        | -                | 1.000 (0.344)    | -         |     5.51 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           18 |     1134 | 2025-02-02 | Sashi Esport          | W   | 0.647      | -            | -                | -                | -         |     6.47 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           17 |     1233 | 2025-01-28 | Zero Tenacity         | W   | 0.622      | 0.500        | -                | 0.778 (0.290)    | -         |     5.07 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           16 |     1318 | 2025-01-24 | ARCRED                | W   | 0.599      | 0.500        | -                | 0.526 (0.189)    | -         |     3.40 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           15 |     1390 | 2025-01-22 | Team Spirit Academy   | L   | 0.588      | -            | -                | -                | -         |   -12.36 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           14 |     1444 | 2025-01-17 | G2 Esports            | L   | 0.561      | -            | -                | -                | -         |    -1.95 | alex666, esenthial, headtr1ck, kensizor, npl     |
|           13 |     2075 | 2024-12-12 | ECSTATIC              | L   | 0.358      | -            | -                | -                | -         |    -8.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           12 |     3109 | 2024-11-22 | Astralis              | L   | 0.247      | -            | -                | -                | -         |    -0.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           11 |     3169 | 2024-11-21 | Aurora Gaming         | L   | 0.242      | -            | -                | -                | -         |    -6.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           10 |     3188 | 2024-11-20 | Team Spirit           | L   | 0.240      | -            | -                | -                | -         |    -0.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            9 |     4538 | 2024-10-27 | SAW                   | L   | 0.105      | -            | -                | -                | -         |    -0.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            8 |     4553 | 2024-10-27 | PaiN Gaming           | W   | 0.104      | 0.500        | 0.357 (0.022)    | -                | 1 (0.124) |     3.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            7 |     4598 | 2024-10-26 | Eternal Fire          | W   | 0.098      | 0.500        | 0.731 (0.043)    | -                | 1 (0.118) |     3.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            6 |     4681 | 2024-10-25 | SAW                   | L   | 0.093      | -            | -                | -                | -         |    -0.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            5 |     4697 | 2024-10-25 | Eternal Fire          | W   | 0.091      | 0.500        | 0.731 (0.040)    | -                | 1 (0.110) |     2.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            4 |     4939 | 2024-10-19 | Team Falcons          | L   | 0.060      | -            | -                | -                | -         |    -0.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            3 |     5007 | 2024-10-18 | JANO Esports          | W   | 0.053      | -            | -                | -                | 1 (0.064) |     0.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            2 |     5140 | 2024-10-16 | The MongolZ           | L   | 0.042      | -            | -                | -                | -         |    -0.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|            1 |     5143 | 2024-10-16 | Ninjas in Pyjamas     | W   | 0.042      | -            | -                | -                | 1 (0.050) |     0.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,215.07)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $22,000.00     | $20,211.48      |
| 2025-02-15 |      0.866 | $5,000.00      | $4,328.70       |
| 2024-10-27 |      0.125 | $20,000.00     | $2,509.26       |
| 2024-10-20 |      0.078 | $15,000.00     | $1,165.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
