# Сinema appliсation

Do you have cinema business or want some?
So you need this app!

Cinema app help you with organization of tickets, orders and users.
Application is easy to use and very understandable.

***
![cinema](https://static.turbosquid.com/Preview/2019/06/11__15_31_43/Cinema_hall.jpg48B2F185-B69C-4B97-83DC-D8E41C93B48EDefault.jpg)
***

### Features of this app :
- Users have their roles for easier managing access to features in this app.
- Cinema app implements 3 layers architecture with DAO, Service, Controller layers.
- In front level we use JSON objects for better view in web.
- Each user need firstly get authenticated.
***
### Technologies which was used in app :
* Apache Tomcat (v9.0.56) 
* Hibernate
* HQL
* Maven
* Spring
* Spring Web
* Spring Security
***

### Things that we need to do for correct working application:
1. Firstly we need to install our additional applications. Such as :
   * Apache Tomcat (v9.0.56)
2. Configure Tomcat in IDE
3. Create a schema in MySQL Workbench
4. In `src/main/resources/db.properies` we need to do some changes, and replace with yours :
   * db.drive, db.url, db.user and db.password
   ```
    //example
    db.driver=com.mysql.cj.jdbc.Driver
    db.url=jdbc:mysql://localhost:3306/(name od your schema)?serverTimeZone=UTC
    db.user=root
    db.password=qwerty
