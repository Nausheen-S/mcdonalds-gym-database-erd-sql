
# Entity Relationship Diagram (ERD) Exercise 4

Moving from [the morning exercise yesterday](https://github.com/wdi-sg/mcdonalds-database-erd-sql/erd-exercise-3.md), we will be moving on to the next part.

# Diagram and SQL

## Now we will have abs

*Part 1*

Now we are going to create a gym.

The management wants an app that can manage membership. The management is technically incompetent and is not very clear in their specifications for the app and this is what they mentioned:

* Members will come to the gym and show their membership card to the receptionist to prove that they are a member and have an active membership.
* We want to enable gym members to be recorded when they come to the gym.

1. Draw the ERD for the situation
2. Create the SQL for tables and columns
  - Note that for the seed data, you can vary the dates and times using something like
  ```
  new Date('2019-08-06, 11:30')
  ```
3. Create the SQL queries, to enable these user stories:
  * We want to find out which gym members are not paying their membership fees.
  * We want to find out how many people come in every day
  * We want to find out which day of the month has the most number of people.
  * We want to find out the average length of the start date and end date of the memberships.
  * We want to find out what percentage of members come more than five times a week.

4. Finish Part 1 by itself first without Part 2.


<details github-only><hint>Clicky Hint</hint>
Hint: Customer management system
<ul>
<li>1. Needs to enable gym members to sign up.</li>
<li>2. Needs to check gym membership.</li>
</ul>
</details>


*Part 2*

The management has started three gym classes - class A, class B, class C.

With new gym classes come new information and the need for management to gather more information about the effectiveness of the classes.

We want to find out which gym classes are being used the most.

We want to find out, for the top 5 gym classes, which are the top 5 members using them.

There has been an outbreak of the bola-bola infection that makes your legs turn green and gym members who have been in the gym class C between the dates of August 1 to August 5 are probably infected with it.

We want to find out who they are.

1. Draw the ERD for the situation
2. Create the SQL code for tables and columns
3. Create the SQL queries

<details github-only><hint>Clicky Hint</hint>
Hint: Joins, foreign keys, many to many
</details>

