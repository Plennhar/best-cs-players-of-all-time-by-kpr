# Best Counter-Strike Players of All Time by KPR
This project ranks Counter-Strike players across 2004 to 2025 by building a yearly performance model based on KPR. For each year, a list of prize-pooled tournaments was compiled, and player KPR data was gathered where available. Players were included only if they had data from at least two tournaments and if the combined prize pool of those tournaments was at least twice that year's average tournament prize pool. A prize-pool-weighted mean KPR was then calculated for each player, with missing tournament values imputed using the mean KPR from the relevant event. Each qualified player's Adjusted Weighted KPR was then transformed into a bounded yearly Performance Score by scaling above-average seasons relative to that season's average qualified player, with the year's best value set to 100 and the yearly average set to 0. This produces a yearly scale where 0 represents an average season and higher values represent increasingly strong above-average performance. Final all-time totals are then calculated with a squared-sum method, using the sum of squared yearly Performance Scores rather than a simple linear sum. This approach gives extra weight to truly elite peak seasons while still rewarding repeated high-level play, creating a more balanced measure of greatness across both dominance and longevity. The squared-sum method was chosen to reflect the assumption that four Performance Score 50 seasons should be valued the same as one Performance Score 100 season. The resulting total is then divided by 100 to place the final rating on a more intuitive scale.

## 2025 List
Place | Country | Nickname | Score
:---: | :---: | :--- | :---:
1 | 🇷🇺 | donk | 100
2 | 🇫🇷 | ZywOo | 55.85
3 | 🇷🇺 | m0NESY | 39.25
4 | 🇷🇺 | sh1ro | 24.69
5 | 🇹🇷 | XANTARES | 23.04
6 | 🇹🇷 | Wicadia | 16.85
7 | 🇷🇺 | kyousuke | 16.28
8 | 🇲🇳 | senzu | 15.74
9 | 🇪🇪 | ropz | 15.67
10 | 🇧🇦 | NiKo | 13.52
11 | 🇰🇿 | molodoy | 12.13
12 | 🇮🇱 | Spinx | 9.72
13 | 🇺🇸 | ELiGE | 9.59
14 | 🇨🇦 | Twistzz | 9.3
15 | 🇸🇰 | frozen | 9.22
16 | 🇸🇪 | REZ | 8.01
17 | 🇲🇳 | 910 | 7.64
18 | 🇧🇷 | kscerato | 7.3
19 | 🇨🇿 | PR | 6.74
20 | 🇺🇦 | B1t | 6.3
21 | 🇭🇺 | torzsi | 6.12
22 | 🇹🇷 | woxic | 4.62
23 | 🇷🇴 | iM | 4.31
24 | 🇮🇱 | Nertz | 3.14
25 | 🇺🇦 | w0nderful | 2.86

## All Time List (2005 - 2025)
Place | Country | Nickname | Score | 1st place | 2nd place | 3rd place | Years above average
:---: | :---: | :--- | :---: | :---: | :---: | :---: | :---:
1 | 🇸🇪 | f0rest | 773.25 | 4 | 1 | 3 | 18
2 | 🇸🇪 | GeT_RiGhT | 637.8 | 3 | 2 | 1 | 12
3 | 🇺🇦 | s1mple | 600.39 | 4 | 1 | 1 | 12
4 | 🇫🇷 | ZywOo | 492.79 | 2 | 5 | 0 | 9
5 | 🇵🇱 | neo | 418.38 | 1 | 2 | 0 | 11
6 | 🇧🇦 | NiKo | 409.07 | 0 | 2 | 2 | 13
7 | 🇩🇰 | dev1ce | 375.9 | 0 | 1 | 1 | 13
8 | 🇧🇷 | coldzera | 312.43 | 2 | 0 | 0 | 10
9 | 🇷🇺 | donk | 208.27 | 2 | 0 | 0 | 5
10 | 🇺🇦 | Edward | 198.24 | 0 | 1 | 0 | 10
11 | 🇺🇸 | ELiGE | 188.36 | 0 | 0 | 0 | 11
12 | 🇫🇷 | kennyS | 178.74 | 0 | 0 | 0 | 10
13 | 🇸🇪 | olofmeister | 171.05 | 1 | 0 | 0 | 7
14 | 🇸🇪 | dsn | 170.69 | 0 | 1 | 0 | 7
15 | 🇧🇷 | fer | 155.62 | 0 | 0 | 0 | 7
16 | 🇩🇰 | dupreeh | 155.6 | 0 | 0 | 1 | 11
17 | 🇪🇪 | ropz | 152.86 | 0 | 1 | 0 | 9
18 | 🇸🇪 | flusha | 148.71 | 1 | 0 | 0 | 7
19 | 🇫🇷 | shox | 148.06 | 0 | 0 | 0 | 10
20 | 🇷🇺 | electroNic | 145.62 | 0 | 0 | 1 | 9
21 | 🇷🇺 | m0NESY | 142.95 | 0 | 0 | 2 | 6
22 | 🇵🇱 | snax | 139.5 | 0 | 0 | 1 | 9
23 | 🇩🇰 | trace | 124.97 | 0 | 0 | 0 | 4
24 | 🇫🇷 | Happy | 123.23 | 0 | 1 | 0 | 6
25 | 🇵🇱 | pashaBiceps | 122.67 | 0 | 0 | 0 | 8

## Feedback
I'm looking for ways to improve this model, even if slightly, so if you have an idea for how I could do that, let me know. I'm especially interested in any ways of obtaining KPR data from between 2001 and 2003, or any other player-specific performance data.
