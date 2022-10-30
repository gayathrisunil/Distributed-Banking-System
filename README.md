## Introduction

Python implementation of a fault tolerant distributed bank transaction using RAFT and blockchain technology.

## How to Run

### Setting up the Environment

1. First install [Poetry](https://python-poetry.org/).
2. Run `poetry shell` to activate a virtual environment.

### Steps

1. In one terminal, run `python3 channel.py`.
2. In three new terminals, run `python3 server.py` and select a unique id in each of them.
3. Now open two more or three more terminals and run `python3 client.py` and enter a unique id in each of them.
4. Use the prompts to manage the different operations

## Stop Running

1. Hit `CTRL+C` in each terminal to stop the process.
2. To exit the virtual environment, enter `exit` on windows or `deactivate` on unix.
