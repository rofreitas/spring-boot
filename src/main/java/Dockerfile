FROM dmreiland/alpine-oraclejre10:latest
COPY java.jar /tmp/myproject-0.0.1-SNAPSHOT.jar
RUN ls -l /tmp/
RUN while true; do java -jar tmp/myproject-0.0.1-SNAPSHOT.jar; done &
