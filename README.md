# Get Youtube Subscribers

The YouTube Subscriber Management system is a robust backend solution designed to efficiently retrieve and manage subscriber information using RESTful API endpoints. Built on a foundation of Node.js, Express.js, and Mongoose, this project offers a versatile and scalable platform for users to access specific subscriber data tailored to their needs.

The API provides several endpoints that allow users to retrieve data in JSON format, including an endpoint to get all subscribers, an endpoint to get all subscribers' names and subscribed channels, and an endpoint to get details about a particular subscriber based on their ID. The project also handles error cases, such as when an incorrect subscriber ID is provided or when a user accesses an unknown endpoint.

## Features

The following features are available in the API:

- Get an array of all subscribers in JSON format.
- Get an array of all subscribers' names and subscribed channels in JSON format.
- Get details about a particular subscriber based on their ID, including their name, subscribed channel, and subscribed date.
- Handle error cases, such as when an incorrect subscriber ID is provided or when a user accesses an unknown endpoint.

## Installation

Clone the repository from Github

Install the required dependencies

bash
npm install

Create Database

bash
node .\src\createDatabase.js

Starting Server

bash
npm run dev

## API Endpoints

Following API endpoints for retrieving subscribers information using the GET method.

GET http://localhost:3000/subscribers to get array of subscribers.

GET http://localhost:3000/subscribers/names to get array of subscribers with only name and subscribedChannel fields.

GET http://localhost:3000/subscribers/:id to get a subscriber by its unique id.

## Dependencies

The following dependencies are required to run the Get YouTube Subscribers :

NodeJs
ExpressJs
Mongoose
nodemon
swagger-jsdoc
swagger-ui-express
dotenv

## Authors

- [@Vanshita](https://github.com/VANSHI1194)

## Demo

https://ytsubs-vzjq.onrender.com/
