# Introduction to SQL

* **SQL - Structured Query Language** - allows to query, manipulate, and transform data from a relational database.
* **Relational Database** - represent a collection of related 2D tables.
* **Database normalization 1NF, 2NF, 3NF... (Normal Form)** : https://www.studytonight.com/dbms/database-normalization.php

## SQL Lesson 1: SELECT

**Select query for a specific columns**

     SELECT column, another_column, …
     FROM mytable;
## SQL Lesson 2: Queries with constraints (Pt. 1)

**Select query with constraints**

    SELECT column, another_column, …

    FROM mytable

    WHERE condition
    AND/OR another_condition   
    AND/OR …;
    
## SQL Lesson 3: Queries with constraints (Pt. 2)

**Select query with constraints**

    SELECT column, another_column, …

    FROM mytable

    WHERE condition

     AND/OR another_condition   
     AND/OR …;
 
 ## SQL Lesson 4: Filtering and sorting Query results
 
 **Select query with limited rows**
 
    SELECT column, another_column, …

    FROM mytable

    WHERE condition(s)

    ORDER BY column ASC/DESC

    LIMIT num_limit OFFSET num_offset;

* It's important to mention that SELECT **DISTINCT** is used to eliminate dublicate column values;

## SQL Lesson 6: Multi-table queries with JOINs

**Select query with INNER JOIN on multiple tables**

SELECT column, another_table_column, …

    FROM mytable

    INNER JOIN another_table 

    ON mytable.id = another_table.id
    
    WHERE condition(s)

    ORDER BY column, … ASC/DESC

    LIMIT num_limit OFFSET num_offset;

![834e9d5d963dfa6c528e5d6e09851233](https://github.com/S-Makeev/reading-notes/assets/71305940/ccc0559e-519c-4175-ad88-081f9a4196ea)
![2cb5986a67e7446aaf1a4e05059e142a](https://github.com/S-Makeev/reading-notes/assets/71305940/91dfbaaf-a1c1-4df7-93dc-480c994afc0b)
![73827b269993152e7d66a8a73f05f876](https://github.com/S-Makeev/reading-notes/assets/71305940/817c1dc7-9250-405b-ad6c-4cb1dd173b0d)
![1b87879f6876f619a6337327a11f06ab](https://github.com/S-Makeev/reading-notes/assets/71305940/3eaa471d-fea5-4c5a-8470-c55976ea46f4)
![fd1196fcdbc4daa917db5b08678a9a5b](https://github.com/S-Makeev/reading-notes/assets/71305940/1c9d5634-2ac5-4f89-9f0f-0f8450bd3b1e)
![248807413a414f315e2010f464459507](https://github.com/S-Makeev/reading-notes/assets/71305940/a7553e44-e878-49a7-b0da-d862e4ff27ab)
![ceb51ca58b91bb683fa97584aaf21b91](https://github.com/S-Makeev/reading-notes/assets/71305940/7b7159e7-490e-43cf-be02-9479739816c6)
![435df4b08b6ce37b70af5df94c7db2ed](https://github.com/S-Makeev/reading-notes/assets/71305940/06135983-c2e4-42de-b346-d3f52db45f7e)
![1ee61fe56886bfce3d4ce79fdfb13f7f](https://github.com/S-Makeev/reading-notes/assets/71305940/433a9492-6e51-4feb-9d22-395403152bd5)
![7cabb1277268c8e7308c7ab9d940a8a3](https://github.com/S-Makeev/reading-notes/assets/71305940/a84bcdea-8b84-489f-9c70-a457ed4d3f13)
![260e29f85e3ac17ee2642bcbf6b031bb](https://github.com/S-Makeev/reading-notes/assets/71305940/aa5e6f88-926d-4bc9-a986-e37146322a66)
![79096f9c1e329098e8b9fc7b45337b33](https://github.com/S-Makeev/reading-notes/assets/71305940/4e0ac406-4f0a-4da4-b852-d5679fd659ca)
