=== Parent Maven POM ===

Add our custom repository:

```
<repository>
    <id>bintray</id>
    <url>http://dl.bintray.com/guestful/maven</url>
</repository>
```

And in your POM:

```
<parent>
    <groupId>com.guestful</groupId>
    <artifactId>maven-pom</artifactId>
    <version>?</version>
</parent>
```

Checkout last version [https://bintray.com/guestful/maven/maven-pom/view/files/com/guestful/maven-pom](here)
