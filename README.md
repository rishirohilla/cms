# ClubManagementSystem

## Description
The ClubManagementSystem is a web-based application designed to showcase and manage all clubs at IIIT Lucknow. This system provides a centralized platform for students, faculty, and administrators to view, join, and manage various clubs within the institution.

## Features
- Display all clubs at IIIT Lucknow
- User registration and authentication
- Club creation and management
- Event scheduling and announcements
- Member management for each club

## Tech Stack
- Backend: Spring Boot
- Database: MySQL
- Frontend: React.js

## Prerequisites
- Java JDK 11 or later
- Maven
- MySQL

## Getting Started

### 1. Clone the repository
git clone https://github.com/rishirohilla/cms.git
cd clubmanagementsystem


### 2. Configure MySQL
- Create a new MySQL database named `clubmanagementsystem`
- Update the `application.properties` file in `src/main/resources` with your MySQL credentials:
- spring.datasource.url=jdbc:mysql://localhost:3306/clubmanagementsystem spring.datasource.username=your_username spring.datasource.password=your_password

### 3. Build and run the application
The application should now be running on `http://localhost:8080`
