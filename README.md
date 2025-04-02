# Product Store - Full Stack Application

Welcome to the **Product Store** app! This is a full-stack application that allows users to **add**, **delete**, **update**, and **view products** in an intuitive and user-friendly interface. The app also provides an image upload functionality to associate product images. It is built with **React** for the frontend and **Spring Boot** for the backend, using **H2 database** for persistence.

This project is part of my **Java Developer Internship**, where I learned and implemented various concepts such as building RESTful APIs, managing databases, and integrating the frontend with the backend using modern JavaScript and Java technologies.

## Table of Contents

- [Tech Stack](#tech-stack)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [How to Use](#how-to-use)
- [Accessing the App](#accessing-the-app)
- [Contributing](#contributing)
- [Internship Experience](#internship-experience)

## Tech Stack

- **Frontend**: React.js, React-Bootstrap
- **Backend**: Spring Boot (Java)
- **Database**: H2 Database
- **UI Libraries**: React-Bootstrap, other libraries for UI components

## Features

- **CRUD Operations**: 
  - Add, update, delete, and view products.
- **Image Upload**: 
  - Upload images for each product.
- **Responsive Design**: 
  - Mobile-first, responsive design using **React-Bootstrap**.
- **H2 Database**: 
  - In-memory database configured for persistence.

## Setup and Installation

### Backend Setup (Spring Boot)

1. Clone the repository:
    ```bash
    git clone https://github.com/karanshah254/Java-Full-Stack-App.git
    cd app-name
    ```

2. Navigate to the backend folder and build the Spring Boot app:
    ```bash
    cd backend
    ./mvnw clean install
    ```

3. Run the Spring Boot backend application:
    ```bash
    ./mvnw spring-boot:run
    ```

   The backend will run on `http://localhost:8080/telusko_products`.

### Frontend Setup (React)

1. Navigate to the frontend folder:
    ```bash
    cd frontend
    ```

2. Install the necessary dependencies:
    ```bash
    npm install
    ```

3. Start the React app:
    ```bash
    npm start
    ```

   The frontend will run on `http://localhost:5173`.

### CORS Configuration

Since the backend and frontend run on different ports, make sure CORS is properly configured in the Spring Boot backend to allow requests from the React frontend.

## How to Use

1. Once both the frontend and backend are running, open your browser and go to `http://localhost:5173` to access the app.

2. Use the UI to:
    - **Add a product**: Fill in the product name, description, price, and upload an image.
    - **View products**: Browse through all products listed.
    - **Update a product**: Edit any existing product.
    - **Delete a product**: Remove a product from the list.
    - **Search product**: Search product from the list.

## Accessing the App

- **Frontend**: [http://localhost:5173](http://localhost:5173)
- **Backend**: [http://localhost:8080/telusko_products](http://localhost:8080/telusko_products)

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open an issue or submit a pull request. Please make sure your contributions align with the overall structure and style of the app.

### Steps to Contribute:

1. Fork the repository.
2. Clone your fork to your local machine.
3. Create a new branch (`git checkout -b feature-branch`).
4. Make your changes.
5. Commit your changes (`git commit -m "Add a feature"`).
6. Push to your fork (`git push origin feature-branch`).
7. Create a pull request from your branch to the main repository.

## Internship Experience

This project was developed as part of my **Java Developer Internship**. This project provided hands-on learning in modern full-stack web development and the integration of multiple technologies in a real-world application.
