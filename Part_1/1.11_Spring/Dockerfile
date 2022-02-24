#Porject requires Java 8. I found this on dockerhub with the help of link
FROM openjdk:8

#required port is 8080
EXPOSE 8080

#Setting work directory
WORKDIR usr/src/app

#Copy the source code
COPY . .

#Build the project as per README
RUN ./mvnw package

#Command to run the application
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
