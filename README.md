# civil-engineer-finder
Civil Engineer Finder is a modern full-stack platform that simplifies finding and connecting with civil engineers. Built with Spring Boot and React, it features a clean UI, RESTful architecture, and scalable backend, making it a strong foundation for real-world service-based applications.

Problem Statement

Finding trustworthy and skilled civil engineers for construction-related services is often difficult for customers. Traditional methods are time-consuming and lack transparency in terms of ratings, expertise, and communication.

Civil Engineer Finder solves this by providing:

A centralized platform for customers to discover civil engineers.
Engineer profiles with ratings and project details.
Search and filter options based on specialization and location.
Direct booking and communication features.
Objectives
Build a platform where customers can find civil engineers easily.
Enable engineers to showcase their expertise and experience.
Provide secure login and profile management.
Improve communication between clients and engineers.
Offer a scalable architecture for future enhancements.
Key Features
User Features
User Registration and Login
Search engineers by specialization and location
View engineer profiles
Send project requests
Track booking status
Rate and review engineers
Engineer Features
Engineer Registration/Login
Create and update professional profile
Manage incoming requests
Accept/Reject projects
View ratings and reviews
Admin Features
Manage users and engineers
Monitor bookings
Maintain platform data
Technology Stack
Frontend
React.js – Dynamic user interface
CSS / Bootstrap / Tailwind CSS – Responsive design
Axios – API communication
React Router – Navigation between pages
Backend
Node.js – Server-side runtime
Express.js – REST API development
JWT – Authentication and authorization
bcrypt.js – Password encryption
Database
MongoDB – NoSQL database for storing users, engineers, bookings, and reviews
System Architecture

The application follows a 3-Tier Architecture:

Presentation Layer (Frontend)
React components for UI
Handles user interactions
Sends requests to backend APIs
Application Layer (Backend)
Express REST APIs
Business logic handling
Authentication and authorization
Data Layer (Database)
MongoDB stores all application data
Architecture Flow
User Interface (React)
        |
        v
 REST API Calls (Axios)
        |
        v
Node.js + Express Backend
        |
        v
MongoDB Database
Module Architecture
1. Authentication Module

Handles registration and login for users and engineers.

Functions:

Signup
Login
JWT Token generation
Protected routes
2. Engineer Management Module

Manages engineer profile creation and updates.

Functions:

Add profile
Update profile
View profile
Add specialization and experience
3. Search Module

Allows users to search engineers.

Filters:

Location
Expertise
Rating
Availability
4. Booking Module

Handles project requests.

Functions:

Send request
Accept request
Reject request
Track status
5. Review Module

Stores feedback from users.

Functions:

Submit rating
View reviews
