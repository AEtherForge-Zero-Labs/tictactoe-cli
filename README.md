# TicTacToe CLI

A command-line interface (CLI) Tic-Tac-Toe game created for the Computer Science Club.

## Project Overview

This project is a simple yet interactive Tic-Tac-Toe game designed to be run directly from the command line. It allows for quick matches and integrates with the `tictactoe-tournament` library for added tournament support. Built with `Click`, the CLI is straightforward to use, and the codebase is well-suited for development and testing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Installation

**Requirements**: Python 3.8 or higher.

To install the project dependencies, clone the repository and run:

```bash
pip install .
```
This will install all necessary dependencies, including click and the tictactoe-tournament package.

## Usage

To start a game, use the following command:
```bash
ttt
```

This will launch the Tic-Tac-Toe CLI. For help and available commands, run:
```bash
ttt --help
```
## Development

To set up the development environment, install the dev dependencies:
```bash
pip install .[dev]
```
Run Tests

Run tests using pytest:
```bash
pytest
```
Code Formatting

This project uses black for code formatting. To format the code, run:
```bash    
black .
```
## Documentation

Documentation is built with Sphinx. To generate the documentation locally:
```bash
sphinx-build docs docs/_build
```
## Contributing

Contributions are welcome! Please open an issue or submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the terms of the GNU General Public License v3.0. See the LICENSE file for details.

## Links

•	[Homepage](https://github.com/AEtherForge-Zero-Labs/tictactoe-cli)
•	[Report Issues](https://github.com/AEtherForge-Zero-Labs/tictactoe-cli/issues)
•	[Source Code](https://github.com/AEtherForge-Zero-Labs/tictactoe-cli)