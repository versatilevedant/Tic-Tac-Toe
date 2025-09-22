# **Tic Tac Toe Game (Python)**

A simple, interactive **Tic Tac Toe** game developed using **Python** for two players. This text-based game allows players to compete against each other in a **console/command-line interface**. Players take turns marking spaces on a 3x3 grid and aim to get three of their marks in a row (horizontally, vertically, or diagonally) to win.

---

### **Features:**
- **Player Turn Management**: Alternates turns between Player 1 and Player 2.
- **Dynamic Board Updates**: The game board is updated in real-time after each move.
- **Win Detection**: Automatically checks for winning conditions after each turn (rows, columns, diagonals).
- **Draw Handling**: If the board is full and no player has won, the game will declare a draw.
- **Input Validation**: Ensures players can only make valid moves (i.e., choosing an empty space on the board).
- **Replay Option**: After each game, players are prompted if they would like to play again.

---

### **How to Play:**
1. Clone or download this repository.
2. Run the `tictactoe.py` file in your terminal.
3. Players will be prompted to choose their marker (either 'X' or 'O').
4. Players will take turns to select a position (1-9) on the board to place their marker.
5. The game will check after every move to see if there's a winner or if the game is a draw.
6. Once the game ends, players can choose to replay or quit.

---

### **Game Flow:**
1. **Choose Player Markers**: The first player decides whether they want to be 'X' or 'O'. The other player will automatically get the other marker.
2. **Turns**: Players alternate placing their markers on the board. The board is displayed after every move.
3. **Win Check**: After each move, the game checks if the current player has won (three in a row horizontally, vertically, or diagonally).
4. **End of Game**: The game ends when a player wins or the board is full (in which case it's a draw).
5. **Replay**: After the game ends, players are prompted to replay or quit.

---

### **Technologies Used:**
- **Python 3**: The programming language used for the game logic and interactions.
- **Command-line Interface (CLI)**: The game is played via a terminal/command-line interface with user prompts for input.

---

### **Installation:**
To get started, simply clone this repository to your local machine:

```bash
git clone https://github.com/your-username/tic-tac-toe.git
