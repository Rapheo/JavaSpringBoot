# Enable devtool in INTELIJ

First paste this in you pom file:

<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
    <version>3.1.3</version>
</dependency>

Then go to 

File > Settings > Build, Execution, Deployment > Compiler > tick (Build project automatically)

and 

File > Settings > Advanced Settings > tick (Allow auto-make to start even if developed application is currently running)



