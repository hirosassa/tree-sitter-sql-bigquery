[![Build/Test](https://github.com/TKNGUE/tree-sitter-sql-bigquery/actions/workflows/ci.yml/badge.svg)](https://github.com/TKNGUE/tree-sitter-sql-bigquery/actions/workflows/ci.yml)

# tree-sitter for BigQuery's SQL

This project supports StandardSQL in BigQuery.
You could try out the demo on [Github Pages](https://tkngue.github.io/tree-sitter-sql-bigquery/)

# Supported BigQuery SQL feature

- [x] Basic Literals/Expressions
- [x] Query Statement 
- [x] DML Statements 

- [ ] DDL Statements

  - [x] CREATE syntax for TABLE/VIEW/MATERIALIZED_VIEW
  - [x] CREATE synteax for FUNCTION
  - [x] CREATE syntax for TABLE FUNCTION
  - [ ] DELETE syntax for any
  - [ ] ALTER sytnax for any

- [ ] DCL Statements
- [ ] Procedural Lalnguage
- [ ] BigQuery ML

- [ ] Pre-GA features
    - [ ] JSON Literal
    - [ ] Collation

### References

- ZetaSQL: https://github.com/google/zetasql/blob/master/docs/README.md
- Other SQL Projects :
    * https://github.com/m-novikov/tree-sitter-sql
    * https://github.com/DerekStride/tree-sitter-sql
    * https://github.com/dhcmrlchtdj/tree-sitter-sqlite

## Development

### Running tests

```
npm install --also=dev
npm test
```

### Debbuging

- `npm run parse <file.sql>` outputs a syntax tree

