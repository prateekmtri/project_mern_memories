# Memories

![Memories](https://i.ibb.co/Z8Y0CJv/Screenshot-2020-10-30-at-11-10-04.png)

## Introduction
This is a code repository for the corresponding video tutorial - https://youtube.com/playlist?list=PL6QREj8te1P7VSwhrMf3D3Xt4V6_SRkhu.

Using React, Node.js, Express & MongoDB you'll learn how to build a Full Stack MERN Application - from start to finish. The App is called "Memories" and it is a simple social media app that allows users to post interesting events that happened in their lives.

By the end of this video, you will have a strong understanding of how the MERN Stack works.

### [🌟 Become a top 1% Next.js 15 developer in only one course](https://jsmastery.pro/next15)
### [🚀 Land your dream programming job in 6 months](https://jsmastery.pro/masterclass)

Setup:
- run ```npm i && npm start``` for both client and server side to start the app





## Environment Setup

This project requires MongoDB to run.

Create a `.env` file inside the `server` folder and add the following:

MONGO_URI=your_mongodb_connection_string
PORT=5000

You can get your MongoDB connection string from MongoDB Atlas.

## Backend Setup

Open terminal and run:

cd server
npm install
npm start

The backend will start on http://localhost:5000

## Frontend Setup

Open another terminal and run:

cd client
npm install
npm start

The frontend will start on http://localhost:3000

Make sure the backend is running before starting the frontend.

## Common Issues

If the server does not start, check if MongoDB is running and the MONGO_URI is correct.

If the frontend cannot fetch data, make sure the backend is running on port 5000.
