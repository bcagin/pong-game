# Python Pong Game

This is a simple implementation of the classic Pong game using Python. The game is a two-player sports game where players control paddles to hit the ball back and forth across the screen. The objective is to score points by making the ball go past the opponent's paddle without letting it pass your own paddle.

## Getting Started

These instructions will help you get a copy of the Pong game up and running on your local machine.

### Prerequisites

To run the Pong game, you need to have the following installed:

- Python 3.x: You can download Python from the official website: [python.org](https://www.python.org/downloads/)

### Installation

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/bcagin/pong-game.git
   ```

   Alternatively, you can download the repository as a ZIP file and extract it.

2. Navigate to the project directory:

   ```bash
   cd pong-game
   ```

## Gameplay

- Player 1 (left paddle) controls the paddle using the `W` and `S` keys to move up and down, respectively.
- Player 2 (right paddle) controls the paddle using the up and down arrow keys.
- The ball will start moving towards a random direction at the beginning of each round.
- The objective is to hit the ball with your paddle and make it go past the opponent's paddle.
- Each time the ball passes a paddle, the opposing player scores a point.

## Customization

You can customize the game by modifying the following parameters in the `pong_game.py` file:

- `WIDTH` and `HEIGHT`: Control the dimensions of the game window.
- `PADDLE_WIDTH` and `PADDLE_HEIGHT`: Define the width and height of the paddles.
- `PADDLE_SPEED`: The speed at which the paddles move.
- `BALL_SIZE`: The radius of the ball.
- `BALL_SPEED`: The speed at which the ball moves.

Feel free to tweak these parameters and experiment with different settings!

## Acknowledgments

This Pong game implementation is based on the tutorial by Angela Yu's The Complete Python Pro Bootcamp for 2023: (https://www.udemy.com/course/100-days-of-code/)
