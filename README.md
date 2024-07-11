# Tic Tac Toe

Computer player uses simplified minimax to play tic-tac-toe. If human player plays perfectly, the game should always end in a draw.

Given the relatively small state-space for tic-tac-toe we can, on each move, search the state graph right down to the leaf nodes. Furthermore, we don't even need to compare state scores because all winning states are equally as good and all losing states are equally as bad; when we do the "maximise/minimise next state" loop in minimax, we can exit as soon as we find a positive/negative outcome. For this same reason, we don't need anything like alpha/beta pruning.

## How to play

1. Open in a browser
2. Click the buttons
3. Try not to cry when the computer inevitably kicks ass
