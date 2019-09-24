# Lab | PostgreSQL Select

In this lab you will practice how to use the Postgres SELECT statement which will be extremely useful in your future work as a data analyst/scientist/engineer. You will use the sakila database that we used in the Joins and Relationships lesson. In case you haven't had that database, go back to the lesson to download it.

You will create a `solutions.sql` file in the `your-code` directory to record your solutions to all challenges.

## Challenge 1 - Getting to know our customers?

In this challenge, you'll need to create a sql query to retrieve how many times each customer has rented a movie, how much they have spent in the store and how much they spent each time they rent something at the store.

You'll need to answer the following questions:
- Who is the customer that has rented the most number of times in the store?
- Who is the customer that has spent the most in the store?
- Who is the customer that has spent the most in average in the store? (Keep in mind that we want to know the average of how much they spent not the total)
- Are they the same person? What conclusions can we draw from here?

## Challenge 2 - Which movie has been more rented?

In this challenge, you'll have to create a sql query to retrieve the 5 filmes that have been rented the most.

To do that, go back to the ERD of the database, which has been provided in the Joins and Relationships lesson. There you'll find the `film` and the `rental` tables. Here are some questions to help you designing your query: How do they relate to each other? How could you join their information? Do they have any field in common?

Your answer should look like:

title | number_of_times_rented
--- | ---
BUCKET BROTHERHOOD | 34
ROCKETEER MOTHER | 33
GRIT CLOCKWORK | 32
RIDGEMONT SUBMARINE | 32
FORWARD TEMPLE | 32

## Challenge 3 - Which movie category has been rented the most?

In this challenge, you'll have to create a sql query to discover the movies categories that have been rented the most.

This query will be a little bit more challenging. Go back to the ERD to understand how each table relate to each other. You'll have to perform several joins to finish this challenge.

## Challenge 4 - Which movie categories do our top customers like?

Remeber the challenge 1? Get the top 5 customer and try to see what are the categories of movies that they like.

This is not an easy task. Take your time to understand how each table relate to each other. You'll have to perform several joins to finish this challenge.