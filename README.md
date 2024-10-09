# gb-java-demos

## IntelliJ IDEA stuff

Make sure you have the correct SDK in both these places:

* File -> Project Structure -> Project -> SDK

* Main Settings -> Build, Execution, Deployment -> Build Tools -> Gradle -> Gradle JVM

## Gradle command line

Make sure it's actually using the SDK you want.  It won't use `JAVA_HOME`!

Run `gradle -v` to see what it's actually using.

(reference: https://stackoverflow.com/questions/18487406/how-do-i-tell-gradle-to-use-specific-jdk-version)

You can do one of these:

* Edit/create `~/.gradle/gradle.properties` to contain `org.gradle.java.home=/path/to/desired/sdk`

* `./gradlew -Dorg.gradle.java.home=/path/to/desired/jdk`
