## Resources 

- alpha-go-(zero?) with chess: https://github.com/Zeta36/chess-alpha-zero
- deepmind https://deepmind.com/blog/article/alphazero-shedding-new-light-grand-games-chess-shogi-and-go
- https://python-chess.readthedocs.io/en/latest/
- existing repo twitchcess: https://github.com/geohot/twitchchess

## Plan

- discover and understand the Chess library
- how to store a state of a position:
value of the position
who should play
serialized version
numpy array version

- how to compute the value of a position:
np.zeros((5,8,8), np.uint8)