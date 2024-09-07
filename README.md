# MySQL Testing Environment with phpMyAdmin

This repository provides a simple setup for practicing and testing MySQL commands without installing MySQL directly on your machine. You can use phpMyAdmin (an old friend for many developers) to interact with the MySQL database via a web interface. The setup is designed to run on macOS ARM architecture using Docker, ensuring data is not stored after the container is stopped.

## Features
- **No MySQL Installation Required**: There's no need to install MySQL on your machine. Everything runs within Docker containers.
- **phpMyAdmin Interface**: Practice MySQL using the well-known phpMyAdmin interface through your browser.
- **Simple Setup**: Just clone the repository and run a single command to get everything up and running.
- **Ephemeral Data**: Data is stored temporarily and will be erased once the container stops, keeping your machine clean.

## Pre-requisites
- macOS ARM architecture (e.g., M1, M2 chips).
- Docker must be installed and running on your system. [Download Docker for Mac](https://docs.docker.com/get-docker/).

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/mysql-phpmyadmin-docker.git
   
   cd dockerized-sql-playground
   
   docker-compose up

2. Open the link in your browser and ready to play (username is root and password is root)
   ```bash
   http://localhost:8080

