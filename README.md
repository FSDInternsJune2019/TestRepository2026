# TestRepository2026
======================Lombok STS===============================================================================================================
Find your lombok.jar, for example, it might be located at C:\Users\{your username}\.m2\repository\org\projectlombok\lombok\1.18.42\lombok-1.18.42.jar
Copy lombok-1.18.42.jar to the STS 5 root directory and rename it to lombok.jar.
Modify the SpringToolsForEclipse.ini file in the STS 5 root directory, adding -javaagent:lombok.jar at the end.
Restart STS 5
