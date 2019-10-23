# My Project

## Resource

**Restaurant**

Attributes:

* name (string)
* cuisine (string)
* hours (string)
* rating (integer)

## Schema

```sql
CREATE TABLE restaurants (
id INTEGER PRIMARY KEY,
name TEXT,
cuisine TEXT,
hours TEXT,
rating INTEGER);
```

## REST Endpoints

Name                           | Method | Path
-------------------------------|--------|------------------
Retrieve restaurant collection | GET    | /restaurants
Retrieve restaurant member     | GET    | /restaurants/*\<id\>*
Create restaurant member       | POST   | /restaurants
Update restaurant member       | PUT    | /restaurants/*\<id\>*
Delete restaurant member       | DELETE | /restaurants/*\<id\>*
