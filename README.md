drawingboard-light.git

lightweight(~10MB) collaborative drawing implementation  using SSE and WebSocket with integration of Jersey and Tyrus on top of Grizzly


to build: "mvn package"
to run: "mvn build" or "java -jar target/drawingboard-light-1.0-SNAPSHOT-jar-with-dependencies.jar"

to deploy to ACCS:
    go in the accs directory
    edit the variables for credentials and identity domain in rest.sh
    run rest.sh e.g. as "bash -x rest.sh create"