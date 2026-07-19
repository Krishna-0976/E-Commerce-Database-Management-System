# E-Commerce Database Management System — Database Design

A relational database for a full-scale e-commerce platform, designed from a conceptual ER model through to a normalized, constraint-enforced PostgreSQL schema.

ER Diagram
<img width="885" height="447" alt="{3946A7D6-F78F-4F93-8EB4-181B38B54975}" src="https://github.com/user-attachments/assets/6d90ab26-a99c-4a84-848a-5f6d6f9abbff" />


## Highlights

- 19 entities, including a self-referential category hierarchy and multiple 1:1/M:N relationship types
- 19 relations, all proven to be in BCNF
- Composite primary keys, unique constraints, and CHECK constraints enforcing rules foreign keys alone can't
- Cascade / set-null / restrict deletion semantics tuned per relationship

## Relational Model

Relational Model
<img width="741" height="458" alt="{A812A2DE-5606-40BB-9338-B4FD088D663B}" src="https://github.com/user-attachments/assets/f537fec0-dafe-4430-9221-91d26b33645f" />


📄 Full FD sets, BCNF proofs, and DDL: [202401079_Relational_Scheme.pdf](./202401079_Relational_Scheme.pdf)

## Repository Structure

```
├── erd_diagram.png                   ER diagram (image)
├── relational_model.png              Relational model diagram (image)
├── E-Commerce-ERD.pdf                Conceptual ER diagram (PDF)
├── 202401079_Relational_Scheme.pdf   Relational schema, FDs, BCNF proofs, DDL
├── ecommerce_schema.sql              Executable CREATE TABLE statements
└── README.md
```

## How to run

Execute in psql or pgAdmin in this order:

```
ecommerce_schema.sql
```

## Tech

- draw.io / ERD tool (ER diagram)
- dbdiagram.io (relational model)
- PostgreSQL
