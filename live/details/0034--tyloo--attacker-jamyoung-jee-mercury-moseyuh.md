### Roster Details<br />
Team Name: TYLOO<br />
Roster: Attacker, JamYoung, Jee, Mercury, Moseyuh<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1066.9<br />
<br />
Final Rank Value (1066.9) = Starting Rank Value (1063.4) + Head To Head Adjustments (3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.490[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.306[<sup>2</sup>](#table1)

The average of these factors is 0.319<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1063.4
- 400 + ( ( 0.319 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1063.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |        2 | 2025-03-03 | GamerLegion             | L   | 1.000      | -            | -                | -                | -         |    -1.74 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           22 |        4 | 2025-03-02 | Eternal Fire            | W   | 1.000      | 0.889        | 0.708 (0.629)    | 0.524 (0.466)    | 1 (1.000) |    31.15 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           21 |        7 | 2025-03-01 | 3DMAX                   | W   | 1.000      | 0.889        | 0.302 (0.268)    | 0.510 (0.454)    | 1 (1.000) |    29.96 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           20 |      642 | 2025-02-11 | Lynn Vision Gaming      | L   | 1.000      | -            | -                | -                | -         |   -20.09 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           19 |      649 | 2025-02-11 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |   -13.18 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           18 |      651 | 2025-02-10 | Rare Atom               | L   | 1.000      | -            | -                | -                | -         |   -23.09 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           17 |     4013 | 2024-11-03 | Lynn Vision Gaming      | W   | 0.395      | 0.417        | 0.013 (0.002)    | 0.333 (0.055)    | 1 (0.395) |     4.11 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           16 |     4075 | 2024-11-02 | ATOX Esports            | W   | 0.388      | 0.417        | 0.010 (0.002)    | 0.053 (0.009)    | 0 (0.000) |     1.71 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           15 |     4932 | 2024-10-16 | Unsettled Resentment    | W   | 0.275      | 0.417        | 0.016 (0.002)    | 0.228 (0.026)    | 0 (0.000) |     1.27 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           14 |     5271 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.229      | -            | -                | -                | -         |    -4.90 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           13 |     5277 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.229      | -            | -                | -                | -         |    -4.98 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           12 |     5350 | 2024-10-08 | Ex-GR Gaming            | W   | 0.222      | 0.417        | 0.013 (0.001)    | 0.074 (0.007)    | 0 (0.000) |     0.84 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           11 |     5356 | 2024-10-08 | Ex-GR Gaming            | W   | 0.222      | 0.417        | 0.013 (0.001)    | 0.074 (0.007)    | 0 (0.000) |     0.85 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           10 |     5682 | 2024-10-02 | DEWA United             | W   | 0.182      | 0.417        | -                | 0.109 (0.008)    | 0 (0.000) |     0.28 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            9 |     5687 | 2024-10-02 | DEWA United             | W   | 0.182      | 0.417        | -                | 0.109 (0.008)    | 0 (0.000) |     0.28 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            8 |     5759 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.175      | -            | -                | -                | 0 (0.000) |     0.51 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            7 |     5762 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.175      | -            | -                | -                | -         |     0.51 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            6 |     5824 | 2024-09-30 | -72C                    | W   | 0.169      | 0.417        | 0.001 (0.000)    | -                | -         |     0.26 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            5 |     5825 | 2024-09-30 | -72C                    | W   | 0.169      | 0.417        | 0.001 (0.000)    | -                | -         |     0.26 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            4 |     6199 | 2024-09-25 | The QUBE Esports        | W   | 0.135      | -            | -                | -                | -         |     0.19 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            3 |     6205 | 2024-09-25 | The QUBE Esports        | W   | 0.135      | -            | -                | -                | -         |     0.19 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            2 |     6296 | 2024-09-24 | The Huns Esports        | L   | 0.129      | -            | -                | -                | -         |    -2.47 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            1 |     6304 | 2024-09-24 | The Huns Esports        | W   | 0.129      | 0.417        | 0.029 (0.002)    | 0.387 (0.021)    | -         |     1.60 | JamYoung, Jee, Mercury, Moseyuh, Starry   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,918.78)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.395 | $15,000.00     | $5,918.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
