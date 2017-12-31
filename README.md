# ka-micro
An open source project for micro-services communication via kafka in a fault-tolerant way.
If your service's code written in Java, Javascript or Python,you can just fork the project and re-use respective libraries for the communication.

 Note: This project is work in progress
 
 ## Vision
 
 To make it easier to communicate between stateless/statefull microservices.
 Communication is entirely based on kafka based topics.
 
 ### Why this is needed?
 
 We build a lot microservices like REST services,workers,email services etc. based on system design and requirement so that it is 
 easier to horizontally scale and manage.But a lot times is happens that these microservices needs to communicate with each other and should be fault-tolerant as well as easier to scale.

 ### Inspiration for project.
 
 - [Event Driven Architecture via kafka](https://www.confluent.io/blog/apache-kafka-for-service-architectures/)
 - [Need of streaming platform for microservices](https://thenewstack.io/microservices-running-containers-need-streaming-platform/)

 
