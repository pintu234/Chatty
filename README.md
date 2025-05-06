# Echos

## Overview

This is a real-time chat app built using ReactJS, NodeJS, ExpressJS, MongoDB, Socket.io, Cloudinary, and JWT. It allows users to create accounts, chat with others, and send images.

## Features

💬 Real-time Messaging: Enable instant communication with WebSocket or Socket.IO.  
🔑 Authentication System: Implement secure user signup and login with JWT.  
👤 User Profiles: Allow users to set profile pictures.  
📡 Online/Offline Status: Show real-time presence of users.  
📄 Chat History Persistence: Store and retrieve messages using MongoDB.  
👥 Group Chat: Support creation and management of group conversations.  
🎨 Responsive UI/UX Design: Build with Tailwind CSS and DaisyUI.  
🔐 End-to-End Security: Use bcrypt for password encryption.  
📂 File Sharing: Allow users to send images.  

## Getting Started

```
PORT=5001
MONGO_URI=your_mongo_uri

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

### Run this app locally
``` npm run build ```

### Start this app
``` npm run start ```

## Tech Stack

- **Frontend:** ReactJS with Tailwind CSS and DaisyUI.
- **Backend:** NodeJS with ExpressJS (for APIs).
- **Database:** MongoDB.
- **Authentication:** JWT
- **WebSocket:** Socket.io
- **Storing Images:** Cloudinary


---




