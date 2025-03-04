### Roster Details<br />
Team Name: Legacy<br />
Roster: dumau, latto, lux, n1ssim, saadzin<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  957.6<br />
<br />
Final Rank Value (957.6) = Starting Rank Value (878.4) + Head To Head Adjustments (79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.422[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.131[<sup>2</sup>](#table1)
- LAN Wins: 0.043[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 878.4
- 400 + ( ( 0.230 - 0.000 ) / ( 0.769 - 0.000 ) ) * 1600 = 878.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |       16 | 2025-02-27 | Akimbo Esports     | W   | 1.000      | 0.477        | -                | 0.431 (0.206)    | 0 (0.000) |     5.65 | dumau, latto, lux, n1ssim, saadzin   |
|           59 |       17 | 2025-02-27 | Akimbo Esports     | W   | 1.000      | 0.477        | -                | 0.431 (0.206)    | 0 (0.000) |     5.96 | dumau, latto, lux, n1ssim, saadzin   |
|           58 |       42 | 2025-02-26 | LAG Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.10 | dumau, latto, lux, n1ssim, saadzin   |
|           57 |       47 | 2025-02-26 | LAG Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.20 | dumau, latto, lux, n1ssim, saadzin   |
|           56 |      241 | 2025-02-21 | Imperial Esports   | L   | 1.000      | -            | -                | -                | -         |   -12.68 | dumau, latto, lux, n1ssim, saadzin   |
|           55 |      295 | 2025-02-20 | UNO MILLE          | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.628 (0.233)    | 0 (0.000) |    10.15 | dumau, latto, lux, n1ssim, saadzin   |
|           54 |      330 | 2025-02-19 | Vagrants           | L   | 1.000      | -            | -                | -                | -         |   -21.00 | dumau, latto, lux, n1ssim, saadzin   |
|           53 |      334 | 2025-02-19 | Vagrants           | L   | 1.000      | -            | -                | -                | -         |   -22.65 | dumau, latto, lux, n1ssim, saadzin   |
|           52 |      361 | 2025-02-18 | Chill Guys         | L   | 1.000      | -            | -                | -                | -         |   -20.30 | dumau, latto, lux, n1ssim, saadzin   |
|           51 |      365 | 2025-02-18 | Chill Guys         | L   | 1.000      | -            | -                | -                | -         |   -21.95 | dumau, latto, lux, n1ssim, saadzin   |
|           50 |      606 | 2025-02-12 | Fluxo              | W   | 1.000      | 0.143        | 0.065 (0.009)    | -                | 0 (0.000) |    16.04 | dumau, latto, lux, n1ssim, saadzin   |
|           49 |      627 | 2025-02-11 | Fluxo              | W   | 1.000      | 0.143        | 0.065 (0.009)    | -                | 0 (0.000) |    16.72 | dumau, latto, lux, n1ssim, saadzin   |
|           48 |      633 | 2025-02-11 | Sharks Esports     | W   | 1.000      | 0.143        | 0.064 (0.009)    | 0.683 (0.098)    | 0 (0.000) |    19.31 | dumau, latto, lux, n1ssim, saadzin   |
|           47 |      740 | 2025-02-08 | BESTIA             | W   | 1.000      | 0.143        | 0.081 (0.012)    | -                | 0 (0.000) |    15.74 | dumau, latto, lux, n1ssim, saadzin   |
|           46 |      742 | 2025-02-08 | LaChampionsLiga    | W   | 1.000      | -            | -                | -                | -         |     4.82 | dumau, latto, lux, n1ssim, saadzin   |
|           45 |      761 | 2025-02-08 | MIBR               | L   | 1.000      | -            | -                | -                | -         |    -8.39 | dumau, latto, lux, n1ssim, saadzin   |
|           44 |      817 | 2025-02-07 | UNO MILLE          | W   | 1.000      | 0.143        | -                | 0.628 (0.090)    | -         |     9.10 | dumau, latto, lux, n1ssim, saadzin   |
|           43 |      863 | 2025-02-07 | Team Solid         | W   | 1.000      | 0.143        | 0.027 (0.004)    | 0.616 (0.088)    | -         |    13.64 | dumau, latto, lux, n1ssim, saadzin   |
|           42 |      942 | 2025-02-05 | Team Solid         | W   | 1.000      | 0.143        | -                | 0.616 (0.088)    | -         |    14.40 | dumau, latto, lux, n1ssim, saadzin   |
|           41 |      965 | 2025-02-05 | Familia Maquininha | W   | 1.000      | -            | -                | -                | -         |     8.02 | dumau, latto, lux, n1ssim, saadzin   |
|           40 |     1344 | 2025-01-12 | BESTIA             | L   | 0.865      | -            | -                | -                | -         |   -12.66 | dumau, latto, lux, n1ssim, saadzin   |
|           39 |     1346 | 2025-01-11 | Dusty Roots        | W   | 0.859      | 0.384        | -                | 0.372 (0.123)    | -         |     8.57 | dumau, latto, lux, n1ssim, saadzin   |
|           38 |     1350 | 2025-01-10 | ShindeN            | W   | 0.852      | 0.384        | -                | 0.316 (0.103)    | -         |     7.00 | dumau, latto, lux, n1ssim, saadzin   |
|           37 |     4452 | 2024-10-26 | Monte              | L   | 0.342      | -            | -                | -                | -         |    -5.74 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           36 |     4511 | 2024-10-25 | PaiN Gaming        | L   | 0.337      | -            | -                | -                | -         |    -0.43 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           35 |     4522 | 2024-10-25 | MIBR               | W   | 0.336      | 0.500        | 0.118 (0.020)    | -                | 1 (0.336) |     8.21 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           34 |     4575 | 2024-10-23 | Imperial Esports   | L   | 0.324      | -            | -                | -                | -         |    -4.98 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           33 |     4598 | 2024-10-23 | Team Falcons       | L   | 0.322      | -            | -                | -                | -         |    -0.04 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           32 |     4744 | 2024-10-19 | NRG                | L   | 0.299      | -            | -                | -                | -         |    -2.76 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           31 |     4826 | 2024-10-17 | M80                | L   | 0.286      | -            | -                | -                | -         |    -3.85 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           30 |     4878 | 2024-10-16 | Nouns Esports      | W   | 0.279      | 0.477        | -                | 0.601 (0.080)    | -         |     4.72 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           29 |     5223 | 2024-10-09 | Familia Maquininha | W   | 0.233      | -            | -                | -                | -         |     1.73 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           28 |     5230 | 2024-10-09 | Familia Maquininha | W   | 0.233      | -            | -                | -                | -         |     1.75 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           27 |     5288 | 2024-10-08 | M80                | L   | 0.226      | -            | -                | -                | -         |    -3.08 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           26 |     5294 | 2024-10-08 | M80                | W   | 0.226      | 0.477        | 0.043 (0.005)    | -                | -         |     4.10 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           25 |     5470 | 2024-10-05 | FLUFFY AIMERS      | L   | 0.205      | -            | -                | -                | -         |    -3.91 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           24 |     5550 | 2024-10-04 | LAG Gaming         | W   | 0.199      | -            | -                | -                | -         |     0.98 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           23 |     5599 | 2024-10-03 | Vagrants           | W   | 0.193      | -            | -                | -                | -         |     1.95 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           22 |     5604 | 2024-10-03 | Vagrants           | W   | 0.193      | -            | -                | -                | -         |     1.98 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           21 |     5656 | 2024-10-02 | Lore Gaming        | W   | 0.185      | -            | -                | -                | -         |     0.32 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           20 |     5706 | 2024-10-01 | NRG                | W   | 0.179      | 0.477        | 0.057 (0.005)    | -                | -         |     4.15 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           19 |     5712 | 2024-10-01 | NRG                | W   | 0.179      | 0.477        | 0.057 (0.005)    | -                | -         |     4.20 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           18 |     5837 | 2024-09-29 | Wildcard           | W   | 0.166      | -            | -                | -                | -         |     4.18 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           17 |     5842 | 2024-09-29 | Nouns Esports      | W   | 0.165      | -            | -                | -                | -         |     2.83 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           16 |     5888 | 2024-09-28 | Wildcard           | L   | 0.159      | -            | -                | -                | -         |    -0.99 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           15 |     5894 | 2024-09-28 | Nouns Esports      | W   | 0.158      | -            | -                | -                | -         |     2.75 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           14 |     5985 | 2024-09-27 | NRG                | W   | 0.152      | -            | -                | -                | -         |     3.64 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           13 |     5991 | 2024-09-27 | BLUEJAYS           | W   | 0.152      | -            | -                | -                | -         |     2.62 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           12 |     6069 | 2024-09-26 | Vorpal Swords      | W   | 0.145      | -            | -                | -                | -         |     0.76 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           11 |     6138 | 2024-09-25 | Bad News Capybaras | W   | 0.139      | -            | -                | -                | -         |     1.12 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|           10 |     6143 | 2024-09-25 | Bad News Capybaras | W   | 0.139      | -            | -                | -                | -         |     1.12 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            9 |     6231 | 2024-09-24 | Chill Guys         | W   | 0.133      | -            | -                | -                | -         |     1.85 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            8 |     6238 | 2024-09-24 | Chill Guys         | W   | 0.133      | -            | -                | -                | -         |     1.87 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            7 |     6320 | 2024-09-23 | Nouns Esports      | W   | 0.126      | -            | -                | -                | -         |     2.28 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            6 |     6324 | 2024-09-23 | Nouns Esports      | W   | 0.126      | -            | -                | -                | -         |     2.30 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            5 |     6446 | 2024-09-21 | FLUFFY AIMERS      | L   | 0.112      | -            | -                | -                | -         |    -1.99 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            4 |     6553 | 2024-09-19 | LAG Gaming         | W   | 0.099      | -            | -                | -                | -         |     0.62 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            3 |     6557 | 2024-09-19 | LAG Gaming         | W   | 0.099      | -            | -                | -                | -         |     0.62 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            2 |     6612 | 2024-09-18 | Party Astronauts   | W   | 0.093      | -            | -                | -                | -         |     1.26 | b4rtiN, dumau, latto, NEKIZ, saadzin |
|            1 |     6621 | 2024-09-18 | Party Astronauts   | W   | 0.093      | -            | -                | -                | -         |     1.26 | b4rtiN, dumau, latto, NEKIZ, saadzin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,804.20)
- Divide that value by the 5th highest value among all rosters ($277,057.00)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-22 |      1.000 | $750.00        | $750.00         |
| 2025-01-12 |      0.865 | $7,500.00      | $6,487.53       |
| 2024-10-27 |      0.351 | $3,000.00      | $1,052.24       |
| 2024-10-20 |      0.305 | $10,500.00     | $3,205.46       |
| 2024-10-05 |      0.206 | $1,500.00      | $308.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
