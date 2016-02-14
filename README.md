# mvn-repo
This is a private maven repository for `unclazz.org`. 
To use this repository as artifact source for your project,
insert a code snippet below into `pom.xml`.

```xml
<repositories>
    ...
    <repository>
        <id>unclazz-mvn-repo</id>
        <url>https://raw.github.com/unclazz/mvn-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
<dependencies>
    ...
    <dependency>
        <groupId>org.unclazz.(sub group id)</groupId>
        <artifactId>(artifact name)</artifactId>
        <version>(version name)</version>
    </dependency>
<dependencies>
```

