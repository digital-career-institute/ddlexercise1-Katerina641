# DDL exercise
Creating Tables:
Create a table named Movies with the following columns:
movie_id (integer)
title (varchar, maximum length 100)
director (varchar, maximum length 50)
release_year (integer)
genre (varchar, maximum length 50)

//CREATE TABLE Movies(movie_id INT, title VARCHAR(100), director VARCHAR(50),release_year INT,genre VARCHAR(50);

Altering Tables:
Alter the Movies table to add a new column named rating of type decimal(3, 1).

//ALTER table Movies ADD rating DECIMAL(3,1);


Dropping Tables:
Create a new table named Students with columns:

student_id (integer)
student_name (varchar, maximum length 50)
age (integer)
grade (varchar, maximum length 2)

//CREATE TABLE Students(studentid INT,studentname VARCHAR(50), age INT, grade VARCHAR(2));

Then, drop the Students table.

//delete table Students;
//describe Events;

Truncating Tables:
Create a table named Events with columns:

event_id (integer)
event_name (varchar, maximum length 100)
date (date)
location (varchar, maximum length 100)

//INSERT INTO Events (eventid,eventname,date,location,age) VALUES(1,'NIKO','2022-12-12','Ukraine',25);

Insert some sample data into the Events table. Once done, truncate the table to remove all records while keeping the table structure intact.
//TRUNCATE table Events;
Renaming Tables:
Create a table named Restaurants with columns:

//create table Restaurants (restid INT,name VARCHAR(50), cuisine VARCHAR(50),location VARCHAR(100));
restaurant_id (integer)
name (varchar, maximum length 50)
cuisine (varchar, maximum length 50)
location (varchar, maximum length 100)
Rename the table to DiningSpots.

//ALTER TABLE Restaurants REname to Restaurants2;


