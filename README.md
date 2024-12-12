<div align="center">
  <h1>Socket Chat</h1>
  <p>Real-time chat application with room support and location sharing</p>
</div>

## 🌟 Features

- **Real-time messaging** - Instant message delivery using Socket.IO
- **Chat rooms** - Create and join different chat rooms
- **Location sharing** - Share your current location with other users
- **Profanity filter** - Blocks inappropriate messages
- **Auto-scroll** - Automatically scrolls to new messages
- **User lists** - Shows active users in each room
- **Clean UI** - Minimalist and responsive design

## 🛠️ Tech Stack

- **[Node.js](https://nodejs.org/)** - Runtime environment
- **[Express](https://expressjs.com/)** - Web framework
- **[Socket.IO](https://socket.io/)** - WebSocket library
- **[Mustache.js](https://github.com/janl/mustache.js)** - Templating
- **[Moment.js](https://momentjs.com/)** - Time formatting
- **[Bad-words](https://www.npmjs.com/package/bad-words)** - Profanity filter

## 🚀 Getting Started

1. Install dependencies:

```bash
npm install
```

2. Start development server:

```bash
npm run dev
```

3. Open http://localhost:3000 in your browser

## 📝 Usage

1. Enter your name and room name to join
2. Start chatting with others in the room
3. Use "Send Location" to share your coordinates
4. Messages are delivered instantly to all room members

## 🔄 WebSocket Events

- `connection` - New user connects
- `join` - User joins a room
- `sendMessage` - Send chat message
- `sendLocation` - Share location
- `disconnect` - User leaves

## 📱 Responsive Design

- Mobile-first approach
- Clean and minimalist UI
- Optimized for all screen sizes
