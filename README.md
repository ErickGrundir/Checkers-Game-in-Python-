# Checkers-Game-in-Python-
Checkers Game in Python:
class CheckersGame:
    def __init__(self):
        self.board = [
            ['_', 'X', '_', 'X', '_', 'X', '_', 'X'],
            ['X', '_', 'X', '_', 'X', '_', 'X', '_'],
            ['_', 'X', '_', 'X', '_', 'X', '_', 'X'],
            ['_', '_', '_', '_', '_', '_', '_', '_'],
            ['_', '_', '_', '_', '_', '_', '_', '_'],
            ['O', '_', 'O', '_', 'O', '_', 'O', '_'],
            ['_', 'O', '_', 'O', '_', 'O', '_', 'O'],
            ['O', '_', 'O', '_', 'O', '_', 'O', '_']
        ]

    def display_board(self):
        for row in self.board:
            print(' '.join(row))

# Example usage
checkers_game = CheckersGame()
checkers_game.display_board()
