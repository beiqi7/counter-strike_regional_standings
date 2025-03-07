### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, ASTRA, D7, Hanka, vicu<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  982.2<br />
<br />
Final Rank Value (982.2) = Starting Rank Value (982.3) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.501[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.291[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 982.3
- 400 + ( ( 0.264 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 982.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2916 | 2024-11-24 | FURIA Female              | L   | 0.259      | -            | -                | -                | -         |    -4.39 | Angelka, ASTRA, D7, Hanka, vicu   |
|           11 |     2996 | 2024-11-23 | MIBR Female               | W   | 0.254      | 0.524        | 0.013 (0.002)    | 0.133 (0.021)    | 1 (0.305) |     1.84 | Angelka, ASTRA, D7, Hanka, vicu   |
|           10 |     3027 | 2024-11-23 | FlyQuest RED              | W   | 0.253      | 0.524        | 0.006 (0.001)    | 0.061 (0.010)    | 1 (0.303) |     1.04 | Angelka, ASTRA, D7, Hanka, vicu   |
|            9 |     3112 | 2024-11-22 | Imperial Female           | L   | 0.247      | -            | -                | -                | -         |    -3.23 | Angelka, ASTRA, D7, Hanka, vicu   |
|            8 |     3549 | 2024-11-14 | Prototype Blaze           | W   | 0.204      | 0.557        | 0.047 (0.006)    | 0.197 (0.027)    | 1 (0.245) |     2.11 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3586 | 2024-11-14 | Team USA (Female team)    | W   | 0.203      | 0.557        | 0.012 (0.002)    | 0.028 (0.004)    | 1 (0.243) |     1.41 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3620 | 2024-11-13 | Team Sweden (Female team) | W   | 0.198      | 0.557        | 0.006 (0.001)    | 0.021 (0.003)    | 1 (0.237) |     0.73 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     3696 | 2024-11-11 | Ex-Astralis Women         | W   | 0.188      | 0.557        | 0.007 (0.001)    | 0.042 (0.005)    | 1 (0.225) |     1.15 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     3708 | 2024-11-11 | Team Canada (Female team) | W   | 0.187      | 0.557        | 0.000 (0.000)    | 0.014 (0.002)    | 1 (0.224) |     0.24 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     4878 | 2024-10-20 | Let Her Cook              | W   | 0.065      | 0.328        | 0.001 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.25 | Angelka, ASTRA, D7, Hanka, vicu   |
|            2 |     4940 | 2024-10-19 | K27 Female                | L   | 0.060      | -            | -                | -                | -         |    -1.58 | Angelka, ASTRA, D7, Hanka, vicu   |
|            1 |     4988 | 2024-10-18 | Ex-Astralis Women         | W   | 0.054      | 0.328        | 0.007 (0.000)    | 0.042 (0.001)    | 0 (0.000) |     0.33 | Angelka, ASTRA, D7, Hanka, vicu   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,224.17)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.312 | $13,000.00     | $4,049.86       |
| 2024-11-14 |      0.245 | $70,000.00     | $17,174.31      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
