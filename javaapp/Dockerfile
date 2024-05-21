#BASE IMAGE

FROM openjdk:11

#WorkDir

WORKDIR app/

#COPY current to WORKDIR

COPY HelloWorld.java .

#Compiler

RUN javac HelloWorld.java

#Run the java compiled code

CMD ["java","HelloWorld"]