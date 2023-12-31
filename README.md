# nosql-challenge
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
# Objectives
1. Gain familiarity with the concept of the NoSQL database with MongoDB.
2. Utilising the PyMongo library to interface with Mongo databases using Python.
3. learn how to build aggregation pipelines when retrieving data.
# libraries/modules required to run the jupyter notebooks
1. pymongo
2. pprint
3. pandas
4. json
# Part 1: Database and Jupyter Notebook: NoSQL_setup_starter.ipynb
1. Imported the data provided in the establishments.json file from the Terminal with the database name as "uk_food" and the collection "establishments". 
>  Import code : mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
2. Created and instance of the mongo client.
3. Updated the database with the new entry.
4. Updated the datatypes of fields for query purposes.
# Part 2: Exploratory Analysis : NoSQL_analysis_starter.ipynb
Eat Safe, Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.
1. Created an instance of mongo client.
2. Performed analysis using queries and created dataframes of the results.
3. Perfomed conversion of Rating value to int and convert string to null and null to null for anlysis purposes.
4. Perfomed analysis using aggregate and pipeline.
