# hello-java  |[![BINPIPE](https://img.shields.io/badge/YouTube-red.svg)](https://www.youtube.com/channel/UCPTgt4Wo0MAnuzNEEZlk90A)
A Simple "Hello World" in Java for Jenkins Demo

-Prerequisites: Jenkins should have git plugin and installed with Java compiler.
yum install java-devel

Repo Reference: https://github.com/prasanjit-/hello-java

```sh
#Build Steps:
echo "Compiling ... "
javac HelloWorld.java
echo "Execution ..."
java HelloWorld
jar cvfe HelloWorld.jar HelloWorld *.class
echo "============================"
#Execution:
java -jar HelloWorld.jar
echo "============================"
```
