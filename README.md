Logentries Maven Repository
===========================

Logentries Java support for Maven users.

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
            <artifactId>logentries-appender</artifactId>
            <version>1.1.8</version>
        </dependency>
    </dependencies>
    
This Java library has support for both log4j and logback. They are optional dependencies, enter one of the below snippets 
inside your `<dependencies>` if you don't already have either log4j or logback installed.

For log4j:

    <dependency>
        <groupId>log4j</groupId>
		<artifactId>log4j</artifactId>
		<version>1.2.17</version>
	</dependency>
    
For logback:

    <dependency>
        <groupId>ch.qos.logback</groupId>
        <artifactId>logback-classic</artifactId>
        <version>0.9.30</version>
    </dependency>
