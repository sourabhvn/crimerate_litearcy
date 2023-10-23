Hi, I am Sourabh Navaratna. I am a data enthusiast who loves to analyse the data. Below are the steps included in analyzing the two govt open data sets crimerate statewise(2017) and literacy rate statewise(2011 census). There is a general notion that lack of literacy in the society leads to increase in crime rates. Let us find out using DATA ANALYSIS.


Problem statememt - Is literacy a determinant for the crimes in the states?

Source of Data:Indian Govt site open data.

Data Analysis process:

1) Asking the right questions so that problem task is clear:
 
Is the general perception that literacy can uproot crime rates based on valid data ?

What kind of data should be used?

What is the source of data?

What tool should I use initially?

Is my source credible?

2)Preparing the data :

Download the data from the source i.e, Govt of India made available opendata.

Storing the datasets in a folder.

Import the dataset downloaded into the spreadsheet.

2 datasets literacyrate.csv(2011 census) and crimerate.csv.(2017 annual report)

Identifying whether the data is reliable,original and cited.

Organising the data using sort().

3)Processing the data:

Cleaning the data 

Replacing the na values with 0 for accurate calculations using find and replace function.
Sorting the states/UTs of literacy dataset from (A-Z) along with corresponding literacy rates
Sorting the states/UTs of crime dataset from (A-Z) along with corresponding crime rates.
using the vlookup() function to get the literacy rate data from the literacy sheet to the crime rate sheet to the corresponding states.


4)Analysing the data:
sorting the sheet with crime rate descending order.
calculating the average crime rate of India using =average() formula.
calculating the average literacy rate of India using =average() formula.
Using Conditional Formatting to highlight all the states having crime rate greater than average crime rate of India.
Using conditional formatting to highlight all the states based on literacy rates.

Using filter to view all the states having their crime rates greater than average crime rate of India.

5)
Sharing the analyzed data into Microsoft Power BI to create reports.

First a fill map is used to show the crime rates in various states.Color grading is used from light red indicating low crime rate and dark red indicating high crime rate.

Another stacked area chart is used which has literacy rate in y-axis and crime rate on x-axis.

Insights:

While there is a general notion that illiteracy leads to increase in crime rate, the notion is a fallacy since the states with high literacy rate are high in crime rates too.
There is no direct causation between illiteracy and increase in crime rates. Other factors such as unemployment,poor law and order may contribute to the increased crime rates.





















