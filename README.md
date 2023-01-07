# BetaOne - AlphaZero's little brother
This project is a personal thingie that uses AlphaZero's algorithm to train an AI in the art of chess.

I rely on the python-chess library to simulate the chess board, as well as suragnair's implementation of the AlphaZero algorithms, found [here](https://github.com/suragnair/alpha-zero-general).
sugarnair's repo contains (rather huge) pretrained models as well as examples for the different games, so instead of submoduling, I've opted to copy the main parts of the code into this repo and extend it. All credits go to sugarnair. 

## Installation
### Requirements
``$ pip install -r requirements.txt``