# Limbo
[![Build and publish](https://github.com/SVA-su/Games-Limbo/actions/workflows/build.yml/badge.svg?branch=translated)](https://github.com/SVA-su/Games-Limbo/actions/workflows/build.yml)
## Standalone Limbo Minecraft Server (Currently 1.21.4)

### Starting the server
Use the following command lines to start the limbo server just like any other Minecraft server
```
java -jar Limbo.jar --nogui
```

Put the world scheme file in the same folder as the server jar file and configure the `server.properties` file to your needs 
***
### Demo Limbo Server
```
IP: mc.loohpjames.com
```
![Server Banner](https://api.loohpjames.com/serverbanner.png?ip=mc.loohpjames.com&width=918&name=IP:%20mc.loohpjames.com)
***
### Downloads (1.17.1-1.21.4)
- [Jenkins](http://ci.loohpjames.com/job/Limbo/)
***
### Offical Plugins
- [ViaLimbo](https://github.com/LOOHP/ViaLimbo/) - Allow other Minecraft versions to join through the use of [ViaProxy](https://github.com/ViaVersion/ViaProxy)
- [Floodgate-Limbo](https://github.com/LOOHP/floodgate-limbo) - [Geyser's](https://geysermc.org/) [floodgate](https://geysermc.org/wiki/floodgate/) plugin implemented for Limbo
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
