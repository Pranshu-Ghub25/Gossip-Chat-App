# Gossip Chat Application

Gossip is a real-time chat application built with React on the frontend and Node.js with Express on the backend. This project leverages Stream Chat for real-time messaging and Twilio for communication features.

## Live Demo : https://lets-gossip.netlify.app/

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
  - [Client](#client)
  - [Server](#server)
- [Usage](#usage)


## Project Description
Gossip allows users to create accounts, join chat rooms, and communicate in real-time. The app is designed to be scalable and easy to extend with additional features.

## Features
- User authentication
- Real-time messaging
- Chat room creation and management
- Integration with Twilio for SMS notifications

## Tech Stack
**Client:**
- React
- Axios
- Stream Chat React

**Server:**
- Node.js
- Express
- Stream Chat
- Twilio
- bcrypt
- cors
- dotenv

## Setup and Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- npm (or yarn)

### Client
1. Navigate to the `client` directory:
    ```bash
    cd client
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Start the client:
    ```bash
    npm start
    ```

### Server
1. Navigate to the `server` directory:
    ```bash
    cd server
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Create a `.env` file in the `server` directory and add your environment variables:
    ```env
    PORT=5000
    STREAM_API_KEY=your_stream_api_key
    STREAM_API_SECRET=your_stream_api_secret
    TWILIO_ACCOUNT_SID=your_twilio_account_sid
    TWILIO_AUTH_TOKEN=your_twilio_auth_token
    ```
4. Start the server:
    ```bash
    npm run dev
    ```

## Usage
1. Open your browser and navigate to the client application (usually `http://localhost:3000`).
2. Register a new account or log in with an existing one.
3. Create or join a chat room.
4. Start chatting in real-time with other users.

