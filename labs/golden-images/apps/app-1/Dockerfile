FROM java:9-b149-jdk

WORKDIR /src
COPY HelloWorld.java .

RUN mkdir -p /out/bin && \
    javac -d /out/bin HelloWorld.java

WORKDIR /out/bin
CMD java HelloWorld
