# da-snake

A terminal-based Snake game implemented in Rust, built by DeflateAwning. This project features a simple and interactive user interface using a terminal TUI (Text User Interface), allowing you to play the classic Snake game directly in your terminal. 

You can install it via `cargo` from [crates.io](https://crates.io) or build it from source.

[![Crates.io](https://img.shields.io/crates/v/da-snake.svg)](https://crates.io/crates/da-snake)

## Features

- **Classic Snake Gameplay**: The game follows the traditional Snake mechanics.
- **Terminal-based User Interface (TUI)**: Built to be fully played within your terminal.
- **Cross-platform**: Compatible with any system that supports Rust and the terminal.
- **High Score Tracking**: Tracks high scores across sessions.
- **Configurable Snake Color**: The snake can be made any color, or can be a gradient. Run `--help` to see available options.
- **Configurable Snake Speed**: The snake's speed can be adjusted via command-line options.

## Table of Contents

- [Installation](#installation)
- [Building from Source](#building-from-source)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

### From Crates.io

You can easily install the Snake Terminal UI directly using `cargo` by running the following command:

```bash
cargo install da-snake
```

This will download and install the latest version of the game from crates.io.

## Building from source

To build the project from source, follow these steps:

1. Clone the repository
    ```bash
    git clone https://github.com/DeflateAwning/da-snake.git
    cd da-snake
    ```
2. Build the project using cargo
    ```bash
    cargo build --release
    ```
3. Run the game
    ```bash
    cargo run
    ```
This will compile the code and start the game in your terminal.

## Usage

After installation or building from source, you can start the game by simply running:

```bash
da-snake
```

Control the snake using the arrow keys and try to eat the food to grow the snake longer. The game ends when the snake collides with itself.

## Credits

This project is a fork of https://github.com/RiccardoSegala04/snake-tui, with added features.
