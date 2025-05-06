# Hotel Booking Configuration Service

This is the **Configuration Service** for the Hotel Booking System. It provides centralized, version-controlled configuration management for all services in the system using **Spring Cloud Config Server**.

## Project Structure

```
hotel.booking.config/
├── src/
│   └── main/
│       ├── java/
│       │   └── com/hotel/booking/config/
│       │       └── ConfigServiceApplication.java
│       └── resources/
│           ├── application.yml
│           └── config/
│               ├── discovery-service.yml
│               ├── gateway-service.yml
│               └── user-services.yml
├── test/
│   └── java/com/hotel/booking/config/
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```
