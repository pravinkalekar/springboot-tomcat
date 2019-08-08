## Introduction

This is a Simple SpringBoot Tomcat example application created using Maven [Archetype](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html).

It starts a tomcat instance on localhost:8080 and prints the output from the injected bean service.

I have added another REST end point which demonstrates how you can pass Request Parameters.

```
http://localhost:8080/test?name=Pravin
```

I have also added the Java Code Coverage Maven plugin to make sure we write test cases for a minimum of 90% coverage ratio.