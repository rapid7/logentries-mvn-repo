Logentries Maven Repository
===========================

Logentries Log4j Jaba plugin for Maven users.

Place the following snippet in your pom.xml:

    <repositories>
      <repository>
        <id>logentries-snapshots</id>
        <url>https://github.com/logentries/logentries-mvn-repo/raw/master/releases</url>
      </repository>
    </repositories>
    <dependencies>
      <dependency>
        <groupId>com.logentries</groupId>
        <artifactId>leappender</artifactId>
        <version>1.1.4</version>
        <scope>compile</scope>
      </dependency>
    </dependencies>