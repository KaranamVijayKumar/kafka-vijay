# kafka-vijay
Creating a simple Kafka Producer and Consumer app using Twitter API

# Instructions to run the App
## Compile and Build a Fat Jar File
Open PowerShell as Administrator in the root project folder, compile the code using Maven and create an executable jar file. Generated artificacts can be found in the new 'target' folder.

mvn clean compile assembly:single

## 1.Start Zookeeper Service
Start and keep running the Zookeeper service.

zkserver

## 2.Start Kafka Service
Start and keep running the Kafka service. What directory must you be in?

 .\kafka-server-start.bat .\server.properties.
