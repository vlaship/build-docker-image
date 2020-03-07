# build-docker

./gradlew clean build docker

./mvnw clean install dockerfile:build

docker run --name gradle -e "SPRING_PROFILES_ACTIVE=prod" -p 8080:8080 -t vlaship/build-tool
