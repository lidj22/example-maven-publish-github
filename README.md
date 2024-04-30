# Example Github Maven Project

Example repository to publish maven artifact to github repo.

## Upstream
In `upstream`, deploy artifact to Github repository:
```sh
mvn clean deploy
```

## Downstream
In `downstream`, run
```sh
mvn clean install
```
Run jar file:
```sh
java -jar target/downstream-artifact-*.jar
```