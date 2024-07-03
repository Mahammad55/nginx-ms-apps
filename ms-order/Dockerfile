FROM openjdk:17
COPY build/libs/ms-order-1.0-SNAPSHOT.jar /app/
WORKDIR /app/
ENTRYPOINT ["java"]
CMD ["-jar", "/app/ms-order-1.0-SNAPSHOT.jar"]