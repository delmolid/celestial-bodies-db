Project : Celestial Bodies Database

This repository contains the SQL schema and sample data for a relational database representing celestial bodies such as galaxies, stars, planets, and moons.

The database was built as part of the freeCodeCamp *Celestial Bodies Database* project, and includes PostgreSQL table definitions, relationships, constraints, and sample data.

---

Project Description

This project models a universe database with the following entities:

Tables

- **galaxy** — contains galaxies with attributes like name, number of stars, distance, type, visibility, etc.
- **star** — contains stars and references the galaxy each star belongs to.
- **planet** — contains planets and references the star each planet orbits.
- **moon** — contains moons and references the planet each moon orbits.
- **(Optional) comet** — example additional table linked to stars.

Each table has at least five columns, includes primary keys, foreign key relationships, and unique constraints where appropriate.

---

Included File

- `universe.sql` — PostgreSQL database dump that includes:
  - Table creation scripts
  - Constraints (primary keys, foreign keys, unique)
  - Sample data for galaxies, stars, planets, and moons


To restore the database on your local machine:

1. Make sure PostgreSQL is installed.
2. Create a database:


