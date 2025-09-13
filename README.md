# Online Gym Management System

A web-based application to streamline gym operations, providing a comprehensive platform for managing memberships, trainers, schedules, and payments.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)

## About
This project automates gym operations using Spring Boot and Java Full Stack technologies. It offers a user-friendly platform for gym administrators and members to efficiently manage members, sessions, and payments. The system enables:
- Simplified member registration and login.
- Role-based access control.
- Real-time booking and feedback management.


## Features
- Member Management
- Gym Item Management
- Slot Scheduling and Management
- Authentication & Authorization
- User Feedback
- Role-Based Access Control (Admin, Trainer, Member)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GymManagementSystem.git
   ```

2. Navigate to the project directory:
   ```bash
   cd GymManagementSystem
   ```

3. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate    # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Start the application using Apache Tomcat server or your preferred IDE (e.g., Eclipse):
- Open the project in Eclipse.
- Run the Spring Boot application.
- Access the system via browser at `http://localhost:8080`.

## Configuration

- Update the database connection settings in `application.properties` located in `src/main/resources/`.
- Example config settings:
  ```properties
  spring.datasource.url=jdbc:mysql://localhost:3306/gymdb
  spring.datasource.username=root
  spring.datasource.password=your_password
  ```

## Contributing

Contributions are welcome! Feel free to:
- Open issues.
- Submit pull requests for bug fixes and features.
- Improve documentation.

