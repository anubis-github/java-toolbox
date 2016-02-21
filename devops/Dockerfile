# Pull base image.
FROM anubisdocker/oracle-java:8.60

# Add libs to classpath
ADD build/libs/<PUT_JAR_NAME>.jar /<PATH>/<PUT_JAR_NAME>.jar

# describe exposed ports
EXPOSE add ports

# command to run in container
ENTRYPOINT java -jar /<PATH>/<PUT_JAR_NAME>.jar


