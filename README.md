# Best Counter-Strike Players of All Time by KPR
This project ranks Counter-Strike (Counter-Strike, Counter-Strike: Global Offensive, and Counter-Strike 2) players across 2004 to 2025 by building a yearly performance model based on KPR. For each year, a list of prize-pooled tournaments was compiled, and player KPR data was gathered where available. Players were included only if they had data from at least two tournaments and if the combined prize pool of those tournaments was at least twice that year's average tournament prize pool. A prize-pool-weighted mean KPR was then calculated for each player, with missing tournament values imputed using the mean KPR from the relevant event. Each qualified player's Adjusted Weighted KPR was then converted into a yearly z-score, measuring how far that player sat above or below the average eligible player in that season. That z-score was subsequently rescaled with a field-size correction factor based on Blom's approximation to the expected maximum of a standard normal sample of size N, implemented as ```NORM.S.INV((N-0.375)/(N+0.25))```. The correction used the median yearly player count in the full dataset as the reference field and the observed number of eligible players in the season as the comparison field. This step was intended to account for the fact that smaller player pools naturally produce less extreme top-end z-scores than larger ones, making yearly Performance Scores more comparable across eras. The resulting yearly value, called Performance Score, measures how strongly a player performed relative to his peers in that year. Final all-time totals are calculated by summing only positive yearly Performance Scores, so the ranking reflects the accumulation of standout seasons rather than penalizing weaker ones.

## 2025 List
1. 🇷🇺 **donk**: 10.4
2. 🇫🇷 **ZywOo**: 7.77
3. 🇷🇺 **m0NESY**: 6.52
4. 🇷🇺 **sh1ro**: 5.17
5. 🇹🇷 **XANTARES**: 4.99
6. 🇹🇷 **Wicadia**: 4.27
7. 🇷🇺 **kyousuke**: 4.2
8. 🇲🇳 **senzu**: 4.13
9. 🇪🇪 **ropz**: 4.12
10. 🇧🇦 **NiKo**: 3.82
11. 🇰🇿 **molodoy**: 3.62
12. 🇮🇱 **Spinx**: 3.24
13. 🇺🇸 **ELiGE**: 3.22
14. 🇨🇦 **Twistzz**: 3.17
15. 🇸🇰 **frozen**: 3.16
16. 🇸🇪 **REZ**: 2.94
17. 🇲🇳 **910**: 2.87
18. 🇧🇷 **kscerato**: 2.81
19. 🇨🇿 **PR**: 2.7
20. 🇺🇦 **B1t**: 2.61
21. 🇭🇺 **torzsi**: 2.57
22. 🇹🇷 **woxic**: 2.23
23. 🇷🇴 **iM**: 2.16
24. 🇮🇱 **Nertz**: 1.84
25. 🇺🇦 **w0nderful**: 1.76

## All Time List (2004 - 2025)
1. 🇺🇦 **s1mple**: 63.51
2. 🇫🇷 **ZywOo**: 59.8
3. 🇧🇦 **NiKo**: 58.18
4. 🇸🇪 **f0rest**: 52.54
5. 🇩🇰 **dev1ce**: 45.12
6. 🇸🇪 **GeT_RiGhT**: 40.87
7. 🇺🇸 **ELiGE**: 34.08
8. 🇪🇪 **ropz**: 32.67
9. 🇵🇱 **neo**: 31.38
10. 🇧🇷 **coldzera**: 29.71
11. 🇷🇺 **sh1ro**: 27.99
12. 🇷🇺 **m0NESY**: 25.95
13. 🇷🇺 **electroNic**: 25.77
14. 🇷🇺 **donk**: 25.55
15. 🇫🇷 **kennyS**: 24.44
16. 🇩🇰 **dupreeh**: 24.19
17. 🇨🇦 **Twistzz**: 22.84
18. 🇹🇷 **XANTARES**: 22.25
19. 🇧🇷 **fer**: 21.56
20. 🇺🇦 **Edward**: 20.61
21. 🇧🇦 **huNter**: 19.87
22. 🇫🇷 **shox**: 19.14
23. 🇩🇰 **Magisk**: 18.31
24. 🇩🇰 **blameF**: 18.21
25. 🇱🇻 **broky**: 18.01

## Feedback
I'm looking for ways to improve this model, even if slightly, so if you have an idea for how I could do that, let me know. I'm especially interested in any ways of obtaining KPR data from between 2001 and 2003, or any other player-specific performance data.
