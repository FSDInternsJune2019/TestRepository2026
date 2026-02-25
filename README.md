# TestRepository2026
======================Lombok STS===============================================================================================================
Find your lombok.jar, for example, it might be located at C:\Users\{your username}\.m2\repository\org\projectlombok\lombok\1.18.42\lombok-1.18.42.jar
Copy lombok-1.18.42.jar to the STS 5 root directory and rename it to lombok.jar.
Modify the SpringToolsForEclipse.ini file in the STS 5 root directory, adding -javaagent:lombok.jar at the end.
Restart STS 5


===============IntelliJ Spring Boot DevTools=================================================================================================
Enable Automatic Build: Go to File -> Settings -> Build, Execution, Deployment -> Compiler and check the option Build project automatically.
Allow Auto-Make: Go to File -> Settings -> Advanced Settings and check the option Allow auto-make to start even if developed application is currently running.
