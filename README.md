# Tic Tac Toe with Minimax Algorithm

This is a simple implementation of Tic Tac Toe with an AI opponent that uses the Minimax algorithm with Alpha-Beta Pruning for decision-making. The game is implemented in Python, and the AI player evaluates the board position using a simple positional matrix score.

## Positional Matrix Score

The `positional_matrix_score` is a matrix that assigns scores to each position on the Tic Tac Toe board. The AI evaluates the board based on the sum of scores for 'X' positions and subtracts the sum of scores for 'O' positions.

```python
positional_matrix_score = [
    [50, -50, 50],
    [-50, 150, -50],
    [50, -50, 50]
]
```

## How to Play
Run the script, and you'll be prompted to make a move as 'O'. The AI player ('X') uses the Minimax algorithm to determine its moves. The game continues until there is a winner or a draw.

bash
Copy code
python tic_tac_toe.py
Implementation Details
The game is implemented using a TicTacToeBoard class.
The AI player evaluates the board using the evaluate_board function and makes decisions with the Minimax algorithm.
The game continues until there is a winner or a draw.
Feel free to explore the code, and enjoy playing Tic Tac Toe against the Minimax AI opponent!
