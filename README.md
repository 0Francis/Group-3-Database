Justice Database System

**Repository**: 0Francis / Group-3-PrisonDatabase
License: GPL-3.0 
GitHub

**Table of Contents**

**Overview**

**Features**

Architecture & Database Schema

Setup & Installation

Usage

Contributing

License

**Overview**

The Justice Database System is a project aimed at modelling and implementing a database system to manage prison data. 
It includes SQL scripts, database schema diagrams, and documentation to support data storage, querying, and management for entities such as prisoners, staff, facilities, etc.

**Features**

1.Structured relational database model for a prison / justice system.

2.Entity-Relationship diagrams illustrating how tables relate. 
GitHub

3.SQL code for creating, populating, and querying the database. 
GitHub

4.Documentation (Word docs) describing project objectives and data rules. 
GitHub

5.Architecture & Database Schema

6.The schema includes tables representing entities like Prisoners, Staff, Facilities, etc.

7.The ER diagrams and PNG files in the repository show relationships, cardinalities, keys. 
GitHub

8.Designed using a relational DBMS (e.g. MySQL, PostgreSQL); SQL scripts are included.

**Setup & Installation**

Here’s how to get the database system running locally:

1.Clone the repository

git clone https://github.com/0Francis/Group-3-PrisonDatabase.git
cd Group-3-PrisonDatabase

2.Choose a DBMS

You’ll need a relational database server; recommendations include MySQL, PostgreSQL, or equivalent.

3.Create a database

For example, in MySQL:
  CREATE DATABASE justice_db;

4.Run the SQL scripts

5.Use the provided SQL files in SQL Codes for the Prison Database (or similar folder) to create tables, constraints, and optionally to insert sample data.

Example:
mysql -u <user> -p justice_db < path/to/create_tables.sql
mysql -u <user> -p justice_db < path/to/insert_sample_data.sql

6.View ER diagrams or schema diagrams

The .png files in the repository (e.g. Database Schema 4.png, ER diagram …) help to visualize the data model. 
GitHub

7.Connect via client/tools
Use any database client (CLI, GUI, or custom frontend) to connect to the database and perform queries.

**Usage**

Typical operations with the system might include:

1.Adding new prisoner records

2.Updating facility or staff information

3.Querying prisoner counts by facility, status, etc.

4.Generating reports (e.g. capacity usage, prisoner demographics)

You can extend with additional queries or functionality as needed.

**Contributing**

If you want to contribute:

1.Fork the repository.

2.Make your feature or bug-fix in a branch.

3.Ensure SQL scripts are well documented.

4.Update ER diagrams or schema if making schema changes.

5.Submit a pull request with a description of changes.

**License**

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). 
GitHub
