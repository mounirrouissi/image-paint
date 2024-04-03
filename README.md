# React/Spring Boot Bookstore Application

## Overview
This application is a full-stack web solution for a bookstore. It features a React frontend, Spring Boot backend, and Integrating ONNX ML models , and includes advanced functionalities such as image processing, OAuth2 Google authentication, email-based login/signup, user feedback, and Stripe payment integration.

## Features
- **Image Processing**: Remove objects from images and upscale images by 4x.
- **OAuth2 Google Authentication**: Secure login using Google accounts.
- **Email Login/Signup**: Users can also register and sign in using their email addresses.
- **User Feedback**: Collect and manage user feedback.
- **Stripe Payment Integration**: Process payments with Stripe for a seamless checkout experience.
- **Load ONNX Models: Utilize ONNX.js to load and run your models within the React application.
## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- JDK 1.8 or later
- Maven 3.2+
- Node.js 10+
- Angular CLI
- PostgreSQL
- AWS Account

### Installing
A step by step series of examples that tell you how to get a development environment running.

#### Backend Setup
```bash
# Clone the repository
git clone [your-repo-link]
# Navigate to the server directory
cd server
# Build the project
mvn clean install
# Run the application
mvn spring-boot:run
