# Cinema app
![](https://images.all-free-download.com/images/graphiclarge/cinema_movie_vector_background_graphics_589337.jpg)




#  Project Description
This project is an imitation of working cinema app for registered users

After you have authenticated in the app you have the following options.

For users with access ADMIN:
- get all existing cinema-halls, movies, movie-sessions
- add new cinema-halls, movies, movie-sessions to DB, update or delete information from DB
- get user's details by email

For users with access USER:
- view all available cinema-halls, movies, movie-sessions
- add a ticket to your shopping cart
- add order
- view order history


##  Project Structure

This Project is based on 3-layered architecture:

- Data access layer (DAO)

- Application layer (service)

- Presentation layer (controllers)

## Technologies:
- JAVA 11+
- Spring core, security, mvc
- Hibernate
- Tomcat
- MySQL
- Maven

## System requirements

- IntelliJ IDEA Ultimate IDEA
- Web-server (Apache Tomcat)
- Database (MySQL)

## Configure you env

- First, make sure your env meets requirements listed above
- Create schema in MySQL
- Then clone project on your IDE, change your driver, url, username and password in resources/db.properties file
- Configure TomCat Local server
- After loading app you can test it logging in as:
  username admin@i.ua password admin123 or
  username user@i.ua password user123