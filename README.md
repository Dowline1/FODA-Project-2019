# FODA-Project-2019
Git Repository for Fundamentals Of Data Analysis Project 2019: Python Analysis of Tips Dataset 

## Running the Jupyter Notebook
1. Click this [link](https://github.com/Dowline1/FODA-Project-2019) for my Github repository.
2. Click the download button to save a copy of the repository on your machine.
3. Make sure you have Python installed including Jupyter, if you require installation please follow instructions in this [link](https://www.anaconda.com/distribution/) to download Python via Anaconda.
4. Use your command line such as CMDER to navigate to the folder housing the Git repository, download for CMDER found via this [link](https://cmder.net/).
5. Once in the folder type the command "Jupyter Notebook" and click enter.
6. This will open a Jupyter Notebook in your default web browser, click on the file "PFDA-Assignment-2019.ipynb".
7. Once in the Jupyter Notebook itself click on Kernel then Restart And Run All as per **image below**, this will run the code and generate all graphs.

<img  src="Resources/Jupyter_Instructions.png">


## Introduction
<p>The Tips Dataset originates from the early 1990's whereby over a period of ~ 3 months a food server recorded several variables (see below table for details) of the sales during the period.
The variables collected once analysed could give insight into the major factors which influence the amount of tips that are paid per bill. Using this knowledge restaurant management could make clear decisions on assigning servers to customers so that tips can be as evenly as possible distributed amongst staff as tips in the US play a major part of server earnings. </p>
<p>&nbsp;</p>

**Table 1:** <span style="text-decoration: underline">**Variables Summary**</span>

|**Variable**|**Details**|
|:-----:|:-----:|
|total\_bill|Total bill including tax in US $|
|tip|Tip amount in $|
|sex|Gender of person paying (Male/Female)|
|smoker|Indicates if smoker present in party (Yes/No)|
|day|Day of week (Thur/Fri/Sat/Sun)|
|time|Service Period (Lunch/Dinner)|
|size|Number of Individuals in Party|
<p>&nbsp;</p>

During the analysis I would expect there to be certain relationships between variables such as the total bill value and the tip amount as in the US it is an unspoken rule thet a typical tip ranges from 10%-15% of the total bill. 
The relationships that I am interested in investigating include whether any of the other variables like gender, smoking preference, day of week or service period impact the amount of tip paid. In some cases there may be a relationship between tip paid and the party size to a point, however I expect that as is the case in some restaurants in Ireland a service charge can apply that can be up to 10% depending on the party size as can be seen in this [article](https://www.irishtimes.com/life-and-style/food-and-drink/before-you-leave-a-tip-in-an-irish-restaurant-read-this-1.3857096) which may add a bias to the analysis.


## Analysis

## Conclusion

[Comment]: <> (Remember to discuss variable of sex of food server which may also impact size of tip)


## References
- tips.csv downloaded from this [link](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv)
- Mukul Chauhan example analysis of tips dataset [link](https://medium.com/@mukul.mschauhan/data-visualisation-using-seaborn-464b7c0e5122)
- Tips Dataset Background Information [link](http://www.ggobi.org/book/chap-data.pdf)
- Case Study of Restaurant Tipping [link](https://dicook.public.iastate.edu/stat503/05/cs-tips2.pdf)
- Markdown Cheatsheet [link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers)
- Underlining in Markdown [link](https://stackoverflow.com/questions/44840416/how-to-make-a-word-underline-in-markdown)
- Blank Rows/Additional Formatting in Markdown [link](https://dotcms.com/docs/latest/markdown-syntax)
- Plot Descriptions Seaborn [link](https://towardsdatascience.com/data-visualization-using-seaborn-fc24db95a850#targetText=Seaborn%20is%20a%20Python%20data,attractive%20and%20informative%20statistical%20graphics.)
- Statistics Quartiles Definition [link](https://www.investopedia.com/terms/q/quartile.asp#targetText=Q1%20tells%20us%20that%2025,the%20scores%20are%20above%2075.)
- Descriptive Statistics Information [link](https://www.investopedia.com/terms/d/descriptive_statistics.asp#targetText=Descriptive%20statistics%20are%20brief%20descriptive,measures%20of%20variability%20(spread).)
- Determining Relationships between variables [link](https://machinelearningmastery.com/how-to-use-correlation-to-understand-the-relationship-between-variables/)
- Regression Analysis [link](http://www.turingfinance.com/regression-analysis-using-python-statsmodels-and-quandl/)
- Sample Size Calculator [link](https://www.surveysystem.com/sscalc.htm)
- Exploring Data with Python [link](https://data-and-design.readthedocs.io/en/latest/02-introPandas.html)
