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

## 2. Component Breakdown

### Frontend (/frontend)

#### Technology Stack:
- React.js
- Tailwind CSS / DaisyUI
- Zustand for State Management
- Socket.io-client for real-time communication

#### Key Components:
- **Authentication Pages**
  - Login
  - Registration
  - Password Reset
- **Chat Interface**
  - Conversation List
  - Message Thread
  - User Profile
- **Real-time Features**
  - Online/Offline Status
  - Typing Indicators
  - Message Delivery Status

### Backend (/backend)

#### Technology Stack:
- Node.js
- Express.js
- Socket.io
- MongoDB
- JWT for Authentication
- Bcrypt for Password Security

#### Core Services:
- **User Management**
  - Registration
  - Authentication
  - Profile Management
- **Messaging Service**
  - Message CRUD Operations
  - Real-time Message Routing
- **File Upload Service**
  - Image Sharing via Cloudinary

### Database (MongoDB)

#### Collections:
- **users**
  - User profile information
  - Authentication credentials
- **conversations**
  - Chat room/group details
  - Participant lists
- **messages**
  - Individual message documents
  - Metadata (sender, timestamp, etc.)

---

## 3. Security Considerations
- JWT-based stateless authentication
- Bcrypt password hashing
- WebSocket connection encryption
- Input validation and sanitization
- Rate limiting on API endpoints

---

## 4. Scalability & Performance
- Implement Redis for caching
- Use MongoDB indexing
- Horizontal scaling support
- Efficient WebSocket connection management

---



