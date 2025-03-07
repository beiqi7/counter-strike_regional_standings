### Roster Details<br />
Team Name: Nemiga Gaming<br />
Roster: 1eeR, khaN, riskyb0b, Xant3r, zweih<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  934.4<br />
<br />
Final Rank Value (934.4) = Starting Rank Value (967.5) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.470[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.086[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 967.5
- 400 + ( ( 0.257 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 967.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      117 | 2025-02-25 | CYBERSHOKE Esports   | L   | 0.776      | -            | -                | -                | -         |   -13.37 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           31 |      144 | 2025-02-24 | Sashi Esport         | W   | 0.771      | 0.500        | 0.007 (0.003)    | 0.535 (0.248)    | 0 (0.000) |    12.53 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           30 |      290 | 2025-02-21 | CYBERSHOKE Esports   | L   | 0.753      | -            | -                | -                | -         |   -14.09 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           29 |      393 | 2025-02-18 | Fire Flux Esports    | W   | 0.738      | 0.500        | 0.008 (0.003)    | 1.000 (0.443)    | 0 (0.000) |    10.67 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           28 |      586 | 2025-02-14 | B8                   | L   | 0.715      | -            | -                | -                | -         |    -6.62 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           27 |      620 | 2025-02-13 | Sashi Esport         | W   | 0.708      | 0.435        | 0.007 (0.003)    | 0.535 (0.198)    | 0 (0.000) |    11.32 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           26 |      666 | 2025-02-11 | Metizport            | L   | 0.697      | -            | -                | -                | -         |    -9.63 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           25 |      692 | 2025-02-10 | TEAM NEXT LEVEL      | W   | 0.693      | 0.143        | -                | 0.442 (0.053)    | 0 (0.000) |     5.85 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           24 |      703 | 2025-02-10 | BetBoom Team         | L   | 0.692      | -            | -                | -                | -         |    -8.66 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           23 |      941 | 2025-02-06 | PARIVISION           | L   | 0.669      | -            | -                | -                | -         |   -15.84 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           22 |      999 | 2025-02-05 | Imperial Female      | W   | 0.665      | 0.143        | 0.146 (0.017)    | 0.159 (0.018)    | 0 (0.000) |    12.39 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           21 |     1008 | 2025-02-05 | B8                   | L   | 0.664      | -            | -                | -                | -         |    -5.97 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           20 |     1320 | 2025-01-24 | 500                  | W   | 0.599      | 0.500        | 0.118 (0.042)    | 1.000 (0.360)    | -         |    11.05 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           19 |     1359 | 2025-01-23 | Betera Esports       | L   | 0.594      | -            | -                | -                | -         |   -15.85 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           18 |     1452 | 2025-01-17 | FURIA                | L   | 0.559      | -            | -                | -                | -         |    -5.68 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           17 |     3304 | 2024-11-18 | BetBoom Team         | L   | 0.229      | -            | -                | -                | -         |    -3.28 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           16 |     3346 | 2024-11-17 | Rebels Gaming        | W   | 0.224      | -            | -                | -                | 1 (0.269) |     1.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           15 |     3386 | 2024-11-17 | Cloud9               | L   | 0.220      | -            | -                | -                | -         |    -6.11 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           14 |     3412 | 2024-11-16 | MOUZ                 | L   | 0.218      | -            | -                | -                | -         |    -0.02 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           13 |     3805 | 2024-11-09 | Natus Vincere Junior | L   | 0.176      | -            | -                | -                | -         |    -2.62 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           12 |     3858 | 2024-11-08 | 500                  | W   | 0.170      | 0.143        | 0.118 (0.003)    | 1.000 (0.029)    | -         |     3.21 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           11 |     3914 | 2024-11-07 | PARIVISION           | W   | 0.164      | -            | -                | -                | -         |     0.81 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|           10 |     4011 | 2024-11-05 | Wild Lotus           | W   | 0.154      | -            | -                | -                | -         |     0.55 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            9 |     4901 | 2024-10-20 | HEROIC               | L   | 0.065      | -            | -                | -                | -         |    -0.83 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            8 |     4938 | 2024-10-19 | BC.Game Esports      | W   | 0.060      | 0.624        | 0.061 (0.003)    | 1.000 (0.045)    | 1 (0.072) |     1.07 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            7 |     4951 | 2024-10-19 | 3DMAX                | W   | 0.059      | 0.500        | 0.261 (0.009)    | -                | -         |     1.80 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            6 |     4968 | 2024-10-19 | Fnatic               | W   | 0.058      | 0.624        | -                | 0.471 (0.021)    | 1 (0.070) |     1.02 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            5 |     5013 | 2024-10-18 | Fluxo                | W   | 0.053      | 0.624        | 0.050 (0.002)    | -                | 1 (0.063) |     0.76 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            4 |     5037 | 2024-10-17 | HEROIC               | L   | 0.049      | -            | -                | -                | -         |    -0.61 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            3 |     5071 | 2024-10-17 | Aurora Gaming        | W   | 0.047      | 0.624        | -                | 0.633 (0.022)    | 1 (0.056) |     0.45 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            2 |     5115 | 2024-10-16 | 3DMAX                | W   | 0.043      | 0.500        | 0.261 (0.007)    | -                | -         |     1.31 | 1eeR, khaN, riskyb0b, Xant3r, zweih |
|            1 |     5148 | 2024-10-16 | HEROIC               | L   | 0.042      | -            | -                | -                | -         |    -0.53 | 1eeR, khaN, riskyb0b, Xant3r, zweih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,630.65)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-15 |      0.866 | $2,000.00      | $1,731.48       |
| 2024-11-09 |      0.211 | $10,060.72     | $2,124.86       |
| 2024-10-20 |      0.078 | $12,500.00     | $972.22         |
| 2024-10-19 |      0.072 | $150,000.00    | $10,802.08      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
