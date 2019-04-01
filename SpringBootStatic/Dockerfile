FROM java:8
VOLUME /tmp
ADD target/SpringBootStatic-1.0-SNAPSHOT.jar SpringBootStatic.jar
RUN bash -c 'touch /SpringBootStatic.jar'
EXPOSE 9000
ENTRYPOINT ["java","-jar","/SpringBootStatic.jar"]
