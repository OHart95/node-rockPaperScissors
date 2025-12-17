# 🪨📄✂️ Node.js Rock Paper Scissors

A sleek, command-line version of the classic Rock Paper Scissors game. This project demonstrates fundamental JavaScript logic, including user input validation, random computer selection, and an interactive scoring system.

## 🧠 Technical Highlights

* **Asynchronous Input Handling:** Uses the Node.js `readline` module wrapped in a custom `Promise` helper to allow for clean `async/await` syntax.
* **Recursive Game Loop:** Implements an asynchronous recursive structure to allow for seamless round restarts and "play again" functionality.
* **Input Sanitization:** Features robust input validation to handle case-sensitivity and invalid choices (including a fun easter egg for Big Bang Theory fans).
* **State Management:** Tracks and displays persistent scores for both the player and the computer across multiple rounds.

## 🛠️ Tech Stack
* **Runtime:** Node.js
* **Modules:** `readline` (Standard Library)

## 🚀 How to Run

1. **Clone the repository:**
```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
```
2. **Navigate to the project folder:**
```bash
cd rock-paper-scissors
```
3. Start the game:
```bash
node app.js
```

## 🎮 How to Play
Enter your choice: rock, paper, or scissors.

The computer will randomly generate its own move.

The winner is determined based on standard rules:

* Rock beats Scissors
* Paper beats Rock
* Scissors beats Paper

View your running score and decide if you want to play another round!

## 📝 Key Code Snippets
The Winner Logic: The game uses conditional logic to evaluate the player's input against the Math.random() generated computer choice.

The "Sheldon" Validation:

```JavaScript

if (playerChoice === 'spock') {
    console.log('Nice try Sheldon');
    return playGame(); 
}
```
## 📈 Future Roadmap
Lizard Spock Expansion: Fully implement the "Rock Paper Scissors Lizard Spock" rules.

Best of Three: Add a game mode that declares a final winner after three rounds.

Sound Effects: Use terminal beeps or external libraries to add audio feedback for wins and losses.
