
# CHESS AND FRIENDS

## Description

This Chess Game project is a web-based application designed to facilitate real-time chess matches between two players while allowing an unlimited number of spectators to watch the game live. Built using Node.js, Express, Chess.js, EJS, and Socket.io, this project aims to provide an interactive and engaging platform for chess enthusiasts.

### Who It's For

- **Chess Enthusiasts**: Anyone who loves playing or watching chess will enjoy this platform.
- **Developers and Learners**: Those interested in learning about web development, real-time communication, and multiplayer game logic can benefit from exploring and contributing to this project.

## Features

- **Real-Time Gameplay**: Two players can join and play chess against each other in real-time.
- **Spectator Mode**: Unlimited spectators can join to watch the live game.
- **Easy Setup**: Quick and simple to set up and start playing.


## Installation

***Make sure you have node.js and nodemon installed***

Follow these steps to set up and run the chess game on your local machine:

1. Clone the repository

```bash
    git clone https://github.com/KartikLove31/chess-game.git
    cd chess-game
```
2. Install the dependencies:
```bash
    npm install express chess.js ejs socket.io
```
3. Start the application:
```bash
    npx nodemon app.js
```
## Demo

#### How to Play
- Open your web browser and navigate to http://localhost:3000.
- The first two users to join the game will be assigned as players.
- Subsequent users will join as spectators and can watch the game in real-time.





## Technologies Used

- **Express**: A fast, unopinionated, minimalist web framework for Node.js.
- **Chess.js**: A JavaScript library for chess move generation, validation, and manipulation.
- **EJS**: Embedded JavaScript templates for rendering dynamic content on the front-end.
- **Socket.io**: A library for enabling real-time, bidirectional communication between web clients and servers.


## Contributing

Contributions are always welcome!

If you'd like to contribute, please follow these steps:

    1. Fork the repository.
    2. Create a new branch (git checkout -b feature-branch).
    3. Make your changes and commit them (git commit -m 'Add some feature').
    4. Push to the branch (git push origin feature-branch).
    5. Open a pull request to the main branch.
## Acknowledgements

Special thanks to the developers of Express, Chess.js, EJS, and Socket.io for their excellent libraries that made this project possible.

