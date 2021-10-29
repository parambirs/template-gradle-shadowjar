## Java Shadow Jar Example

A small application that shows how to build a shadow jar
using SLF4J and LogBack Classic.

The plugin is configured in `build.gradle` as follows:

```
plugins {
    id 'com.github.johnrengelman.shadow' version '7.0.0'
    ...
}
```

### Usage
**Running with gradle:**
```
./gradlew run
```

**Creating and executing the fat jar:**
```
./gradlew shadowJar
java -jar build/libs/template-gradle-shadowjar-all.jar
```
