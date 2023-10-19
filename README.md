{
  "name": "chat-app",
  "version": "1.0.0",
  "description": "",
  "main": "server.js",
  "scripts": {
    "start": "node backend/server.js",
    "server": "nodemon backend/server.js",
    "build": "npm install && npm install --prefix frontend && npm run build --prefix frontend"
    "build": "npm install --legacy-peer-deps && npm install --legacy-peer-deps --prefix frontend && npm run build --prefix frontend"
  },
  "keywords": [
    "mern",
    "chat-app"
  ],
  "author": "Piyush Agarwal",
  "license": "ISC",
  "dependencies": {
    "bcryptjs": "^2.4.3",
    "colors": "^1.4.0",
    "dotenv": "^9.0.2",
    "express": "^4.17.1",
    "express-async-handler": "^1.1.4",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.12.9",
    "nodemon": "^2.0.7",
    "socket.io": "^4.1.2"
  }
}
