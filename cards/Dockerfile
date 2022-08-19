#Start with a base image containing Java runtime
FROM openjdk:11 as build



# Add the application's jar to the container
COPY target/cards-0.0.1-SNAPSHOT.jar.original cards-0.0.1-SNAPSHOT.jar.original

#execute the application
ENTRYPOINT ["java","-jar","/cards-0.0.1-SNAPSHOT.jar.original"]