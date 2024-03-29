# Taxi Service :oncoming_taxi:
### Project description:
This is a simple web application, as a learning project, realized in Java, based on SOLID principles, implements basic knowledge of HTML.
The main purpose of this application is to keep records of taxi service drivers and cars, so firstly you have to register yourself as a taxi driver, then the following sections will be available to you:

+ Create/delete driver, manufacturer or car
+ Add driver to car
+ Display all drivers, cars, current cars for driver, manufacturers.

### Project architecture represent by:

- **DAO** - *Data access Tier*
- **Service** - *Business Tier*
- **Controllers** - *Presentation Tier*

### Data management structure

![img.png](img.png)

### Technologies:

+ Java 11
+ Apache Tomcat 9
+ MySQL 8
+ Maven 3.8
+ Java Servlet 4
+ JSTL 1.2
+ Dependency Injector
+ HTML, CSS

### Launching the project locally: :rocket:

1. Download and install JDK 11, Git, Maven, MySQL (MySQL Workbench), Apache Tomcat 9.
2. Fork this project.
3. Configure MySQL:
    * Create a database connection;
    * Initialize tables in the database by the path: `src/main/resources/init_db.sql`;
    * Establish a connection between the database and IntelliJ IDEA in the file: `src/main/java/taxi/util/ConnectionUtil.java`;
4. Configure Tomcat 9:
    * Add locally Tomcat 9 in configurations;
    * Select `taxi_service:war exploded` in the fix window;
    * Change the initial path from `/web_security_war_exploded` to `/`;
5. Run the project.