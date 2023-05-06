AngularJS Web App Backend
This repository contains the backend code for an AngularJS web app. It provides a Dockerfile for containerization and includes commands in the package.json file to build and run the application.

Prerequisites
Node.js
Docker
Setup
Clone the repository:


git clone https://github.com/your-username/your-repo.git
Change to the backend directory:


cd backend
Install the dependencies:

npm install
Directly Run
You can run the example Node.js application directly with the following command:



npm start
Build and Run using Docker
To build the Docker image, use the following command:


npm run docker:build
To run the Docker image, execute the following command:


npm run docker:run
To check the status of the Docker containers, use the following command:

docker ps
To stop the Docker container, run the following command:

npm run docker:stop
That's it! You now have the AngularJS web app backend running locally using Docker.
