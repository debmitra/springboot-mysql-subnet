FROM java:8
VOLUME /tmp
ADD gs-mysql-data-0.1.0.jar app.jar
EXPOSE 9077
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
