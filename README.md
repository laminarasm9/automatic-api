The following is a list of tools that automatically expose a REST, GraphQL, or another kind of API for your database.

|                          Project name/link                           |                                       Database(s) supported                                       | API type | Implementation language |                  License                  |          GitHub stats           |   Notes    |
|----------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|----------|-------------------------|-------------------------------------------|---------------------------------|------------|
| [Datasette](https://github.com/simonw/datasette)                     | SQLite 3                                                                                          | REST     | Python 3                | Apache 2.0                                | 1092&nbsp;★, 253&nbsp;commits   | Read-only. |
| [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) | MySQL, PostgreSQL, SQLite, MongoDB, CouchDB, and [others](https://www.dreamfactory.com/products). | REST     | PHP 5                   | Apache 2.0, proprietary (optional extras) | 723&nbsp;★, 760&nbsp;commits    |            |
| [PostGraphQL](https://github.com/postgraphql/postgraphql)            | PostgreSQL                                                                                        | GraphQL  | TypeScript (Node.js)    | MIT                                       | 4484&nbsp;★, 664&nbsp;commits   |            |
| [PostgREST](https://github.com/begriffs/postgrest)                   | PostgreSQL                                                                                        | REST     | Haskell                 | MIT                                       | 10051&nbsp;★, 1351&nbsp;commits |            |
| [sandman2](https://github.com/jeffknupp/sandman2)                    | All supported by SQLAlchemy (MySQL, PostgreSQL, SQLite, Oracle, MS SQL, and others).              | REST     | Python 2/3              | Apache 2.0                                | 641&nbsp;★, 129&nbsp;commits    |            |
| [tuql](https://github.com/bradleyboy/tuql)                           | SQLite 3                                                                                          | GraphQL  | JavaScript (Node.js)    | MIT                                       | 174&nbsp;★, 34&nbsp;commits     | Read-only. |
| [xmysql](https://github.com/o1lab/xmysql)                            | MySQL                                                                                             | REST     | JavaScript (Node.js)    | MIT                                       | 1672&nbsp;★, 205&nbsp;commits   |            |


GitHub stats updated 2017-12-18.

# Contributing

Your contributions are welcome! Please submit a pull request or create an issue to add a new project to the list or update an existing one.

Note that `README.md` is automatically generated from `README.md.template` and the data in [`data/`](./data/). Do not edit `README.md` directly. To update a project's information, edit the corresponding file in `data/`. To add a project, create a new file.

# License

This document and the data in `data/` are licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). By contributing you agree to release your contribution under this license.
