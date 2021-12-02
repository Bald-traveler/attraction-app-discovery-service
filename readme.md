# Attractions Bald Traveler
The Attractions Backend is responsible for handling all requests for users and places.

Users use the system and need to authenticate with the backend to make changes or add new places.

Places are venues, parks, museums, restaurants, hotels, etc that users feel are worth visiting.

[![Java CI with Maven](https://github.com/Bald-traveler/attraction-app-discovery-service/actions/workflows/maven.yml/badge.svg)](https://github.com/Bald-traveler/attraction-app-discovery-service/actions/workflows/maven.yml)

## Discovery Service
This is the Eureka Discovery Server.  The code here is bolierplate to run the Spring Cloud Eureka Server.

### Testing
No testing is done in this package as it's all bolierplate code.

### Building

mvn clean install

### Installation/Running

```bash
java -jar attractionsappdiscoveryservice-<version>.jar
```
