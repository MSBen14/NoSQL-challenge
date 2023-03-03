# nosql-challenge
![nosql](https://ravendb.net/wp-content/uploads/2021/04/nosql-document-oriented-databases-detailed-overview.jpg)


##Instructions


The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.


## Part 1: Database and Jupyter Notebook Set Up
1.Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to 2.import your data from your Terminal to a markdown cell in your notebook.

3.Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

4.Create an instance of the Mongo Client.

** Confirm that you created the database and loaded the data properly:

+ List the databases you have in MongoDB. Confirm that uk_food is listed.
+ List the collection(s) in the database to ensure that establishments is there.
+ Find and display one document in the establishments collection using find_one and display with pprint.
5.Assign the establishments collection to a variable to prepare the collection for use.
