# spring-boot


Generating JAR file
```
    mvn package
```

Executing JAVA application
```
    java -jar target/myproject-0.0.1-SNAPSHOT.jar
``` 

Building Container
```
    docker build java
```

Tagging Container
```
    docker tag <ID> rofreitas/lgp:latest
```

Pushing Container to DockerHub
```
    docker push rofreitas/lgp
```

