# 🎮 VideoGameApi

## Overview
A simple **RESTful Web API** built with **ASP.NET Core 9** and **Entity Framework Core** to manage a list of video games (CRUD operations).

## Technologies
- .NET 9  
- ASP.NET Core  
- Entity Framework Core  
- In-memory database for testing  

## Getting Started

1. Clone the repo:

```bash
git clone https://github.com/ZvoneK99/VideoGameApi.git
cd VideoGameApi
```

2. Restore packages:

```bash
dotnet restore
```

3. Run the project:

```bash
dotnet run
```

The API will run at `https://localhost:5001`.

## API Endpoints
- `GET /api/videogames` – Get all games  
- `GET /api/videogames/{id}` – Get game by ID  
- `POST /api/videogames` – Add a new game  
- `PUT /api/videogames/{id}` – Update a game  
- `DELETE /api/videogames/{id}` – Delete a game  

Test with **Postman** or **Swagger UI**.

## GitHub
[https://github.com/ZvoneK99/VideoGameApi](https://github.com/ZvoneK99/VideoGameApi)
