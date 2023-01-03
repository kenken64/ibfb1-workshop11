## Workshop 11

1. Compile maven project
```
mvn compile
```

2. Package maven project
```
mvn package
```

3. Clean up the maven project
```
mvn clean
```

4. Run spring boot locally
```
mvn spring-boot:run
```

5. Login to railway, this will launch your browser (access using github)
```
railway login
```

6. Init your project to enable railway

```
railway init
```
7. Change the jdk version under the pom.xml

```
<properties>
    <java.version>11</java.version>
</properties>
```

8. Poject provision completed

```
railway up
```
