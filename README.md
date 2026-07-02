# Full-Stack-Projects
Curated collection of end‑to‑end web applications with clear run instructions and architecture notes.

## About
This repository gathers my full‑stack applications that demonstrate real‑world features, architecture decisions, and deployment workflows. Each project includes a short overview, tech stack, setup and run instructions, sample data, and links to the project repository. The collection highlights frontend interfaces, backend APIs, databases, authentication, testing, and CI/CD patterns used to build production‑style apps.

## Key Features
● Project summaries with purpose and screenshots  
● Tech stack listed per project (frontend, backend, database, infra)  
● Quick start commands and environment variables for each project  
● Docker examples for reproducible environments  
● Tests and sample data to verify functionality  
● Links to project repositories  

## Overview
A central hub containing all my full‑stack projects. Each project is organized in its own folder with a dedicated README, making it easy to explore, run, and understand the architecture behind each application.

## Tech Stack
Across the projects, you will find combinations of:
- Frontend: HTML, CSS, JavaScript, React  
- Backend: Node.js, Express, Java, Spring Boot, Python Flask  
- Databases: PostgreSQL, MySQL, MongoDB  
- Tools: Docker, GitHub Actions, REST APIs, authentication libraries  

Each project specifies its exact stack in its own README.

## Quick Start
Use this snippet for any project inside this repository.  
Replace `project-name` with the actual folder name.

```bash
# clone the project
git clone https://github.com/Maze990/project-name.git
cd project-name

# install and run locally (Node example)
npm install
npm run dev

# or with Docker
docker build -t project-name .
docker run -p 3000:3000 project-name
```

## Architecture
What’s included across the projects (depending on the project):

- Frontend interface  
- Backend API (if the project includes one)  
- Database layer (SQL or NoSQL, depending on the project)  
- Optional background jobs or services  
- Environment variables for configuration  
- Clear separation of concerns  

Each project’s README explains exactly which components it uses.

## Contributing
To add a new project:

1. Create a new folder under `projects/your-project-name`.  
2. Add a complete README using the structure above.  
3. Include environment variables and run instructions.  
4. Commit and push your changes.

