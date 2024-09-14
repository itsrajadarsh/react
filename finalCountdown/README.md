# The Almost Final Countdown

A fun and interactive timer challenge game built with React! In this game, you try to stop the timer as close to zero as possible, testing your reflexes and precision through varying difficulty levels.

![Game Screenshot](/src/assets/demo.png)

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Components](#components)
- [How to Run the Project](#how-to-run-the-project)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Contact](#contact)

## Demo

![Game Screenshot](screenshot.png)  
_Try to stop the timer as close to zero as possible!_

## Features

- **Welcome Screen**: Set your name or remain as the 'unknown entity.'
- **Four Difficulty Levels**:
  - **Easy**: 1-second timer.
  - **Not Easy**: 5-second timer.
  - **Getting Tough**: 10-second timer.
  - **Pros Only**: 15-second timer.
- **Interactive Timer**: Start and stop the timer with a button click.
- **Score Calculation**: Displays your score based on how close you stop the timer to zero.
- **Modal Feedback**: Shows results in a modal dialog with the target time and remaining time.
- **Reset Feature**: Allows you to reset and try again.

## Components

### 1. `Player.jsx`

- Allows the player to set their name.
- Displays a welcome message, either addressing the entered name or "unknown entity" by default.

### 2. `ResultModal.jsx`

- Displays the result once the timer challenge is stopped.
- Shows whether the player won or lost and provides feedback on their performance.
- Uses React Portals to render the modal outside the main component tree.

### 3. `TimerChallenge.jsx`

- Handles the timer challenge logic.
- Starts and stops the timer based on user input.
- Calculates the remaining time and updates the state accordingly.
- Communicates with the `ResultModal` to show the results.

### 4. `App.jsx`

- Combines all components.
- Provides different timer challenges with increasing difficulty levels.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/itsrajadarsh/react.git
   ```
2. Navigate to the project directory:
   ```bash
   cd finalCountdown
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and go to `http://localhost:5173/` to start the game.

## Technologies Used

- **React.js**: Frontend framework used for building the UI.
- **JavaScript**: For logic and interactivity.
- **CSS**: For styling the components.
- **HTML**: Basic structure for the components.

## Future Enhancements

- **Leaderboard**: Track and display the best scores.
- **More Difficulty Levels**: Add more levels for a more challenging experience.
- **Sound Effects**: Add sounds to enhance user experience.
- **Animations**: Improve visual feedback with animations.
- **Multiplayer Mode**: Allow multiple players to compete in the same session.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, feel free to fork the repository and create a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes.
4. Commit the changes:
   ```bash
   git commit -m "Add new feature"
   ```
5. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
6. Create a pull request.

## Contact

For any inquiries or feedback, feel free to reach out:

- **Name**: Adarsh Raj
- **Email**: adarshraj6113@gmail.com
- **GitHub**: https://github.com/itsrajadarsh
