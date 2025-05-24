# Suretshi AI Drawing Assistant

A real-time drawing assistant that uses your camera to analyze your drawings and provide personalized artistic feedback using AI.

## Features

- Real-time camera capture of drawings
- AI-powered analysis of proportions, perspective, and anatomy
- Voice feedback system
- Modern, responsive UI

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- OpenAI API key

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. Create a `.env` file in the server directory with the following content:
   ```
   PORT=3000
   CLIENT_URL=http://localhost:5173
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. Start the development servers:
   ```bash
   # Start the backend server
   cd server
   npm run dev

   # In a new terminal, start the frontend
   cd client
   npm run dev
   ```

5. Open http://localhost:5173 in your browser

## Usage

1. Position your camera above your drawing paper
2. Click the "Analyze Drawing" button to capture and analyze your drawing
3. Receive AI-powered feedback on your drawing

## Technologies Used

- Frontend:
  - React
  - TypeScript
  - Tailwind CSS
  - Socket.IO Client
  - React Webcam

- Backend:
  - Node.js
  - Express
  - Socket.IO
  - OpenAI API
  - TypeScript

## License

MIT 