- **Get-YouTube-Subscribers**

This is an Almabetter's backend capstone project on Get-Youtube-Subscribers using ExpressJs, MongoDb, and NodeJs. This project involves developing a backend system for managing YouTube subscribers. We've designed a backend API that delivers responses in JSON format. 

## Table of Contents

- [Introduction ](#introduction)
- [API Reference ](#api-reference)
- [Features ](#features)
- [Tech Stack ](#tech-stack)
- [Prerequisites ](#prerequisites)
- [Installation & Run](#installation-and-run)
  


## Introduction
Get YouTube Subscribers is an Application that serves as a RESTful API created by using MongoDB in Node.js. It is designed to fetch all subscribers information related to YouTube channel subscribers. The primary technologies used to develop this application are Node.js and Express.js which are used to create API endpoints and manage HTTP requests. Additionally, this application utilizes MongoDB as the database to store and manage subscribers data efficiently.

## API Reference
The following API endpoints are for retrieving subscribers information using the GET method. 

- `/subscribers`: Retrieve a list of all subscribers with their ID, name, subscribed channel, and date.
- `/subscribers/names`: Obtain subscribers name along with the channel they are subscribed to.
- `/subscribers/id`: Access subscribers information based on their ID.


## Features
Some features of this application :
- **Seamless Data Retrieval:** Effortlessly fetch subscribers data from YouTube channels using API endpoints.
- **Structured JSON Output:** Present retrieved data in well-organized JSON format for easy interpretation.
- **Versatile API Endpoints:** Provide users with multiple API endpoints catering to various data retrieval needs.
- **Effective YouTube Data API Integration:** Interact seamlessly with the YouTube Data API for accurate data retrieval.
- **User-Friendly Setup:** Follow a straightforward setup process, enabling swift tool utilization.

## Tech Stack
GET-Youtube-Subscriber is built using the following technologies:

- **Node.js:** A runtime environment that executes JavaScript code on the server-side.
- **Express.js:** A node.js framework for building web applications and RESTful API.
- **MongoDB:** Is a NoSQL Database system that stores and manages data in JSON-like format.

## Prerequisites

To run this project locally, make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Installation and Run
1. Clone the repository from GitHub:
    ```
     git clone https://github.com/priya1599/Get-YouTube-Subscribers
    ```
2. Redirect to the project folder:
    ```
     cd Get-YouTube-Subscribers
    ```
3. Install the required dependencies:
    ```
     npm install
    ```
4. Configure the application:
   - Create a `.env` file in the project's root directory.
   - Add the following environment variables to the `.env` file:
      ```
       PORT=3000                             # The port on which the application will run
       DATABASE_URI= <your_uri_here>         # The MongoDB connection string
      ```
5. Create Database:
    - Inserting subscribers data into MongoDB.
        ```
         npm run createDB
        ```
6. Start server:
    ```
     npm start
    ```
    > [!NOTE]
    > Access the  application in your web browser at `http://localhost:3000` (base URL)













