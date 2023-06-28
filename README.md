# Game_theory
Original code inspired by the learning process of game theory. This repository contains simple implementations of games from game theory.

## Contents
- [Soccer Penalty Game](#soccer-penalty-game)

## Soccer Penalty Game
The Soccer Penalty Game is a fun, interactive way to understand the concepts of Nash Equilibrium and mixed strategies in game theory.

### Description
The game involves two participants, a server and a client, each representing a player in a soccer penalty shootout: the striker (player) and the goalkeeper (goalie). The game is designed to run on two separate computers, utilizing socket programming in Python to facilitate communication between the two machines.

Each player can choose one of two actions: "left" or "right". The server and client code enable each player to input their action choice. The game's outcome depends on both the goalie's and the player's choices, following the principles of the mixed strategy Nash Equilibrium.

### Features
- **Role assignment**: The server randomly assigns the roles of 'goalie' and 'player' to itself and the client at the start of each round, providing variety in gameplay.
- **Concealment of actions**: The server does not reveal the client's action until it has input its own action. This mimics the simultaneous action selection in a real penalty shootout.
- **Result Communication**: The server calculates the game's outcome based on a payoff matrix that mimics real-world soccer penalty statistics and sends a summary message to the client. The message includes the actions of both players, the result, and whether the server won or lost.
- **Game termination**: Either player can end the game at any time by inputting 'quit'. If either side sends the 'quit' command, the game ends for both participants.

Have fun with the codes!

