# Airbnb Clone Project
ALX Back End ProDev AirBnB Clone project.

<h2>Overview</h2>

The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts.


<h2>Project Goals</h2>

This isn’t just a fun project; it’s a hands-on way to understand how professional software systems are built from the ground up. I’ll dive into key features like **_user authentication_**, **_property listings_**, **_booking management_**, and **_payment integration_**. By the end, I’ll have a fully functional application that mirrors the complexity and utility of industry-level projects.


<h2>Team Roles</h2>

  1. **Backend Developer** 👨‍💻 - Responsible for implementing API endpoints, database schemas, and business logic.
  2. **Database Administrator** 📃 - Manages database design, indexing, and optimizations.
  3. **DevOps Engineer** 👷‍♂️ - Facilitates cooperation between development and operations teams. Builds continuous integration and continuous delivery (CI/CD) pipelines for faster delivery.
  4. **QA Engineer** 🕵️‍♀️ - Makes sure an application performs according to requirements. Spots functional and non-functional defects.


<h2>Technology Stack</h2>

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/django.svg" /> Django & Django REST Framework

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/postgresql.svg" /> PostgreSQL

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/graphql.svg" /> GraphQL

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/celery.svg" /> Celery

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/redis.svg" /> Redis

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/docker.svg" /> Docker


<h2>Database Design</h2>

  1. **Users** 🧘‍♂️ - User ID, name, password. User has property and receives payment.
  2. **Properties** 🏡 - Property ID, name, location, picture. A property is booked by a user and reviewed. 
  3. **Bookings** 📖 - Booking ID, date. A booking is made by a user for a property.
  4. **Payments** 💳 - Payment ID. Payment is made by a user to book a property.
  5. **Reviews** 🧾 - Review ID, review. A review is made by a user for a property.


<h2>Feature Breakdown</h2>

  1. **User Management** 🧘‍♂️ - Implement a secure system for **_user registration_**, **_authentication_**, and **_profile management_**.
  2. **Property Management** 🏡 - Develop features for **_property listing creation_**, **_updates_**, and **_retrieval_**.
  3. **Booking System** 📖 - Create a booking mechanism for users to **_reserve properties_** and **_manage booking details_**.
  4. **Review System** 🧾 - Allow users to **_leave reviews_** and **_ratings for properties_**.
  5. **Data Optimization** 📂 - Esure **_efficient data retrieval_** and **_storage_** through database optimizations.


<h2>API Security</h2>

  1. **Authentication & Authorization** 👮‍♂️ - Authenticating credentials, and determining the level of access of the client.
  2. **Data Protection** 🚨 - Securing data using encription like TLS/SSL.
  3. **Schema Validation** ✅ - Identifying invalid requests and responses through API schema validation.
  4. **Rate Limiting** 🛑 - Putting a cap on how often someone can repeat an action within a certain timeframe.
  5. **API Gateway** 🌉 - API gateways act as a central point for managing API traffic, enforcing security policies, and providing features like authentication, authorization, and rate limiting.


<h2>CI/CD Pipeline</h2>

A continuous integration and continuous deployment (CI/CD) pipeline is a series of established steps that developers must follow in order to deliver a new version of software.

Tools:

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" /> Github Actions

<img align="left" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/docker.svg" /> Docker
