# mvn-repo
maven repository for java library that does not release via maven central

```xml
 <dependency>
            <groupId>it.sauronsoftware</groupId>
            <artifactId>ftp4j</artifactId>
            <version>1.7.2</version>
        </dependency>
        <dependency>
            <groupId>com.gaurav.tree</groupId>
            <artifactId>jc-tree</artifactId>
            <version>1.2.1</version>
        </dependency>
```
Add special repository. 

```xml
 <repositories>
 ...
        <repository>
            <id>github-mvn-releases</id>
            <url>https://raw.github.com/dahoba/mvn-repo/repository/</url>
        </repository>
    </repositories>
```

