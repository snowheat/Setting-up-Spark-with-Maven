# Setting-up-Spark-with-Maven
First Spark tutorial solution with explanation

After cloning the repository you have cd to main my-app directory to execute maven build tool.
Execution below:
"mvn compile assembly:single"

-- > http://stackoverflow.com/questions/574594/how-can-i-create-an-executable-jar-with-dependencies-using-maven
mvn clean compile assembly:single


After that in target directory new jar file will pop up.
This jar file contains compiled and builded source code with all dependencies.

Now you just have to execute the program with below instruction:
java -cp ".\target\*" Main

Server starts and we can make request thorugh opening chrome browser
and pasting --> "localhost:4567/hello"
to address bar

==============================
https://github.com/kliakos/sparkjava-war-example

https://steveperkins.com/war-files-vs-embedded-servers/

