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
### Phase 7:
