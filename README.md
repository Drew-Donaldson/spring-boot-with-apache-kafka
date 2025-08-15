# Spring Boot with Apache Kafka

## Project Overview
This repository contains a Spring Boot 3 application developed as part of the Udemy course *"Spring Boot 3 and Spring Framework 6"* by Shabbir Dawoodi, specifically **Section 10: Spring Boot with Apache Kafka**. The project demonstrates the integration of Spring Boot with Apache Kafka to build an event-driven application using Kafka's publish-subscribe messaging system. The application includes both a Kafka producer and consumer to send and receive messages, showcasing real-time data processing.

### Key Features
- Configured **Apache Kafka** with Spring Boot to enable message-driven communication.
- Implemented a **Kafka Producer** to publish messages to a Kafka topic.
- Implemented a **Kafka Consumer** to subscribe to and process messages from a Kafka topic.
- Set up Kafka configuration using Spring Boot properties for topic creation and broker connection.
- Demonstrated message serialization and deserialization using JSON.
- Integrated error handling and retry mechanisms for robust message processing.

## Technologies Used
- **Java**: 17
- **Spring Boot**: 3.x
- **Spring Kafka**: For Kafka integration
- **Apache Kafka**: Messaging system (tested with a local Kafka server)
- **Maven**: Dependency management
- **H2 Database**: For in-memory database testing (if applicable)
- **Postman**: For testing REST endpoints that trigger Kafka messages

## Learning Outcomes
Through this project, I gained hands-on experience with:
- Setting up Apache Kafka with Spring Boot for event-driven architecture.
- Configuring Kafka producers and consumers using Spring Kafka annotations.
- Managing Kafka topics and partitions.
- Handling JSON message serialization/deserialization with Spring Kafka.
- Understanding the basics of distributed messaging systems and their use cases.
