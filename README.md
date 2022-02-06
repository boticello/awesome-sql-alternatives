# Awesome SQL alternatives

## Relational data

- [Logica](https://github.com/EvgSkv/logica) – logic programming language that compiles to Standard SQL (BigQuery, SQLite, PostgreSQL)
- [Malloy](https://github.com/looker-open-source/malloy) – an experimental language for describing data relationships and transformations, akin to a SQL extension (BigQuery)
- [Flux](https://docs.influxdata.com/flux/) – functional data scripting language (**InfluxDB**, MySQL, PostgreSQL, CSV)
- [openCypher on AgensGraph](https://github.com/bitnine-oss/agensgraph) – SQL and [Cypher](http://opencypher.org/) queries can be integrated into a single query in [AgensGraph](https://bitnine.net/agensgraph/). (AgensGraph, built on PostgreSQL)
- [Rel](https://docs.relational.ai/rel/intro/overview/) – an expressive, declarative, and relational language designed for modeling domain knowledge (RelationalAI)

## Poly-store
Query languages which operate on both relational and non-relational data

- [PartiQL](https://partiql.org/tutorial.html) – treats nested data as first class citizens and composes seamlessly with SQL, enabling intuitive filtering, joining and aggregation on the combination of structured, semistructured and nested datasets (AWS various, others)
- [Optic API](https://docs.marklogic.com/guide/app-dev/OpticAPI) – makes it possible to perform relational operations on indexed values and documents (Marklogic)

## Relational Algebra
- [Morel](https://github.com/julianhyde/morel) – Standard ML interpreter with relational extensions
- [Tutorial D](https://github.com/DaveVoorhis/Rel) – a desktop database management system that implements Date & Darwen's "Tutorial D" database language (Rel)
- [Datalog Educational System](http://des.sourceforge.net/) – deductive database system with Datalog, SQL, Relational Algebra, Tuple Relational Calculus and Domain Relational Calculus as query languages (DES)

## ORM

### Python
- [Pony](https://github.com/ponyorm/pony/) – writes queries to the database using Python generator expressions and lambdas, analyzing the abstract syntax tree of the expression and translating it into a SQL query (SQLite, MySQL, PostgreSQL and Oracle)
- [PINQ](https://macropy3.readthedocs.io/en/latest/pinq.html#pinq) – write your database queries like queries on in-memory lists (uses SQLAlchemy)

## Using SQL

### CLI
- [OctoSQL](https://github.com/cube2222/octosql) – allows you to join, analyse and transform data from multiple databases and file formats using SQL
- [dsq](https://github.com/multiprocessio/dsq) – execute SQL on JSON, CSV, Excel, Parquet, and more
- [textql](https://github.com/dinedal/textql) – execute SQL on structured text like CSV or TSV
- 
