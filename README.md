# MovieApp

MovieApp is my full-stack web application where users can search movies, rate movies and get personalized recommendations.

Link to deployed web app: https://movieapp.jcoder.dk

Link to repo for frontend project: https://github.com/pbollhorn/movie-app-frontend

Link to repo for backend project: https://github.com/pbollhorn/movie-app-backend

Author: Peter Bollhorn

## Features

- Search ~90,000 movies via trigram-based fuzzy search
- View movie posters
- View movie details, including full cast and crew, and if the movie belongs to a collection
- View list of movies for cast/crew member
- View list of movies in collection
- Rate movies 😀 (Good) or 😐 (OK/Bad)
- Get movie recommendations based on your ratings
- Mobile and desktop friendly
- Automatic light/dark mode according to browser setting

## Screenshots of deployed web app

<table>
<tr>
  <td><img src="screenshots/screenshot1.jpg" width="500"></td>
  <td><img src="screenshots/screenshot2.jpg" width="500"></td>
  <td><img src="screenshots/screenshot3.jpg" width="500"></td>
  <td><img src="screenshots/screenshot4.jpg" width="500"></td>
</tr>
</table>


## Tech Stack

### Frontend
- React 19 - JavaScript library for building UI
- CSS Modules - For scoped and modular styling
- React Router DOM - For client-side routing

### Backend
- Java 17 - Programming language
- Javalin - Lightweight web framework
- Jackson - JSON serialization/deserialization
- SLF4J/Logback - Logging
- Maven - Build tool and dependency management
- Hibernate - ORM for database access

### Database
- PostgreSQL 16 - Relational database
- pg_trgm - Extension used for trigram-based fuzzy search

### Deployment & Hosting
- GitHub Actions - For CI/CD pipeline
- DigitalOcean - Cloud hosting provider
- Ubuntu 22 - OS running on the cloud server
- Docker - For containerization
- Jetty - For serving the backend
- Caddy - For serving the frontend

### Tools
- VS Code - For frontend development
- IntelliJ IDEA - For backend development
- pgAdmin - For database management

## TMDB (The Movie Database)
This web app uses TMDB and the TMDB APIs but is not endorsed, certified, or otherwise approved by TMDB.

Link to TMDB: https://www.themoviedb.org/