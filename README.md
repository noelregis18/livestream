# OhMyStream - Livestreaming Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern livestreaming platform that allows users to create and watch live video streams using RTMP protocol.

## Project Overview

OhMyStream (ohmystream.co) is a full-stack livestreaming application built with React and Node.js. The platform supports real-time video streaming through RTMP protocol with ffmpeg for video processing.

## Features

- Live video streaming via RTMP protocol
- User authentication and account management
- Stream creation and management
- Real-time chat using WebSockets
- Email notifications
- Responsive design for various devices

## Tech Stack

### Frontend
- React JS
- CSS
- React Router
- React Icons
- React Hot Toast for notifications

### Backend
- Node.js
- Express
- Node Media Server (RTMP server)
- FFmpeg for video processing
- WebSockets (ws)
- Nodemailer for email functionality

## Project Structure

```
├── client/             # React frontend application
├── server/             # Node.js backend server
├── env.example         # Example environment variables
├── env.sh              # Environment setup script
├── startup.sh          # Server startup script
└── update.sh           # Update script
```

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm or yarn
- FFmpeg installed on your system

### Setup Instructions

1. Clone the repository
   ```
   git clone <repository-url>
   cd Project-39
   ```

2. Frontend setup
   ```
   cd client
   npm install
   npm start
   ```

3. Backend setup
   ```
   cd server
   cp env.example .env  # Configure your environment variables
   npm install
   node server.js
   ```

## Environment Variables

Create a `.env` file in the server directory with the variables from `env.example`.

## Usage

1. Start the backend server
2. Start the frontend application
3. Access the application at `http://localhost:3000`
4. Create an account and start streaming

## Streaming Setup

To stream to the platform, use an RTMP-compatible streaming software like OBS Studio:

1. Set the stream URL to: `rtmp://your-server-address/live`
2. Set the stream key to your account's stream key

## Development

The project uses a Trello board for task management: [OhMyStream Trello](https://trello.com/b/W8LZ83oV/ohmystream)

## Contributing

Feel free to use the code however you would like. Contributions, issues, and feature requests are welcome!

Reach out on Twitter: [@t0xsh](https://twitter.com/t0xsh)

## License

This project is licensed under the MIT License - see the LICENSE file for details.