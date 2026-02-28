## Exercise 3

Find all the Toy Story movies

```sql
SELECT title, director FROM movies
WHERE title LIKE 'Toy Story%';
```

Find all the movies directed by John Lasseter

```sql
SELECT title, director FROM movies
WHERE director = 'John Lasseter';
```

Find all the movies (and director) not directed by John Lasseter

```sql
SELECT title, director FROM movies
WHERE director != 'John Lasseter';
```

Find all the WALL-* movies

```sql
SELECT * FROM movies
WHERE title LIKE 'WALL-%';
```
