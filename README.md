## Hibernate DAO

### Technologies
JPA, Hibernate, MySQL <br />


### Project Structure
Model: <br />
JPA Entity <br />

DAO: <br />
CRUD operations <br />
Interface generic <br /> 
Implementation  <br />
org.hibernate.Session <br />
org.hibernate.SessionFactory <br />

Service: <br />
Implementation <br />
Transactions: write operations <br />





### Steps
##### MySQL
Start MySQL server  <br />

create database: <br />
*mysql –uroot –p –e “source src/main/resources/create_database.sql”*  <br />

create table:  <br />
*mysql –uroot –p –e “source src/main/resources/create_table.sql”*  <br />


##### Compile, create jar
*mvn clean compile package*  <br />


##### Run Application
*java -jar target/jar-name.jar* <br />



