# Limbo
[![Build and publish](https://github.com/SVA-su/Games-Limbo/actions/workflows/build.yml/badge.svg?branch=translated)](https://github.com/SVA-su/Games-Limbo/actions/workflows/build.yml)
## Standalone Limbo Minecraft Server (Currently 1.21.1)

### Starting the server
Use the following command lines to start the limbo server just like any other Minecraft server
```
java -jar Limbo.jar --nogui
```

Put the world scheme file in the same folder as the server jar file and configure the `server.properties` file to your needs 
***
### Maven
```html
<repository>
  <id>loohp-repo</id>
  <url>https://repo.loohpjames.com/repository</url>
</repository>
```
```html
<dependency>
  <groupId>com.loohp</groupId>
  <artifactId>Limbo</artifactId>
  <version>VERSION</version>
  <scope>provided</scope>
</dependency>
```
Replace `VERSION` with the version.
