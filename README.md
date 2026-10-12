# Flappy Bird

A Flappy Bird-inspired terminal game written in C, featuring ASCII graphics, gravity-based movement, jumping mechanics, randomized pipes, and collision detection.

## Features

- Terminal-based ASCII graphics with ANSI colors
- Bird movement with gravity and jumping mechanics
- Moving pipes with randomized gaps
- Collision detection against pipes and boundaries
- Non-blocking keyboard input
- Lightweight implementation using C and POSIX APIs

## Controls

| Key | Action |
|---|---|
| `W` | Jump |
| `Q` | Quit the game |

## Requirements

- GCC or another compatible C compiler
- macOS or Linux
- A terminal that supports ANSI escape sequences

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Hammadmustafagundroo/Flappy-Bird.git
cd Flappy-Bird
```

Compile the source code:

```bash
gcc -Wall -Wextra main.c -o not-flappy-duck
```

Run the game:

```bash
./not-flappy-duck
```

## How to Play

1. Launch the game in a compatible terminal.
2. Press `W` to make the bird jump.
3. Navigate through the moving pipes without colliding with them.
4. Press `Q` to quit.

The game ends when a collision is detected.

## Project Structure

```text
Flappy-Bird/
├── main.c
├── .gitignore
├── LICENSE
└── README.md
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
