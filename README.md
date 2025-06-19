# MoviesDatabase API Integration

## API Overview

The MoviesDatabase API provides developers with a comprehensive way to access movie-related data. With this API, you can search for movies, retrieve details about specific titles, access cast and crew information, and more. It's designed to support various movie applications, from entertainment sites to recommendation systems.

## Version

v1

## Available Endpoints

- **GET /titles**  
  Retrieve a list of movie titles. You can filter by genre, year, rating, etc.

- **GET /titles/{id}**  
  Fetch detailed information for a specific movie by ID.

- **GET /titles/search/title/{title}**  
  Search for movies by title keyword.

- **GET /actors/{id}**  
  Retrieve information about a specific actor using their ID.

- **GET /titles/{id}/cast**  
  Get the cast list for a specific movie.

- **GET /titles/{id}/crew**  
  Retrieve crew details (e.g., directors, producers) for a specific movie.

- **GET /genres**  
  List all available genres in the database.

## Request and Response Format

### Request Example

```http
GET /titles/search/title/Inception
Host: moviesdatabase.example.com
x-api-key: YOUR_API_KEY
```

## Authentication

## Error Handling

## Usage Limits and Best Practices
