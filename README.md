# matplotlib_challenge

To do:

Beginning:

	- read sheets
	- merge data frames
	- find unique values
	- remove redundant values
	- display new df

Summary Statistics:

	- Group data
	- calculate stats
	- put it into dataframe

Bar and Pie Charts:
	
	- Generate bar chart for Drug Regimen and Observed Timepoints (mouse count)
	- Make pie chart to visualize Sex ratio for mice
	
Quartiles, Outliers and Boxplots

	- make separate drug dataframes
	- get greatest timepoint for each Group
	- merge group together
	- loop through all the drugs
		- Calculate quantiles, iqr, upper bound, lower bound
		- look through mouse rows to find outliers
		- print out potential outliers
	-make a boxplot for the drugs with the new information gathered above
	
Line and Scatter Plots

	- Make line plot for Timepoint vs. Tumor Volume for a specific mouse on Capomulin
	- Make scatter plot for mouse weight vs. Tumor Volume
Correlation and Regression:

	- Calculate linear regression for same scatter plot
	- Calculate correlation coefficient for the relationship

Resources:

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html

https://www.geeksforgeeks.org/find-duplicate-rows-in-a-dataframe-based-on-all-or-selected-columns/#

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.loc.html

https://www.geeksforgeeks.org/change-the-order-of-a-pandas-dataframe-columns-in-python/

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.agg.html

https://numpy.org/doc/stable/reference/generated/numpy.arange.html

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.bar.html

https://pandas.pydata.org/docs/reference/api/pandas.concat.html

https://sparkbyexamples.com/pandas/pandas-merge-multiple-dataframes-2/?expand_article=1

https://www.geeksforgeeks.org/how-to-rename-columns-in-pandas-dataframe/#

https://matplotlib.org/stable/gallery/color/named_colors.html

https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.scatter.html
