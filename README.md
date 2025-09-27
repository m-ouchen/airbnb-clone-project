# Airbnb Clone Project

## Project overview

The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.

### Project goals

1. User Management: Implement a secure system for user registration, authentication, and profile management.
2. Property Management: Develop features for property listing creation, updates, and retrieval.
3. Booking System: Create a booking mechanism for users to reserve properties and manage booking details.
4. Payment Processing: Integrate a payment system to handle transactions and record payment details.
5. Review System: Allow users to leave reviews and ratings for properties.
6. Data Optimization: Ensure efficient data retrieval and storage through database optimizations.

## Team Roles

- Backend Developer: Responsible for implementing API endpoints, database schemas, and business logic.
- Database Administrator: Manages database design, indexing, and optimizations.
- DevOps Engineer: Handles deployment, monitoring, and scaling of the backend services.
- QA Engineer: Ensures the backend functionalities are thoroughly tested and meet quality standards.

## Technology Stack

- Django: A high-level Python web framework used for building the RESTful API.
- Django REST Framework: Provides a comprehensive RESTful API for handling CRUD operations on user and property data.
- PostgreSQL: A powerful relational database used for data storage.
- GraphQL: Offers a flexible and efficient query mechanism for interacting with the backend.
- Celery: For handling asynchronous tasks such as sending notifications or processing payments.
- Redis: Used for caching and session management.
- Docker: Containerization tool for consistent development and deployment environments.
- CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

## Database Design

- Key entities:
  - Users: login, password, firstName, lastName, phone, email
  - Properties: propertyId, propertyAddress, propertyPrice, owner
  - Bookings: bookingId, startDate, endDate, property, booker
  - Reviews: reviewId, reviewMessage, reviewer, property
  - Payments: paymentId, booking, date

## Feature Breakdown

1. User Authentication
Endpoints: /users/, /users/{user_id}/
Features: Register new users, authenticate, and manage user profiles.
2. Property Management
Endpoints: /properties/, /properties/{property_id}/
Features: Create, update, retrieve, and delete property listings.
3. Booking System
Endpoints: /bookings/, /bookings/{booking_id}/
Features: Make, update, and manage bookings, including check-in and check-out details.
4. Payment Processing
Endpoints: /payments/
Features: Handle payment transactions related to bookings.
5. Review System
Endpoints: /reviews/, /reviews/{review_id}/
Features: Post and manage reviews for properties.

## API Security

Authentication, Authorization, Rate limiting

## CI/CD Pipeline

GitHub Actions, Docker
