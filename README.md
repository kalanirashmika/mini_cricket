# Mini Cricket App

## Description

Mini Cricket is a simple Flutter mobile application that simulates a short cricket batting game. The player gets 6 balls and scores random runs on each ball. This project was created as a university Computer Science coursework assignment to practice basic Flutter and Dart skills.

## Features

- Shows cricket bat and ball images
- Displays total runs and remaining balls
- Generates a random score when the Bat button is pressed
- Updates the score message after each ball
- Shows a Restart button when all 6 balls are finished
- Resets the game back to the starting state

## Technologies Used

- Flutter
- Dart
- Android

## How to Run

1. Make sure Flutter is installed on your computer.
2. Open a terminal in the project folder.
3. Run the following commands:

```bash
flutter pub get
flutter run
```

4. Choose an Android emulator or a connected Android phone.

## Game Logic

- The game starts with **Runs = 0** and **Balls = 6**.
- When the player presses **Bat**, the app randomly selects one of these scores: 0, 1, 2, 3, 4, or 6.
- The selected score is added to the total runs.
- The number of balls left is reduced by 1.
- A message is shown based on the result:
  - 0 → "No Runs"
  - 1 → "1 Run"
  - any other value → for example "3 Runs" or "6 Runs"
- When balls reach 0, the Bat button is replaced by a red **Restart** button.
- Pressing Restart sets Runs back to 0, Balls back to 6, and clears the message.

## Screenshots

Add screenshots of the app here after running it on your phone or emulator.

## Project Structure

```text
mini_cricket/
├── android/
├── ios/
├── lib/
│   └── main.dart
├── assets/
│   └── images/
│       ├── bat.png
│       └── ball.png
├── pubspec.yaml
└── README.md
```

## Author

University Computer Science student
