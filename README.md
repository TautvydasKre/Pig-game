# Pig Game

Pig Game is a two-player dice game built using HTML, CSS, and JavaScript DOM manipulation. The main goal of the game is to reach 100 points before the other player.

## How to Play

1. **Roll the Dice**: 
   - Click on the **🎲 Roll Dice** button to roll the dice.
   - If you roll any number other than 1, it gets added to your current score.
   - If you roll a 1, your current score becomes 0, and it's the other player's turn.

2. **Hold Your Score**: 
   - Click on the **📥 Hold** button to add your current score to your total score and pass the turn to the other player.
   - Be strategic: Hold your score before you roll a 1, or you’ll lose the points from that round.

3. **Winning the Game**:
   - The first player to reach 100 points wins the game.
   - If a player's score reaches 100 or more, the game ends, and they are declared the winner.

4. **New Game**:
   - Click on the **🔄 New Game** button to reset the game and start a new match.

## Game Rules

- Each turn, a player can roll the dice multiple times. The number rolled is added to their current score.
- If the player rolls a 1, they lose their current score for that round, and the turn goes to the other player.
- A player can choose to hold their current score, adding it to their total score and passing the turn.
- The first player to reach 100 points wins the game.

## Technologies Used

- **HTML5**: For the structure of the game.
- **CSS3**: For styling the game layout and UI elements.
- **JavaScript (DOM manipulation)**: For game logic, updating scores, switching turns, and managing the game state.

## Installation

To run the game locally:

1. Clone the repository or download the ZIP file:
   ```bash
   git clone https://github.com/TautvydasKre/Pig-game.git
