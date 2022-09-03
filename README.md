# Web app with user/password authentication

### How to run
1. Install JDK 17 https://adoptium.net/temurin
1. Install https://maven.apache.org/
2. Run command:
```
mvn clean package
```
3. Run command:
```
java -jar -Dapp.user=<your user> -Dapp.password=<your password> target/auth.jar
```
for example
```
java -jar -Dapp.user=john -Dapp.password=MySecretPassword123 target/auth.jar
```
4. Open the page http://localhost:8080
