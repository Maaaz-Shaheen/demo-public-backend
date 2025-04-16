# Basic Express Server

A simple Express server with a static API endpoint.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

Or for development with auto-reload:
```bash
npm run dev
```

## Available Endpoints

- `GET /`: Welcome message
- `GET /api/message`: Returns a JSON object with a message and timestamp

## Example Response

```json
{
  "message": "Hello from the Express server!",
  "timestamp": "2024-02-20T12:00:00.000Z"
}
``` # demo-public-backend
