./gradlew test
./gradlew assemble
PACT_FILE=./microservices-pact-consumer/target/pacts/Foo_Consumer-Foo_Provider.json ./gradlew pactVerify
