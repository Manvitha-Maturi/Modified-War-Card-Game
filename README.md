# Modified-War-Card-Game

Modified War Card Game

A strategic, two-player card game (Human vs Computer) inspired by the classic War game.
This project demonstrates practical use of Stacks and Queues implemented using arrays and linked lists.

📌 Project Overview

The game introduces decision-based gameplay where players can manipulate cards using push and pull actions. Each round is decided by the total value of cards played, adding strategy beyond simple card comparison.

🎯 Features

Custom Queue (Linked List) implementation for player decks

Custom Stack (Array) implementation for side piles

Two gameplay modes:

Play until one player runs out of cards

Play for a fixed number of rounds

Interactive player choices with strategic impact

Automated computer opponent

Comprehensive test cases for validation

🕹️ Game Rules
Cards

Face values range from 1 to 10

Player Actions

Each round, players may:

Push

Move the top card from the deck to the side pile

Draw a new card to play

Pull

Remove one card from the side pile

Play two cards this round

Winning a Round

The player with the higher total card value wins the round

Ties are awarded to the computer

Running Out of Cards

If the deck is empty, players must use cards from their side pile

If both deck and side pile are empty, the player loses

🧱 Data Structures Used
🔁 Deck (Queue – Linked List)

First-In, First-Out (FIFO)

Cards drawn from the front

Won cards added to the rear

Displays number of remaining cards

Players can view both decks at any time

📚 SidePile (Stack – Array)

Last-In, First-Out (LIFO)

Maximum capacity of 5 cards

No peek operation allowed

Only push and pop operations supported

Players can view only their own side pile size

🧪 Testing

Multiple structured test cases included

Test cases are independently designed and executed

Results include pass/fail status and debugging notes

Demonstrates correctness and edge-case handling

🗂️ Project Structure
📦 Modified-War-Game
 ┣ 📜 Deck.h
 ┣ 📜 Deck.cpp
 ┣ 📜 SidePile.h
 ┣ 📜 SidePile.cpp
 ┣ 📜 main.cpp
 ┣ 📄 TestCases.pdf
 ┣ 📄 ProjectReport.pdf
 ┗ 📄 README.md

▶️ How to Compile & Run
Requirements

C++ compiler (g++ recommended)

Compile
g++ main.cpp Deck.cpp SidePile.cpp -o war_game

Run
./war_game

🧠 Key Concepts Demonstrated

Linked List–based Queue

Array-based Stack

Object-Oriented Programming

Game state management

Defensive programming

Manual testing and debugging

🚀 Future Enhancements

Smarter AI decision-making

Shuffle functionality for decks

Save/load game state

GUI or web-based interface
