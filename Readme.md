![Visitors](https://api.visitorbadge.io/api/visitors?path=https://github.com/Zaytsev-Dmitry/dependency-counter-maven-pluginVisits&countColor=%230c7ebe&style=flat&labelStyle=none)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?logo=java&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?logo=Apache%20Maven&logoColor=white)
### Run phase:
 - COMPILE

### How to run:
```
mvn counter.plugin:dependency-counter-maven-plugin:1.0.0-SNAPSHOT:calculate
mvn counter.plugin:dependency-counter-maven-plugin:calculate
```

### How to add in project:
```
<repositories>
    <repository>
        <id>[name-project]-mvn-repo</id>
        <url>https://raw.github.com/Zaytsev-Dmitry/dependency-counter-maven-plugin/mvn-repo/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>

<dependency>
    <groupId>counter.plugin</groupId>
    <artifactId>dependency-counter-maven-plugin</artifactId>
    <version>{actual-version}</version>
</dependency>

```