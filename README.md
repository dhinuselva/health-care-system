# Health-Care-System
Enrollment Api for Health care system using Spring Boot

# Api Description
The Enrollment Api provides below set of operations to enable the Enrollment process for the Health Care System
1) Add Enrollee
2) Update Enrollee
3) Retrieve Enrollee details
4) Delete Enrollee
5) Add Dependent under an Enrollee
6) Update Dependent details
7) Retrieve Dependent details
8) Delete Dependent

# Technology stack
1) Sprint Boot v2.4.0
2) PostgreSQL v12
3) Java SDK 1.8
4) Maven v3.6.3
5) Lombak framework
6) Model Mapper
7) GIT

# Steps to Run the Application
1) git clone https://github.com/dhinuselva/health-care-system.git
2) Run "mvn clean install"
3) cd target
4) java -jar healthcaresystem-0.0.1-SNAPSHOT.jar

# Postman
Sample requests for all the API operations are added to the below Postman project

# Swagger API Documentation
Use the url - http://localhost:9090/swagger-ui/ to get the Swagger API documentation page

![Alt text](/screenshots/swagger.png?raw=true "Swagger")

Use the url - http://localhost:9090/v2/api-docs to get the Swagger API documentation in JSON format

# Health Check
Use the url - http://localhost:9090/actuator to get the health check metrics of your application
