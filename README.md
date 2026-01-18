# Simple Movie Booking System

This is a Spring Boot application for movie ticket booking. You can add movies, create shows, book tickets, view bookings, and cancel bookings.

## How to Run the Project

1. Clone the repo
2. Open the project in Eclipse or any IDE
3. Configure MySQL database in `application.properties`
4. Run the application

## API Endpoints

- **POST /api/movies** — Add movie
- **GET /api/movies** — Get all movies
- **POST /api/shows** — Create show
- **GET /api/shows** — Get all shows
- **GET /api/shows/movie/{id}** — Get shows by movie
- **POST /api/bookings** — Book tickets
- **GET /api/bookings** — Get all bookings
- **DELETE /api/bookings/{id}** — Cancel booking
