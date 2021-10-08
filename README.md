# Jumia-service

# JUMIA-EXERCISE-SERVICE

This is a sample spring boot app that's categorzie and filter phone numbers on country name and state (valid or not valid).
built on docker image.

## Prerequisites -> navigate to project directory then :
 
1 - First run mvn clean install to create jar file.
2 - execute docker build -t jumia-exercise-service.jar . command to build docker image.
3 - execute docker run -p 8080:8080 jumia-exercise-service.jar command to run the docker container

Then go to http://localhost:8080/swagger-ui.html#/ to test the application functionality. 
