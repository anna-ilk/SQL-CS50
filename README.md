# Cyberchase - CS50's Introduction to Databases with SQL

## Project Description
This repository contains my solutions for the "Cyberchase" Problem Set, which is part of the official **CS50's Introduction to Databases with SQL (CS50 SQL)** course by Harvard University. 

The goal of this project was to extract and analyze data from a relational database (SQLite) containing information about episodes of the popular PBS educational series, *Cyberchase*.

## Skills & Technologies
During the implementation of this project, I used **SQL (SQLite)** to write queries that solve specific problems. The core concepts applied include:
* Data retrieval (`SELECT`, `FROM`)
* Filtering with multiple conditions (`WHERE`, `AND`, `OR`)
* Sorting results (`ORDER BY`, `ASC`, `DESC`)
* Pattern matching for text and dates (`LIKE`, `%`)
* Handling missing/null data (`IS NULL`, `IS NOT NULL`)

## File Structure
The project consists of the `cyberchase.db` database (provided by Harvard) and 13 standalone `.sql` files. Each `.sql` file contains a single SQL query that solves a specific requirement of the assignment.

* `1.sql` - `13.sql`: The SQL scripts containing the query solutions.
* `cyberchase.db`: The SQLite database containing the `episodes` table.

*Note: The database schema (`episodes` table) includes columns such as `id`, `season`, `episode_in_season`, `title`, `topic`, `air_date`, and `production_code`.*
