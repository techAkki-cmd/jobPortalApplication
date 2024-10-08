# Job Portal Application

## Overview

The **Job Portal Application** is a web-based platform designed to connect recruiters and job seekers. It enables recruiters to create profiles, post job listings, and manage their postings. Job seekers can register, log in, search for jobs, and apply for positions. Built with modern technologies, this application provides a robust and scalable solution for job management and search.

## Features

### Recruiter Profile Management

- **Create and Manage Profiles**: Recruiters can create and update their profiles, ensuring they have a professional presence on the platform.
- **Post Job Listings**: Recruiters can post new job openings, including detailed information such as job title, description, location, and requirements.
- **Manage Job Postings**: Edit or remove existing job listings as needed.

### Job Seeker Functions

- **Register and Create Accounts**: Job seekers can sign up and create their profiles on the platform.
- **Login**: Secure login to access job search and application features.
- **Search for Jobs**: Find job opportunities using various filters such as job title, location, and company.
- **Apply for Jobs**: Submit applications for job listings directly through the platform.

## Technologies Used

### Backend

- **Spring Boot**: Framework for creating stand-alone, production-grade Spring-based applications with ease.
- **Hibernate**: Object-Relational Mapping (ORM) framework for handling database interactions and data persistence.
- **Spring MVC**: Framework that follows the Model-View-Controller (MVC) design pattern to build web applications.
- **Thymeleaf**: Modern server-side Java template engine for rendering HTML pages, providing dynamic content on the frontend.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK)**: Ensure you have JDK 11 or higher installed.
- **Maven**: For dependency management and building the project.
- **Database**: A relational database like MySQL or PostgreSQL for persistence.

## Usage

### For Recruiters

- **Create Profile**:
  Register and set up your recruiter profile to start managing job listings and applicants.

- **Post Jobs**:
  Navigate to the job management section to post new job listings. Provide details such as job title, description, location, and requirements.

- **Manage Postings**:
  Edit or remove job postings as needed to keep your listings up-to-date.

### For Job Seekers

- **Register and Log In**:
  Create an account and log in to access job search features and apply for jobs.

- **Search Jobs**:
  Use the search functionality to find job opportunities. Apply filters such as job title, location, and company to refine your search.

- **Apply for Jobs**:
  Apply for positions that match your skills and interests directly through the platform.

## Code Structure

- **`src/main/java/com/yourcompany/jobportal/`**
    - **`controller/`**: Contains Spring MVC controllers responsible for handling web requests and managing the flow of data between the view and model.
    - **`model/`**: Contains entity classes that represent the database schema, including the structures for users, job listings, and applications.
    - **`repository/`**: Contains Spring Data JPA repositories for database interactions, providing methods to query and manipulate data.
    - **`service/`**: Contains service classes that encapsulate business logic and interact with repositories to perform operations on data.

- **`src/main/resources/`**
    - **`application.properties`**: Configuration file for setting application properties such as database connections, server ports, and other environment-specific settings.
    - **`templates/`**: Contains Thymeleaf templates used for rendering dynamic HTML pages based on the data provided by the controllers.
    - **`static/`**: Contains static resources like CSS, JavaScript files, and images that are served directly to the client.

## Acknowledgements

- **Libraries and Tools**:
    - **Spring Boot**: A framework for creating stand-alone, production-grade Spring-based applications with ease.
    - **Hibernate**: An Object-Relational Mapping (ORM) framework for handling database interactions and data persistence.
    - **Spring MVC**: A framework following the Model-View-Controller (MVC) design pattern for building web applications.
    - **Thymeleaf**: A modern server-side Java template engine for rendering HTML pages and providing dynamic content on the frontend.

- **Inspiration**:
    - Modern web application development practices and job portal solutions have guided the design and implementation of this application. The goal was to create a user-friendly, scalable, and efficient platform for job management and search.

