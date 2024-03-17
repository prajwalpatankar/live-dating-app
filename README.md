# Live Dating App

## Overview
Live Dating App is an innovative platform designed to revolutionize the online dating experience. Unlike traditional dating apps, our app combines the instant decision-making process with the immediate connection of live video calls. When two users mutually swipe right, they are instantly connected through a video call, facilitating real-time conversations and interactions.

## Features
- **Swipe Mechanism:** Users can swipe left to pass or right to like other users. If both users swipe right, it's a match.
- **Instant Video Calls:** Matches immediately initiate a live video call, encouraging real-time interaction and connection.
- **User Profiles:** Users can create and customize their profiles, adding photos and a bio to express their personalities and interests.
- **Privacy and Security:** Ensures user privacy with secure video connections and gives users control over their personal information and who they choose to connect with.
- **Responsive Design:** Optimized for both mobile and desktop devices, ensuring a seamless user experience across all platforms.

## Technologies Used
- Frontend: React.js, Redux for state management, and WebRTC for real-time communication.
- Backend: Node.js with Express for the server, MongoDB for the database, and Socket.IO for managing live connections.
- Deployment: Docker for containerization and AWS for hosting.

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- Docker (optional)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/prajwalpatankar/live-dating-app.git
```
2. Install NPM packages for both server and client:
```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd ./frontend
npm install
```

3. Setup environment variables:

    Create a .env file in the backend directory.
    Add the necessary environment variables (e.g., database URI, secret keys).
    Run the application:

```bash
# Start the backend server
cd backend
npm start

# In another terminal, start the frontend client
cd frontend
npm start
```

## Contact
Your Name - patankarprajwal@example.com

Project Link: https://github.com/prajwalpatankar/live-dating-app
