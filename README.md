# Real-Time Chat Web Application

## Overview
This project is a real-time chat web application that enables instant messaging between a user and the server using WebSockets. The backend is powered by **Strapi**, while the frontend is built using **Next.js** and **TypeScript**. The application also supports user authentication, local storage for chat sessions, and a responsive design.


## Main Focus Areas
- **Local Storage**
- **Backend Setup**
- **WebSockets**
- **Responsiveness**

## Features

### 1. **Backend Setup**
- Built using **Strapi**, an open-source headless CMS.
- Provides a structured backend infrastructure.

### 2. **User Authentication**
- Users can **sign up, log in, and log out** securely.
- Authentication is handled via JWT or session storage.

### 3. **WebSocket API**
- Establishes a **WebSocket connection** between client and server.
- The server **echoes back** any message received from the client.
- Ensures that the connection remains active throughout the session.

### 4. **Chat Interface**
- **User-friendly interface** with a real-time chat box.
- Messages appear in a conversational format.
- Users can **switch between sessions**.

### 5. **Local Database Storage**
- Stores **user authentication data**.
- Stores **chat session history** for future reference.
- Uses local storage or indexedDB for persistence.

### 6. **Responsive Design**
- Works seamlessly on **desktop, tablet, and mobile**.
- Uses **flexible layouts and media queries**.

## Tech Stack
### **Frontend**
- **Next.js** (React Framework)
- **TypeScript** (Strongly-typed JavaScript)
- **TailwindCSS** (Styling)
- **WebSockets API** (For real-time communication)

### **Backend**
- **Strapi** (Headless CMS)
- **WebSockets (ws library)** for real-time communication

### **Database & Storage**
- **LocalStorage / IndexedDB** (For storing chat sessions)
- **Strapi Database** (For user authentication)

## Setup Instructions

### **1. Backend Setup (Strapi)**
```sh
npx create-strapi-app@latest chat-backend --quickstart
cd chat-backend
npm install ws  # Install WebSockets support
npm run develop
```

### **1. Frontend Setup
```
npx create-next-app@latest chat-frontend --typescript
cd chat-frontend
npm install tailwindcss websocket

```
### **1. Run the app
```
# Start Backend (Strapi)
cd chat-backend
npm run develop

# Start Frontend (Next.js)
cd chat-frontend
npm run dev

```
