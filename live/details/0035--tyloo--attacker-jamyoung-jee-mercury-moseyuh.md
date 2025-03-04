### Roster Details<br />
Team Name: TYLOO<br />
Roster: Attacker, JamYoung, Jee, Mercury, Moseyuh<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1062.5<br />
<br />
Final Rank Value (1062.5) = Starting Rank Value (1062.9) + Head To Head Adjustments (-0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.490[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.306[<sup>2</sup>](#table1)

The average of these factors is 0.319<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1062.9
- 400 + ( ( 0.319 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1062.9


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
|           23 |        1 | 2025-03-03 | GamerLegion             | L   | 1.000      | -            | -                | -                | -         |    -1.70 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           22 |        3 | 2025-03-02 | Eternal Fire            | W   | 1.000      | 0.889        | 0.708 (0.629)    | 0.524 (0.466)    | 1 (1.000) |    31.16 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           21 |        5 | 2025-03-01 | 3DMAX                   | W   | 1.000      | 0.889        | 0.302 (0.268)    | 0.510 (0.454)    | 1 (1.000) |    30.00 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           20 |      640 | 2025-02-11 | Lynn Vision Gaming      | L   | 1.000      | -            | -                | -                | -         |   -22.29 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           19 |      647 | 2025-02-11 | ATOX Esports            | L   | 1.000      | -            | -                | -                | -         |   -13.08 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           18 |      649 | 2025-02-10 | Rare Atom               | L   | 1.000      | -            | -                | -                | -         |   -23.00 | Attacker, JamYoung, Jee, Mercury, Moseyuh |
|           17 |     4011 | 2024-11-03 | Lynn Vision Gaming      | W   | 0.395      | 0.417        | 0.013 (0.002)    | 0.284 (0.047)    | 1 (0.395) |     3.17 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           16 |     4073 | 2024-11-02 | ATOX Esports            | W   | 0.389      | 0.417        | 0.010 (0.002)    | 0.053 (0.009)    | 0 (0.000) |     1.72 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           15 |     4930 | 2024-10-16 | Unsettled Resentment    | W   | 0.276      | 0.417        | 0.016 (0.002)    | 0.228 (0.026)    | 0 (0.000) |     1.28 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           14 |     5269 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.229      | -            | -                | -                | -         |    -5.48 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           13 |     5275 | 2024-10-09 | Lynn Vision Gaming      | L   | 0.229      | -            | -                | -                | -         |    -5.55 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           12 |     5348 | 2024-10-08 | Ex-GR Gaming            | W   | 0.223      | 0.417        | 0.013 (0.001)    | 0.074 (0.007)    | 0 (0.000) |     0.85 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           11 |     5354 | 2024-10-08 | Ex-GR Gaming            | W   | 0.222      | 0.417        | 0.013 (0.001)    | 0.074 (0.007)    | 0 (0.000) |     0.85 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|           10 |     5680 | 2024-10-02 | DEWA United             | W   | 0.183      | 0.417        | -                | 0.109 (0.008)    | 0 (0.000) |     0.28 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            9 |     5685 | 2024-10-02 | DEWA United             | W   | 0.182      | 0.417        | -                | 0.109 (0.008)    | 0 (0.000) |     0.28 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            8 |     5757 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.176      | -            | -                | -                | 0 (0.000) |     0.51 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            7 |     5760 | 2024-10-01 | Nomads (Mongolian team) | W   | 0.176      | -            | -                | -                | -         |     0.51 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            6 |     5822 | 2024-09-30 | -72C                    | W   | 0.169      | 0.417        | 0.001 (0.000)    | -                | -         |     0.26 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            5 |     5823 | 2024-09-30 | -72C                    | W   | 0.169      | 0.417        | 0.001 (0.000)    | -                | -         |     0.27 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            4 |     6197 | 2024-09-25 | The QUBE Esports        | W   | 0.136      | -            | -                | -                | -         |     0.19 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            3 |     6203 | 2024-09-25 | The QUBE Esports        | W   | 0.136      | -            | -                | -                | -         |     0.19 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            2 |     6294 | 2024-09-24 | The Huns Esports        | L   | 0.129      | -            | -                | -                | -         |    -2.48 | JamYoung, Jee, Mercury, Moseyuh, Starry   |
|            1 |     6302 | 2024-09-24 | The Huns Esports        | W   | 0.129      | 0.417        | 0.029 (0.002)    | 0.387 (0.021)    | -         |     1.60 | JamYoung, Jee, Mercury, Moseyuh, Starry   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,924.37)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.395 | $15,000.00     | $5,924.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
