# Simple Spring Hibernate Application Using Annotations

In this project i have integrate `Spring` with `Hibernate` using annotation based configuration. 
I have developed a simple CRUD oriented web application containing a form asking user input, saving that input in `MySQL` database using Hibernate, 
retrieving the records from database and updating or deleting them within `transaction`, all using annotation configuration.

**Testing** I have added unit and integration test using `TestNG`, `mockito`, `spring-test`, `DBUnit` & `H2 database`

**Following technologies being used**

- Spring 4.0.6.RELEASE
- Hibernate Core 4.3.6.Final
- Validation-api 1.1.0.Final
- Hibernate-validator 5.1.3.Final
- MySQL Server 5.6
- Maven 3
- JDK 1.8
- Tomcat 9.0.0.M21
- Eclipse JUNO Service Release 2
- TestNG 6.9.4
- Mockito 1.10.19
- DBUnit 2.2
- H2 Database 1.4.187
#
**Following is the final project structure**

![alt text][structure]

[structure]: https://lh6.googleusercontent.com/XF8ZTIjvsZfmt_TgHuTY__GTki8m9rEFHIt5GVaMIbF4CX_waFUOdWODxujgNT0SlOcM8QIk9vxMa2g "project structure"

![alt text][test]

[test]: https://lh3.googleusercontent.com/EGf7qWpdDzOxCUQzY1EfbMOeELAg9kkjWQWpZKm_8YGT6y6VYwkKmu4gAFmpEtYXdZz-fmS_Tl6Bs_o "test structure"
#
**Create Schema in database**
<pre> CREATE TABLE EMPLOYEE(
    id INT NOT NULL auto_increment, 
    name VARCHAR(50) NOT NULL,
    joining_date DATE NOT NULL,
    salary DOUBLE NOT NULL,
    ssn VARCHAR(30) NOT NULL UNIQUE,
    PRIMARY KEY (id)
); </pre>
#
