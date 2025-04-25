## Social Space Book Api
A back-end API for a social networking application where users can share thoughts, react to friends’ thoughts, and create a friend list. Built using Node.js, Express, MongoDB, and Mongoose.

## Features
- CRUD operations for Users and Thoughts
- Reactions (like comments) on Thoughts
- Add/Remove friends
- MongoDB NoSQL database with Mongoose ODM
- RESTful architecture
- JSON responses

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JavaScript

## Usage
Use Insomnia or Postman to interact with the API routes.

The API allows you to:

Create, update, delete users

Post and manage thoughts

Add/remove friends

React to thoughts


## Users
GET /api/users — Get all users

GET /api/users/:id — Get user by ID

POST /api/users — Create a new user

PUT /api/users/:id — Update user by ID

DELETE /api/users/:id — Delete user by ID

POST /api/users/:userId/friends/:friendId — Add a friend

DELETE /api/users/:userId/friends/:friendId — Remove a friend

## Thoughts
GET /api/thoughts — Get all thoughts

GET /api/thoughts/:id — Get a single thought

POST /api/thoughts — Create a new thought

PUT /api/thoughts/:id — Update a thought

DELETE /api/thoughts/:id — Delete a thought

Reactions
POST /api/thoughts/:thoughtId/reactions — Add a reaction

DELETE /api/thoughts/:thoughtId/reactions/:reactionId — Remove a reaction

## Demo
 Walk Through Video Link
https://drive.google.com/file/d/1MOBgOtSQKZU6_i8MGjv0j7LGjE9O77F1/view?usp=sharing
