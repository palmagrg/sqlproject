# SQL Project
A database schema created using SQL commands


Description:
This repo contains database schema using the existing ER diagram. SQL queries is used to create database schema to implement the relational database.
The schema here is intended for a MySQL database. In this database schema, I've created 5 tables using MYSQL queries and constraint is also implemented. SQL INSERT queries are used to populate the schema. 


Synopsis:
"assignment4.sql" will have database schema to create tables and data is populated into schema using INSERT queries.

Database Tables:
Below is the overview on individial tables:

Author :
It consists of email addresses , firstname and last name of the author.

Reviewer:
It consists information of reviewer.
columns:
-Emailaddress , it is a primary key.
-FirstName
-AuthorFeedback
-LastName
-CommiteeFeedback
-Phonenum
-Affiliation

Paper:
It has information about papers written.
columns:
Id , it is a primary key.
Abstract
FileName

Topic:
columns:
Id , it is primary key
Topicname

Review:
It contains the information about the paper. 
Colums
Recommendation
Id, it is primary key
MeritSCore
PaperID
Readabilityscore
ReviewId
OriginalityScore
RelevanceSCore

