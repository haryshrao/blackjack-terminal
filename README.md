**Discription:** 
Terminal Blackjack (Python)
A sleek, command-line version of the classic casino game Blackjack, built with Python. This project demonstrates the use of Object-Oriented Programming (OOP), handling game logic, and user input validation.

**🚀 Features**

OOP Design: Modular code structure with Card, Deck, Hand, and Game classes.

Smart Ace Logic: The game automatically adjusts the value of an Ace from 11 to 1 if the player's hand exceeds 21.

Dealer AI: The dealer follows standard casino rules, hitting until their hand reaches at least 17.

Replayability: Choose how many games you want to play in a single session.

**🛠️ How to Play**

*Clone the repository:*
git clone *https://github.com/haryshrao/blackjack-terminal.git*

*Navigate to the folder:*
cd blackjack-terminal

*Run the game:*
python main.py

**🎮 Game Rules**

Goal: Get a hand value as close to 21 as possible without going over.

Card Values: Numbered cards are worth their face value.

Face cards (J, Q, K) are worth 10.

Aces are worth 11 or 1.

Dealer's Turn: The dealer will show one card and keep one hidden until you "Stand." They must hit until they have at least 17.

**📂 Project Structure**

Card: Handles the rank and suit of individual cards.

Deck: Manages the 52-card deck, including shuffling and dealing.

Hand: Calculates scores and manages the cards held by the player/dealer.

Game: Controls the main loop, win conditions, and user interaction.
