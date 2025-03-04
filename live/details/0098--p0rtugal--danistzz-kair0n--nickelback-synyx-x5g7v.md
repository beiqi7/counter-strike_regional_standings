### Roster Details<br />
Team Name: P0RTUGAL<br />
Roster: danistzz, KaiR0N-, NickelBack, synyx, X5G7V<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  888.9<br />
<br />
Final Rank Value (888.9) = Starting Rank Value (802.0) + Head To Head Adjustments (86.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.425[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 802.0
- 400 + ( ( 0.193 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 802.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1507 | 2024-12-22 | Metizport                                 | W   | 0.724      | 0.143        | 0.087 (0.009)    | 0.517 (0.053)    | 0 (0.000) |    17.70 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           11 |     1526 | 2024-12-22 | RUSH B (Russian team)                     | W   | 0.723      | 0.143        | 0.032 (0.003)    | 0.985 (0.102)    | 0 (0.000) |    15.24 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           10 |     1583 | 2024-12-21 | Nexus Gaming                              | W   | 0.716      | 0.143        | 0.219 (0.022)    | 0.808 (0.083)    | 0 (0.000) |    18.12 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            9 |     1884 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.664      | -            | -                | -                | -         |   -10.12 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            8 |     1891 | 2024-12-13 | ROYALS                                    | W   | 0.664      | 0.143        | 0.005 (0.000)    | 0.202 (0.019)    | 0 (0.000) |     6.82 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            7 |     1898 | 2024-12-13 | VOLT (European team)                      | W   | 0.663      | 0.143        | 0.003 (0.000)    | 0.166 (0.016)    | 0 (0.000) |     7.13 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            6 |     2075 | 2024-12-08 | VOLT (European team)                      | W   | 0.631      | 0.143        | 0.003 (0.000)    | 0.166 (0.015)    | 0 (0.000) |     7.16 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            5 |     2082 | 2024-12-08 | AMKAL ESPORTS                             | W   | 0.631      | 0.143        | 0.020 (0.002)    | 0.386 (0.035)    | 0 (0.000) |    10.29 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            4 |     2096 | 2024-12-08 | Kubix Esports                             | W   | 0.630      | 0.143        | 0.053 (0.005)    | 0.494 (0.044)    | 0 (0.000) |    13.25 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            3 |     3966 | 2024-11-03 | Fire Flux Esports                         | L   | 0.397      | -            | -                | -                | -         |    -3.67 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            2 |     4072 | 2024-11-02 | Dynamo Eclot                              | L   | 0.389      | -            | -                | -                | -         |    -1.81 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            1 |     4528 | 2024-10-25 | Copenhagen Wolves (American organization) | W   | 0.335      | 0.384        | 0.019 (0.002)    | 1.000 (0.129)    | 0 (0.000) |     6.77 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,277.19)
- Divide that value by the 5th highest value among all rosters ($276,969.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.724 | $16,949.15     | $12,277.19      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
