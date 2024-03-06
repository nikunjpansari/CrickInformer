# CrickInformer Backend Application

This project implements the backend for CrickInformer, a web application for fetching live cricket match data, storing it in a MySQL database, and providing functionality to retrieve the Cricket World Cup 2023 points table.

## Technologies Used

- Spring Framework
- Spring Boot
- REST API
- JPA (Java Persistence API)
- Jsoup (for web scraping)
- MySQL (for database connectivity)

## Functionality

1. **Live Matches Storage**: The application fetches live cricket match data from various sources and stores it in a MySQL database.

2. **Cricket World Cup 2023 Points Table**: The application provides functionality to fetch the points table of Cricket World Cup 2023.

## Implementation Details

- **Spring and Spring Boot**: Utilized for building RESTful APIs and managing application dependencies.
- **JPA**: Used for object-relational mapping to interact with the MySQL database.
- **Jsoup**: Employed for web scraping to fetch live cricket match data from websites.
- **MySQL**: Configured as the database for storing live match data.

## API Endpoints

1. `/crikcet/live`: Endpoint to fetch live cricket match data.
2. `/cricket/points-table`: Endpoint to retrieve the points table of Cricket World Cup 2023.

## Testing

The API endpoints have been thoroughly tested using Postman to ensure proper functionality and data retrieval.

## Usage

1. Clone the repository.
2. Configure MySQL database settings in the application properties.
3. Run the application.
4. Access the API endpoints using a REST client or Postman.
