# nosql-challenge
module 12 challenge

# ProjectOverview'
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

# Part 1: Database and Jupyter Notebook Set Up

- Using the NoSQL_setup_starter.ipynb I imported the data provided in the establishments.json file from your Terminal. The database name is set to uk_food and the collection name is establishments. The import text is provided in the jupyter notebook file.
- The libraries that I imported are the following: PyMongo and Pretty Print (pprint).
- Next I created an instance of the Mongo Client and confirmed that the databased loaded in properly.

# Part 2: Update the Database

- To include the restaurant Penang Flavours in the NOSQL_setup_starter.ipynb I created a query to return only the BusinessTypeID for "Restaurant/Cafe/Canteen" and BusinessType fields.
- I updated the restaurant to include the new BusinessTypeID.
- I dropped the unwanted establishments in Dover.
- Lastly, I converted the data types for latitude/longitude into decimals, and the rating value to integer numbers.

