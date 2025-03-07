### Roster Details<br />
Team Name: Eruption<br />
Roster: fury5k, MagnumZ, sideffect, sk0R, xenization<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
<br />
Final Rank Value:  890.7<br />
<br />
Final Rank Value (890.7) = Starting Rank Value (902.0) + Head To Head Adjustments (-11.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.260[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 902.0
- 400 + ( ( 0.228 - 0.000 ) / ( 0.725 - 0.000 ) ) * 1600 = 902.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       43 | 2025-02-26 | ATOX Esports              | L   | 0.785      | -            | -                | -                | -         |    -7.07 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           16 |       90 | 2025-02-25 | Nomads (Mongolian team)   | W   | 0.780      | 0.143        | 0.000 (0.000)    | 0.230 (0.031)    | 0 (0.000) |     3.36 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           15 |      131 | 2025-02-24 | The QUBE Esports          | W   | 0.774      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.42 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           14 |      155 | 2025-02-24 | The Huns Esports          | L   | 0.769      | -            | -                | -                | -         |   -11.44 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           13 |      708 | 2025-02-09 | Chinggis Warriors         | L   | 0.691      | -            | -                | -                | -         |   -15.85 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           12 |      748 | 2025-02-08 | Believe.                  | W   | 0.685      | 0.143        | 0.000 (0.000)    | 0.196 (0.023)    | 0 (0.000) |     2.22 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           11 |      900 | 2025-02-06 | Chinggis Warriors         | W   | 0.674      | 0.143        | 0.011 (0.001)    | 0.397 (0.046)    | 0 (0.000) |     5.41 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|           10 |      951 | 2025-02-06 | Tsegtaslal                | W   | 0.669      | 0.143        | 0.000 (0.000)    | 0.048 (0.006)    | 0 (0.000) |     1.17 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            9 |     1013 | 2025-02-05 | IHC Esports               | W   | 0.663      | 0.143        | 0.003 (0.000)    | 0.134 (0.015)    | 0 (0.000) |     4.99 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            8 |     1534 | 2024-12-29 | ATOX Esports              | L   | 0.452      | -            | -                | -                | -         |    -4.75 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            7 |     1570 | 2024-12-28 | Rare Atom                 | W   | 0.448      | 0.384        | 0.008 (0.002)    | 0.339 (0.070)    | 1 (0.537) |     5.58 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            6 |     1598 | 2024-12-26 | ATOX Esports              | W   | 0.441      | 0.384        | 0.057 (0.012)    | 0.519 (0.105)    | 1 (0.529) |     9.39 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            5 |     1600 | 2024-12-26 | IHC Esports               | W   | 0.440      | 0.384        | 0.003 (0.001)    | 0.134 (0.027)    | 1 (0.528) |     3.64 | fury5k, MagnumZ, sideffect, sk0R, xenization      |
|            4 |     3460 | 2024-11-16 | SayGGTeam                 | L   | 0.214      | -            | -                | -                | -         |    -5.26 | fury5k, MagnumZ, Tamiraarita, tsukimi, xenization |
|            3 |     3471 | 2024-11-16 | DEWA United               | W   | 0.214      | 0.143        | 0.000 (0.000)    | 0.027 (0.001)    | 0 (0.000) |     0.62 | fury5k, MagnumZ, Tamiraarita, tsukimi, xenization |
|            2 |     3474 | 2024-11-16 | MOLEGAN                   | W   | 0.213      | -            | -                | -                | -         |     0.39 | fury5k, MagnumZ, Tamiraarita, tsukimi, xenization |
|            1 |     3479 | 2024-11-15 | Just Swing (Chinese team) | L   | 0.213      | -            | -                | -                | -         |    -5.15 | fury5k, MagnumZ, Tamiraarita, tsukimi, xenization |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,257.50)
- Divide that value by the 5th highest value among all rosters ($210,045.49)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.543 | $6,000.00      | $3,257.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
