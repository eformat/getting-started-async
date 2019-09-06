# getting-started-async

```
export GRAALVM_HOME=/opt/graalvm-ce-19.1.1
mvn package -Pnative -DskipTests -Dnative-image.docker-build=true
./target/getting-started-camel-1.0-SNAPSHOT-runner
```