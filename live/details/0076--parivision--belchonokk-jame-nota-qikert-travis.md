### Roster Details<br />
Team Name: PARIVISION<br />
Roster: BELCHONOKK, Jame, nota, Qikert, TRAVIS<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  886.8<br />
<br />
Final Rank Value (886.8) = Starting Rank Value (685.3) + Head To Head Adjustments (201.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.3
- 400 + ( ( 0.129 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 685.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |       15 | 2025-02-28 | BC.Game Esports                           | W   | 0.793      | 0.143        | 0.061 (0.008)    | 1.000 (0.136)    | 0 (0.000) |    18.76 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           26 |       18 | 2025-02-28 | Partizan Esports                          | L   | 0.792      | -            | -                | -                | -         |    -7.21 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           25 |       33 | 2025-02-27 | Alliance                                  | L   | 0.787      | -            | -                | -                | -         |   -13.19 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           24 |       74 | 2025-02-26 | Natus Vincere Junior                      | L   | 0.782      | -            | -                | -                | -         |   -10.03 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           23 |       78 | 2025-02-26 | BC.Game Esports                           | W   | 0.781      | 0.143        | 0.061 (0.008)    | 1.000 (0.134)    | 0 (0.000) |    18.95 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           22 |      110 | 2025-02-25 | 9Pandas                                   | W   | 0.777      | 0.500        | 0.084 (0.039)    | 0.481 (0.224)    | 0 (0.000) |    16.38 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           21 |      143 | 2025-02-24 | RUSH B (Russian team)                     | W   | 0.771      | 0.143        | -                | 0.901 (0.119)    | 0 (0.000) |    14.02 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           20 |      325 | 2025-02-20 | Ninjas in Pyjamas                         | W   | 0.749      | 0.143        | -                | 0.649 (0.083)    | 0 (0.000) |     7.68 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           19 |      362 | 2025-02-19 | Rhyno Esports                             | W   | 0.742      | -            | -                | -                | 0 (0.000) |     9.21 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           18 |      392 | 2025-02-18 | Monte                                     | W   | 0.738      | 0.500        | 0.036 (0.016)    | 0.766 (0.339)    | 0 (0.000) |    15.94 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           17 |      567 | 2025-02-14 | OG                                        | L   | 0.716      | -            | -                | -                | -         |    -8.38 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           16 |      735 | 2025-02-09 | Astralis                                  | L   | 0.688      | -            | -                | -                | -         |    -0.07 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           15 |      745 | 2025-02-09 | HEROIC                                    | W   | 0.686      | 0.143        | 0.120 (0.014)    | -                | 0 (0.000) |    17.49 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           14 |      809 | 2025-02-08 | Hesta                                     | L   | 0.682      | -            | -                | -                | -         |   -12.53 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           13 |      821 | 2025-02-08 | GamerLegion                               | W   | 0.681      | 0.143        | 0.094 (0.011)    | -                | 0 (0.000) |    21.16 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           12 |      869 | 2025-02-07 | Preasy Esport                             | W   | 0.677      | -            | -                | -                | 0 (0.000) |     9.67 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           11 |      898 | 2025-02-07 | B8                                        | W   | 0.675      | 0.143        | 0.134 (0.016)    | 0.740 (0.086)    | -         |    18.58 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|           10 |      941 | 2025-02-06 | Nemiga Gaming                             | W   | 0.669      | 0.143        | 0.074 (0.009)    | -                | -         |    15.84 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            9 |      993 | 2025-02-05 | B8                                        | L   | 0.665      | -            | -                | -                | -         |    -2.38 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            8 |     1009 | 2025-02-05 | Imperial Female                           | W   | 0.664      | 0.143        | 0.146 (0.017)    | -                | -         |    17.49 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            7 |     1050 | 2025-02-04 | Bad News Eagles                           | W   | 0.659      | -            | -                | -                | -         |     6.58 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            6 |     1061 | 2025-02-04 | Aurora Gaming                             | W   | 0.659      | -            | -                | -                | -         |    13.21 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            5 |     1092 | 2025-02-04 | Zero Tenacity                             | W   | 0.659      | 0.143        | -                | 0.778 (0.088)    | -         |    15.20 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            4 |     1098 | 2025-02-04 | Dardanians                                | W   | 0.659      | -            | -                | -                | -         |     3.21 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            3 |     1268 | 2025-01-27 | JiJieHao                                  | W   | 0.616      | 0.500        | -                | 0.252 (0.093)    | -         |     5.82 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            2 |     1357 | 2025-01-23 | Copenhagen Wolves (American organization) | W   | 0.594      | 0.500        | 0.017 (0.006)    | 1.000 (0.356)    | -         |    13.92 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |
|            1 |     1422 | 2025-01-21 | SINNERS Esports                           | L   | 0.583      | -            | -                | -                | -         |    -3.82 | BELCHONOKK, Jame, nota, Qikert, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
