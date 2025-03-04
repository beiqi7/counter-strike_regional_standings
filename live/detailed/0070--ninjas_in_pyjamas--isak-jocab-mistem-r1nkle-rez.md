### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: isak, jocab, MisteM, r1nkle, REZ<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  932.1<br />
<br />
Final Rank Value (932.1) = Starting Rank Value (911.7) + Head To Head Adjustments (20.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.393[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.256[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 911.7
- 400 + ( ( 0.246 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 911.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2796 | 2024-11-24 | Team Spirit      | L   | 0.536      | -            | -                | -                | -         |    -0.06 | isak, jocab, MisteM, r1nkle, REZ   |
|           18 |     2816 | 2024-11-23 | 9Pandas          | W   | 0.533      | 0.143        | 0.104 (0.008)    | 0.628 (0.048)    | 1 (0.533) |    12.59 | isak, jocab, MisteM, r1nkle, REZ   |
|           17 |     2909 | 2024-11-22 | TSM              | W   | 0.528      | 0.143        | 0.010 (0.001)    | 0.128 (0.010)    | 1 (0.528) |     5.20 | isak, jocab, MisteM, r1nkle, REZ   |
|           16 |     2997 | 2024-11-21 | Team Falcons     | L   | 0.521      | -            | -                | -                | -         |    -0.07 | isak, jocab, MisteM, r1nkle, REZ   |
|           15 |     3053 | 2024-11-21 | PARIVISION       | W   | 0.515      | 0.143        | 0.007 (0.001)    | 0.058 (0.004)    | 1 (0.515) |     4.81 | isak, jocab, MisteM, r1nkle, REZ   |
|           14 |     3066 | 2024-11-20 | G2 Esports       | L   | 0.514      | -            | -                | -                | -         |    -0.16 | isak, jocab, MisteM, r1nkle, REZ   |
|           13 |     3516 | 2024-11-12 | BetBoom Team     | L   | 0.456      | -            | -                | -                | -         |    -4.36 | isak, jocab, MisteM, r1nkle, REZ   |
|           12 |     3547 | 2024-11-11 | Zero Tenacity    | W   | 0.451      | 0.384        | 0.032 (0.006)    | 0.843 (0.146)    | 0 (0.000) |     8.04 | isak, jocab, MisteM, r1nkle, REZ   |
|           11 |     3664 | 2024-11-09 | Metizport        | L   | 0.437      | -            | -                | -                | -         |    -3.01 | isak, jocab, MisteM, r1nkle, REZ   |
|           10 |     3717 | 2024-11-08 | Alliance         | W   | 0.430      | 0.143        | 0.018 (0.001)    | 0.584 (0.036)    | 1 (0.430) |     7.42 | isak, jocab, MisteM, r1nkle, REZ   |
|            9 |     4516 | 2024-10-25 | Imperial Esports | L   | 0.337      | -            | -                | -                | -         |    -4.92 | isak, jocab, MisteM, r1nkle, REZ   |
|            8 |     4560 | 2024-10-23 | Team Falcons     | L   | 0.325      | -            | -                | -                | -         |    -0.03 | isak, jocab, MisteM, r1nkle, REZ   |
|            7 |     4596 | 2024-10-23 | Imperial Esports | W   | 0.323      | 0.934        | 0.083 (0.025)    | 0.533 (0.161)    | 0 (0.000) |     5.48 | isak, jocab, MisteM, r1nkle, REZ   |
|            6 |     4913 | 2024-10-16 | JANO Esports     | L   | 0.277      | -            | -                | -                | -         |    -3.65 | isak, jocab, MisteM, r1nkle, REZ   |
|            5 |     4928 | 2024-10-16 | B8               | L   | 0.276      | -            | -                | -                | -         |    -1.29 | isak, jocab, MisteM, r1nkle, REZ   |
|            4 |     5592 | 2024-10-04 | ECSTATIC         | L   | 0.195      | -            | -                | -                | -         |    -2.94 | isak, jocab, MisteM, r1nkle, REZ   |
|            3 |     6172 | 2024-09-25 | ARCRED           | L   | 0.138      | -            | -                | -                | -         |    -2.70 | isak, maxster, MisteM, r1nkle, REZ |
|            2 |     7308 | 2024-09-07 | Team Falcons     | L   | 0.016      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |
|            1 |     7456 | 2024-09-05 | FaZe Clan        | L   | 0.004      | -            | -                | -                | -         |    -0.00 | alex, isak, maxster, r1nkle, REZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,863.90)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-12 |      0.457 | $1,500.00      | $685.18         |
| 2024-11-09 |      0.437 | $11,097.44     | $4,849.01       |
| 2024-10-20 |      0.303 | $5,000.00      | $1,514.95       |
| 2024-09-22 |      0.116 | $7,000.00      | $814.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
