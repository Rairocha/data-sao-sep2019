![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Lab | Advanced PostgreSQL

## Introduction

In this lab you will practice PostgreSQL Subqueries and Temp Tables. 
Create a `solutions.sql` file to record your solutions to all challenges.

## Challenge 1 - 10 cities with biggest profit coming from rental payment.

In this challenge let's have a close look at the sikala database.

In order to solve this problem, it is important for you to keep the following points in mind:

You will not be able to achieve the goal with a single SELECT query. 
Instead, you will need to follow several steps in order to achieve the eventual solution. Below is an overview of the steps:

1 Add the amount of payment for each customer 

2 Discover what city every customer is from using the address table

3 Add the amount of payment by cities 

4 Order by highest payment, get the first 10  

## Challenge 2 - Alternative Solution

In the previous challenge, you may have developed your solution in either of the following ways:

* Subqueries
* Creating temporary tables in the initial steps, and query the temporary tables in the subsequent steps.

Either way you have used, we'd like you to try the other way. Include your alternative solution in your solutions file.