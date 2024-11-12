# Project-Javascript

This project aims to showcase a simple web page built using **HTML**, **CSS**, and **JavaScript**. It is a basic demonstration of a static webpage that can be run locally using Docker.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**

## Installation

To run this project, follow these steps:

### 1. Download the project image from DockerHub:

Run the following command to pull the latest image of the project:

    docker pull andrespaida/my-web-page:latest

### 2. Create a container from the downloaded image:

Next, create and run the container with this command:

    docker run -d -p 8080:80 --name web-container1 andrespaida/my-web-page:latest

### 3. Access the webpage:

Once the container is running, open your browser and go to:

    http://localhost:8080

## License

Tis project is under the creator's license (Andrés Paida). All rights reserved.
