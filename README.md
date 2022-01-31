# TODOProj
List of dependencies:

Spring-boot starter web
Spring-boot starter JPA
Spring-boot starter security
Spring-boot starter test
spring-boot-devtools



Build Spring Boot Project with Maven


mvn package
mvn install
java -jar target/TodoProj-0.0.1-SNAPSHOT.jar


Database: todolist
Table:TODO
creating a table:
CREATE TABLE TODO (taskID int, task varchar(255), status TINYINT );

list of APIS
http://localhost:8080/todoproj/save

http://localhost:8080/todoproj/get

http://localhost:8080/todoproj/update/1

http://localhost:8080/todoproj/delete/1





