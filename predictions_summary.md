# Probability Cup — predictions submitted 2026-06-12

Bias corrections: **none applied** — `GET /results` returned no settled predictions, so there is no calibration history yet.

De-vig method: 3-way markets (match winner, 1H result, correct-score grid) normalized to sum to 1; binary Kalshi markets use bid/ask mid (vig sits in the spread, mid is the fair point).

| Match | Question | Source | Raw implied | De-vigged | Bias adj | Submitted |
|---|---|---|---|---|---|---|
| CAN vs BIH | Will Jonathan David score a goal (excluding own goals)? | Kalshi KXWCGOAL | 0.323 | 0.323 | — | 32 |
| CAN vs BIH | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.447 | 0.448 | — | 45 |
| CAN vs BIH | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.380 | 0.380 | — | 38 |
| CAN vs BIH | Will Bosnia and Herzegovina commit more fouls than Canada? | base rate + favorite tilt | 0.568 | 0.568 | — | 57 |
| CAN vs BIH | Will Canada win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.537 | 0.533 | — | 53 |
| CAN vs BIH | Will Edin Džeko have at least 1 shot on target? | Kalshi KXWCGOAL | 0.593 | 0.593 | — | 59 |
| CAN vs BIH | Will Bosnia and Herzegovina have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.290 | 0.290 | — | 29 |
| CAN vs BIH | Will Bosnia and Herzegovina score in the second half? | derived Kalshi team lambda | 0.391 | 0.391 | — | 39 |
| CAN vs BIH | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| CAN vs BIH | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.587 | 0.587 | — | 59 |
| USA vs PAR | Will United States be caught offside 2 or more times? | base rate + attacking tilt | 0.539 | 0.539 | — | 54 |
| USA vs PAR | Will United States win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.477 | 0.486 | — | 49 |
| USA vs PAR | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.463 | 0.453 | — | 45 |
| USA vs PAR | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.407 | 0.407 | — | 41 |
| USA vs PAR | Will Paraguay score in the second half? | derived Kalshi team lambda | 0.409 | 0.409 | — | 41 |
| USA vs PAR | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| USA vs PAR | Will Folarin Balogun have at least 1 shot on target? | Kalshi KXWCGOAL | 0.660 | 0.660 | — | 66 |
| USA vs PAR | Will Julio Enciso have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.346 | 0.346 | — | 35 |
| USA vs PAR | Will Paraguay finish with more corner kicks than United States? | Kalshi team-corners fit | 0.310 | 0.310 | — | 31 |
| USA vs PAR | Will United States score the first goal of the game and Paraguay score in the second half? | derived Kalshi lambdas | 0.223 | 0.223 | — | 22 |
| QAT vs SUI | Will Akram Afif have at least 1 shot on target? | Kalshi KXWCGOAL | 0.593 | 0.593 | — | 59 |
| QAT vs SUI | Will Granit Xhaka have at least 1 shot on target? | Kalshi KXWCGOAL | 0.518 | 0.518 | — | 52 |
| QAT vs SUI | Will Qatar score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.403 | 0.403 | — | 40 |
| QAT vs SUI | Will Qatar have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.269 | 0.269 | — | 27 |
| QAT vs SUI | Will Switzerland receive at least 1 card in the second half? | base rate (cards) | 0.625 | 0.625 | — | 63 |
| QAT vs SUI | Will Switzerland be caught offside 2 or more times? | base rate + attacking tilt | 0.663 | 0.663 | — | 66 |
| QAT vs SUI | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.536 | 0.536 | — | 54 |
| QAT vs SUI | Will both teams score AND the match have 3 or more total goals? | Kalshi KXWCSCORE grid (de-vig) | 0.393 | 0.393 | — | 39 |
| QAT vs SUI | Will Qatar have 2 or more shots on target? | derived Kalshi team lambda (SOT) | 0.506 | 0.506 | — | 51 |
| QAT vs SUI | Will Qatar commit more fouls than Switzerland? | base rate + favorite tilt | 0.694 | 0.694 | — | 69 |
| BRA vs MAR | Will the match be tied at halftime? | Kalshi KXWC1H (de-vig 3-way) | 0.427 | 0.424 | — | 42 |
| BRA vs MAR | Will Brazil win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.587 | 0.581 | — | 58 |
| BRA vs MAR | Will Morocco have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.290 | 0.290 | — | 29 |
| BRA vs MAR | Will Brazil be caught offside 2 or more times? | base rate + attacking tilt | 0.579 | 0.579 | — | 58 |
| BRA vs MAR | Will Morocco commit more fouls than Brazil? | base rate + favorite tilt | 0.593 | 0.593 | — | 59 |
| BRA vs MAR | Will Morocco score the first goal of the second half? | derived Kalshi lambdas | 0.249 | 0.249 | — | 25 |
| BRA vs MAR | Will Brazil score more goals than Morocco in the second half? | derived Kalshi lambdas | 0.473 | 0.473 | — | 47 |
| BRA vs MAR | Will Morocco have more shots on target than Brazil in the second half? | derived Kalshi lambdas (SOT) | 0.208 | 0.208 | — | 21 |
| BRA vs MAR | Will Brazil receive more cards than Morocco? | base rate + underdog tilt | 0.318 | 0.318 | — | 32 |
| BRA vs MAR | Will both teams score AND the match have 3 or more total goals? | Kalshi KXWCSCORE grid (de-vig) | 0.429 | 0.429 | — | 43 |
| Haiti vs SCO | Will the match be tied at halftime? | Kalshi KXWC1H (de-vig 3-way) | 0.405 | 0.406 | — | 41 |
| Haiti vs SCO | Will Haiti score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.567 | 0.567 | — | 57 |
| Haiti vs SCO | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.449 | 0.449 | — | 45 |
| Haiti vs SCO | Will Duckens Nazon have at least 1 shot on target? | Kalshi KXWCGOAL | 0.593 | 0.593 | — | 59 |
| Haiti vs SCO | Will Scott McTominay have at least 1 shot on target? | Kalshi KXWCGOAL | 0.737 | 0.737 | — | 74 |
| Haiti vs SCO | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| Haiti vs SCO | Will Haiti have more shots on target than Scotland in the second half? | derived Kalshi lambdas (SOT) | 0.190 | 0.190 | — | 19 |
| Haiti vs SCO | In the second half, will Haiti have more corner kicks than Scotland? | Kalshi team-corners fit, 2H | 0.279 | 0.279 | — | 28 |
| Haiti vs SCO | Will Haiti commit more fouls than Scotland? | base rate + favorite tilt | 0.607 | 0.607 | — | 61 |
| Haiti vs SCO | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.493 | 0.493 | — | 49 |
| AUS vs TUR | Will Australia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.177 | 0.175 | — | 17 |
| AUS vs TUR | Will Riley McGree have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| AUS vs TUR | Will Australia commit more fouls than Türkiye? | base rate + favorite tilt | 0.589 | 0.589 | — | 59 |
| AUS vs TUR | Will Türkiye have more shots on target than Australia in the second half? | derived Kalshi lambdas (SOT) | 0.640 | 0.640 | — | 64 |
| AUS vs TUR | Will Australia be caught offside 2 or more times? | base rate + attacking tilt | 0.454 | 0.454 | — | 45 |
| AUS vs TUR | Will Türkiye finish with more corner kicks than Australia? | Kalshi team-corners fit | 0.663 | 0.663 | — | 66 |
| AUS vs TUR | Will Orkun Kökçü have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.310 | 0.310 | — | 31 |
| AUS vs TUR | Will both teams score AND the match have 3 or more total goals? | Kalshi KXWCSCORE grid (de-vig) | 0.495 | 0.495 | — | 49 |
| AUS vs TUR | Will Türkiye score in the second half? | derived Kalshi team lambda | 0.613 | 0.613 | — | 61 |
| AUS vs TUR | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| GER vs Curacao | Will Curaçao receive more cards than Germany? | base rate + underdog tilt | 0.575 | 0.575 | — | 58 |
| GER vs Curacao | Will Germany be caught offside 2 or more times? | base rate + attacking tilt | 0.810 | 0.810 | — | 81 |
| GER vs Curacao | Will Curaçao commit more fouls than Germany? | base rate + favorite tilt | 0.741 | 0.741 | — | 74 |
| GER vs Curacao | Will Germany win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.933 | 0.927 | — | 93 |
| GER vs Curacao | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.173 | 0.173 | — | 17 |
| GER vs Curacao | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.683 | 0.683 | — | 68 |
| GER vs Curacao | Will Curaçao have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.210 | 0.210 | — | 21 |
| GER vs Curacao | Will Leandro Bacuna have at least 1 shot on target? | modeled from Kalshi team lambda | 0.451 | 0.451 | — | 45 |
| GER vs Curacao | Will Curaçao be caught offside 2 or more times? | base rate + attacking tilt | 0.375 | 0.375 | — | 37 |
| GER vs Curacao | In the second half, will Germany have more shots on target than Curaçao? | derived Kalshi lambdas (SOT) | 0.916 | 0.916 | — | 92 |
| NED vs JPN | Will Japan receive more cards than Netherlands? | base rate + underdog tilt | 0.440 | 0.440 | — | 44 |
| NED vs JPN | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.782 | 0.782 | — | 78 |
| NED vs JPN | Will Netherlands win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.487 | 0.483 | — | 48 |
| NED vs JPN | Will Japan score in the second half? | derived Kalshi team lambda | 0.438 | 0.438 | — | 44 |
| NED vs JPN | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.633 | 0.633 | — | 63 |
| NED vs JPN | Will Cody Gakpo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.669 | 0.669 | — | 67 |
| NED vs JPN | Will Takefusa Kubo score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.262 | 0.262 | — | 26 |
| NED vs JPN | Will Japan commit more fouls than Netherlands? | base rate + favorite tilt | 0.534 | 0.534 | — | 53 |
| NED vs JPN | Will Netherlands be caught offside 2 or more times? | base rate + attacking tilt | 0.574 | 0.574 | — | 57 |
| NED vs JPN | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.414 | 0.414 | — | 41 |
| CIV vs ECU | Will Ivory Coast win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.277 | 0.271 | — | 27 |
| CIV vs ECU | Will Ibrahim Sangaré have at least 1 shot on target? | modeled from Kalshi team lambda | 0.295 | 0.295 | — | 30 |
| CIV vs ECU | Will the second half have more total goals than the first half? | derived Kalshi totals | 0.406 | 0.406 | — | 41 |
| CIV vs ECU | Will Ecuador have more shots on target than Ivory Coast in the second half? | derived Kalshi lambdas (SOT) | 0.475 | 0.475 | — | 47 |
| CIV vs ECU | Will Ivory Coast be caught offside 2 or more times? | base rate + attacking tilt | 0.457 | 0.457 | — | 46 |
| CIV vs ECU | At halftime, will Ecuador have more corner kicks than Ivory Coast? | Kalshi team-corners fit, 1H | 0.423 | 0.423 | — | 42 |
| CIV vs ECU | Will Ecuador commit more fouls than Ivory Coast? | base rate + favorite tilt | 0.417 | 0.417 | — | 42 |
| CIV vs ECU | Will Ivory Coast score in the second half? | derived Kalshi team lambda | 0.392 | 0.392 | — | 39 |
| CIV vs ECU | Will Jeremy Sarmiento score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.203 | 0.203 | — | 20 |
| CIV vs ECU | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| SWE vs TUN | Will Sweden commit more fouls than Tunisia? | base rate + favorite tilt | 0.362 | 0.362 | — | 36 |
| SWE vs TUN | Will Tunisia have more shots on target than Sweden in the second half? | derived Kalshi lambdas (SOT) | 0.251 | 0.251 | — | 25 |
| SWE vs TUN | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| SWE vs TUN | Will Viktor Gyökeres score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.498 | 0.498 | — | 50 |
| SWE vs TUN | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.430 | 0.430 | — | 43 |
| SWE vs TUN | Will Sweden win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.517 | 0.512 | — | 51 |
| SWE vs TUN | Will the second half have more total goals than the first half? | derived Kalshi totals | 0.444 | 0.444 | — | 44 |
| SWE vs TUN | Will Sweden score the first goal of the game and Tunisia score in the second half? | derived Kalshi lambdas | 0.217 | 0.217 | — | 22 |
| SWE vs TUN | At halftime, will Tunisia have more corner kicks than Sweden? | Kalshi team-corners fit, 1H | 0.325 | 0.325 | — | 32 |
| SWE vs TUN | Will Ellyes Skhiri have at least 1 shot on target? | modeled from Kalshi team lambda | 0.295 | 0.295 | — | 30 |
| ESP vs CPV | Will Cape Verde commit more fouls than Spain? | base rate + favorite tilt | 0.732 | 0.732 | — | 73 |
| ESP vs CPV | Will Dani Olmo score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.530 | 0.530 | — | 53 |
| ESP vs CPV | Will Cape Verde be caught offside 2 or more times? | base rate + attacking tilt | 0.382 | 0.382 | — | 38 |
| ESP vs CPV | In the second half, will Spain have more corner kicks than Cape Verde? | Kalshi team-corners fit, 2H | 0.823 | 0.823 | — | 82 |
| ESP vs CPV | Will Spain have more shots on target than Cape Verde in the second half? | derived Kalshi lambdas (SOT) | 0.897 | 0.897 | — | 90 |
| ESP vs CPV | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| ESP vs CPV | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.304 | 0.304 | — | 30 |
| ESP vs CPV | Will Ryan Mendes have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| ESP vs CPV | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.855 | 0.855 | — | 85 |
| ESP vs CPV | Will Spain win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.907 | 0.901 | — | 90 |
| BEL vs EGY | Will Belgium be caught offside 2 or more times? | base rate + attacking tilt | 0.579 | 0.579 | — | 58 |
| BEL vs EGY | Will Egypt have more shots on target than Belgium in the second half? | derived Kalshi lambdas (SOT) | 0.203 | 0.203 | — | 20 |
| BEL vs EGY | Will Mahmoud Trezeguet score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.215 | 0.215 | — | 21 |
| BEL vs EGY | Will Youri Tielemans have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| BEL vs EGY | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.420 | 0.420 | — | 42 |
| BEL vs EGY | Will Belgium win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.597 | 0.597 | — | 60 |
| BEL vs EGY | Will Egypt commit more fouls than Belgium? | base rate + favorite tilt | 0.600 | 0.600 | — | 60 |
| BEL vs EGY | Will there be 2 or more total cards shown in the second half? | base rate (cards) | 0.696 | 0.696 | — | 70 |
| BEL vs EGY | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.359 | 0.359 | — | 36 |
| BEL vs EGY | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.645 | 0.645 | — | 64 |
| KSA vs URU | Will Uruguay have more shots on target than Saudi Arabia in the second half? | derived Kalshi lambdas (SOT) | 0.734 | 0.734 | — | 73 |
| KSA vs URU | Will Saudi Arabia commit more fouls than Uruguay? | base rate + favorite tilt | 0.642 | 0.642 | — | 64 |
| KSA vs URU | Will a penalty kick be awarded in the match? | base rate | 0.280 | 0.280 | — | 28 |
| KSA vs URU | Will Uruguay score more goals than Saudi Arabia in the second half? | derived Kalshi lambdas | 0.510 | 0.510 | — | 51 |
| KSA vs URU | Will Saudi Arabia receive more cards than Uruguay? | base rate + underdog tilt | 0.507 | 0.507 | — | 51 |
| KSA vs URU | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.667 | 0.667 | — | 67 |
| KSA vs URU | Will Saudi Arabia be caught offside 2 or more times? | base rate + attacking tilt | 0.420 | 0.420 | — | 42 |
| KSA vs URU | Will Darwin Núñez score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.358 | 0.358 | — | 36 |
| KSA vs URU | Will Salem Al-Dawsari score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.256 | 0.256 | — | 26 |
| KSA vs URU | Will Saudi Arabia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.117 | 0.117 | — | 12 |
| IRN vs New Zealand | Will Iran be caught offside 2 or more times? | base rate + attacking tilt | 0.539 | 0.539 | — | 54 |
| IRN vs New Zealand | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.624 | 0.624 | — | 62 |
| IRN vs New Zealand | Will Ben Waine score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.230 | 0.230 | — | 23 |
| IRN vs New Zealand | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| IRN vs New Zealand | Will Iran score in the second half? | derived Kalshi team lambda | 0.545 | 0.545 | — | 55 |
| IRN vs New Zealand | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.603 | 0.603 | — | 60 |
| IRN vs New Zealand | Will Iran win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.537 | 0.528 | — | 53 |
| IRN vs New Zealand | Will Mehdi Taremi have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.477 | 0.477 | — | 48 |
| IRN vs New Zealand | Will New Zealand finish with more corner kicks than Iran? | Kalshi team-corners fit | 0.351 | 0.351 | — | 35 |
| IRN vs New Zealand | In the second half, will Iran have more shots on target than New Zealand? | derived Kalshi lambdas (SOT) | 0.603 | 0.603 | — | 60 |
| FRA vs SEN | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.341 | 0.341 | — | 34 |
| FRA vs SEN | Will France have more shots on target than Senegal in the second half? | derived Kalshi lambdas (SOT) | 0.733 | 0.733 | — | 73 |
| FRA vs SEN | Will France win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.677 | 0.663 | — | 66 |
| FRA vs SEN | At halftime, will France be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.497 | 0.497 | — | 50 |
| FRA vs SEN | Will Senegal have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.246 | 0.246 | — | 25 |
| FRA vs SEN | Will France score in the first half? | derived Kalshi team lambda | 0.561 | 0.561 | — | 56 |
| FRA vs SEN | Will Sadio Mané score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.153 | 0.153 | — | 15 |
| FRA vs SEN | Will France be caught offside 2 or more times? | base rate + attacking tilt | 0.603 | 0.603 | — | 60 |
| FRA vs SEN | Will Senegal receive at least 1 card in the second half? | base rate (cards) | 0.748 | 0.748 | — | 75 |
| FRA vs SEN | Will Senegal be caught offside 2 or more times? | base rate + attacking tilt | 0.424 | 0.424 | — | 42 |
| IRQ vs NOR | Will Iraq have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.296 | 0.296 | — | 30 |
| IRQ vs NOR | Will Iraq score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.403 | 0.403 | — | 40 |
| IRQ vs NOR | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.756 | 0.756 | — | 76 |
| IRQ vs NOR | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.603 | 0.603 | — | 60 |
| IRQ vs NOR | Will Mohanad Ali score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.209 | 0.209 | — | 21 |
| IRQ vs NOR | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| IRQ vs NOR | Will Iraq have more shots on target than Norway in the second half? | derived Kalshi lambdas (SOT) | 0.102 | 0.102 | — | 10 |
| IRQ vs NOR | Will Norway be caught offside 2 or more times? | base rate + attacking tilt | 0.682 | 0.682 | — | 68 |
| IRQ vs NOR | Will Norway commit more fouls than Iraq? | base rate + favorite tilt | 0.235 | 0.235 | — | 23 |
| IRQ vs NOR | Will Norway score in the second half? | derived Kalshi team lambda | 0.748 | 0.748 | — | 75 |
| ARG vs ALG | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.487 | 0.487 | — | 49 |
| ARG vs ALG | Will Riyad Mahrez have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| ARG vs ALG | Will Argentina be caught offside 2 or more times? | base rate + attacking tilt | 0.611 | 0.611 | — | 61 |
| ARG vs ALG | Will Algeria commit more fouls than Argentina? | base rate + favorite tilt | 0.650 | 0.650 | — | 65 |
| ARG vs ALG | Will Argentina win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.707 | 0.693 | — | 69 |
| ARG vs ALG | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| ARG vs ALG | Will Algeria have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.324 | 0.324 | — | 32 |
| ARG vs ALG | Will Argentina score the first goal of the game and Algeria score in the second half? | derived Kalshi lambdas | 0.198 | 0.198 | — | 20 |
| ARG vs ALG | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.654 | 0.654 | — | 65 |
| ARG vs ALG | Will Argentina score in the first half? | derived Kalshi team lambda | 0.589 | 0.589 | — | 59 |
| AUT vs JOR | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| AUT vs JOR | Will Marcel Sabitzer have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| AUT vs JOR | Will Mousa Al-Taamari have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| AUT vs JOR | Will Austria win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.737 | 0.729 | — | 73 |
| AUT vs JOR | Will Jordan have more shots on target than Austria in the second half? | derived Kalshi lambdas (SOT) | 0.129 | 0.129 | — | 13 |
| AUT vs JOR | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.413 | 0.413 | — | 41 |
| AUT vs JOR | Will Jordan commit more fouls than Austria? | base rate + favorite tilt | 0.661 | 0.661 | — | 66 |
| AUT vs JOR | Will Austria score in the second half? | derived Kalshi team lambda | 0.707 | 0.707 | — | 71 |
| AUT vs JOR | Will Jordan finish with more corner kicks than Austria? | Kalshi team-corners fit | 0.195 | 0.195 | — | 20 |
| AUT vs JOR | Will Austria have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.720 | 0.720 | — | 72 |
| POR vs COD | Will Portugal win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.767 | 0.759 | — | 76 |
| POR vs COD | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.326 | 0.326 | — | 33 |
| POR vs COD | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| POR vs COD | Will the second half have more goals than the first half? | derived Kalshi totals | 0.447 | 0.447 | — | 45 |
| POR vs COD | In the second half, will Portugal have more shots on target than DR Congo? | derived Kalshi lambdas (SOT) | 0.806 | 0.806 | — | 81 |
| POR vs COD | Will DR Congo commit more fouls than Portugal? | base rate + favorite tilt | 0.679 | 0.679 | — | 68 |
| POR vs COD | Will Cédric Bakambu have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| POR vs COD | Will Gonçalo Ramos score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.396 | 0.396 | — | 40 |
| POR vs COD | Will there be 5 or more total corner kicks in the second half? | Kalshi corners fit, 2H share | 0.575 | 0.575 | — | 57 |
| POR vs COD | Will DR Congo have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.223 | 0.223 | — | 22 |
| ENG vs CRO | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.704 | 0.704 | — | 70 |
| ENG vs CRO | Will England win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.567 | 0.556 | — | 56 |
| ENG vs CRO | Will Luka Sučić have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| ENG vs CRO | Will England have more shots on target than Croatia in the second half? | derived Kalshi lambdas (SOT) | 0.634 | 0.634 | — | 63 |
| ENG vs CRO | Will Harry Kane have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.560 | 0.560 | — | 56 |
| ENG vs CRO | Will England commit more fouls than Croatia? | base rate + favorite tilt | 0.342 | 0.342 | — | 34 |
| ENG vs CRO | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| ENG vs CRO | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.334 | 0.334 | — | 33 |
| ENG vs CRO | At halftime, will Croatia have more corner kicks than England? | Kalshi team-corners fit, 1H | 0.303 | 0.303 | — | 30 |
| ENG vs CRO | Will Croatia be caught offside 2 or more times? | base rate + attacking tilt | 0.441 | 0.441 | — | 44 |
| GHA vs PAN | Will Ghana commit more fouls than Panama? | base rate + favorite tilt | 0.407 | 0.407 | — | 41 |
| GHA vs PAN | Will Panama receive more cards than Ghana? | base rate + underdog tilt | 0.426 | 0.426 | — | 43 |
| GHA vs PAN | Will Ghana win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.447 | 0.442 | — | 44 |
| GHA vs PAN | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.359 | 0.359 | — | 36 |
| GHA vs PAN | Will Antoine Semenyo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.671 | 0.671 | — | 67 |
| GHA vs PAN | Will José Fajardo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| GHA vs PAN | Will Ghana have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.790 | 0.790 | — | 79 |
| GHA vs PAN | Will Ghana have more shots on target than Panama in the second half? | derived Kalshi lambdas (SOT) | 0.536 | 0.536 | — | 54 |
| GHA vs PAN | Will Panama be caught offside 2 or more times? | base rate + attacking tilt | 0.470 | 0.470 | — | 47 |
| GHA vs PAN | Will Panama score the first goal of the second half? | derived Kalshi lambdas | 0.294 | 0.294 | — | 29 |
| UZB vs COL | Will Uzbekistan have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.278 | 0.278 | — | 28 |
| UZB vs COL | Will Eldor Shomurodov score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.236 | 0.236 | — | 24 |
| UZB vs COL | Will Colombia have more shots on target than Uzbekistan in the second half? | derived Kalshi lambdas (SOT) | 0.764 | 0.764 | — | 76 |
| UZB vs COL | Will Uzbekistan be caught offside 2 or more times? | base rate + attacking tilt | 0.410 | 0.410 | — | 41 |
| UZB vs COL | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| UZB vs COL | Will Luis Díaz have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.559 | 0.559 | — | 56 |
| UZB vs COL | Will Uzbekistan score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.457 | 0.457 | — | 46 |
| UZB vs COL | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.380 | 0.385 | — | 38 |
| UZB vs COL | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.497 | 0.497 | — | 50 |
| UZB vs COL | Will Colombia score in the second half? | derived Kalshi team lambda | 0.655 | 0.655 | — | 65 |
| CZE vs RSA | Will Oswin Appollis score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.210 | 0.210 | — | 21 |
| CZE vs RSA | Will Czechia have more shots on target than South Africa in the second half? | derived Kalshi lambdas (SOT) | 0.655 | 0.655 | — | 65 |
| CZE vs RSA | In the second half, will Czechia have more corner kicks than South Africa? | Kalshi team-corners fit, 2H | 0.701 | 0.701 | — | 70 |
| CZE vs RSA | Will South Africa commit more fouls than Czechia? | base rate + favorite tilt | 0.596 | 0.596 | — | 60 |
| CZE vs RSA | Will Czechia be caught offside 2 or more times? | base rate + attacking tilt | 0.568 | 0.568 | — | 57 |
| CZE vs RSA | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| CZE vs RSA | Will Czechia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.597 | 0.591 | — | 59 |
| CZE vs RSA | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.567 | 0.567 | — | 57 |
| CZE vs RSA | Will South Africa score in the second half? | derived Kalshi team lambda | 0.346 | 0.346 | — | 35 |
| CZE vs RSA | Will Patrik Schick have at least 1 shot on target? | modeled from Kalshi team lambda | 0.724 | 0.724 | — | 72 |
| SUI vs BIH | Will Switzerland have more shots on target than Bosnia and Herzegovina in the second half? | derived Kalshi lambdas (SOT) | 0.665 | 0.665 | — | 67 |
| SUI vs BIH | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.637 | 0.637 | — | 64 |
| SUI vs BIH | Will Switzerland be caught offside 2 or more times? | base rate + attacking tilt | 0.571 | 0.571 | — | 57 |
| SUI vs BIH | Will there be 2 or more total cards shown in the second half? | base rate (cards) | 0.696 | 0.696 | — | 70 |
| SUI vs BIH | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.323 | 0.323 | — | 32 |
| SUI vs BIH | Will Bosnia and Herzegovina commit more fouls than Switzerland? | base rate + favorite tilt | 0.604 | 0.604 | — | 60 |
| SUI vs BIH | Will a penalty kick be awarded in the match? | base rate | 0.280 | 0.280 | — | 28 |
| SUI vs BIH | Will Granit Xhaka have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.253 | 0.253 | — | 25 |
| SUI vs BIH | Will Switzerland win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.617 | 0.605 | — | 60 |
| SUI vs BIH | Will Edin Džeko have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| CAN vs QAT | Will Canada have 5 or more shots on target? | derived Kalshi team lambda (SOT) | 0.753 | 0.753 | — | 75 |
| CAN vs QAT | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.645 | 0.645 | — | 64 |
| CAN vs QAT | Will Qatar commit more fouls than Canada? | base rate + favorite tilt | 0.670 | 0.670 | — | 67 |
| CAN vs QAT | At halftime, will Canada be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.527 | 0.532 | — | 53 |
| CAN vs QAT | Will Canada win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.747 | 0.739 | — | 74 |
| CAN vs QAT | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| CAN vs QAT | Will Jonathan David have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.574 | 0.574 | — | 57 |
| CAN vs QAT | Will Akram Afif have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| CAN vs QAT | Will Qatar have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.051 | 0.051 | — | 5 |
| CAN vs QAT | Will Qatar score in the second half? | derived Kalshi team lambda | 0.260 | 0.260 | — | 26 |
| MEX vs KOR | Will Mexico win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.497 | 0.482 | — | 48 |
| MEX vs KOR | Will Mexico be caught offside 2 or more times? | base rate + attacking tilt | 0.524 | 0.524 | — | 52 |
| MEX vs KOR | Will Mexico score the first goal of the game and South Korea score in the second half? | derived Kalshi lambdas | 0.205 | 0.205 | — | 20 |
| MEX vs KOR | Will South Korea finish with more corner kicks than Mexico? | Kalshi team-corners fit | 0.250 | 0.250 | — | 25 |
| MEX vs KOR | Will Son Heung-min score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.281 | 0.281 | — | 28 |
| MEX vs KOR | Will Germán Berterame have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| MEX vs KOR | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| MEX vs KOR | Will South Korea score in the second half? | derived Kalshi team lambda | 0.369 | 0.369 | — | 37 |
| MEX vs KOR | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.407 | 0.407 | — | 41 |
| MEX vs KOR | At halftime, will Mexico be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.360 | 0.356 | — | 36 |
| USA vs AUS | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.354 | 0.354 | — | 35 |
| USA vs AUS | Will United States commit more fouls than Australia? | base rate + favorite tilt | 0.345 | 0.345 | — | 35 |
| USA vs AUS | Will Australia be caught offside 2 or more times? | base rate + attacking tilt | 0.454 | 0.454 | — | 45 |
| USA vs AUS | Will United States score more goals than Australia in the second half? | derived Kalshi lambdas | 0.437 | 0.437 | — | 44 |
| USA vs AUS | Will United States have more shots on target than Australia in the second half? | derived Kalshi lambdas (SOT) | 0.620 | 0.620 | — | 62 |
| USA vs AUS | Will Australia finish with more corner kicks than United States? | Kalshi team-corners fit | 0.179 | 0.179 | — | 18 |
| USA vs AUS | Will United States win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.567 | 0.556 | — | 56 |
| USA vs AUS | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| USA vs AUS | Will Folarin Balogun have at least 1 shot on target? | modeled from Kalshi team lambda | 0.720 | 0.720 | — | 72 |
| USA vs AUS | Will Riley McGree have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| SCO vs MAR | Will Morocco receive at least 1 card in the second half? | base rate (cards) | 0.676 | 0.676 | — | 68 |
| SCO vs MAR | Will Morocco commit more fouls than Scotland? | base rate + favorite tilt | 0.372 | 0.372 | — | 37 |
| SCO vs MAR | Will Scotland be caught offside 2 or more times? | base rate + attacking tilt | 0.447 | 0.447 | — | 45 |
| SCO vs MAR | Will Scotland have more shots on target than Morocco in the second half? | derived Kalshi lambdas (SOT) | 0.281 | 0.281 | — | 28 |
| SCO vs MAR | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.312 | 0.312 | — | 31 |
| SCO vs MAR | Will Morocco score in the second half? | derived Kalshi team lambda | 0.508 | 0.508 | — | 51 |
| SCO vs MAR | Will Scott McTominay have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| SCO vs MAR | Will Scotland have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.519 | 0.519 | — | 52 |
| SCO vs MAR | Will Scotland win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.227 | 0.224 | — | 22 |
| SCO vs MAR | Will Morocco be caught offside 2 or more times? | base rate + attacking tilt | 0.521 | 0.521 | — | 52 |
| BRA vs Haiti | Will Haiti have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.247 | 0.247 | — | 25 |
| BRA vs Haiti | Will Haiti receive more cards than Brazil? | base rate + underdog tilt | 0.565 | 0.565 | — | 56 |
| BRA vs Haiti | Will Duckens Nazon have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| BRA vs Haiti | Will Brazil commit more fouls than Haiti? | base rate + favorite tilt | 0.208 | 0.208 | — | 21 |
| BRA vs Haiti | Will Haiti be caught offside 2 or more times? | base rate + attacking tilt | 0.386 | 0.386 | — | 39 |
| BRA vs Haiti | Will Brazil win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.907 | 0.895 | — | 89 |
| BRA vs Haiti | Will Brazil score in the second half? | derived Kalshi team lambda | 0.860 | 0.860 | — | 86 |
| BRA vs Haiti | Will Haiti have 3 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.302 | 0.302 | — | 30 |
| BRA vs Haiti | Will Brazil score 3 or more total goals? | Kalshi KXWCTEAMTOTAL direct | 0.650 | 0.650 | — | 65 |
| BRA vs Haiti | Will Haiti have at least 1 shot on target in the second half? | derived Kalshi team lambda (SOT) | 0.554 | 0.554 | — | 55 |
| TUR vs PAR | Will Türkiye be caught offside 2 or more times? | base rate + attacking tilt | 0.464 | 0.464 | — | 46 |
| TUR vs PAR | In the second half, will Türkiye have more corner kicks than Paraguay? | Kalshi team-corners fit, 2H | 0.533 | 0.533 | — | 53 |
| TUR vs PAR | Will Türkiye win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.437 | 0.432 | — | 43 |
| TUR vs PAR | Will Paraguay commit more fouls than Türkiye? | base rate + favorite tilt | 0.511 | 0.511 | — | 51 |
| TUR vs PAR | Will Türkiye have more shots on target than Paraguay in the second half? | derived Kalshi lambdas (SOT) | 0.396 | 0.396 | — | 40 |
| TUR vs PAR | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| TUR vs PAR | Will Julio Enciso have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| TUR vs PAR | Will Paraguay receive more cards than Türkiye? | base rate + underdog tilt | 0.426 | 0.426 | — | 43 |
| TUR vs PAR | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.593 | 0.593 | — | 59 |
| TUR vs PAR | Will Orkun Kökçü have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| NED vs SWE | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.415 | 0.426 | — | 43 |
| NED vs SWE | Will Cody Gakpo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.658 | 0.658 | — | 66 |
| NED vs SWE | Will Netherlands score more goals than Sweden in the second half? | derived Kalshi lambdas | 0.447 | 0.447 | — | 45 |
| NED vs SWE | Will Viktor Gyökeres have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.442 | 0.442 | — | 44 |
| NED vs SWE | Will Sweden receive more cards than Netherlands? | base rate + underdog tilt | 0.476 | 0.476 | — | 48 |
| NED vs SWE | Will Netherlands be caught offside 2 or more times? | base rate + attacking tilt | 0.568 | 0.568 | — | 57 |
| NED vs SWE | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.375 | 0.375 | — | 37 |
| NED vs SWE | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.732 | 0.732 | — | 73 |
| NED vs SWE | Will Netherlands win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.597 | 0.591 | — | 59 |
| NED vs SWE | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.646 | 0.646 | — | 65 |
| GER vs CIV | Will Germany score in the second half? | derived Kalshi team lambda | 0.652 | 0.652 | — | 65 |
| GER vs CIV | Will Germany win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.637 | 0.624 | — | 62 |
| GER vs CIV | Will Ivory Coast receive more cards than Germany? | base rate + underdog tilt | 0.487 | 0.487 | — | 49 |
| GER vs CIV | Will Ivory Coast commit more fouls than Germany? | base rate + favorite tilt | 0.610 | 0.610 | — | 61 |
| GER vs CIV | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.711 | 0.711 | — | 71 |
| GER vs CIV | Will Germany be caught offside 2 or more times? | base rate + attacking tilt | 0.619 | 0.619 | — | 62 |
| GER vs CIV | Will Ivory Coast be caught offside 2 or more times? | base rate + attacking tilt | 0.454 | 0.454 | — | 45 |
| GER vs CIV | Will Ivory Coast have more shots on target than Germany in the second half? | derived Kalshi lambdas (SOT) | 0.183 | 0.183 | — | 18 |
| GER vs CIV | Will the second half have more goals than the first half? | derived Kalshi totals | 0.412 | 0.412 | — | 41 |
| GER vs CIV | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| ECU vs Curacao | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.521 | 0.521 | — | 52 |
| ECU vs Curacao | Will the second half have more total goals than the first half? | derived Kalshi totals | 0.443 | 0.443 | — | 44 |
| ECU vs Curacao | Will Ecuador win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.813 | 0.808 | — | 81 |
| ECU vs Curacao | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.573 | 0.573 | — | 57 |
| ECU vs Curacao | Will Ecuador have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.880 | 0.880 | — | 88 |
| ECU vs Curacao | Will Leandro Bacuna have at least 1 shot on target? | modeled from Kalshi team lambda | 0.451 | 0.451 | — | 45 |
| ECU vs Curacao | Will Jeremy Sarmiento have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.387 | 0.387 | — | 39 |
| ECU vs Curacao | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| ECU vs Curacao | Will Ecuador score the first goal of the game and Curaçao score in the second half? | derived Kalshi lambdas | 0.184 | 0.184 | — | 18 |
| ECU vs Curacao | Will Ecuador commit more fouls than Curaçao? | base rate + favorite tilt | 0.235 | 0.235 | — | 23 |
| TUN vs JPN | Will Ellyes Skhiri have at least 1 shot on target? | modeled from Kalshi team lambda | 0.295 | 0.295 | — | 30 |
| TUN vs JPN | In the second half, will Tunisia have more shots on target than Japan? | derived Kalshi lambdas (SOT) | 0.223 | 0.223 | — | 22 |
| TUN vs JPN | Will Japan be caught offside 2 or more times? | base rate + attacking tilt | 0.550 | 0.550 | — | 55 |
| TUN vs JPN | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| TUN vs JPN | Will Japan commit more fouls than Tunisia? | base rate + favorite tilt | 0.327 | 0.327 | — | 33 |
| TUN vs JPN | Will Takefusa Kubo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.591 | 0.591 | — | 59 |
| TUN vs JPN | Will Japan score in the second half? | derived Kalshi team lambda | 0.553 | 0.553 | — | 55 |
| TUN vs JPN | Will there be 5 or more total corner kicks in the second half? | Kalshi corners fit, 2H share | 0.591 | 0.591 | — | 59 |
| TUN vs JPN | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.593 | 0.593 | — | 59 |
| TUN vs JPN | Will Tunisia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.167 | 0.163 | — | 16 |
| ESP vs KSA | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| ESP vs KSA | Will Spain be caught offside 2 or more times? | base rate + attacking tilt | 0.714 | 0.714 | — | 71 |
| ESP vs KSA | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.256 | 0.256 | — | 26 |
| ESP vs KSA | Will Saudi Arabia be caught offside 2 or more times? | base rate + attacking tilt | 0.382 | 0.382 | — | 38 |
| ESP vs KSA | Will Saudi Arabia score in the second half? | derived Kalshi team lambda | 0.215 | 0.215 | — | 22 |
| ESP vs KSA | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.798 | 0.798 | — | 80 |
| ESP vs KSA | Will Spain win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.887 | 0.878 | — | 88 |
| ESP vs KSA | Will Salem Al-Dawsari score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.110 | 0.110 | — | 11 |
| ESP vs KSA | In the second half, will Spain have more corner kicks than Saudi Arabia? | Kalshi team-corners fit, 2H | 0.825 | 0.825 | — | 83 |
| ESP vs KSA | Will Spain have more shots on target than Saudi Arabia in the second half? | derived Kalshi lambdas (SOT) | 0.882 | 0.882 | — | 88 |
| BEL vs IRN | At halftime, will Belgium be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.490 | 0.505 | — | 51 |
| BEL vs IRN | Will Youri Tielemans have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| BEL vs IRN | Will Mehdi Taremi score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.250 | 0.250 | — | 25 |
| BEL vs IRN | Will Iran commit more fouls than Belgium? | base rate + favorite tilt | 0.641 | 0.641 | — | 64 |
| BEL vs IRN | Will there be 2 or more total cards shown in the second half? | base rate (cards) | 0.696 | 0.696 | — | 70 |
| BEL vs IRN | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.328 | 0.328 | — | 33 |
| BEL vs IRN | Will Belgium have more shots on target than Iran in the second half? | derived Kalshi lambdas (SOT) | 0.740 | 0.740 | — | 74 |
| BEL vs IRN | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.669 | 0.669 | — | 67 |
| BEL vs IRN | Will there be 9 or more total corner kicks? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| BEL vs IRN | Will Belgium win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.697 | 0.683 | — | 68 |
| URU vs CPV | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.689 | 0.689 | — | 69 |
| URU vs CPV | Will a penalty kick be awarded in the match? | base rate | 0.280 | 0.280 | — | 28 |
| URU vs CPV | Will Uruguay commit more fouls than Cape Verde? | base rate + favorite tilt | 0.280 | 0.280 | — | 28 |
| URU vs CPV | Will Cape Verde have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.378 | 0.378 | — | 38 |
| URU vs CPV | Will Uruguay win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.697 | 0.690 | — | 69 |
| URU vs CPV | Will Cape Verde score in the second half? | derived Kalshi team lambda | 0.320 | 0.320 | — | 32 |
| URU vs CPV | Will Darwin Núñez score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.537 | 0.537 | — | 54 |
| URU vs CPV | Will Uruguay have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.586 | 0.586 | — | 59 |
| URU vs CPV | Will Uruguay be caught offside 2 or more times? | base rate + attacking tilt | 0.606 | 0.606 | — | 61 |
| URU vs CPV | Will Cape Verde receive more cards than Uruguay? | base rate + underdog tilt | 0.510 | 0.510 | — | 51 |
| New Zealand vs EGY | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| New Zealand vs EGY | Will New Zealand win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.197 | 0.197 | — | 20 |
| New Zealand vs EGY | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.593 | 0.593 | — | 59 |
| New Zealand vs EGY | Will Ben Waine have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| New Zealand vs EGY | Will Mahmoud Trezeguet score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.350 | 0.350 | — | 35 |
| New Zealand vs EGY | Will Egypt finish with more corner kicks than New Zealand? | Kalshi team-corners fit | 0.757 | 0.757 | — | 76 |
| New Zealand vs EGY | Will the second half have more goals than the first half? | derived Kalshi totals | 0.341 | 0.341 | — | 34 |
| New Zealand vs EGY | In the second half, will New Zealand have more shots on target than Egypt? | derived Kalshi lambdas (SOT) | 0.247 | 0.247 | — | 25 |
| New Zealand vs EGY | Will New Zealand commit more fouls than Egypt? | base rate + favorite tilt | 0.578 | 0.578 | — | 58 |
| New Zealand vs EGY | Will Egypt be caught offside 2 or more times? | base rate + attacking tilt | 0.539 | 0.539 | — | 54 |
| ARG vs AUT | Will Argentina have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.416 | 0.416 | — | 42 |
| ARG vs AUT | Will Argentina score in the second half? | derived Kalshi team lambda | 0.571 | 0.571 | — | 57 |
| ARG vs AUT | Will Austria be caught offside 2 or more times? | base rate + attacking tilt | 0.437 | 0.437 | — | 44 |
| ARG vs AUT | Will Austria have more shots on target than Argentina in the second half? | derived Kalshi lambdas (SOT) | 0.222 | 0.222 | — | 22 |
| ARG vs AUT | Will the second half have more goals than the first half? | derived Kalshi totals | 0.432 | 0.432 | — | 43 |
| ARG vs AUT | Will Austria finish with more corner kicks than Argentina? | Kalshi team-corners fit | 0.142 | 0.142 | — | 14 |
| ARG vs AUT | Will Marcel Sabitzer have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| ARG vs AUT | Will Argentina win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.617 | 0.599 | — | 60 |
| ARG vs AUT | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.517 | 0.517 | — | 52 |
| ARG vs AUT | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| FRA vs IRQ | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.273 | 0.273 | — | 27 |
| FRA vs IRQ | Will France win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.877 | 0.868 | — | 87 |
| FRA vs IRQ | Will Iraq score in the second half? | derived Kalshi team lambda | 0.218 | 0.218 | — | 22 |
| FRA vs IRQ | Will Iraq have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.131 | 0.131 | — | 13 |
| FRA vs IRQ | Will France score in the first half? | derived Kalshi team lambda | 0.717 | 0.717 | — | 72 |
| FRA vs IRQ | Will Mohanad Ali have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| FRA vs IRQ | At halftime, will Iraq have more corner kicks than France? | Kalshi team-corners fit, 1H | 0.121 | 0.121 | — | 12 |
| FRA vs IRQ | Will France commit more fouls than Iraq? | base rate + favorite tilt | 0.212 | 0.212 | — | 21 |
| FRA vs IRQ | Will Iraq receive at least 1 card in the second half? | base rate (cards) | 0.769 | 0.769 | — | 77 |
| FRA vs IRQ | Will Iraq have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.236 | 0.236 | — | 24 |
| NOR vs SEN | Will Senegal commit more fouls than Norway? | base rate + favorite tilt | 0.514 | 0.514 | — | 51 |
| NOR vs SEN | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.630 | 0.630 | — | 63 |
| NOR vs SEN | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| NOR vs SEN | Will Norway score more goals than Senegal in the second half? | derived Kalshi lambdas | 0.370 | 0.370 | — | 37 |
| NOR vs SEN | Will Senegal be caught offside 2 or more times? | base rate + attacking tilt | 0.480 | 0.480 | — | 48 |
| NOR vs SEN | Will Sadio Mané score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.219 | 0.219 | — | 22 |
| NOR vs SEN | Will Norway have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.337 | 0.337 | — | 34 |
| NOR vs SEN | Will there be 9 or more total corner kicks? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| NOR vs SEN | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.440 | 0.436 | — | 44 |
| NOR vs SEN | Will Norway win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.457 | 0.452 | — | 45 |
| JOR vs ALG | Will Riyad Mahrez have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.454 | 0.454 | — | 45 |
| JOR vs ALG | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.493 | 0.493 | — | 49 |
| JOR vs ALG | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.415 | 0.423 | — | 42 |
| JOR vs ALG | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| JOR vs ALG | Will Jordan score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.533 | 0.533 | — | 53 |
| JOR vs ALG | Will Algeria be caught offside 2 or more times? | base rate + attacking tilt | 0.582 | 0.582 | — | 58 |
| JOR vs ALG | Will Jordan score the first goal of the game and Algeria score in the second half? | derived Kalshi lambdas | 0.163 | 0.163 | — | 16 |
| JOR vs ALG | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.645 | 0.645 | — | 64 |
| JOR vs ALG | Will Jordan commit more fouls than Algeria? | base rate + favorite tilt | 0.621 | 0.621 | — | 62 |
| JOR vs ALG | Will Mousa Al-Taamari have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| POR vs UZB | Will Portugal be caught offside 2 or more times? | base rate + attacking tilt | 0.679 | 0.679 | — | 68 |
| POR vs UZB | In the second half, will Portugal have more shots on target than Uzbekistan? | derived Kalshi lambdas (SOT) | 0.822 | 0.822 | — | 82 |
| POR vs UZB | Will Uzbekistan be caught offside 2 or more times? | base rate + attacking tilt | 0.424 | 0.424 | — | 42 |
| POR vs UZB | Will Uzbekistan have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.246 | 0.246 | — | 25 |
| POR vs UZB | Will Gonçalo Ramos score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.422 | 0.422 | — | 42 |
| POR vs UZB | Will Portugal win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.797 | 0.799 | — | 80 |
| POR vs UZB | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.513 | 0.513 | — | 51 |
| POR vs UZB | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.383 | 0.383 | — | 38 |
| POR vs UZB | Will Eldor Shomurodov have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.379 | 0.379 | — | 38 |
| POR vs UZB | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| ENG vs GHA | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| ENG vs GHA | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.336 | 0.336 | — | 34 |
| ENG vs GHA | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.666 | 0.666 | — | 67 |
| ENG vs GHA | Will Ghana have more shots on target than England in the second half? | derived Kalshi lambdas (SOT) | 0.137 | 0.137 | — | 14 |
| ENG vs GHA | Will England win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.747 | 0.732 | — | 73 |
| ENG vs GHA | Will Harry Kane score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.656 | 0.656 | — | 66 |
| ENG vs GHA | Will Antoine Semenyo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.632 | 0.632 | — | 63 |
| ENG vs GHA | Will Ghana commit more fouls than England? | base rate + favorite tilt | 0.662 | 0.662 | — | 66 |
| ENG vs GHA | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.615 | 0.615 | — | 61 |
| ENG vs GHA | Will Ghana have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.061 | 0.061 | — | 6 |
| PAN vs CRO | Will Panama score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.515 | 0.515 | — | 52 |
| PAN vs CRO | Will Panama have more shots on target than Croatia in the second half? | derived Kalshi lambdas (SOT) | 0.185 | 0.185 | — | 19 |
| PAN vs CRO | Will Croatia score the first goal of the second half? | derived Kalshi lambdas | 0.504 | 0.504 | — | 50 |
| PAN vs CRO | Will Panama commit more fouls than Croatia? | base rate + favorite tilt | 0.620 | 0.620 | — | 62 |
| PAN vs CRO | Will Croatia receive more cards than Panama? | base rate + underdog tilt | 0.303 | 0.303 | — | 30 |
| PAN vs CRO | Will Panama be caught offside 2 or more times? | base rate + attacking tilt | 0.430 | 0.430 | — | 43 |
| PAN vs CRO | Will Luka Sučić have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| PAN vs CRO | Will José Fajardo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| PAN vs CRO | Will Panama have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.448 | 0.448 | — | 45 |
| PAN vs CRO | Will there be 9 or more total corner kicks? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| COL vs COD | Will Colombia have more shots on target than DR Congo in the second half? | derived Kalshi lambdas (SOT) | 0.691 | 0.691 | — | 69 |
| COL vs COD | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| COL vs COD | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.567 | 0.567 | — | 57 |
| COL vs COD | Will Colombia have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.844 | 0.844 | — | 84 |
| COL vs COD | Will Luis Díaz score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.498 | 0.498 | — | 50 |
| COL vs COD | Will Cédric Bakambu have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| COL vs COD | Will Colombia commit more fouls than DR Congo? | base rate + favorite tilt | 0.285 | 0.285 | — | 29 |
| COL vs COD | At halftime, will Colombia be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.460 | 0.465 | — | 46 |
| COL vs COD | Will Colombia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.677 | 0.670 | — | 67 |
| COL vs COD | Will Colombia score more goals than DR Congo in the second half? | derived Kalshi lambdas | 0.455 | 0.455 | — | 46 |
| BIH vs QAT | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| BIH vs QAT | Will Qatar be caught offside 2 or more times? | base rate + attacking tilt | 0.430 | 0.430 | — | 43 |
| BIH vs QAT | In the second half, will Bosnia and Herzegovina have more corner kicks than Qatar? | Kalshi team-corners fit, 2H | 0.708 | 0.708 | — | 71 |
| BIH vs QAT | Will Bosnia and Herzegovina score more goals than Qatar in the second half? | derived Kalshi lambdas | 0.379 | 0.379 | — | 38 |
| BIH vs QAT | Will Qatar have more shots on target than Bosnia and Herzegovina in the second half? | derived Kalshi lambdas (SOT) | 0.255 | 0.255 | — | 26 |
| BIH vs QAT | Will Qatar commit more fouls than Bosnia and Herzegovina? | base rate + favorite tilt | 0.600 | 0.600 | — | 60 |
| BIH vs QAT | Will Bosnia and Herzegovina receive more cards than Qatar? | base rate + underdog tilt | 0.314 | 0.314 | — | 31 |
| BIH vs QAT | Will Bosnia and Herzegovina win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.597 | 0.593 | — | 59 |
| BIH vs QAT | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.537 | 0.537 | — | 54 |
| BIH vs QAT | Will Edin Džeko have at least 1 shot on target? | modeled from Kalshi team lambda | 0.638 | 0.638 | — | 64 |
| SUI vs CAN | Will Canada commit more fouls than Switzerland? | base rate + favorite tilt | 0.515 | 0.515 | — | 51 |
| SUI vs CAN | Will Switzerland be caught offside 2 or more times? | base rate + attacking tilt | 0.539 | 0.539 | — | 54 |
| SUI vs CAN | Will there be 2 or more total cards shown in the second half? | base rate (cards) | 0.696 | 0.696 | — | 70 |
| SUI vs CAN | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.372 | 0.372 | — | 37 |
| SUI vs CAN | Will a penalty kick be awarded in the match? | base rate | 0.280 | 0.280 | — | 28 |
| SUI vs CAN | Will Switzerland have more shots on target than Canada in the second half? | derived Kalshi lambdas (SOT) | 0.530 | 0.530 | — | 53 |
| SUI vs CAN | Will Switzerland win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.447 | 0.447 | — | 45 |
| SUI vs CAN | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.373 | 0.373 | — | 37 |
| SUI vs CAN | Will Granit Xhaka have at least 1 shot on target? | modeled from Kalshi team lambda | 0.423 | 0.423 | — | 42 |
| SUI vs CAN | Will Jonathan David have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| MAR vs Haiti | Will Morocco have more shots on target than Haiti in the second half? | derived Kalshi lambdas (SOT) | 0.776 | 0.776 | — | 78 |
| MAR vs Haiti | Will Haiti receive more cards than Morocco? | base rate + underdog tilt | 0.523 | 0.523 | — | 52 |
| MAR vs Haiti | Will Duckens Nazon have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| MAR vs Haiti | Will Morocco score in the first half? | derived Kalshi team lambda | 0.608 | 0.608 | — | 61 |
| MAR vs Haiti | Will Morocco win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.737 | 0.737 | — | 74 |
| MAR vs Haiti | At halftime, will Haiti have more corner kicks than Morocco? | Kalshi team-corners fit, 1H | 0.127 | 0.127 | — | 13 |
| MAR vs Haiti | Will Haiti commit more fouls than Morocco? | base rate + favorite tilt | 0.666 | 0.666 | — | 67 |
| MAR vs Haiti | Will Haiti score in the second half? | derived Kalshi team lambda | 0.299 | 0.299 | — | 30 |
| MAR vs Haiti | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| MAR vs Haiti | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.704 | 0.704 | — | 70 |
| SCO vs BRA | Will Brazil score in the first half? | derived Kalshi team lambda | 0.576 | 0.576 | — | 58 |
| SCO vs BRA | Will Scott McTominay have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| SCO vs BRA | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| SCO vs BRA | Will Brazil score in the second half? | derived Kalshi team lambda | 0.664 | 0.664 | — | 66 |
| SCO vs BRA | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.530 | 0.530 | — | 53 |
| SCO vs BRA | Will Scotland score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.520 | 0.520 | — | 52 |
| SCO vs BRA | Will Brazil have more shots on target than Scotland in the second half? | derived Kalshi lambdas (SOT) | 0.732 | 0.732 | — | 73 |
| SCO vs BRA | Will Scotland be caught offside 2 or more times? | base rate + attacking tilt | 0.434 | 0.434 | — | 43 |
| SCO vs BRA | Will Scotland score the first goal of the game and Brazil score in the second half? | derived Kalshi lambdas | 0.173 | 0.173 | — | 17 |
| SCO vs BRA | Will Brazil finish with more corner kicks than Scotland? | Kalshi team-corners fit | 0.848 | 0.848 | — | 85 |
| CZE vs MEX | Will Czechia commit more fouls than Mexico? | base rate + favorite tilt | 0.572 | 0.572 | — | 57 |
| CZE vs MEX | Will Mexico be caught offside 2 or more times? | base rate + attacking tilt | 0.550 | 0.550 | — | 55 |
| CZE vs MEX | Will Czechia have more shots on target than Mexico in the second half? | derived Kalshi lambdas (SOT) | 0.287 | 0.287 | — | 29 |
| CZE vs MEX | Will Mexico finish with more corner kicks than Czechia? | Kalshi team-corners fit | 0.745 | 0.745 | — | 75 |
| CZE vs MEX | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.340 | 0.340 | — | 34 |
| CZE vs MEX | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| CZE vs MEX | Will Czechia score in the second half? | derived Kalshi team lambda | 0.414 | 0.414 | — | 41 |
| CZE vs MEX | Will Czechia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.197 | 0.199 | — | 20 |
| CZE vs MEX | Will Germán Berterame score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.333 | 0.333 | — | 33 |
| CZE vs MEX | Will Patrik Schick have at least 1 shot on target? | modeled from Kalshi team lambda | 0.632 | 0.632 | — | 63 |
| RSA vs KOR | Will South Africa have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.448 | 0.448 | — | 45 |
| RSA vs KOR | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.312 | 0.312 | — | 31 |
| RSA vs KOR | Will South Korea have more shots on target than South Africa in the second half? | derived Kalshi lambdas (SOT) | 0.576 | 0.576 | — | 58 |
| RSA vs KOR | Will South Africa commit more fouls than South Korea? | base rate + favorite tilt | 0.611 | 0.611 | — | 61 |
| RSA vs KOR | Will Son Heung-min have at least 1 shot on target? | modeled from Kalshi team lambda | 0.638 | 0.638 | — | 64 |
| RSA vs KOR | Will Oswin Appollis have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| RSA vs KOR | Will South Korea receive at least 1 card in the second half? | base rate (cards) | 0.655 | 0.655 | — | 66 |
| RSA vs KOR | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.435 | 0.445 | — | 45 |
| RSA vs KOR | Will South Africa win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.157 | 0.154 | — | 15 |
| RSA vs KOR | Will South Korea be caught offside 2 or more times? | base rate + attacking tilt | 0.517 | 0.517 | — | 52 |
| Curacao vs CIV | Will Curaçao score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.405 | 0.405 | — | 40 |
| Curacao vs CIV | Will Ivory Coast have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.880 | 0.880 | — | 88 |
| Curacao vs CIV | Will Leandro Bacuna have at least 1 shot on target? | modeled from Kalshi team lambda | 0.451 | 0.451 | — | 45 |
| Curacao vs CIV | Will Ibrahim Sangaré have at least 1 shot on target? | modeled from Kalshi team lambda | 0.295 | 0.295 | — | 30 |
| Curacao vs CIV | Will Curaçao receive more cards than Ivory Coast? | base rate + underdog tilt | 0.538 | 0.538 | — | 54 |
| Curacao vs CIV | Will Curaçao have more shots on target than Ivory Coast in the second half? | derived Kalshi lambdas (SOT) | 0.154 | 0.154 | — | 15 |
| Curacao vs CIV | Will the second half have more goals than the first half? | derived Kalshi totals | 0.406 | 0.406 | — | 41 |
| Curacao vs CIV | Will Ivory Coast score the first goal of the second half? | derived Kalshi lambdas | 0.592 | 0.592 | — | 59 |
| Curacao vs CIV | Will Ivory Coast commit more fouls than Curaçao? | base rate + favorite tilt | 0.242 | 0.242 | — | 24 |
| Curacao vs CIV | Will Curaçao be caught offside 2 or more times? | base rate + attacking tilt | 0.393 | 0.393 | — | 39 |
| ECU vs GER | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| ECU vs GER | Will Germany have more shots on target than Ecuador in the second half? | derived Kalshi lambdas (SOT) | 0.622 | 0.622 | — | 62 |
| ECU vs GER | Will Germany score more goals than Ecuador in the second half? | derived Kalshi lambdas | 0.449 | 0.449 | — | 45 |
| ECU vs GER | In the second half, will Ecuador have more corner kicks than Germany? | Kalshi team-corners fit, 2H | 0.220 | 0.220 | — | 22 |
| ECU vs GER | Will Ecuador commit more fouls than Germany? | base rate + favorite tilt | 0.573 | 0.573 | — | 57 |
| ECU vs GER | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.760 | 0.760 | — | 76 |
| ECU vs GER | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.389 | 0.389 | — | 39 |
| ECU vs GER | Will Ecuador score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.595 | 0.595 | — | 60 |
| ECU vs GER | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.513 | 0.513 | — | 51 |
| ECU vs GER | Will Ecuador be caught offside 2 or more times? | base rate + attacking tilt | 0.483 | 0.483 | — | 48 |
| JPN vs SWE | Will Sweden score more goals than Japan in the second half? | derived Kalshi lambdas | 0.320 | 0.320 | — | 32 |
| JPN vs SWE | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| JPN vs SWE | Will Japan have more shots on target than Sweden in the second half? | derived Kalshi lambdas (SOT) | 0.352 | 0.352 | — | 35 |
| JPN vs SWE | In the second half, will Japan have more shots on target than Sweden? | derived Kalshi lambdas (SOT) | 0.352 | 0.352 | — | 35 |
| JPN vs SWE | Will Sweden be caught offside 2 or more times? | base rate + attacking tilt | 0.464 | 0.464 | — | 46 |
| JPN vs SWE | Will Japan win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.467 | 0.467 | — | 47 |
| JPN vs SWE | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.553 | 0.553 | — | 55 |
| JPN vs SWE | Will Sweden have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.359 | 0.359 | — | 36 |
| JPN vs SWE | Will Takefusa Kubo score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.215 | 0.215 | — | 21 |
| JPN vs SWE | Will Viktor Gyökeres score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.229 | 0.229 | — | 23 |
| TUN vs NED | Will Netherlands receive more cards than Tunisia? | base rate + underdog tilt | 0.297 | 0.297 | — | 30 |
| TUN vs NED | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.366 | 0.366 | — | 37 |
| TUN vs NED | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.776 | 0.776 | — | 78 |
| TUN vs NED | Will Tunisia commit more fouls than Netherlands? | base rate + favorite tilt | 0.631 | 0.631 | — | 63 |
| TUN vs NED | Will Tunisia score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.560 | 0.560 | — | 56 |
| TUN vs NED | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.413 | 0.405 | — | 41 |
| TUN vs NED | Will Tunisia score in the second half? | derived Kalshi team lambda | 0.381 | 0.381 | — | 38 |
| TUN vs NED | Will Ellyes Skhiri have at least 1 shot on target? | modeled from Kalshi team lambda | 0.295 | 0.295 | — | 30 |
| TUN vs NED | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.646 | 0.646 | — | 65 |
| TUN vs NED | Will Cody Gakpo score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.448 | 0.448 | — | 45 |
| PAR vs AUS | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| PAR vs AUS | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.323 | 0.323 | — | 32 |
| PAR vs AUS | Will Paraguay win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.457 | 0.457 | — | 46 |
| PAR vs AUS | Will Julio Enciso have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| PAR vs AUS | Will the second half have more total goals than the first half? | derived Kalshi totals | 0.374 | 0.374 | — | 37 |
| PAR vs AUS | Will Australia have more shots on target than Paraguay in the second half? | derived Kalshi lambdas (SOT) | 0.415 | 0.415 | — | 41 |
| PAR vs AUS | Will Paraguay be caught offside 2 or more times? | base rate + attacking tilt | 0.441 | 0.441 | — | 44 |
| PAR vs AUS | Will Australia commit more fouls than Paraguay? | base rate + favorite tilt | 0.525 | 0.525 | — | 52 |
| PAR vs AUS | Will Australia be caught offside 2 or more times? | base rate + attacking tilt | 0.451 | 0.451 | — | 45 |
| PAR vs AUS | Will Riley McGree have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| TUR vs USA | Will Folarin Balogun score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.304 | 0.304 | — | 30 |
| TUR vs USA | Will Türkiye be caught offside 2 or more times? | base rate + attacking tilt | 0.553 | 0.553 | — | 55 |
| TUR vs USA | Will the second half have more total goals than the first half? | derived Kalshi totals | 0.420 | 0.420 | — | 42 |
| TUR vs USA | Will Türkiye score the first goal of the game and United States score in the second half? | derived Kalshi lambdas | 0.260 | 0.260 | — | 26 |
| TUR vs USA | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| TUR vs USA | Will Orkun Kökçü score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.265 | 0.265 | — | 27 |
| TUR vs USA | Will United States commit more fouls than Türkiye? | base rate + favorite tilt | 0.462 | 0.462 | — | 46 |
| TUR vs USA | Will Türkiye have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.531 | 0.531 | — | 53 |
| TUR vs USA | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.507 | 0.507 | — | 51 |
| TUR vs USA | Will Türkiye win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.387 | 0.375 | — | 38 |
| NOR vs FRA | Will France score in the first half? | derived Kalshi team lambda | 0.568 | 0.568 | — | 57 |
| NOR vs FRA | Will Norway score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.410 | 0.410 | — | 41 |
| NOR vs FRA | Will there be 8 or more total shots on target? | derived from Kalshi total-goals | 0.612 | 0.612 | — | 61 |
| NOR vs FRA | Will France score in the second half? | derived Kalshi team lambda | 0.731 | 0.731 | — | 73 |
| NOR vs FRA | Will Norway commit more fouls than France? | base rate + favorite tilt | 0.559 | 0.559 | — | 56 |
| NOR vs FRA | In the second half, will Norway have more corner kicks than France? | Kalshi team-corners fit, 2H | 0.240 | 0.240 | — | 24 |
| NOR vs FRA | Will France have more shots on target than Norway in the second half? | derived Kalshi lambdas (SOT) | 0.669 | 0.669 | — | 67 |
| NOR vs FRA | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| NOR vs FRA | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.430 | 0.430 | — | 43 |
| NOR vs FRA | Will Norway win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.227 | 0.222 | — | 22 |
| SEN vs IRQ | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.650 | 0.650 | — | 65 |
| SEN vs IRQ | Will Mohanad Ali score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.256 | 0.256 | — | 26 |
| SEN vs IRQ | Will Senegal win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.703 | 0.706 | — | 71 |
| SEN vs IRQ | At halftime, will Iraq have more corner kicks than Senegal? | Kalshi team-corners fit, 1H | 0.138 | 0.138 | — | 14 |
| SEN vs IRQ | Will Iraq be caught offside 2 or more times? | base rate + attacking tilt | 0.420 | 0.420 | — | 42 |
| SEN vs IRQ | Will Iraq receive more cards than Senegal? | base rate + underdog tilt | 0.515 | 0.515 | — | 51 |
| SEN vs IRQ | Will Senegal have more shots on target than Iraq in the second half? | derived Kalshi lambdas (SOT) | 0.759 | 0.759 | — | 76 |
| SEN vs IRQ | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.339 | 0.339 | — | 34 |
| SEN vs IRQ | Will Iraq commit more fouls than Senegal? | base rate + favorite tilt | 0.654 | 0.654 | — | 65 |
| SEN vs IRQ | Will Sadio Mané have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.570 | 0.570 | — | 57 |
| CPV vs KSA | Will Cape Verde be caught offside 2 or more times? | base rate + attacking tilt | 0.434 | 0.434 | — | 43 |
| CPV vs KSA | Will Cape Verde commit more fouls than Saudi Arabia? | base rate + favorite tilt | 0.446 | 0.446 | — | 45 |
| CPV vs KSA | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.517 | 0.517 | — | 52 |
| CPV vs KSA | Will Saudi Arabia receive more cards than Cape Verde? | base rate + underdog tilt | 0.403 | 0.403 | — | 40 |
| CPV vs KSA | Will a penalty kick be awarded in the match? | base rate | 0.280 | 0.280 | — | 28 |
| CPV vs KSA | Will Saudi Arabia have more shots on target than Cape Verde in the second half? | derived Kalshi lambdas (SOT) | 0.365 | 0.365 | — | 37 |
| CPV vs KSA | Will Cape Verde win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.387 | 0.379 | — | 38 |
| CPV vs KSA | Will Cape Verde score in the second half? | derived Kalshi team lambda | 0.301 | 0.301 | — | 30 |
| CPV vs KSA | Will Ryan Mendes score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.245 | 0.245 | — | 24 |
| CPV vs KSA | Will Salem Al-Dawsari score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.164 | 0.164 | — | 16 |
| URU vs ESP | Will Uruguay commit more fouls than Spain? | base rate + favorite tilt | 0.596 | 0.596 | — | 60 |
| URU vs ESP | In the second half, will Uruguay have more shots on target than Spain? | derived Kalshi lambdas (SOT) | 0.182 | 0.182 | — | 18 |
| URU vs ESP | Will Dani Olmo have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.358 | 0.358 | — | 36 |
| URU vs ESP | Will Uruguay score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.345 | 0.345 | — | 34 |
| URU vs ESP | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.405 | 0.409 | — | 41 |
| URU vs ESP | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.497 | 0.497 | — | 50 |
| URU vs ESP | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.481 | 0.481 | — | 48 |
| URU vs ESP | Will there be 9 or more total corner kicks in the match? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| URU vs ESP | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| URU vs ESP | Will Darwin Núñez have at least 1 shot on target? | modeled from Kalshi team lambda | 0.632 | 0.632 | — | 63 |
| EGY vs IRN | Will the second half have 2 or more total goals? | derived Kalshi totals (2H lambda) | 0.219 | 0.219 | — | 22 |
| EGY vs IRN | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.630 | 0.630 | — | 63 |
| EGY vs IRN | Will Iran finish with more corner kicks than Egypt? | Kalshi team-corners fit | 0.305 | 0.305 | — | 31 |
| EGY vs IRN | Will Iran have more shots on target than Egypt in the second half? | derived Kalshi lambdas (SOT) | 0.367 | 0.367 | — | 37 |
| EGY vs IRN | Will Iran be caught offside 2 or more times? | base rate + attacking tilt | 0.499 | 0.499 | — | 50 |
| EGY vs IRN | Will there be 4 or more total cards shown? | base rate (cards) | 0.542 | 0.542 | — | 54 |
| EGY vs IRN | Will Egypt have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.771 | 0.771 | — | 77 |
| EGY vs IRN | Will Egypt win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.427 | 0.424 | — | 42 |
| EGY vs IRN | Will Mahmoud Trezeguet have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| EGY vs IRN | Will Mehdi Taremi have at least 1 shot on target? | modeled from Kalshi team lambda | 0.631 | 0.631 | — | 63 |
| New Zealand vs BEL | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.272 | 0.272 | — | 27 |
| New Zealand vs BEL | Will New Zealand have 2 or more shots on target in the second half? | derived Kalshi team lambda (SOT) | 0.204 | 0.204 | — | 20 |
| New Zealand vs BEL | Will New Zealand receive more cards than Belgium? | base rate + underdog tilt | 0.530 | 0.530 | — | 53 |
| New Zealand vs BEL | Will Youri Tielemans have at least 1 shot on target? | modeled from Kalshi team lambda | 0.503 | 0.503 | — | 50 |
| New Zealand vs BEL | Will Belgium have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.711 | 0.711 | — | 71 |
| New Zealand vs BEL | Will New Zealand score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.265 | 0.265 | — | 26 |
| New Zealand vs BEL | Will Belgium score in the second half? | derived Kalshi team lambda | 0.617 | 0.617 | — | 62 |
| New Zealand vs BEL | At halftime, will both teams have at least 1 shot on target? | derived Kalshi lambdas (SOT) | 0.416 | 0.416 | — | 42 |
| New Zealand vs BEL | Will New Zealand commit more fouls than Belgium? | base rate + favorite tilt | 0.677 | 0.677 | — | 68 |
| New Zealand vs BEL | Will Belgium receive at least 1 card in the second half? | base rate (cards) | 0.632 | 0.632 | — | 63 |
| CRO vs GHA | Will Croatia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.597 | 0.597 | — | 60 |
| CRO vs GHA | At halftime, will Croatia be winning? | Kalshi KXWC1H (de-vig 3-way) | 0.415 | 0.423 | — | 42 |
| CRO vs GHA | Will Croatia score in the second half? | derived Kalshi team lambda | 0.373 | 0.373 | — | 37 |
| CRO vs GHA | Will there be 9 or more total corner kicks? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| CRO vs GHA | Will Ghana be caught offside 2 or more times? | base rate + attacking tilt | 0.382 | 0.382 | — | 38 |
| CRO vs GHA | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| CRO vs GHA | Will Luka Sučić have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.310 | 0.310 | — | 31 |
| CRO vs GHA | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.625 | 0.625 | — | 62 |
| CRO vs GHA | Will Croatia have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.155 | 0.155 | — | 16 |
| CRO vs GHA | Will Antoine Semenyo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.632 | 0.632 | — | 63 |
| PAN vs ENG | Will Panama score the first goal of the game and England score in the second half? | derived Kalshi lambdas | 0.123 | 0.123 | — | 12 |
| PAN vs ENG | Will Harry Kane have at least 1 shot on target? | modeled from Kalshi team lambda | 0.796 | 0.796 | — | 80 |
| PAN vs ENG | Will José Fajardo have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| PAN vs ENG | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| PAN vs ENG | At halftime, will the match be tied? | Kalshi KXWC1H (de-vig 3-way) | 0.345 | 0.356 | — | 36 |
| PAN vs ENG | Will the match have 3 or more total goals? | Kalshi KXWCTOTAL direct | 0.593 | 0.593 | — | 59 |
| PAN vs ENG | Will there be 5 or more total corner kicks in the second half? | Kalshi corners fit, 2H share | 0.591 | 0.591 | — | 59 |
| PAN vs ENG | Will Panama score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.280 | 0.280 | — | 28 |
| PAN vs ENG | Will Panama commit more fouls than England? | base rate + favorite tilt | 0.673 | 0.673 | — | 67 |
| PAN vs ENG | Will there be 4 or more total shots on target in the second half? | derived from Kalshi total-goals | 0.735 | 0.735 | — | 74 |
| COD vs UZB | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.370 | 0.370 | — | 37 |
| COD vs UZB | Will Uzbekistan be caught offside 2 or more times? | base rate + attacking tilt | 0.505 | 0.505 | — | 51 |
| COD vs UZB | Will Uzbekistan commit more fouls than DR Congo? | base rate + favorite tilt | 0.494 | 0.494 | — | 49 |
| COD vs UZB | Will DR Congo win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.413 | 0.411 | — | 41 |
| COD vs UZB | Will Cédric Bakambu score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.491 | 0.491 | — | 49 |
| COD vs UZB | Will Uzbekistan have 5 or more corner kicks? | Kalshi KXWCTCORNERS fit | 0.438 | 0.438 | — | 44 |
| COD vs UZB | Will Eldor Shomurodov have at least 1 shot on target in the second half? | modeled from Kalshi team lambda | 0.421 | 0.421 | — | 42 |
| COD vs UZB | Will Uzbekistan have more shots on target than DR Congo in the second half? | derived Kalshi lambdas (SOT) | 0.334 | 0.334 | — | 33 |
| COD vs UZB | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| COD vs UZB | Will both teams have at least 1 shot on target in the second half? | derived Kalshi lambdas (SOT) | 0.819 | 0.819 | — | 82 |
| COL vs POR | Will Luis Díaz score a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.132 | 0.132 | — | 13 |
| COL vs POR | Will Gonçalo Ramos have at least 1 shot on target? | modeled from Kalshi team lambda | 0.593 | 0.593 | — | 59 |
| COL vs POR | Will Colombia win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.287 | 0.278 | — | 28 |
| COL vs POR | Will Colombia have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.191 | 0.191 | — | 19 |
| COL vs POR | Will Portugal have 4 or more shots on target? | derived Kalshi team lambda (SOT) | 0.331 | 0.331 | — | 33 |
| COL vs POR | Will there be 5 or more total corner kicks in the second half? | Kalshi corners fit, 2H share | 0.591 | 0.591 | — | 59 |
| COL vs POR | In the second half, will Colombia have more shots on target than Portugal? | derived Kalshi lambdas (SOT) | 0.303 | 0.303 | — | 30 |
| COL vs POR | Will Colombia be caught offside 2 or more times? | base rate + attacking tilt | 0.406 | 0.406 | — | 41 |
| COL vs POR | Will a penalty kick be awarded OR a red card be shown? | base rate | 0.360 | 0.360 | — | 36 |
| COL vs POR | Will both teams score AND the match have 3 or more total goals? | bivariate Poisson calibrated to Kalshi BTTS | 0.275 | 0.275 | — | 28 |
| ALG vs AUT | Will Marcel Sabitzer have at least 1 shot on target? | modeled from Kalshi team lambda | 0.551 | 0.551 | — | 55 |
| ALG vs AUT | Will Austria have 5 or more shots on target? | derived Kalshi team lambda (SOT) | 0.218 | 0.218 | — | 22 |
| ALG vs AUT | Will there be 9 or more total corner kicks? | Kalshi KXWCCORNERS fit | 0.620 | 0.620 | — | 62 |
| ALG vs AUT | Will Algeria win the match? | Kalshi KXWCGAME (de-vig 3-way) | 0.247 | 0.247 | — | 25 |
| ALG vs AUT | Will Algeria have 3 or more shots on target? | derived Kalshi team lambda (SOT) | 0.357 | 0.357 | — | 36 |
| ALG vs AUT | Will Austria receive more cards than Algeria? | base rate + underdog tilt | 0.356 | 0.356 | — | 36 |
| ALG vs AUT | Will Austria score more goals than Algeria in the second half? | derived Kalshi lambdas | 0.299 | 0.299 | — | 30 |
| ALG vs AUT | Will Austria score the first goal of the second half? | derived Kalshi lambdas | 0.396 | 0.396 | — | 40 |
| ALG vs AUT | Will Austria have more shots on target than Algeria in the second half? | derived Kalshi lambdas (SOT) | 0.482 | 0.482 | — | 48 |
| ALG vs AUT | Will Algeria commit more fouls than Austria? | base rate + favorite tilt | 0.525 | 0.525 | — | 52 |
| JOR vs ARG | Will a penalty kick be awarded OR a red card be shown in the match? | base rate | 0.360 | 0.360 | — | 36 |
| JOR vs ARG | Will Argentina have more shots on target than Jordan in the second half? | derived Kalshi lambdas (SOT) | 0.850 | 0.850 | — | 85 |
| JOR vs ARG | Will Jordan be caught offside 2 or more times? | base rate + attacking tilt | 0.375 | 0.375 | — | 37 |
| JOR vs ARG | Will Jordan commit more fouls than Argentina? | base rate + favorite tilt | 0.700 | 0.700 | — | 70 |
| JOR vs ARG | Will Argentina have at least 1 corner kick in the first half? | Kalshi team-corners fit, 1H | 0.971 | 0.971 | — | 97 |
| JOR vs ARG | Will the match have 2 or fewer total goals? | Kalshi KXWCTOTAL direct | 0.387 | 0.387 | — | 39 |
| JOR vs ARG | Will Jordan score at least 1 goal? | Kalshi KXWCTEAMTOTAL direct | 0.250 | 0.250 | — | 25 |
| JOR vs ARG | Will Argentina have 6 or more shots on target? | derived Kalshi team lambda (SOT) | 0.726 | 0.726 | — | 73 |
| JOR vs ARG | Will Mousa Al-Taamari score or assist a goal (excluding own goals)? | modeled from Kalshi team lambda | 0.166 | 0.166 | — | 17 |
| JOR vs ARG | Will Jordan score in the second half? | derived Kalshi team lambda | 0.200 | 0.200 | — | 20 |

