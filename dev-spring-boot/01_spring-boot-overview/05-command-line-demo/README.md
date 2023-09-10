# Command_line Run

To run from the commant line simply 'cd' to the file directory and run 'mvnw package', it will build the project into a .jar file located in genarated 'target' folder.

'cd target' and run 'java -jar jarname.jar'


If you want to run with spring-boot mavin plugin run 'mvnw spring:run'.

If you already have mavin installed locally in you computer then just use 'mvn' instead of 'mvnw'

if you get no JAVA_HOME evniroment then just create a new variable in the and put Variable Name = JAVA_HOME and Variable value = C:\Program Files\Java\jdk-**  (** == version)
