# Record Label Management Database (SQL)  

## Project Overview  
This project is a relational database system designed to store and manage information related to one or more record labels. It efficiently handles contracts, musicians, instruments, albums, songs, bands, and employees, offering a structured and optimized approach to database management.  

The database captures key relationships between record labels, artists, and their work while allowing efficient data manipulation through SQL queries, constraints, views, and normalization techniques.  

## Key Features  
- Complex entity-relationship model:  
  - The **CASA_DISCURI** (Record Label) table manages contracts, musicians, and albums.  
  - The **ALBUM** table contains one or more songs (**CANTEC**), each associated with a band (**TRUPA**).
  - The **CANTEC** table represents songs, each can appear in one or more band and have one or more bands.  
  - The **TRUPA** table represents bands, which consist of one or more musicians (**MUZICIAN**), and a musician can belong to multiple bands.  
  - The **INSTRUMENT** table records the instruments associated with a band.  
  - The **ANGAJAT** table tracks employees, including managers, marketing researchers, contract administrators, and audio engineers.  

- Advanced SQL functionalities:  
  - Full support for data manipulation, including inserting, updating, deleting, and retrieving records.  
  - Implementation of complex queries using joins, subqueries, views, outer joins, divisions, and top-n analysis.  
  - Stored procedures and triggers for automating database operations.  

- Constraints and data integrity:  
  - Use of primary keys, foreign keys, unique constraints, and check constraints to ensure data consistency.  
  - Implementation of business rules for data validation and integrity.  

- Normalization and optimization:  
  - Normalization up to the third normal form (3NF) and beyond, including BCNF, fourth normal form (4NF), and fifth normal form (5NF).  
  - Denormalization applied where necessary to improve performance.  

## Functionality  
This database enables users to store and manage information related to record labels, contracts, bands, musicians, instruments, albums, songs, and employees. It allows for data creation, reading, updating, and deletion, making it a valuable tool for record label companies that need an efficient and structured way to store and manage their data.  

The project is implemented in a complex manner and includes thorough documentation, covering all aspects from entity descriptions to relational schema design, constraints, and SQL implementation. It follows best practices in database normalization, query optimization, and data consistency management.
