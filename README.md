# Football Data API

**Football Data API** is an educational backend project built with **NestJS** and **TypeScript**.  
It provides a simple REST API for managing football clubs, their players, and user favorites.  
Data can come from local storage (in-memory or JSON) or be enriched from the public API [football-data.org](https://www.football-data.org/).



## Features

- **List all clubs** with their main details  
- **Display club details** and player squads  
- **Add new clubs** locally via `POST /clubs`  
- **Delete clubs** by ID  
- **Manage favorites** (`/clubs/favori`)  
- **Search** clubs or players by name or acronym  
- **Integrate external data** from *football-data.org* (read-only, via API key)



## Project Overview

This project demonstrates how to:
- Build a RESTful API using **NestJS (Node.js + TypeScript)**
- Organize code into **Controllers, Services, and Modules**
- Manage **in-memory data** and optional persistence via JSON
- Consume an **external public API** using `HttpModule` and Axios
- Handle multiple routes and HTTP methods cleanly



## Project Structure

````
Football-Data-API/
│
├── src/
│   ├── ApiClub.ts
│   ├── Club.ts
│   ├── club.controller.ts
│   ├── club.module.ts
│   ├── club.service.ts
│   ├── dataset.json
│   └── main.ts
│
├── test/
│   └── app.e2e-spec.ts
│
├── .gitignore
├── .nvmrc
├── FootballClubs.postman_collection.json
├── LICENSE
├── NEST_README.md
├── README.md
├── biome.json
├── dataset.json
├── nest-cli.json
├── package-lock.json
├── package.json
├── tsconfig.build.json
└── tsconfig.json
````
