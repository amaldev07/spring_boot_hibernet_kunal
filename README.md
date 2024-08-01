# sprint_boot_hibernet_kunal
1. Install JDk
    https://www.oracle.com/in/java/technologies/downloads/#jdk17-windows
    Install jdk
2. Install Apache Maven
    https://maven.apache.org/download.cgi
    1. Extract the downloaded ZIP file to a directory of your choice (e.g., C:\Program Files\Apache\maven).
        Set up environment variables:
        MAVEN_HOME:
            Go to System Properties > Environment Variables.
            Under System Variables, click New and add MAVEN_HOME with the path to the Maven directory (e.g., C:\Program Files\Apache\maven). 
        Add Maven to PATH:
            Find the Path variable under System Variables and edit it.
            Add a new entry with %MAVEN_HOME%\bin.
            Open a new command prompt and run mvn -version to verify the installation.
3. To automatically build and run your Java application after each change
    Use Spring Boot DevTools
        Add the dependency to your pom.xml
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
            <optional>true</optional>
        </dependency>

