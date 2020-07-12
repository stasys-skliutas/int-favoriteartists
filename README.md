[![Pipeline Status](https://gitlab.com/stasys/int-favoriteartists/badges/master/pipeline.svg)](https://gitlab.com/stasys/int-favoriteartists/pipelines)
## Build and run
### Prerequisites
+ Java 11 JDK installed ([download](https://adoptopenjdk.net/releases.html?variant=openjdk11&jvmVariant=openj9))
### Make executable
This will result in executable named `favoriteartists-0.0.1-SNAPSHOT.jar` built in project's `/build/libs` directory.
To build service executable issue:
```shell script 
# In *nix like environments
./gradlew clean bootJar
# In Windows
gradlew.bat clean bootJar
```
### Run
```shell script 
java -jar build/libs/favoriteartists-0.0.1-SNAPSHOT.jar
```