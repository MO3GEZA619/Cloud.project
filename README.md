# ProlectCloudAPI

This project provides a guide on how to install and launch the ProlectCloudAPI on your local computer using Docker.

## Prerequisites

Before proceeding with the installation, ensure that you have Docker and Docker Compose installed on your system. If you don't have them installed already, download the appropriate versions for your operating system from the official Docker website.

## Installation and Launch

To install and launch the ProlectCloudAPI, follow these steps:

1. Clone the ProlectCloudAPI repository to your local computer.

   ```
   git clone https://github.com/MO3GEZA619/Cloud.project.git
Navigate to the project directory in your terminal or command prompt.


cd ProlectCloudAPI
```

Build the Docker images for the backend and frontend applications using Docker Compose.


docker-compose build
```

Start the Docker containers.


docker-compose up
```

Note: Ensure that port 5000 is not being used by any other application on your computer.

Once the containers are up and running, access the frontend application by opening a web browser and entering the following URL:


http://localhost:5000/persons
```
That's it! You should now be able to use the ProlectCloudAPI on your local computer.

