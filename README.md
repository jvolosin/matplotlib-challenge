# matplotlib-challenge
Repo for the Rutgers matplotlib HW
This repo contains statistical analysis for data about mice tested with different medicine to control and reduce tumor growth. Different regimens were used to see which medication is more effective. 
To determine which regimen is best, we used scatter plots and box and whisker plots to observe the change in tumor size over time and the average size of a tumor depending on the regimen implemented. 
Statistical analysis was accomplished by using python code and importing pandas and matplotlib dependencies. 

Analysis
Mice treated with the Infubinol and Ceftamin regimens had significantly larger final tumor volumes compared to mice treated with the Ramicane and Capomulin regimens. Those treated with Infubinol and Ceftamin had a final average tumor volume of about 60mm3 while those treated with Ramicane and Capomulin had a final average tumor volume of about 37mm3.

There is a high correlation between mouse weight and average tumor volume (.84). So, the more a mouse weighs, the larger their tumor is going to be (typically speaking, this observation does not hold true for every mouse but does for most).

The single mouse we looked at for the Capomulin regimen is below the lower quartile and the tumor seems to have responded well to the treatment. The mouse ended with a tumor size of under 25mm3 and the lower quartile end at around 32mm3 for this regimen.

Some final thoughts: The sample was pretty even between male and female mice tested but we did not do any observations on how well males responded vs females to different regimens. It would also be interesting to look at age data. How do older vs younger mice respond to treatment?
