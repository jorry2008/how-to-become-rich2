# How to Become Rich

This is a tutorial about how to publish a Maven artifact to GitHub:

### Usage

Add the following to `pom.xml`:

```
<project ...>

    ...

    <repositories>
        <repository>
            <id>github-rich-repo</id>
            <name>The Rich Repository on Github</name>
            <url>https://jorry2008.github.io/how-to-become-rich/maven-repo/</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <groupId>com.diffcoder</groupId>
            <artifactId>how-to-become-rich</artifactId>
            <version>1.1-SNAPSHOT</version>
        </dependency>
    </dependencies>

    ...

</project>
```

### Sample code

```
Millionaire millionaire = new Millionaire();
System.out.println(millionaire.howToBecomeRich());
```
