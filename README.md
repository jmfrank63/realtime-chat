# Project: Real-time Chat Application using Deno, Oak and HTMX

This project will allow you to demonstrate your skills in real-time communication, front-end development, and back-end server handling.

## Technologies to be used

1. **Deno**: As the runtime environment to run TypeScript on the server side.
2. **Oak**: A middleware framework for Deno's http server, including a router middleware. This can be used as an alternative to Express.js in Deno.
3. **WebSocket**: Deno has built-in support for WebSocket, which you can use for real-time communication.
4. **HTMX**: You will use HTMX for building user interfaces on the client side.
5. **MongoDB**: Deno has a third-party module for MongoDB which you can use to interact with your MongoDB database.

## Features to implement

1. User authentication (you can use JWT for session handling)
2. Individual chat rooms
3. Real-time message broadcasting
4. Message history for each chat room
5. Online status of users

## Pseudocode

1. Set up your Deno server with Oak.
2. Connect your server to MongoDB using a third-party Deno module for MongoDB.
3. Set up WebSocket on the server side and implement event listeners for different events like 'open', 'message', 'close', etc.
4. Create HTMX templates for the login page, chat room list, individual chat room, etc. You can use server-side rendering to generate these templates.
5. Use HTMX on the client side to handle WebSocket events and update the UI in real-time.
6. Implement JWT for user authentication and session handling. You can use a third-party Deno module for JWT.
7. Implement the logic for creating and joining chat rooms.
8. Implement the logic for storing and retrieving message history from MongoDB.
