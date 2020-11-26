# Drawingboard-light


[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

This is a lightweight(~10MB) collaborative realtime drawing application using SSE and WebSocket with integration of Jersey and Tyrus on top of Grizzly.
It is called *light* since it has a minimal footprint and a very fast startup time, compared to a former Java EE implementation.


to build:
```bash
mvn package
```
to run:
```bash
java -jar target/drawingboard-light-1.0-SNAPSHOT-jar-with-dependencies.jar
```
