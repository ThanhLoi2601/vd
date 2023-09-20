## Deploy Java Servlet

### 1. Env:

- JDK
- Tomcat

### 2. Docker

- Build JDK
- Build Tomcat

> Build Tomcat

```
FROM tomcat:9.0.58-jdk20-openjdk-slim
```
[Link Tomcat Alpine](https://hub.docker.com/layers/library/tomcat/9.0.8-jre8-alpine/images/sha256-c4845bc8196eb07ff6e993415a60eac4273de59ce432133d66a4d2f9f72e564b)

> Build JDK:

```
FROM VERSION_OPENJDK_ALPINE_YOUR_PC
```

> Run on Port 8080

```
EXPOSE 8080
```