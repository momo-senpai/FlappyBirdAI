# FlappyBird AI

This project is a simple implementation of the classic Flappy Bird game with an added twist – it incorporates an AI agent trained using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to play the game. The AI learns to navigate through pipes and accumulate a higher score over generations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Game Controls](#game-controls)
- [Training the AI](#training-the-ai)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/flappybird-ai.git
    cd flappybird-ai
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the game:

    ```bash
    python flappybird_ai.py
    ```

## Usage

The game can be played manually or left to run autonomously with the AI taking control. The AI is trained using the NEAT algorithm and evolves over multiple generations to improve its performance.

## Game Controls

- **Space Bar**: Jump (Manual mode)
- **Close Window Button**: Quit the game

## Training the AI

The AI is trained automatically during the execution of the game. It uses the NEAT algorithm to evolve neural networks for the bird entities. The training progress and generation statistics are displayed on the game window.

## Configuration

The game's behavior and AI training parameters can be configured using the `config-feedforward.txt` file. Adjustments to parameters such as mutation rates, population size, and neural network architecture can be made to experiment with different training strategies.

## Dependencies

- Python 3.x
- Pygame
- NEAT-Python

Install the required dependencies using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your own purposes.