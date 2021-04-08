# matplotlib-project
Matplotlib Project

![Laboratory](Images/Laboratory.jpg)

I have access of a complete dataset from Pymaceuticals' animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I generated all of the tables and figures needed for the technical report of the study. 

My tasks:

* Checked the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID (i.e., exclude that mouse from the analysis). 

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas' `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. timepoint for that mouse.

* Generated a scatter plot of average tumor volume vs. mouse weight for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
