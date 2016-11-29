# A Practical Guide to Coding with Databases

CompCon AU 2016

[Video of talk (thanks CompCon AU!)](https://youtu.be/4xhSf5DMyrU?list=PLeiahqHp4F82ED1_LzsuPNM6K273azDjh)

Betsy Alpert
lizbeth.alpert@gmail.com

## Requirements

### Notebook

This talk is presented as a jupyter notebook, using Python 3.

### Slides

To view as a slideshow, use the Jupyter extension [RISE](https://github.com/damianavila/RISE)

### Database environment

These examples use PostgreSQL (9.5).

Using Docker:

`docker run -d --name dbtalk postgres:9.5`

The notebook has a cell in which to enter your database connection information.

### Python environment

The async examples require Python 3 to run. Earlier examples should work with either Python 2 or 3, but were designed for 3.

Requirements:
* psycopg2
* SQLalchemy
* asyncpg

