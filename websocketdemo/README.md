**Note:** This one uses a Maven build file, not Gradle.

I'm not sure why, but it's using my default java (23), even though pom.xml says java.version=21.

--

Built from following this tutorial: https://spring.io/guides/gs/messaging-stomp-websocket

Run with `./mvnw spring-boot:run`

Then open "localhost:8080" in your browser to do stuff


Build jar with `./mvnw clean package` then run with java -jar target/gs-messaging-stomp-websocket-0.1.0.jar


