## Java - Restful access 
Learn Java and Spring Boot restful end point

### Components
1. Rest Repository (*CrudRepository, PagingAndSortingRepository*)
2. JPA
3. H2 Database


### Pre-reqs
- Java 17+
- Maven 3.5+


### Build/Run
`./mvnw spring-boot:run`  


### Results
With 3 files, able to support following HTTP methods
- GET /people
- GET /people/1
- POST /people
- GET /people/search
- GET /people/search/..query params..
- PUT
- PATCH
- DELETE


*Docs: https://spring.io/guides/gs/accessing-data-rest*
