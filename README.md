### gradle bulid

build.gradle에서 processResources 주석 풀기
```shell
./gradlew build
```

### jar 실행하기
```shell
java -jar [실행할 jar 파일명]
```

### 배포할 때만 react 포함하여 build하기
build.gradle에서 tasks.bootJar 주석 풀기
```shell
./gradlew bootJar
```

test
