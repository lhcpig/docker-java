# docker-java
java environment that base on centos7

## compile a java file

```console
$ docker run --rm -v "$PWD":/usr/src/myapp -w /usr/src/myapp java javac Main.java
```

This will add your current directory as a volume to the container, set the working directory to the volume, and run the command javac Main.java which will tell Java to compile the code in Main.java and output the Java class file to Main.class.

