# Slot Machine Simulator

A simple terminal-based slot machine simulator built using JavaScript and Node.js. This project serves as a beginner-friendly introduction to JavaScript programming by walking through the creation of a complete project with practical use of core JavaScript concepts. 

The slot machine allows users to deposit money, place bets on up to three lines, spin the reels, and calculate payouts based on matching symbols.

## Features

- Deposit funds and manage your balance.
- Bet on up to three lines for each spin.
- Randomized reel symbols for every spin.
- Dynamic payout calculations based on matching symbols and their respective multipliers.
- Simple and interactive terminal-based interface.

## Requirements

- [Node.js](https://nodejs.org/) (latest stable version recommended)
- NPM (comes with Node.js installation)
- `prompt-sync` NPM package for collecting user input

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/codree8/slot-machine-simulator.git
   cd slot-machine-simulator

2. Install the required dependencies:

   npm install prompt-sync

3. Run the application:

   node project.js

## How to Play

1. Deposit money into your account.
2. Choose how many lines you want to bet on (1 to 3).
3. Enter the amount you wish to bet per line.
4. Spin the reels and check if you've won based on the matching symbols.
5. Winnings are added to your balance, and you can play again or quit.

## Directory Structure

slot-machine-simulator/
│
├── project.js        # Main JavaScript file for the project
├── package.json      # NPM package configuration file
└── README.md         # Project documentation

## License

This project is for educational purposes only. Gambling is not supported or encouraged. Please use responsibly and only as a learning tool.