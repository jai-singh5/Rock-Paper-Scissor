# Rock, Paper, Scissors Game

This is a simple implementation of the classic **Rock, Paper, Scissors** game using HTML, CSS, and JavaScript. The user plays against the computer, and the game keeps track of the scores. 

## Features
- User can choose between "Rock," "Paper," or "Scissors" to play against the computer.
- The game generates a random choice for the computer.
- The game determines the result (win, lose, or draw) based on the user's and computer's choices.
- Scores are tracked for both the user and the computer.
- Messages are displayed to inform the user of the game outcome (win, lose, or draw).

## How to Play
1. The user clicks one of the three buttons: "Rock", "Paper", or "Scissors".
2. The game randomly generates the computer's choice.
3. The result of the game (win, lose, or draw) is displayed, and the score is updated accordingly.

## Code Explanation

### JavaScript Code

- **Variables**:
  - `userScore` and `compScore`: Keep track of the user's and computer's scores.
  - `choices`: A collection of elements representing the game choices ("Rock," "Paper," "Scissors").
  - `msg`: The element used to display game result messages.
  - `userScorePara` and `compScorePara`: Display the scores for the user and the computer.

- **Functions**:
  - `genCompChoice`: Generates a random choice for the computer by selecting from "rock," "paper," or "scissors."
  - `drawGame`: Displays a message and style when the game is a draw.
  - `showWinner`: Updates the score and displays a message when either the user or the computer wins.
  - `playGame`: Compares the user's choice to the computer's choice and determines whether the user won, lost, or if it was a draw.
  
- **Event Listeners**:
  - Each choice (rock, paper, or scissors) has a click event listener that triggers the game logic.

## How to Run

1. Clone or download this repository.
2. Open the index.html file in a web browser.
3. Play the game by clicking on your desired choice (Rock, Paper, or Scissors).

## Future Improvements

1. Add sound effects when the user wins or loses.
2. Add animations for the choices.
3. Add a reset button to restart the game.

## License

- This project is licensed under the MIT License.