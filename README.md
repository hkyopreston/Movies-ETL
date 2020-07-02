# Module 8 challenge
## ETL

In this challenge, I created an automated ETL pipeline that extracts data from multiple sources, cleans and transforms the data automatically using Pandas and regular expressions, and then loads the new data into PostgreSQL. 

This automated function takes into account several assumptions: 

    1. When extracting the Wikipedia and Kaggle data, all rows are pulled in from the csv files. 
    2. There are null or mostly null columns that need to be removed. 
    3. The list of 'alternate titles' is valid, and that there will not be new alternate titles added to the data. 
    4. When creating regular expressions for budget and box office figures, we will need to capture 'million' and 'billion' as expressions. 
    5. When data is loaded into SQL, it will have the correct data types. 
