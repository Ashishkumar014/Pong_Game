# Pong_Game
This is a simple Pong game implemented using HTML, JavaScript, and Python with Flask. The game runs in a web browser and can be controlled using the keyboard.

## Features

- Two-player Pong game
- Control paddles using keyboard keys:
  - Player A: `W` (up) and `S` (down)
  - Player B: `Up Arrow` (up) and `Down Arrow` (down)
- Ball movement and collision detection

## Project Structure
pong_game/
├── app.py
└── templates/
└── index.html

- `app.py`: The Python backend using Flask to serve the HTML file.
- `templates/index.html`: The HTML file containing the Pong game implemented with JavaScript.

## Prerequisites

- Python 3.x
- Flask

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/pong_game.git
    cd pong_game
    ```

2. Install Flask:
    ```sh
    pip install flask
    ```

## Running the Game

1. Start the Flask server:
    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/` to play the game.

## Game Controls

- Player A:
  - Move Up: `W`
  - Move Down: `S`
- Player B:
  - Move Up: `Up Arrow`
  - Move Down: `Down Arrow`

## Code Reference

The HTML and JavaScript for the game are located in `templates/index.html`. The Flask backend is in `app.py`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is based on a simple Pong game tutorial using HTML5 and JavaScript.


