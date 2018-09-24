SELECT * FROM movies;

SELECT name FROM people;

UPDATE people
SET name = 'Keith Douglas'
WHERE name = 'Kith Douglas';

SELECT name FROM people
WHERE name = 'Oksana Richards';

DELETE FROM movies
WHERE title = 'Batman Begins';

INSERT INTO people (name) VALUES ('Craig Morton');

DELETE FROM people WHERE name = 'Pawel Scott';

INSERT INTO movies (title, year, show_time) VALUES ('Avengers: Infinity War', 2017, '18:30');

SELECT show_time FROM movies WHERE title = 'Guardians of the Galaxy';

UPDATE movies
SET show_time = '18:20'
WHERE title = 'Guardians of the Galaxy

DELETE FROM people
WHERE name LIKE '%A%'; 
