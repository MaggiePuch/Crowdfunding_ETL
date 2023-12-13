# Crowdfunding_ETL
Completed by Maggie Puch and Daniel Stephens

This project demonstrates ETL practices using Python and Pandas to extract and transform data that is then loaded into a Postgres database. We'll be using data from a fictional crowdfunding campaign to complete this project. 

Data extraction and transformation is completed in three parts in the Python notebook:

1. We start by extracting data from the crowdfunding.xlsx spreadsheet to a Pandas dataframe. Once extracted, we split the category & subcategory fields into separate fields. We then generate unique ids for each category and subcategory and store these ids along with the category and subcategory titles into separate dataframes, which are then exported to csv files

2. Working again with our crowdfunding dataframe, we perform some data cleaning, by renaming fields to be more descriptive, changing field types to integer and float where appropriate, and converting epoch timestamps to familiar date formats. Lastly, we drop unnecessary fields along with the category and subcategory titles(ids remain), since this data will be housed in separate tables in our database. 

3. 
