# Flight_Booking
Overview


This project provides a real-time flight status update and notification system. It includes a web frontend to display flight statuses, a backend API to handle requests and a notification system for real-time alerts. The system integrates with Kafka for message processing and Firebase Cloud Messaging for notifications.

Features


Real-Time Updates:   Displays current flight status including delays, cancellations, and gate changes.
Push Notifications:  Sends notifications for flight status changes via SMS, email, or app notifications.
Integration with Airport Systems:  Uses mock data to simulate integration with airport databases.


Technologies


Frontend:      React.js, HTML, CSS
Backend:       Java, Spring Boot
Database:      MongoDB, PostgreSQL
Notifications: Firebase Cloud Messaging
Real-Time Messaging: Kafka (RabbitMQ can be used alternatively)

Project Structure


Frontend: frontend/

src/ - React.js source code
public/ - Public assets


Backend: backend/

src/main/java/com/example/flightstatus/ - Java source code
src/main/resources/ - Configuration files

Kafka: kafka/ (Setup and configuration files for Kafka

Firebase: firebase/ (Firebase configuration and service files
