# Statistic for P115
+ The P115 version of the statistic code is slightly different compared to the previous versions.

+ For this semester, Roland has assigned specific Category A and Category B times. Programs can have time for both categories, or just for one.

+ **10.04.2025:** There was an error with Arne Rau's PID for FEROS (P115_pi.list). I corrected it and also assigned 20 h to  this run. He does not have specific amounts for FEROS or WFI, so that is completely random. I also reduced his GROND time by that amount.
+ **21.04.2025:** Update of the script with one more calculation of percentages, i.e. time observed s less than Cat. A, even if Cat. B is > 0h (e.g. for Eberhardt).
+ **27.04.2025:** Update how the total time for Neuman is calculated
+ **16.06.2025:** Update for GROND. Wolfgang Brandner only uses IRACE, so the number of files counts only those. Arne Rau has both, so the number of files is the sum of both, IRACE and FIERA images. Up to now, Demianenko is not been calculated; it will depend on the OB she will use. The overheads are difficult, but since neither Arne nor Wolfgang will get close to the total available time, that should not be a problem.
+ **27.06.2025:** Update for GROND: Mariia Demianenkos program. I used the number of IRACE images for the calculation of total exposure times and total execution times. The number of files counts both FIERA and IRACE images. Suyu has WFI and GROND time. She will get about 122 hours. According to the last e-mail, they get about 4 hours for WFI, and then will switch to GROND, so I split the 122 hours into 118 hours for GROND and 4 hours for WFI and changed it in the P115_pi.list file. Ramirez-Tannus is now also included.
+ **18.07.2025:** Update of the script, adding a separate count of NIR and optical images for GROND, in case only one instrument is used. In general, the number and exposure time for IRACE is used, plus a 400 sec overhead. Demianenko is added, but her overheads are unclear.
+ **05.08.2025:** I changed the overheads for GROND back to 220 sec, because the total times were allocated before each block had those extra 3 minutes.
+ **27.08.2025:** Overheads for Kohornen 115.28KG.001 are corrected, since we take multiple exposures per acquisition. I use 70 sec per image as an average. 
