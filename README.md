# Capstone_Project_on_Olympic_Data_Using_Python_DS_Pyspark_SQL

## Data Description :
In this Olympic data , 110 countries were added in 49 sports from year  2000 to 2012 in olympic games.
Also contains player names with their age and number of gold , silver and brone medals , they won . With total medals they won.

## Variables in the Data

| |  Variables  | Type    | Sub-Types   | 
|---:|:-------------|:-----------|:------|
| 1 | Name  | Categorical       |Nominal  | 
| 2 | Age   | Numeric  |Continuous  | 
| 3 | Country  | Categorical    |Nominal   |
| 4 | Year  | Categorical    |Ordinal   | 
| 5 | Date  | Categorical   |Ordinal   | 
| 6 | Sports  | Numeric    |Nominal    | 
| 7 | Gold_medal | Numeric    |Discrete    | 
| 8 | Silver_Medal  | Numeric    |Discrete    | 
| 9 | Brone_medal  | Numeric    |Discrete    | 
| 10 | Total_Medal  | Numeric    |Discrete   |      


## Libraries:
* Pandas # data processing, CSV file I/O (e.g. pd.read_csv)
* Numpy #linear algebra  
* Seaborn & Matplotlib #data visualisation
* missingno  #  visualising missing values
* Pyspark
* Use of MySQL Workbench

## Questions - For Python - Data_Science 
- Please do the basic exploration of the data. Remember the dataset contains information from different years. So whatever steps you perform should make logical sense.
- Deal with missing values appropriately. You can either remove them or fill them, but a proper justification is required.
- Duplicates in the dataset introduces bias in the study. Please check and perform appropriate steps.
- Please remove special characters from the name column.
- Perform data visualization techniques to appropriate columns and explain them.  
- Please check if the age dataset is skewed or symmetric. Based on results perform transformation.
- Please perform appropriate numerical measures on each column and report them accordingly.
- Please list the top 10 countries with the gold medal, then top10 countries with the silver medal, then bronze medal and the total medal.

## Questions - For SQL
-  Find the average number of medals won by each country
- Display the countries and the number of gold medals they have won in decreasing order
- Display the list of people and the medals they have won in descending order, grouped by their country
- Display the list of people with the medals they have won according to their their age
- Which country has won the most number of medals 


## Questions - For PySpark
- Write PySpark code to read olympix_data.csv file
- Write PySpark code to print the Olympic Sports/games in the dataset.
- Write PySpark code to print the total number of medals in  each Olympic Sport/game
- Sort the result based on the total number of medals.
- Find the total number of medals won by each country in swimming.
- Find the total number of medals won by each country in Skeleton.
- Find the number of medals that the US won yearly.
- Find the total number of medals won by each country.
- Who was the oldest athlete in the olympics? 
- Which country was he/she from?
- Write PySpark code to plot the total number of medals in  each Olympic Sport/game


                 
