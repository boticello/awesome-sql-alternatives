# Awesome SQL alternatives

## Relational data

### SQL transpilers

- [PRQL](https://github.com/max-sixty/prql) – simpler and more powerful SQL 
- [Logica](https://github.com/EvgSkv/logica) – logic programming language (BigQuery, SQLite, PostgreSQL)
- [Cytosm](https://github.com/cytosm/cytosm) – Cypher to SQL
- [HTSQL](https://www.htsql.org/doc/overview.html) – XPath-like navigational query language for relational databases and web service gateways (PostgreSQL, MySQL, SQLite, Oracle, Microsoft SQL Server)

### Other
- [Malloy](https://github.com/looker-open-source/malloy) – an experimental language for describing data relationships and transformations, akin to a SQL extension (BigQuery)
- [Flux](https://docs.influxdata.com/flux/) – functional data scripting language (**InfluxDB**, MySQL, PostgreSQL, CSV)

### Language or platform-specific
- [FunSQL.jl](https://github.com/MechanicalRabbit/FunSQL.jl) – library for compositional construction of SQL queries (Julia)
- [TreSQL](https://github.com/mrumkovskis/tresql) – query language built on SQL that selects data into hierarchical JSON objects (JDBC)
- [Kusto Query Language](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/) – requests are stated in plain text using a data-flow model that is easy to read, author, and automate (Azure)
- [Cloudwatch Logs Insight query language](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/CWL_QuerySyntax.html) – (Cloudwatch)
- [dplyr](https://github.com/tidyverse/dplyr/) – grammar of data manipulation, providing a consistent set of verbs (R)
- [SQL Frames](https://sqlframes.com/docs/sql_frames/intro) – low code data management framework that can be directly embedded in the browser to provide rich data visualization and UX (web)

### Custom databases
- [Rel](https://docs.relational.ai/rel/intro/overview/) – an expressive, declarative, and relational language designed for modeling domain knowledge (RelationalAI)
- [openCypher](https://github.com/bitnine-oss/agensgraph) – SQL and [Cypher](http://opencypher.org/) queries can be integrated into a single query ([AgensGraph](https://bitnine.net/agensgraph/), built on PostgreSQL)
- [EdgeQL](https://www.edgedb.com/tutorial) 
- 



## Poly-store
Query languages which operate on both relational and non-relational data

- [PartiQL](https://partiql.org/tutorial.html) – treats nested data as first class citizens and composes seamlessly with SQL, enabling intuitive filtering, joining and aggregation on the combination of structured, semistructured and nested datasets (AWS various, others)
- [Optic API](https://docs.marklogic.com/guide/app-dev/OpticAPI) – makes it possible to perform relational operations on indexed values and documents (Marklogic)

## Relational Algebra
- [Morel](https://github.com/julianhyde/morel) – Standard ML interpreter with relational extensions
- [Tutorial D](https://github.com/DaveVoorhis/Rel) – a desktop database management system that implements Date & Darwen's "Tutorial D" database language (Rel)
- [Datalog Educational System](http://des.sourceforge.net/) – deductive database system with Datalog, SQL, Relational Algebra, Tuple Relational Calculus and Domain Relational Calculus as query languages (DES)
- [Sift](https://github.com/RCHowell/Sift) – a basic, Relational Algebra based query engine built on top of Apache Arrow, drawing inspiration from Andy Grove's KQuery

## ORM

- [Pony](https://github.com/ponyorm/pony/) – writes queries to the database using Python generator expressions and lambdas, analyzing the abstract syntax tree of the expression and translating it into a SQL query (SQLite, MySQL, PostgreSQL and Oracle)
- [PINQ](https://macropy3.readthedocs.io/en/latest/pinq.html#pinq) – write your database queries like queries on in-memory Python lists (uses SQLAlchemy)
- [LINQ to SQL](https://docs.microsoft.com/en-us/dotnet/framework/data/adonet/sql/linq/) – a .NET component that provides a run-time infrastructure for managing relational data as objects


## Using SQL

### CLI
- [OctoSQL](https://github.com/cube2222/octosql) – allows you to join, analyse and transform data from multiple databases and file formats using SQL
- [dsq](https://github.com/multiprocessio/dsq) – execute SQL on JSON, CSV, Excel, Parquet, and more
- [textql](https://github.com/dinedal/textql) – execute SQL on structured text like CSV or TSV
- 
