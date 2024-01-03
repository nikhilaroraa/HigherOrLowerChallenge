# High-Low Card Challenge Game
The "High-Low Card Challenge" is a Python-based card game that engages players in predicting whether the next card drawn will be higher or lower than the previous one. The game incorporates random card generation, betting mechanics, and win/lose conditions. The game utilizes several functions for different aspects:

- getCardValue(): This function generates a random card value between 2 and 14, representing card numbers.

- getCardStr(cardValue): Converts a card number into a string representation, considering special cases for numbers 10-14.

- getHLGuess(): Prompts the user to input whether they expect the next card to be "HIGH" or "LOW."

- getBetAmount(maximum): Takes user input for the bet amount, ensuring it is within a specified range.

- playerGuessCorrect(card1, card2, betType): Determines if the player's guess (HIGH/LOW) is correct based on the comparison of two card values.

The main game loop runs for 10 rounds, allowing the player to bet on the outcome of each draw. The game begins with 100 points, and the player aims to reach 500 points within the given rounds. After each round, the player's points and the current round number are displayed. The game concludes with a victory message if the player reaches 500 points, a loss message if they run out of points, or a message indicating the number of rounds won if neither condition is met. The user-friendly interface and simple yet engaging mechanics make the "High-Low Card Challenge" an enjoyable and strategic card game experience.
