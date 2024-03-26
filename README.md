# Chat App Backend

This is the backend code for the Chat App. It provides the server-side functionality for the chat application.

## Features

- User authentication and authorization
- Real-time messaging using WebSockets
- Persistent storage of chat messages
- User management (create, update, delete)
- Chat room management (create, join, leave)

## Technologies Used

- Node.js
- Express.js
- Socket.io
- MongoDB (or any other database of your choice)

## Getting Started

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Configure the environment variables:
    MONGO_URI,JWT_SECRET,ADMIN_SECRET_KEY,NODE_ENV = DEVELOPMENT,CLIENT_URL,CLOUDINARY_CLOUD_NAME,CLOUDINARY_API_KEY,CLOUDINARY_API_SECRET
4. Start the server: `npm start`

## Configuration

The following environment variables need to be configured:

- `CLIENT_URL`: The URL on which the client will run
- `MONGO_URI`: The URI for connecting to the MongoDB database
- `JWT_SECRET`: The secret key used for JWT authentication
- `ADMIN_SECRET_KEY`: The secret key used for Admin Dashboard
- `NODE_ENV`: Set to either 'development', 'production', or 'test' to indicate the current environment. This can be used for configuration changes based on the environment.
- `CLOUDINARY_API_KEY`:Your Cloudinary API key 
- `CLOUDINARY_CLOUD_NAME`:our Cloudinary cloud name
- `CLOUDINARY_API_SECRET`: Your Cloudinary API secret 

