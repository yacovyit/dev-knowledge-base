
---

## `sql/postgres.md`
```markdown
# PostgreSQL Commands

```sql
-- Connect
psql -U user -d dbname

-- List
\dt         -- tables
\l          -- databases

-- Create
CREATE TABLE test(id SERIAL PRIMARY KEY, name TEXT);

-- Query
SELECT * FROM test;
```
