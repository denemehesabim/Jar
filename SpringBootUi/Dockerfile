FROM java:8
VOLUME /tmp
ADD target/SpringBootUi-1.0-SNAPSHOT.jar SpringBootUi.jar
RUN bash -c 'touch /SpringBootUi.jar'
EXPOSE 9000
ENTRYPOINT ["java","-jar","/SpringBootUi.jar"]
