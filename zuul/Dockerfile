FROM java:8
COPY ./build/libs/zuul-service-0.0.1-SNAPSHOT.jar /usr/src/item/
WORKDIR /usr/src/item
EXPOSE 8069
ENTRYPOINT ["java","-jar","zuul-service-0.0.1-SNAPSHOT.jar"]