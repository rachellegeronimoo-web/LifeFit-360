# LifeFit 360

## Project Overview
LifeFit 360 is a fitness and nutrition website designed to help users explore workout routines, discover meals, and support healthier lifestyle habits.

## Features
- **Workout Programs:** Browse workout categories and follow daily workout routines.
- **Workout Videos:** Access linked workout videos for exercise guidance.
- **Nutrition and Meals:** Explore meal ideas and cooking instructions.
- **Favorite Meals:** Save favorite meals and review their calorie information.
- **Fitness Challenges:** Explore challenges that encourage consistent activity.

## Technologies Used
- HTML
- CSS
- JavaScript
- Docker
- Nginx
- GitHub Actions
- GitHub Pages

## Run the Project Locally with Docker

### Requirements
Install Docker Desktop before running the following commands.

### Build the Docker image
```bash
docker build -t lifefit360 .
```

### Run the container
```bash
docker run -d -p 8080:80 --name lifefit360-container lifefit360
```

### Open the website
Visit http://localhost:8080 in your browser.

### Stop the container
```bash
docker stop lifefit360-container
```

### Remove the container
```bash
docker rm lifefit360-container
```

## Continuous Integration
GitHub Actions runs the Docker build and website response test when changes are pushed to the main branch. The workflow helps verify that the project can be built and served successfully.

## Live Website
https://rachellegeronimoo-web.github.io/LifeFit-360/

## Repository
https://github.com/rachellegeronimoo-web/LifeFit-360

## Developer
Rachelle Geronimo

## Purpose
This project was developed as part of a DevOps and Platform Integration activity to practice version control, containerization, automated testing, and deployment concepts.
