<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">

  <modelVersion>4.0.0</modelVersion>

  <groupId>com.example.maven-samples</groupId>
  <artifactId>parent</artifactId>
  <packaging>pom</packaging>
  <version>1.0-SNAPSHOT</version>
  <name>Parent</name>
  <description>Just a pom that makes it easy to build both projects at the same time.</description>

  <modules>
    <module>multi-module</module>
    <module>single-module</module>
  </modules>

  <prerequisites>
    <maven>3.0.3</maven>
  </prerequisites>

</project>
