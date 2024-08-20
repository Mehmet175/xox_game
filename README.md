# Tic Tac Toe Game

## Overview

This is a simple turn-based Tic Tac Toe game developed using Flutter. The application uses Firebase as the database. Users play anonymously, and the game features real-time updates, allowing for a seamless and interactive experience.

## Features

- **User Management**: Users must enter a name before accessing the game list.
- **Game Creation**: Users can create a new game by specifying the game name, board background color, and participants.
- **Real-Time Game List**: All created games are listed and updated instantly whenever there is a change in Firebase.
- **Game Play**: The game follows classic Tic Tac Toe rules. The game grid is 3x3 by default, and users take turns placing "X" and "O".
- **Game Reset**: If the game ends in a tie, it automatically restarts. If a player wins, the game is marked as completed and cannot be played again.
- **Flexible Grid Size**: Users have the option to select grid sizes larger than 3x3 when creating a game, offering a more customizable gaming experience.

## Screens

- **Name Entry Screen**: Users must enter their name to proceed.
- **Game Creation Screen**: Allows the creation of a new game with options to set the name, background color, and grid size.
- **Game List Screen**: Displays all available games with real-time updates.
- **Game Screen**: Displays the game board where users play Tic Tac Toe.

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/) SDK
- A Firebase project for backend services