---

# Session 2 — 2026-06-12 (afternoon review)

## Step 1: Calibration from settled results (CAN vs BIH, n=10)

Outcomes inferred from Brier scores (brier = (p − outcome)²):

| Question type | Submitted | Outcome | Hit |
|---|---|---|---|
| BiH more fouls than Canada | 57 | 1 | ✓ |
| Canada win | 53 | 0 | ✗ |
| BiH 5+ corners | 29 | 0 | ✓ |
| Penalty OR red card | 36 | 0 | ✓ |
| Halftime tied | 45 | 0 | ✗ |
| BiH score 2nd half | 39 | 0 | ✓ |
| Džeko 1+ SOT | 59 | 0 | ✗ |
| 4+ SOT 2nd half | 59 | 1 | ✓ |
| 2nd half 2+ goals | 38 | 0 | ✓ |
| Jonathan David scores | 32 | 0 | ✓ |

Average submitted 44.7 vs hit rate 20% (2/10). Direction: mild overconfidence on mid-range
"event happens" props (player SOT, match winner). Sample = one match, so only a modest
shade-down (~3–4 pts) would be justified on 45–65 "yes" props — no new submissions were
needed this session, so no corrections were applied to fresh picks. (To be revisited once
more matches settle.)

## Step 2/5: Coverage check

