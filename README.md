# Chess ♟️

A real-time, multiplayer chess game built with Node.js, Express, Socket.io, and EJS. This web application allows two users to play chess against each other in their browsers, with automatic assignment of white and black pieces and seamless synchronization of the board state using websockets. Spectators can also join to watch ongoing games in real time. The user interface features a responsive and interactive chessboard with drag-and-drop support for moving pieces, and a visually appealing design for an enjoyable playing experience. Perfect for learning, casual play, or as a foundation for further development of chess-related features!
## Features

- Real-time chess gameplay using websockets
- Automatic player assignment (White/Black/Spectator)
- Responsive chessboard UI
- Drag-and-drop piece movement

## Demo 

Sample screenshot of two players connected to the chess game on localhost.

<img width="957" alt="Image" src="https://github.com/user-attachments/assets/db4dfa4f-5938-4327-addd-1bce89f7ee9c" />

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes with Node.js)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sejaljadhav21/Chess.git
   cd Chess
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the local development server using nodemon:**
   ```bash
   npx nodemon app.js
   ```
   The server will start on [http://localhost:3000](http://localhost:3000).

4. **Open your browser and visit:**
   ```
   http://localhost:3000
   ```

## Project Structure

```
.
├── app.js              # Main server file
├── package.json
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── chessgame.js
├── views/
│   └── index.ejs
└── ...
```

## Dependencies

- express
- socket.io
- chess.js
- ejs

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

---
