# auth-client
Spring-boot auth-client

## Usage

### Gradle
`./gradlew bootRun`

### Docker
1. `./gradlew build`
2. `docker build --build-arg JAR_FILE="build/libs/*.jar" -t auth-client .`
3. `docker run --network host auth-client`