- 69 matches with open markets; 687 open markets total (66×10 + 3×9 — one AUS market in
  each of AUS vs TUR / USA vs AUS / PAR vs AUS closed since submission).
- All 687 open markets verified to already carry a prediction (diffed full market dump
  against the 687 open predictions). **Zero NEW submissions required.**

## Step 1b: Odds-movement review (matches closing within ~40h, checked vs current Kalshi/books)

| Match | Question | Source | Raw implied | De-vigged | Bias adj | Submitted | Action |
|---|---|---|---|---|---|---|---|
| USA vs PAR | Julio Enciso 1+ SOT in 2nd half | News: Enciso ruled OUT (thigh/quad, stretchered off Jun 6 friendly) | ~0 (won't play) | — | — | 35 → **4** | UPDATED |
| USA vs PAR | United States win | Kalshi 50/29/23 → de-vig 49.0 | 0.50 | 0.490 | — | 49 | SKIPPED (Δ0) |
| USA vs PAR | 3+ total goals | FanDuel O2.5 +130/U −166 → de-vig 41.1 | 0.435 | 0.411 | — | 41 | SKIPPED (Δ0) |
| USA vs PAR | Balogun 1+ SOT | Lineups: Balogun confirmed projected starter | — | — | — | 66 | SKIPPED |
| USA vs PAR | other 6 props (offsides, corners, cards, HT tie, PAR 2H goal, USA-first-goal combo) | no liquid market; no news | — | — | — | — | SKIPPED |
| QAT vs SUI | all 10 props | Kalshi SUI 81 / draw 14 / QAT 7; O2.5 = 57% — consistent with submitted (QAT score ≥1 @ 40, BTTS&3+ @ 39); no SUI-win market held | — | — | — | — | SKIPPED |
| BRA vs MAR | Brazil win | Prediction markets 59.0/24.5/16.7 (already de-vigged) | 0.590 | 0.589 | — | 58 | SKIPPED (Δ1) |
| BRA vs MAR | other 9 props | no liquid market; no news | — | — | — | — | SKIPPED |
| Haiti vs SCO | all 10 props | bet365 SCO −225 / draw +350 / HAI +525 → de-vig 64/21/15; no SCO-win market held; Haiti score ≥1 @ 57 within tolerance | — | — | — | — | SKIPPED |
| AUS vs TUR | Australia win | bet365 TUR −125 / draw +250 / AUS +350 → de-vig AUS 20.9 | 0.222 | 0.209 | — | 17 | SKIPPED (Δ3.9 < 5) |
| AUS vs TUR | other 8 props | no liquid market; no news | — | — | — | — | SKIPPED |
| All other 64 matches (637 markets) | — | submitted ~6–13h ago from de-vigged Kalshi/book prices; injury sweep found no news touching any held player prop (Rodrygo/Ekitike/Simons/Fermín/Karl/Timber have no markets here and were already priced in) | — | — | — | — | SKIPPED |

**Session actions: 1 UPDATED, 686 SKIPPED, 0 NEW. All 687 open markets have a submitted prediction.**

Sources: Kalshi KXWCGAME (USA-PAR, QAT-SUI), SI/MSN Kalshi-Polymarket previews, FanDuel,
bet365 via Covers/Racing Post, ESPN/Yahoo/SI injury trackers (Enciso ruled out; Balogun starting).

---

# Session 3 — 2026-06-12 (evening, post USA-PAR settlement)

## Step 1: Refreshed calibration — now 17 settled (CAN-BIH ×10, USA-PAR ×7)

USA vs PAR settled and dropped off the open board (10 markets → settled). Outcomes
decoded from Brier scores:

| Match | Question | Sub | Outcome |
|---|---|---|---|
| USA-PAR | Paraguay score in 2nd half | 41 | YES |
| USA-PAR | USA caught offside 2+ | 54 | YES |
| USA-PAR | Halftime tied | 45 | NO |
| USA-PAR | 4+ total cards | 54 | YES |
| USA-PAR | Balogun 1+ SOT | 66 | YES |
| USA-PAR | 3+ total goals | 41 | YES |
| USA-PAR | USA 1st goal AND PAR 2H score | 22 | YES |

(Note: the Enciso "1+ SOT 2nd half" prop I cut to 4 after his injury did not appear in
settled results — voided/removed, no Brier impact.)

### Calibration by question type (all 17 settled)

| Question type | n | Avg sub | Hit rate | Direction of error |
|---|---|---|---|---|
| Halftime tied | 2 | 45 | 0% (0/2) | **Over** — shade HT-tie DOWN ~5pt |
| Match winner (favorite) | 1 | 53 | 0% | Over (Canada lost) — small n |
| Player 1+ SOT | 2 | 63 | 50% (Balogun Y, Džeko N) | Mixed / unbiased |
| Total goals & 2H-goal overs | 4 | 40 | 50% (2/4) | Mixed — high variance |
| Foul/card/corner/offside props | 5 | 47 | 60% (3/5) | ≈ Calibrated |
| Score-combo (1st goal + 2H) | 1 | 22 | 100% | Under — small n |

**Read:** the two settled matches were opposite archetypes — CAN-BIH dull/low-event
(2/10 "yes"), USA-PAR wild/high-event (6/7 "yes"). That's match-level variance, not a
stable directional bias. The **one repeatable signal is halftime-tied: 0/2, overestimated**
— worth shading down ~5pt on future HT-tie submissions. No broad favorite/draw correction
is justified at n=2 matches.

## Step 1b / Step 5: Coverage + movement check

- 68 open matches, **677 open markets, all 677 carry a prediction** (full dump diffed
  against fresh predictions — zero gaps).
- Most imminent: QAT vs SUI (closes 2026-06-13 21:30Z). Re-checked: bet365 SUI −334,
  SUI heavy favorite — consistent with held props (QAT score ≥1 @ 40, BTTS&3+ @ 39).
  No line move >5pp; no roster news affecting held markets (Afif/Xhaka/Embolo all expected
  to start). BRA-MAR, Haiti-SCO, AUS-TUR re-confirmed unchanged from Session 2.
- **0 NEW, 0 UPDATED this session.** No corrections applied because no new markets were
  submitted; HT-tie shade-down logged for future submissions.

**All open markets have a submitted prediction. Goal condition satisfied.**

Sources: Kalshi/bet365 via ESPN, Squawka, Lineups.com, Sports Mole (QAT-SUI previews).

---

# Session 4 — 2026-06-13

## Step 1: Calibration refreshed — now 20 settled (CAN-BIH ×10, USA-PAR ×10)

USA-PAR fully settled since Session 3 (was 7/10). Three newly-decoded outcomes:

| Match | Question | Sub | Brier | Outcome |
|---|---|---|---|---|
| USA-PAR | United States win the match | 49 | 0.2601 | YES |
| USA-PAR | Julio Enciso 1+ SOT (2nd half) | 4 | 0.0016 | NO (injury cut to 4 paid off) |
| USA-PAR | Paraguay more corners than USA | 31 | 0.0961 | NO |

### Calibration by question type (all 20 settled, avg Brier 0.210)

| Question type | n | Avg sub | Hit rate | Direction → correction |
|---|---|---|---|---|
| Halftime tied | 2 | 45 | 0% (0/2) | **Over** — shade HT-tie DOWN ~5pt (repeatable) |
| Match winner | 2 | 51 | 50% (CAN N, USA Y) | ≈ calibrated; mild fav over-conf, small n |
| Player 1+ SOT | 3 | 43 | mixed (Balogun Y, Džeko N, Enciso N) | generic 59-default slightly high → trim toward 55 |
| Goal-over / team-score 2H | 6 | ~40 | 50% (3/6 YES) | mild **under** → shade goal-overs UP ~+3 |
| Foul/card/corner/offside | 6 | ~47 | well-calibrated | no change |
| Score-combo (1st goal + 2H) | 1 | 22 | YES | under, n=1 ignore (variance) |

**Read:** stable signals = HT-tied overestimated (0/2) and goal-over markets mildly
underestimated. Both logged for future submissions. No broad favorite/draw shift justified
at n=2 matches.

## Step 1b / Step 5: Coverage + movement check

- 68 open matches, **677 open markets, all 677 carry a prediction** (full predictions dump
  diffed against the live market list — zero gaps; 677 = 65×10 + 3×9).
- **0 NEW** required (nothing unpredicted), **0 UPDATED** (no live line moved >5pp).
- Re-checked the four matches closest to kickoff against current Kalshi/book lines:

| Match | Question | Source | Raw implied | De-vigged | Bias adj | Submitted | Action |
|---|---|---|---|---|---|---|---|
| QAT vs SUI | (props only; no win mkt) | Kalshi: SUI 81 / draw 14 / QAT 7 | — | SUI .794 / draw .137 / QAT .069 | — | held | SKIPPED |
| QAT vs SUI | Qatar score ≥1 goal | held vs SUI-dominant low-scoring | — | — | — | 40 | SKIPPED |
| BRA vs MAR | Brazil win the match | bet365 −175 / BetOnline −145 (3-way devig) | .636/.592 | ~.59 | — | 58 | SKIPPED (~1pp) |
| BRA vs MAR | BTTS & 3+ goals | book under-2.5 lean (−123) | — | ~.40 | — | 43 | SKIPPED |
| Haiti vs SCO | (props only; no win mkt) | Kalshi: SCO 62 / draw 22 / HAI 17 | — | SCO .614/draw .218/HAI .168 | — | held | SKIPPED |
| Haiti vs SCO | Haiti score ≥1 goal | Kalshi team-total (orig) | — | — | — | 57 | SKIPPED |
| AUS vs TUR | Australia win the match | TUR 4/6 (.60), AUS +450 (.182), 3-way devig | .182 | ~.175 | — | 17 | SKIPPED (<1pp) |

No roster news touching held player props (Afif/Xhaka, McTominay/Nazon, Yıldız/McGree all
expected to start; no fresh injuries). All four imminent matches confirmed within the 5pp
threshold → no updates.

**Session actions: 0 NEW, 0 UPDATED, all 677 open markets carry a prediction. Goal condition satisfied.**

Sources: Kalshi KXWCGAME (QAT-SUI, Haiti-SCO), bet365 / BetOnline / ESPN / Covers / Racing
Post / Squawka previews (BRA-MAR, AUS-TUR), Yahoo/FOX injury & lineup trackers.

---

# Session 5 — 2026-06-13 (bias calibration from first 30 settled results)

## Step 1 — Bias analysis (30 settled predictions, mean Brier 0.2415)

Outcomes back-solved from each Brier score (brier = (p−outcome)²).

| Question type | n | Avg submitted | Hit rate | Error direction | Action |
|---|---|---|---|---|---|
| Player "1+ shot on target" (my modeled props) | 5 | 59% | 20% (1/5) | **Overconfident** | shade DOWN −5pp |
| Team SOT count/threshold (derived) | 4 | 48% | 100% (4/4) | **Underconfident** | shade UP +5pp |
| Team to score (2H / 1+ goal) | 3 | 40% | 67% | mild under | none (market-anchored) |
| Halftime tied (Kalshi 3-way) | 2 | 45% | 0% | mild over | none (market-anchored, n=2) |
| Fouls "more than" (favorite model) | 2 | 63% | 100% | well-calibrated | none |
| Corner thresholds | 2 | 30% | 0% | well-calibrated | none |
| Match winner (Kalshi de-vig) | 2 | 51% | 50% | neutral | none |
| Offside 2+ / cards | 2 ea | ~60% | split | neutral | none |
| Penalty/red, BTTS&3+, anytime goalscorer | 1 ea | ~36% | 0% | well-calibrated | none |

Rationale: the two shot-on-target buckets are the only consistent, mechanistically-coherent signal — my SOT model was internally inconsistent (too generous to named individuals, too stingy on team aggregates). These are MY modeled outputs, not Kalshi prices, so correcting them does not override market data. Correction capped at ±5pp (player floor 10, team ceiling 92) given the small sample (n=4–5). Everything else stayed market-anchored.

## Step 1b — Open-prediction line-move review
Coverage check: 657/657 open markets already have predictions (zero gaps; nothing NEW to submit).
Imminent matches checked vs current books (June 14 kickoffs):
- Haiti vs SCO: market Scotland ~62%, Haiti-to-score ~57% — matches submission (Haiti score 1+ = 57). No >5pp move → SKIPPED.
- AUS vs TUR: de-vigged Australia win ≈18% vs submitted 17. No move → SKIPPED.

## Step 5/6 — Updates applied this session (117 total)

| Match | Question | Bucket | Old | New | Action |
|---|---|---|---|---|---|
| ALG | vs | PLAYER | 55 | 50 | UPDATED |
| NED | vs | PLAYER | 44 | 39 | UPDATED |
| ECU | vs | PLAYER | 39 | 34 | UPDATED |
| NED | vs | PLAYER | 67 | 62 | UPDATED |
| Curacao | vs | PLAYER | 45 | 40 | UPDATED |
| UZB | vs | PLAYER | 56 | 51 | UPDATED |
| SWE | vs | PLAYER | 30 | 25 | UPDATED |
| CRO | vs | PLAYER | 63 | 58 | UPDATED |
| New | Zealand | PLAYER | 55 | 50 | UPDATED |
| GHA | vs | PLAYER | 67 | 62 | UPDATED |
| USA | vs | PLAYER | 72 | 67 | UPDATED |
| SUI | vs | PLAYER | 25 | 20 | UPDATED |
| GHA | vs | PLAYER | 55 | 50 | UPDATED |
| PAN | vs | PLAYER | 50 | 45 | UPDATED |
| JOR | vs | PLAYER | 45 | 40 | UPDATED |
| ECU | vs | PLAYER | 45 | 40 | UPDATED |
| CZE | vs | PLAYER | 63 | 58 | UPDATED |
| BEL | vs | PLAYER | 50 | 45 | UPDATED |
| Haiti | vs | PLAYER | 59 | 54 | UPDATED |
| BIH | vs | PLAYER | 64 | 59 | UPDATED |
| CAN | vs | PLAYER | 59 | 54 | UPDATED |
| Curacao | vs | PLAYER | 30 | 25 | UPDATED |
| New | Zealand | PLAYER | 50 | 45 | UPDATED |
| CIV | vs | PLAYER | 30 | 25 | UPDATED |
| PAN | vs | PLAYER | 80 | 75 | UPDATED |
| URU | vs | PLAYER | 36 | 31 | UPDATED |
| RSA | vs | PLAYER | 55 | 50 | UPDATED |
| AUT | vs | PLAYER | 59 | 54 | UPDATED |
| TUR | vs | PLAYER | 50 | 45 | UPDATED |
| JOR | vs | PLAYER | 59 | 54 | UPDATED |
| NED | vs | PLAYER | 66 | 61 | UPDATED |
| AUS | vs | PLAYER | 31 | 26 | UPDATED |
| RSA | vs | PLAYER | 64 | 59 | UPDATED |
| ENG | vs | PLAYER | 50 | 45 | UPDATED |
| MAR | vs | PLAYER | 59 | 54 | UPDATED |
| SEN | vs | PLAYER | 57 | 52 | UPDATED |
| TUR | vs | PLAYER | 55 | 50 | UPDATED |
| PAR | vs | PLAYER | 55 | 50 | UPDATED |
| EGY | vs | PLAYER | 63 | 58 | UPDATED |
| PAN | vs | PLAYER | 55 | 50 | UPDATED |
| URU | vs | PLAYER | 63 | 58 | UPDATED |
| GER | vs | PLAYER | 45 | 40 | UPDATED |
| SCO | vs | PLAYER | 55 | 50 | UPDATED |
| Haiti | vs | PLAYER | 74 | 69 | UPDATED |
| ESP | vs | PLAYER | 55 | 50 | UPDATED |
| PAN | vs | PLAYER | 55 | 50 | UPDATED |
| EGY | vs | PLAYER | 55 | 50 | UPDATED |
| SUI | vs | PLAYER | 59 | 54 | UPDATED |
| SCO | vs | PLAYER | 55 | 50 | UPDATED |
| ARG | vs | PLAYER | 55 | 50 | UPDATED |
| CRO | vs | PLAYER | 31 | 26 | UPDATED |
| TUN | vs | PLAYER | 30 | 25 | UPDATED |
| FRA | vs | PLAYER | 59 | 54 | UPDATED |
| TUN | vs | PLAYER | 30 | 25 | UPDATED |
| BEL | vs | PLAYER | 50 | 45 | UPDATED |
| AUT | vs | PLAYER | 59 | 54 | UPDATED |
| COL | vs | PLAYER | 59 | 54 | UPDATED |
| TUN | vs | PLAYER | 59 | 54 | UPDATED |
| SUI | vs | PLAYER | 42 | 37 | UPDATED |
| POR | vs | PLAYER | 38 | 33 | UPDATED |
| COD | vs | PLAYER | 42 | 37 | UPDATED |
| BRA | vs | PLAYER | 59 | 54 | UPDATED |
| ENG | vs | PLAYER | 56 | 51 | UPDATED |
| COL | vs | PLAYER | 59 | 54 | UPDATED |
| SUI | vs | PLAYER | 59 | 54 | UPDATED |
| ENG | vs | PLAYER | 63 | 58 | UPDATED |
| MEX | vs | PLAYER | 55 | 50 | UPDATED |
| IRN | vs | PLAYER | 48 | 43 | UPDATED |
| CZE | vs | PLAYER | 72 | 67 | UPDATED |
| CAN | vs | PLAYER | 57 | 52 | UPDATED |
| POR | vs | PLAYER | 59 | 54 | UPDATED |
| ARG | vs | PLAYER | 55 | 50 | UPDATED |
| SUI | vs | TEAM | 64 | 69 | UPDATED |
| IRN | vs | TEAM | 62 | 67 | UPDATED |
| ENG | vs | TEAM | 61 | 66 | UPDATED |
| CPV | vs | TEAM | 52 | 57 | UPDATED |
| New | Zealand | TEAM | 42 | 47 | UPDATED |
| URU | vs | TEAM | 69 | 74 | UPDATED |
| KSA | vs | TEAM | 67 | 72 | UPDATED |
| ENG | vs | TEAM | 70 | 75 | UPDATED |
| CRO | vs | TEAM | 16 | 21 | UPDATED |
| URU | vs | TEAM | 38 | 43 | UPDATED |
| PAN | vs | TEAM | 45 | 50 | UPDATED |
| COD | vs | TEAM | 82 | 87 | UPDATED |
| IRQ | vs | TEAM | 30 | 35 | UPDATED |
| FRA | vs | TEAM | 24 | 29 | UPDATED |
| EGY | vs | TEAM | 77 | 82 | UPDATED |
| GER | vs | TEAM | 21 | 26 | UPDATED |
| New | Zealand | TEAM | 71 | 76 | UPDATED |
| ECU | vs | TEAM | 76 | 81 | UPDATED |
| GER | vs | TEAM | 71 | 76 | UPDATED |
| ARG | vs | TEAM | 42 | 47 | UPDATED |
| New | Zealand | TEAM | 20 | 25 | UPDATED |
| CAN | vs | TEAM | 75 | 80 | UPDATED |
| ALG | vs | TEAM | 22 | 27 | UPDATED |
| AUT | vs | TEAM | 72 | 77 | UPDATED |
| ENG | vs | TEAM | 67 | 72 | UPDATED |
| FRA | vs | TEAM | 25 | 30 | UPDATED |
| BRA | vs | TEAM | 25 | 30 | UPDATED |
| TUN | vs | TEAM | 78 | 83 | UPDATED |
| COL | vs | TEAM | 33 | 38 | UPDATED |
| ARG | vs | TEAM | 32 | 37 | UPDATED |
| NED | vs | TEAM | 78 | 83 | UPDATED |
| POR | vs | TEAM | 22 | 27 | UPDATED |
| JOR | vs | TEAM | 73 | 78 | UPDATED |
| POR | vs | TEAM | 25 | 30 | UPDATED |
| ALG | vs | TEAM | 36 | 41 | UPDATED |
| URU | vs | TEAM | 59 | 64 | UPDATED |
| ECU | vs | TEAM | 52 | 57 | UPDATED |
| NED | vs | TEAM | 73 | 78 | UPDATED |
| COL | vs | TEAM | 19 | 24 | UPDATED |
| NOR | vs | TEAM | 34 | 39 | UPDATED |
| RSA | vs | TEAM | 45 | 50 | UPDATED |
| GHA | vs | TEAM | 79 | 84 | UPDATED |
| FRA | vs | TEAM | 13 | 18 | UPDATED |
| SCO | vs | TEAM | 52 | 57 | UPDATED |
| BRA | vs | TEAM | 55 | 60 | UPDATED |

All other open predictions (540 markets): SKIPPED — already submitted, market-anchored, no >5pp move and outside the two bias-corrected buckets.

---

# Session 6 — 2026-06-13 (offside bias correction from 40 settled results)

## Step 1 — Bias analysis refreshed (now 40 settled, +10 from BRA-MAR since Session 5)

Outcomes back-solved from each Brier score (brier = (p−outcome)²). The new BRA-MAR
block added one clean, actionable signal that Session 5 (n=30) lacked the sample to act on:

| Question type | n settled | Avg submitted | Hit rate | Direction | Action this session |
|---|---|---|---|---|---|
| **Caught offside 2+ times** | 3 | ~59% | 33% (USA 54✓, BRA 58✗, SUI 66✗) | **Overestimated at the high end** | shade DOWN values ≥55 |
| Player "1+ SOT" | 5 | ~59% | ~25% | over (already corrected S5) | none (S5 −5pp stands) |
| Team SOT count/threshold | 4 | ~48% | 100% | under (already corrected S5) | none (S5 +5pp stands) |
| Halftime tied | 3 | ~44% | 33% | regressed to calibrated (was 0/2, now 1/3 after BRA-MAR HT tie) | none |
| Match winner (favorite, Kalshi) | 3 | ~53% | 33% | mild over, but market-anchored | none (don't override Kalshi) |
| Fouls / cards "more than" | mixed | mixed | ~50-67% | calibrated | none |

Rationale for offside-only action: the miss is **concentrated in high submissions** — the one
value at 54 (USA) HIT, while 58 and 66 both missed. So I shade DOWN only predictions ≥55
(−8pp for ≥60, −6pp for 55–59) and leave ≤54 untouched (the 54 datapoint validated that band).
Offside props are MY base-rate+tilt model, not Kalshi prices, so correcting them does not override market data. True per-team base rate P(offside 2+) ≈ 0.50 (Poisson, mean ~1.7), so pulling the inflated highs toward ~50–60 is also independently coherent.

## Step 1b — Open-prediction line-move review (imminent matches)
Coverage check: **657/657 open markets carry a prediction** (computed: 63 matches×10 + 3 matches×9 [AUS-TUR, USA-AUS, PAR-AUS] = 657; my open predictions = 697 total − 40 settled = 657). Zero gaps; nothing NEW to submit.
- **Haiti vs SCO** (6/14 01:00Z): current books Scotland ~61% de-vig, draw ~20%, Haiti ~19%; Haiti-to-score ~57%, O/U 2.5 (slight over lean). Matches submissions (Haiti score 1+ = 57, tied-at-HT = 41). No >5pp move → SKIPPED.
- **AUS vs TUR** (6/14 04:00Z): Türkiye favored (~-145), Australia +420 → de-vig Australia win ≈18% vs submitted 17. No move → SKIPPED.

## Step 5/6 — Updates applied this session (17 total, all "offside 2+ times")

| Match (team) | Question | Bucket | Old | New | Action |
|---|---|---|---|---|---|
| GER vs Curacao | Will Germany be caught offside 2+? | OFFSIDE | 81 | 73 | UPDATED |
| ESP vs CPV | Will Spain be caught offside 2+? | OFFSIDE | 71 | 63 | UPDATED |
| POR vs COD | Will Portugal be caught offside 2+? | OFFSIDE | 68 | 60 | UPDATED |
| IRQ vs NOR | Will Norway be caught offside 2+? | OFFSIDE | 68 | 60 | UPDATED |
| GER vs CIV | Will Germany be caught offside 2+? | OFFSIDE | 62 | 54 | UPDATED |
| KSA vs URU | Will Uruguay be caught offside 2+? | OFFSIDE | 61 | 53 | UPDATED |
| ARG vs ALG | Will Argentina be caught offside 2+? | OFFSIDE | 61 | 53 | UPDATED |
| FRA vs SEN | Will France be caught offside 2+? | OFFSIDE | 60 | 52 | UPDATED |
| ARG vs ALG | Will Algeria be caught offside 2+? | OFFSIDE | 58 | 52 | UPDATED |
| BEL vs EGY | Will Belgium be caught offside 2+? | OFFSIDE | 58 | 52 | UPDATED |
| NED vs JPN | Will Netherlands be caught offside 2+? | OFFSIDE | 57 | 51 | UPDATED |
| SUI vs BIH | Will Switzerland be caught offside 2+? | OFFSIDE | 57 | 51 | UPDATED |
| CZE vs RSA | Will Czechia be caught offside 2+? | OFFSIDE | 57 | 51 | UPDATED |
| NED vs SWE | Will Netherlands be caught offside 2+? | OFFSIDE | 57 | 51 | UPDATED |
| AUS vs TUR | Will Türkiye be caught offside 2+? | OFFSIDE | 55 | 49 | UPDATED |
| MEX vs KOR | Will Mexico be caught offside 2+? | OFFSIDE | 55 | 49 | UPDATED |
| NED vs JPN | Will Japan be caught offside 2+? | OFFSIDE | 55 | 49 | UPDATED |

**Session actions: 0 NEW, 17 UPDATED, 640 SKIPPED. All 657 open markets carry a prediction; goal condition satisfied.** Offside predictions ≤54 (39 markets) left unchanged — already at/below base rate and consistent with the USA 54✓ datapoint.
