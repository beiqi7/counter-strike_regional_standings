### Roster Details<br />
Team Name: Prototype Blaze<br />
Roster: ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  838.9<br />
<br />
Final Rank Value (838.9) = Starting Rank Value (850.8) + Head To Head Adjustments (-11.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.429[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.151[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.8
- 400 + ( ( 0.204 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 850.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       29 | 2025-02-27 | Imperial Female             | L   | 0.788      | -            | -                | -                | -         |    -7.42 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            9 |     1126 | 2025-02-02 | Permitta W                  | W   | 0.649      | 0.143        | 0.000 (0.000)    | 0.142 (0.016)    | 0 (0.000) |     1.69 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            8 |     1145 | 2025-02-01 | Eco Warriors                | L   | 0.644      | -            | -                | -                | -         |   -17.14 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            7 |     1150 | 2025-02-01 | Artemis (Female team)       | W   | 0.643      | 0.143        | 0.000 (0.000)    | 0.047 (0.005)    | 0 (0.000) |     2.53 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            6 |     1178 | 2025-01-31 | CS2NEWS Ladies              | W   | 0.639      | 0.143        | 0.000 (0.000)    | 0.112 (0.012)    | 0 (0.000) |     3.94 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            5 |     3549 | 2024-11-14 | NAVI Javelins               | L   | 0.204      | -            | -                | -                | -         |    -2.11 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            4 |     3587 | 2024-11-14 | Team Portugal (Female team) | W   | 0.203      | 0.557        | 0.023 (0.003)    | 0.043 (0.006)    | 1 (0.243) |     2.91 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            3 |     3626 | 2024-11-13 | Ex-Astralis Women           | W   | 0.197      | 0.557        | 0.007 (0.001)    | 0.042 (0.005)    | 1 (0.236) |     2.05 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            2 |     3695 | 2024-11-11 | Team Sweden (Female team)   | W   | 0.188      | 0.557        | 0.006 (0.001)    | 0.021 (0.003)    | 1 (0.225) |     1.28 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            1 |     3706 | 2024-11-11 | Messitas                    | W   | 0.187      | 0.557        | 0.000 (0.000)    | 0.048 (0.006)    | 1 (0.224) |     0.44 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,813.89)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.245 | $40,000.00     | $9,813.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
