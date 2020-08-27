# sonar-java-test
Local
```shell script
mvn -X --update-snapshots org.jacoco:jacoco-maven-plugin:prepare-agent sonar:sonar -Djavax.xml.accessExternalSchema=all -Dsonar.host.url=http://localhost:9000 -Dsonar.login=admin -Dsonar.password=admin -Dsonar.dependencyCheck.reportPath=./target/dependency-check-report.xml
```