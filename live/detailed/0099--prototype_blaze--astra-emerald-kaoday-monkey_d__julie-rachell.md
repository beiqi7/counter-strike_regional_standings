### Roster Details<br />
Team Name: Prototype Blaze<br />
Roster: ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  885.1<br />
<br />
Final Rank Value (885.1) = Starting Rank Value (901.9) + Head To Head Adjustments (-16.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.461[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.233[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.9
- 400 + ( ( 0.241 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 901.9


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
|           10 |       23 | 2025-02-27 | Imperial Female             | L   | 1.000      | -            | -                | -                | -         |    -9.96 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            9 |     1101 | 2025-02-02 | Permitta W                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.145 (0.021)    | 0 (0.000) |     2.11 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            8 |     1120 | 2025-02-01 | Eco Warriors                | L   | 0.998      | -            | -                | -                | -         |   -27.30 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            7 |     1125 | 2025-02-01 | Artemis (Female team)       | W   | 0.997      | 0.143        | 0.000 (0.000)    | 0.048 (0.007)    | 0 (0.000) |     3.00 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            6 |     1152 | 2025-01-31 | CS2NEWS Ladies              | W   | 0.992      | 0.143        | 0.001 (0.000)    | 0.151 (0.021)    | 0 (0.000) |     4.98 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            5 |     3417 | 2024-11-14 | NAVI Javelins               | L   | 0.471      | -            | -                | -                | -         |    -4.41 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            4 |     3454 | 2024-11-14 | Team Portugal (Female team) | W   | 0.468      | 0.557        | 0.034 (0.009)    | 0.067 (0.017)    | 1 (0.468) |     6.55 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            3 |     3492 | 2024-11-13 | Ex-Astralis Women           | W   | 0.462      | 0.557        | 0.012 (0.003)    | 0.084 (0.022)    | 1 (0.462) |     4.64 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            2 |     3560 | 2024-11-11 | Team Sweden (Female team)   | W   | 0.451      | 0.557        | 0.008 (0.002)    | 0.039 (0.010)    | 1 (0.451) |     2.77 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |
|            1 |     3571 | 2024-11-11 | Messitas                    | W   | 0.449      | 0.557        | 0.000 (0.000)    | 0.049 (0.012)    | 1 (0.449) |     0.80 | ASTRA, Emerald, Kaoday, Monkey D. Julie, RacheLL |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,825.18)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.471 | $40,000.00     | $18,825.18      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
