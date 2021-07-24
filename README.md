# AI---Minesweeper

### An implementation of the Minesweeper Game where AI can play by itself. The system uses information from cells already discovered and generate knowledge using proposicional logic algorithm.

There are two main files in this project: runner.py and minesweeper.py.

runner.py was provided and it contains all of the code to run the graphical interface for the game.

minesweeper.py was implemented by myself, and it contains all of the logic for playing the game, and for making optimal moves. AI inferes secure movement (if it is able to do that, based on the knowledge base). If there are not secure movements, AI picks a random cell.


## Getting Started

1. Once in the directory for the project, run `pip3 install -r requirements.txt` to install the required Python package (pygame) for this project.

2. Then run `python runner.py` and play with your AI. 

Have Fun!
