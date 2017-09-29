# IMDb-Web-Application


This project focuses on querying relational databases using SQL in PHP along with HTML/CSS.

Background Information:
The Six Degrees of Kevin Bacon is a game based upon the theory that every actor can be connected to actor Kevin Bacon by a chain of movies no more than 6 in length. Most, but not all, can reach him in 6 steps. 12% of all actors cannot reach him at all.
The project is built on HTML/CSS and PHP code for a web site called MyMDb that mimics part of the popular IMDb movie database site. The site will show the movies in which another actor has appeared with Kevin Bacon.

File Lists:

•	1degree.php, the page showing search results for all films with the given actor and Kevin Bacon
•	2degrees.php, the page showing search results for two degrees of separation with the given actor and Kevin Bacon
•	1genre.php, the page showing genre(s) with max. number of movies
•	2genre.php, the page showing actors with max. number of movies of a user-given genre
•	director.php, the page showing actors who also directed a movie
•	common.php, any common code that is shared between pages
•	bacon.css, the CSS styles shared by all pages
•	output.txt, output file including SQL queries submitted and resulting output

Front-End:
You can use HTML/CSS, JavaScript/jQuery or any other JavaScript-based frameworks for front-end development.

Database System:
MySQL database

Movie Search Pages:
The search pages perform queries on the (small) imdb database using PHP's PDO.
