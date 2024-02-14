Where clause
```
WHERE color = 'green'

```
WHERE with comparison operators
e.g. 
```
SELECT title
FROM films
WHERE release_year > 1960
```
Less than is also a thing, >=, etc, =

```
WHERE release_year <> 1960
```
That's all but 1960 aka not equal to.

Where with strings: 
```
SELECT title
FROM films
WHERE country = 'Japan'
```
Must be single quotes

Order -- comes after FROM statement, before LIMIT


Multiple criteria:
Presumably and/or? Naw it's
or, and, between

```
SELECT *
FROM coats
WHERE color = 'yellow' and blah = 'heehee'
```
and and or do what you'd expect 

must do full boolean statement w each -- jk no you don't e..g WHERE releas_year BETWEEN 1994 AND 2000 AND country='UK'

Remember to end queries with semicolons

between is inclusive
