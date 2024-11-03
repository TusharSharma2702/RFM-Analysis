## RFM - Recency Frequency Monetary
RFM is used for analyzing customer value(CLV). It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries.

RFM stands for the three dimensions:

* Recency – How recently did the customer purchase?
* Frequency – How often do they purchase?
* Monetary Value – How much do they spend?


### Pandas :
1) .read_excel => read excel file 
2) .isnull => returns a data frame showing true in places of null values
3) .isnull().sum => show coloumnwise null values
4) .dropna => drop all null value rows and coloumn accordingly
5) .str (accessor) => allows us to use string method on coloumns containing string value
6) .agg => used to aplly function on data frame coloumns
7) .groupby => group items by unique id in coloumn
8) .value_count => shows occurence of values
9) .concat =>  concatenate (combine) two or more pandas objects (like DataFrames or Series) along a particular axis
10) .astype => converts data frame coloumnt to another data type
11) .qcut() => quantiles a given data series into discrete intervals