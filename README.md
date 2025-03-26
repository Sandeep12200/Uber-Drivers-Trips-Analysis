# Uber Driver Trip Analysis
## Project Description: 
The project is based on the trips made by Uber drivers. It contains START_DATE, END_DATE, CATEGORY, START, STOP, MILES, PURPOSE variables. Here, we are analyzing different aspects of the trips by doing Exploratory Data Analysis.

## Problems:
* What is the most popular starting point & dropping point for the Uber drivers?
* What is the most frequent route taken by Uber drivers.
* Plot a bar graph of Purpose vs Miles(Distance
* Display a dataframe of Purpose and the total distance travelled for that particular Purpose.
* Generate a plot showing count of trips vs category of trips.
* What percentage of Miles were clocked under Business Category and what percentage of Miles were clocked under Personal Category ?

## Insights:
* This dataset contains 7 variables (columns) and 1155 rows.
* Among 7 variables, majority of the columns are object type, except for MILES* which is numerical.
* And it contains total 8085 elements which indicates that there are null values in the dataset. After checking information using info(), I found that PURPOSE* column contains 502 null values.
* There are total of 176 locations from where Uber drivers have started their trip and 187 drop locations where their trip finished.
* Cary is the most popular Starting and Dropping point having total of 201 and 203 trips.
* Most frequent route taken by Uber drivers is Cary to Morrisville with total of 52 trips.
* Uber is used for 7 different purposes in which "Meeting" has the highest number of trips. "Customer Visit", "Meal/Entertain" and “Errand/Supplies” are the second most frequent purpose trips. Some purposes like "Airport/Travel", “Charity”, “Commute” and "Moving" have very low trips.
* Majority users use Uber for Business Purposes occupying appox.93% of total trips while only 7% uses for Personal Purposes.
