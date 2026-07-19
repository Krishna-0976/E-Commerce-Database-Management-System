# E-Commerce Database Management System — Database Design

A relational database for a full-scale e-commerce platform, designed from a conceptual ER model through to a normalized, constraint-enforced PostgreSQL schema.


<img width="885" height="447" alt="{3946A7D6-F78F-4F93-8EB4-181B38B54975}" src="https://github.com/user-attachments/assets/6d90ab26-a99c-4a84-848a-5f6d6f9abbff" />


## Highlights

- 19 entities, including a self-referential category hierarchy and multiple 1:1/M:N relationship types
- 19 relations, all proven to be in BCNF
- Composite primary keys, unique constraints, and CHECK constraints enforcing rules foreign keys alone can't
- Cascade / set-null / restrict deletion semantics tuned per relationship

## Relational Model

<img width="741" height="458" alt="{A812A2DE-5606-40BB-9338-B4FD088D663B}" src="https://github.com/user-attachments/assets/f537fec0-dafe-4430-9221-91d26b33645f" />


## Repository Structure

```
├── erd_diagram.png          ER diagram (image, for README preview)
├── relational_model.png     Relational model diagram (image, for README preview)
├── E-Commerce-ERD.pdf       Conceptual ER diagram (PDF)
├── E-Commerce_ERD.dia       ER diagram source file (Dia)
├── Relational_Schema.pdf    Relational schema, FDs, BCNF proofs, DDL
├── ddl_scripts.txt          CREATE TABLE statements
├── insert_scripts.txt       Sample seed data (INSERT statements)
├── select_queries.txt       Sample analytical queries
└── README.md
```
 
Execute in psql or pgAdmin in this order:
 
```
ddl_scripts.txt
insert_scripts.txt
select_queries.txt
```
 
## Tech
 
- draw.io / ERD tool (ER diagram)
- dbdiagram.io (relational model)
- PostgreSQL
 
