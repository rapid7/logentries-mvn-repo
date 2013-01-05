Logentries Maven Repository
===========================

Logentries Log4j Java plugin for Maven users.

Place the following snippet in your pom.xml:

    <repositories>
      <repository>
        <id>logentries-releases</id>
        <url>https://github.com/logentries/logentries-mvn-repo/raw/master/releases</url>
      </repository>
    </repositories>
    <dependencies>
      <dependency>
        <groupId>com.logentries</groupId>
        <artifactId>logentriesappender</artifactId>
        <version>1.1.6</version>
        <scope>compile</scope>
      </dependency>
    </dependencies>
