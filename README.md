# GraalVM-Scala-Hellworld

A helloworld project which serves as an example for GraalVM, Scala and Maven.

## Build

Clone this repository, make sure GraalVM is used as your Java Environment. You should have installed native-image as well.

    mvn package 
    
This command should create a binary in your target folder which is named `helloworld`` It can be executed without JRE, and is about 7 MB in size.

Read more about GraalVM here: https://www.graalvm.org/reference-manual/

    