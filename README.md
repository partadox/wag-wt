# WhatsApp Gateway Webhook Tester

A simple webhook tester for WhatsApp Gateway that displays incoming webhook events in real-time.

## Features

- Real-time webhook event display
- WebSocket-based updates
- Persistent storage of webhook events
- Easy deployment with Docker
- Mobile-friendly UI
- Displays different event types:
  - Message events
  - Connection events
  - Receipt events

## Usage

### Running Locally

#### With Node.js

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```
4. Open your browser at http://localhost:3000

#### With Docker

```bash
docker-compose up -d
```

The application will be available at http://localhost:3000

### Deploying to Coolify

1. Add this repository to your Coolify instance
2. Deploy as a Docker service
3. Make sure port 3000 is exposed

## Configuring the WhatsApp Gateway

1. Get your webhook URL from the web interface (e.g., `https://your-domain.com/webhook`)
2. In your WhatsApp Gateway client detail page:
   - Enable the webhook
   - Enter the webhook URL
   - Save the configuration

## Development

To run in development mode with auto-restart:

```bash
npm run dev
```

## License

MIT
