# Home Service Booking System
A **Home Service Booking System** using Java + Spring Boot is basically an app/platform where customers can book services like electricians, plumbers, cleaners, appliance repair, beauty services, etc., and service providers can manage bookings.

Think of apps like:
* **Urban Company**
* **TaskRabbit**

A Spring Boot backend project for this is a very strong portfolio project because it covers:

* Authentication
* REST APIs
* Database design
* Payments
* Scheduling
* Admin systems
* Real-world business logic

Summary - 
- Developing a role-based Home Service Booking System with separate modules for Customers, Service providers, Admin.
- Implementing secure authentication and authorization using Spring Security, JWT, and BCrypt password hashing.
- Building RESTful APIs following layered MVC architecture with DTO validation and global exception handling.
- Designing a relational database using MySQL to manage users, services, bookings, reviews, and provider information.

## API Endpoints

| Method | Endpoint        | Description |
|------|----------------|-------------|
| GET | `/api/card/{id}` | Get card by ID |
| PUT | `/api/card/{id}` | Update an existing card |
| DELETE | `/api/card/{id}` | Delete a card |
| GET | `/api/card` | Get all cards |
| POST | `/api/card` | Create a new card |
