### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, FL4MUS, ICY<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1627.8<br />
<br />
Final Rank Value (1627.8) = Starting Rank Value (1661.1) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.669[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.929[<sup>2</sup>](#table1)

The average of these factors is 0.572<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1661.1
- 400 + ( ( 0.572 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 1661.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      399 | 2025-02-18 | MOUZ          | L   | 0.737      | -            | -                | -                | -         |    -3.89 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           23 |      421 | 2025-02-17 | PaiN Gaming   | L   | 0.732      | -            | -                | -                | -         |   -11.22 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           22 |      489 | 2025-02-16 | Wildcard      | W   | 0.725      | 1.000        | 0.162 (0.141)    | 0.216 (0.188)    | 1 (0.870) |     1.28 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           21 |      545 | 2025-02-15 | Complexity    | W   | 0.720      | 1.000        | 0.092 (0.079)    | 0.102 (0.088)    | 1 (0.864) |     0.40 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           20 |      599 | 2025-02-14 | 3DMAX         | L   | 0.714      | -            | -                | -                | -         |   -14.14 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           19 |      879 | 2025-02-07 | Team Spirit   | L   | 0.677      | -            | -                | -                | -         |    -3.18 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           18 |     1045 | 2025-02-04 | Team Vitality | L   | 0.659      | -            | -                | -                | -         |    -4.82 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           17 |     1128 | 2025-02-02 | Eternal Fire  | W   | 0.649      | 1.000        | 0.731 (0.569)    | 0.557 (0.434)    | 1 (0.778) |    16.89 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           16 |     1154 | 2025-02-01 | G2 Esports    | W   | 0.643      | 1.000        | 0.528 (0.407)    | 0.246 (0.189)    | 1 (0.771) |     6.01 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           15 |     1185 | 2025-01-31 | MIBR          | W   | 0.637      | 1.000        | 0.105 (0.080)    | 0.265 (0.203)    | 1 (0.765) |     1.80 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           14 |     1196 | 2025-01-30 | SAW           | W   | 0.631      | 1.000        | 0.316 (0.240)    | 0.260 (0.197)    | 1 (0.757) |     3.16 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           13 |     1209 | 2025-01-29 | PaiN Gaming   | L   | 0.625      | -            | -                | -                | -         |    -9.74 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           12 |     1426 | 2025-01-19 | Team Vitality | L   | 0.571      | -            | -                | -                | -         |    -4.08 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           11 |     1457 | 2025-01-16 | Complexity    | W   | 0.553      | 0.363        | 0.092 (0.022)    | 0.102 (0.025)    | -         |     0.34 | electroNic, fame, FL1T, FL4MUS, ICY   |
|           10 |     3040 | 2024-11-22 | Sashi Esport  | W   | 0.251      | 0.143        | -                | 0.535 (0.023)    | 1 (0.302) |     0.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            9 |     3119 | 2024-11-21 | 9Pandas       | W   | 0.246      | 0.143        | 0.084 (0.004)    | 0.481 (0.020)    | 1 (0.295) |     0.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            8 |     3161 | 2024-11-21 | TSM           | W   | 0.242      | 0.143        | -                | 0.065 (0.003)    | 1 (0.291) |     0.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            7 |     3186 | 2024-11-20 | Passion UA    | L   | 0.241      | -            | -                | -                | -         |    -7.49 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            6 |     4691 | 2024-10-25 | OG            | L   | 0.092      | -            | -                | -                | -         |    -2.86 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            5 |     4841 | 2024-10-21 | Team Falcons  | W   | 0.071      | -            | -                | -                | -         |     0.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            4 |     4853 | 2024-10-21 | OG            | L   | 0.070      | -            | -                | -                | -         |    -2.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            3 |     5403 | 2024-10-11 | Natus Vincere | L   | 0.015      | -            | -                | -                | -         |    -0.30 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            2 |     5482 | 2024-10-09 | The MongolZ   | W   | 0.005      | 0.624        | 1.000 (0.003)    | -                | 1 (0.006) |     0.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|            1 |     5502 | 2024-10-09 | Astralis      | W   | 0.003      | 0.624        | 0.788 (0.002)    | -                | -         |     0.09 | electroNic, fame, FL1T, Jame, n0rb3r7 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,175.46)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      0.919 | $31,250.00     | $28,713.83      |
| 2025-02-09 |      0.825 | $40,000.00     | $33,000.00      |
| 2025-01-19 |      0.686 | $7,500.00      | $5,144.97       |
| 2024-10-13 |      0.032 | $10,000.00     | $316.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
