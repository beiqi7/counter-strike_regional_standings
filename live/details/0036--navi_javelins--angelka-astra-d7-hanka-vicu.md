### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, ASTRA, D7, Hanka, vicu<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1059.3<br />
<br />
Final Rank Value (1059.3) = Starting Rank Value (1069.6) + Head To Head Adjustments (-10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.544[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.429[<sup>2</sup>](#table1)

The average of these factors is 0.322<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1069.6
- 400 + ( ( 0.322 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 1069.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     2794 | 2024-11-24 | FURIA Female              | L   | 0.536      | -            | -                | -                | -         |   -10.40 | Angelka, ASTRA, D7, Hanka, vicu     |
|           21 |     2874 | 2024-11-23 | MIBR Female               | W   | 0.530      | 0.524        | 0.019 (0.005)    | 0.197 (0.055)    | 1 (0.530) |     3.13 | Angelka, ASTRA, D7, Hanka, vicu     |
|           20 |     2904 | 2024-11-23 | FlyQuest RED              | W   | 0.528      | 0.524        | 0.008 (0.002)    | 0.086 (0.024)    | 1 (0.528) |     1.69 | Angelka, ASTRA, D7, Hanka, vicu     |
|           19 |     2992 | 2024-11-22 | Imperial Female           | L   | 0.522      | -            | -                | -                | -         |    -7.50 | Angelka, ASTRA, D7, Hanka, vicu     |
|           18 |     3417 | 2024-11-14 | Prototype Blaze           | W   | 0.471      | 0.557        | 0.068 (0.018)    | 0.234 (0.061)    | 1 (0.471) |     4.41 | Angelka, Hanka, LETi, Liina, vicu   |
|           17 |     3453 | 2024-11-14 | Team USA (Female team)    | W   | 0.468      | 0.557        | 0.017 (0.004)    | 0.022 (0.006)    | 1 (0.468) |     1.31 | Angelka, Hanka, LETi, Liina, vicu   |
|           16 |     3486 | 2024-11-13 | Team Sweden (Female team) | W   | 0.463      | 0.557        | 0.008 (0.002)    | 0.039 (0.010)    | 1 (0.463) |     1.30 | Angelka, Hanka, LETi, Liina, vicu   |
|           15 |     3561 | 2024-11-11 | Ex-Astralis Women         | W   | 0.451      | 0.557        | 0.012 (0.003)    | 0.084 (0.021)    | 1 (0.451) |     2.32 | Angelka, Hanka, LETi, Liina, vicu   |
|           14 |     3573 | 2024-11-11 | Team Canada (Female team) | W   | 0.449      | 0.557        | -                | 0.022 (0.006)    | 1 (0.449) |     0.40 | Angelka, Hanka, LETi, Liina, vicu   |
|           13 |     4689 | 2024-10-20 | Let Her Cook              | W   | 0.304      | -            | -                | -                | 0 (0.000) |     0.89 | Angelka, ASTRA, D7, Hanka, vicu     |
|           12 |     4751 | 2024-10-19 | K27 Female                | L   | 0.297      | -            | -                | -                | -         |    -8.02 | Angelka, ASTRA, D7, Hanka, vicu     |
|           11 |     4796 | 2024-10-18 | Ex-Astralis Women         | W   | 0.290      | 0.328        | 0.012 (0.001)    | 0.084 (0.008)    | 0 (0.000) |     1.51 | Angelka, ASTRA, D7, Hanka, vicu     |
|           10 |     5667 | 2024-10-02 | Take Flyte Female         | W   | 0.184      | 0.328        | 0.007 (0.000)    | 0.271 (0.016)    | 0 (0.000) |     0.60 | Angelka, ASTRA, D7, Hanka, vicu     |
|            9 |     6653 | 2024-09-18 | ENCE Athena               | W   | 0.090      | -            | -                | -                | -         |     0.14 | Angelka, ASTRA, D7, Hanka, vicu     |
|            8 |     6729 | 2024-09-17 | Eternal prem              | L   | 0.084      | -            | -                | -                | -         |    -2.43 | Angelka, ASTRA, D7, Hanka, vicu     |
|            7 |     6769 | 2024-09-16 | NeedONE Agency            | W   | 0.077      | -            | -                | -                | -         |     0.06 | AlcesT, Angelka, ASTRA, Hanka, vicu |
|            6 |     6839 | 2024-09-15 | Imperial Female           | W   | 0.069      | 0.294        | 0.160 (0.003)    | -                | -         |     1.18 | Angelka, ASTRA, D7, Hanka, vicu     |
|            5 |     6901 | 2024-09-14 | NIP Impact                | W   | 0.063      | 0.294        | 0.014 (0.000)    | -                | -         |     0.29 | Angelka, ASTRA, D7, Hanka, vicu     |
|            4 |     6930 | 2024-09-14 | Take Flyte Female         | W   | 0.062      | 0.294        | -                | 0.271 (0.005)    | -         |     0.20 | Angelka, ASTRA, D7, Hanka, vicu     |
|            3 |     7078 | 2024-09-11 | NoLightGaming             | L   | 0.043      | -            | -                | -                | -         |    -1.25 | Angelka, ASTRA, D7, Hanka, vicu     |
|            2 |     7315 | 2024-09-07 | CS2NEWS Ladies            | W   | 0.016      | -            | -                | -                | -         |     0.04 | Angelka, ASTRA, D7, Hanka, vicu     |
|            1 |     7462 | 2024-09-05 | NIP Impact                | L   | 0.004      | -            | -                | -                | -         |    -0.10 | Angelka, ASTRA, D7, Hanka, vicu     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,167.46)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.537 | $13,000.00     | $6,978.53       |
| 2024-11-14 |      0.471 | $70,000.00     | $32,944.06      |
| 2024-09-21 |      0.111 | $350.00        | $38.74          |
| 2024-09-15 |      0.069 | $3,000.00      | $206.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
