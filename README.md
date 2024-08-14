# nginx-docker-webpage


This project contains a simple yet beautiful HTML and CSS web page that is served using Nginx in a Docker container. The page is deployed locally using Docker Compose.

## Project Structure
 
  index.html: The HTML file for the web page.
  styles.css: The CSS file for styling the web page.
  Dockerfile: The Dockerfile used to build the Docker image.
  docker-compose.yml: The Docker Compose file used to orchestrate the container.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have the following installed:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/aaabaza761/nginx-docker-webpage.git
   cd nginx-docker-webpage
### RUNNING 
1. Build and run the Docker containers:
    docker-compose up --build
2. Open your browser and navigate to http://localhost:8080 to see the web page.

OR
# Docker Hub Image
### You can also pull the Docker image directly from Docker Hub:
  1. docker pull ahmed377/nginx-webpage:latest
  2. docker run -p 8080:80 ahmed377/nginx-webpage:latest

