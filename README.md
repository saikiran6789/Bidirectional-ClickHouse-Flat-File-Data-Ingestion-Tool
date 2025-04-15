# Bidirectional ClickHouse & Flat File Data Ingestion Tool

## Project Overview
This project is a web-based application that enables bidirectional data ingestion between a ClickHouse database and flat files (CSV format). Users can select specific columns for ingestion and handle JWT token-based authentication.

## Technologies Used
- Backend: Java, Spring Boot
- Frontend: React.js
- Database: ClickHouse
- JWT Authentication
- Maven for build management

## Backend Setup
1. Clone the repository.
2. Open the `backend` directory.
3. Set up your `application.properties` file with the correct ClickHouse credentials.
4. Install dependencies with Maven:
   ```bash
   mvn clean install
