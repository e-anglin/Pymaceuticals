# Pymaceuticals
**Credit**
Assisted by Kourt (tutor) when finding and isolating data of the duplicate mouse. Assisted by Joseph (classmate) when creating pyplot bar plot. Assisted by Herbert and Frank (classmates) when creating the scatter plot. Assisted by Zubair (tutor) on box plot.

Analysis
Null hypothesis - Capomulin has no discernible effect on the developing SCC tumors, when looking at the continuous dependent variables, compared to other treatment regimens.

Alternate hypothesis - Capomulin has a discernible effect on SCC tumors, when looking at continuous dependent variables, compared to other treatments.

The study began with 249 mice, all with squamous cell carcinoma tumors at tumor volume of 45 mm3. Findings for one mouse had to be eliminated due to duplicated results.

Treatment regimens included the following: Capomulin Ceftamin Infubinol Ketapril Naftisol Propriva Ramicane Stelasyn Zoniferol placebo

Of note: *Seven mice made it to day 45 with no appearance of metastatic sites. Six of seven of the mice showed a decrease in tumor volume, three on Capomulin and three on Ramicane.

*Five mice made it to day 45 with a decrease in tumor volume to less than 30 mm3. three of these were Ramicane and two on Capomulin.

The weight of the mice stayed consistent regardless of the development of the tumors. Smaller mice (<25g) showed better results. The top performers were Capomulin and Ramicane, however, the heaviest mice at the beginning of the study (>25g) were placed on other regimens. I recommend a thorough study using mice of a greater range of sizes on each treatment regimen.

A single mouse (g316) on Capomulin was pulled from the dataframe for a closer look. At 22 months, 22 g, she is one of the older mice in the study. Tumor volume dropped slightly to 44.02275246 at the 5 day check, increased to 45.56582103 at day 40, before dropping for the last five days of the study to 40.1592203. Despite two metastatic sites by the end of the study, data suggests that tumor volume will continue to decrease. I would like to see more long-term studies to gauge the result of prolonged use on the regimen.

After isolating the Capomulin data from the original cleaned dataframe, the remaining value shows a correlation coefficient of 0.84 for the weight of the mice - the independent variable - on Capomulin and the tumor volume - dependent variable - for the mice on Capomulin.

These findings suggest that the treatment is less effective on heavier mice. However, they still show a decrease in tumor volume, suggesting that the null hypothesis be rejected.
