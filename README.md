# Spring Boot Kafka Transaction System

Backend transaction processing system built using Spring Boot, Apache Kafka, REST APIs, H2 Database, and Spring Data JPA.

## Features
- Kafka-based transaction message consumption
- REST API integration
- Spring Boot microservices architecture
- H2 Database persistence
- Transaction validation and balance updates
- Maven testing support
- Layered backend architecture

## Tech Stack
- Java
- Spring Boot
- Apache Kafka
- REST APIs
- Spring Data JPA
- H2 Database
- Maven

## Project Preview
<img width="1600" height="900" alt="Jp" src="https://github.com/user-attachments/assets/1dee3e83-5a34-40b3-862e-a1f15754fb72" />




## Architecture Flow

Client
   ↓
REST API (Spring Boot)
   ↓
Kafka Producer
   ↓
Kafka Topic
   ↓
Kafka Consumer
   ↓
H2 Database

## Why Kafka?

Apache Kafka is used to enable asynchronous communication between services. Instead of processing transactions synchronously, transaction requests are published to a Kafka topic and consumed independently. This improves scalability, reliability, and system decoupling.

## Learning Outcomes

- Developed REST APIs using Spring Boot
- Implemented asynchronous messaging using Apache Kafka
- Performed database operations using Spring Data JPA
- Designed a layered backend architecture
- Improved understanding of event-driven systems and microservices concepts
