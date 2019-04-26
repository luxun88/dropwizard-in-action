# dropwizard-in-action

How to start the dropwizard-in-action application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/hello-world-1.0-SNAPSHOT.jar server hello-world.yml`
1. To check that your application is running enter url `http://localhost:8080/hello-world`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`

Refference
https://www.dropwizard.io/1.3.5/docs/getting-started.html
