# MovieApp

MovieApp is my full-stack web application where users can search movies, rate movies and get personalized recommendations.

Link to deployed web app: https://movieapp.jcoder.dk

Link to repo for frontend project: https://github.com/pbollhorn/movie-app-frontend

Link to repo for backend project: https://github.com/pbollhorn/movie-app-backend

Author: Peter Bollhorn

## Features

- Search ~90,000 movies via trigram-based fuzzy search
- See movie posters
- View movie details, including full cast and crew, and if the movie belongs to a collection
- View list of movies for cast/crew member
- View list of movies in collection
- Rate movies 😀 (Good) or 😐 (OK/Bad)
- Get movie recommendations based on your ratings
- Mobile and desktop friendly
- Automatic light/dark mode according to browser setting

## Tech Stack

### Frontend
- React 19
- CSS Modules
- React 19 – for building the user interface
- React Router DOM – for client-side routing
- Vite – as the build tool and development server
- CSS Modules – for scoped and modular styling
- ESLint – for code linting and quality assurance
- VS Code – as the code editor

### Backend
- **Java 17** - Programming language
- **Maven** - Build tool and dependency management
- **Javalin** - Lightweight web framework
- **Hibernate** - ORM for database access
- **SLF4J/Logback** - Logging
- **Jackson** - JSON serialization/deserialization
- **Lombok** - Reduces boilerplate code

### Database
- **PostgreSQL** – relational database
- pg_trgm - extension used for trigram-based fuzzy search

### Deployment & Hosting
- GitHub Action (CI/CD pipeline)
- Docker / Docker Compose
- Digital Ocean
- Ubuntu

### Tools
- VS Code – For frontend development
- IntelliJ IDEA – For backend development
- pgAdmin – For database management

## TMDB (The Movie Database)
This web app uses TMDB and the TMDB APIs but is not endorsed, certified, or otherwise approved by TMDB.

Link to TMDB: https://www.themoviedb.org/
