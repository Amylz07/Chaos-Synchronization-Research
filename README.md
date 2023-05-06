# Chaos-Synchronization-Research
## Description
## Information
## Detailed Research Progress
### Phase 1: Pre-reading and learning (Sep. 22 - Oct. 12, 2022)
For codes, see Phase 1 folder.
For detailed notes, see Learning Log.
### Phase 2: Paper reading & deciding on the non-linear system for investigation (Oct. 13 - Nov. 9, 2022)
For codes, see Phase 2 folder.
For detailed notes, see Research Log Week 1-4.
- decided on ThermoElectricPhotoneuronsJJ paper: Phase synchronization between two thermo-photoelectric neurons coupled through a Josephson Junction, https://doi.org/10.1140/epjb/s10051-022-00324-x.
### Phase 3: Initial explorations of the system (Nov. 10 - Nov. 30, 2022)
For codes, see Phase 3 folder.
For detailed notes, see Research Log Week 5-7.
- reproduction of the time series of the system
### Phase 4: Error function of the system (Dec. 1, 2022 - Jan. 11 2023)
For codes, see Phase 4 folder.
For detailed notes, see Research Log Week 8-14.
- we had a one-month break in December because Professor Arjendu was traveling to a conference in Europe
- error function time series
- error function heatmaps (the two coupling strengths as the two parameters at the axes, color as representation of error function value)
### Phase 5: Permutation entropy and ordinal pattern analysis of time series (Jan. 12 - Feb. 8, 2023)
For codes, see Phase 5 folder.
For detailed notes, see Research Log Week 15-18.
- algorithm: ordpy package
- 2D heatmap (the two coupling strengths as the two parameters at the axes, color as representation of error function value)
- 3D heatmap (adding a third paramter)
    - unimportant so abandoned later on
### Phase 6: Comparing heatmaps and compiling findings (Feb. 9 - Feb. 15, 2023)
For codes, see Phase 6 folder.
For detailed notes, see Research Log Week 19.
- comparing heatmaps of (1) mean of error function values (2) permutation entropy of error function values (3) ordinal pattern probability difference of error function values 
- identifying the four regions via the heatmap of permutation entropy (which indicates chaoticness) and ordinal pattern probability difference (which indicates synchronization level):
    - region 1: chaos & non-sync
    - region 2: chaos & sync
    - region 3: non-chaos & non-sync
    - regions 4: non-chaos & sync
### Phase 7: Truncated time series analysis (Feb. 16 - Mar. 1, 2023)
For codes, see Phase 7 folder.
For detailed notes, see Research Log Week 20-21.
- same methods as before, applied on truncated time series, aiming to identify different patterns in a single time series (sometimes synchronization and non-synchronization co-exist in a single time series)
    - didn't work well so abandoned
### Phase 8: Problem identification, major turning point (Mar. 2, 2023 meeting)
For detailed notes, see Research Log Mar. 2 2023 meeting notes.
- realized the need to verify the chaoticness of the original system (the chaoticness of the original variables), not just the error function
### Phase 9: Permutation entropy and ordinal pattern analysis on the original system (Mar. 2 - Apr. 6, 2023)
For codes, see Phase 9 folder.
For detailed notes, see Research Log Week 22-26.
- permutation entropy and ordinal pattern analysis on x1, a variable in the original system, instead of investigating the error function
- one week off because of Professor Arjendu's personal issues; another week off because of FP project week hiking
- found results on chaos and sync regions different from those in the original JJ paper; although the tools I used and the author used were different, the chaos and sync regions should roughly be the same
### Phase 10: Contacting JJ paper for code issues; identifying algorithm problem within ordpy Python package (Apr. 6-12, 2023)
For codes, see Phase 10 folder.
For detailed notes, see Research Log Week 27.
- email to Professor Fossi (author of JJ paper) asking about code issues
- ordpy package problem identification
### Phase 11: Fixing algorithm issue (Apr. 13 - May 3, 2023)
For codes, see Phase 11 folder.
For detailed notes, see Research Log Week 28-30.
- new code for ordinal distribution found and edited
- new code tested
### Phase 12: Previous problems solved; finalizing future directions (May 4, 2023 meeting)
For detailed notes, see Research Log May 4 meeting notes.
- a major turning point; future directions:
    - stop meddling with the JJ paper system, choose well understood systems (Lorenz, Duffing, Chua, Rössler, etc.) to couple
    - use different tools to measure chaoticness and sync, including tools like phase space, Poincaré sections, error function, Lyapunov exponent, ordinal pattern analysis, permutation entropy
    - compare heatmaps generated from using different tools; find the pros and cons of each method, preferably focusing on permutation entropy and ordinal distribution
    - find the four regions: chaos & sync; chaos & non-sync; non-chaos & sync; non-chaos & non-sync
    - investigate complicated transitions - identifying different patterns of sync and chaos within a single time series; classification of different transition types/patterns
