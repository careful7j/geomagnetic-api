# Geomagnetic API

## This service is used of an android application [Weather: Any place on the Earth!](https://play.google.com/store/apps/details?id=net.c7j.wna&hl=ru "Google Play")

The Geomagnetic API gets a geomagnetic forecast from [SWPC NOAA API](https://services.swpc.noaa.gov/text/3-day-geomag-forecast.txt) as a common .txt file, it occurs every day. After a process of getting the service parses the file and saves a result to a database. All process is entirely self-acting.  
The Weather Application accesses the API via REST.

### Tech

Geomagnetic API uses of next libraries:

* [Spring Boot]
* [Spring Starter Web]
* [Spring Starter Actuator]
* [Spring Starter Validation]
* [PostgreSQL]
* [Lombok]
* [JUnit5]
* [H2] 

This project itself is open source with a [public repository][git-repo].

### Build

### Docker

License
----

MIT


[Spring Boot]: <https://spring.io/projects/spring-boot>
[Spring Starter Web]: <https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-web/2.1.5.RELEASE>
[Spring Starter Actuator]: <https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-actuator/2.1.5.RELEASE>
[Spring Starter Validation]: <https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation/2.1.5.RELEASE>
[PostgreSQL]: <https://www.postgresql.org/>
[Lombok]: <https://projectlombok.org/>
[JUnit5]: <https://junit.org/junit5/>
[H2]: <https://www.h2database.com/html/main.html>
[git-repo]: <https://github.com/Illine/geomagnetic-api>