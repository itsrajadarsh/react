# Investment Calculator

![Tic-Tac-Toe Screenshot](./public/demo.png)

A simple investment calculator built with React. This application allows users to input their initial investment, annual investment, expected return rate, and duration to calculate the final investment outcome over time.

## Features

- **User Input:** Allows users to input initial investment, annual contributions, expected return rate, and investment duration.
- **Validation:** Ensures that the duration is at least 1 year.
- **Results Calculation:** Calculates and displays the investment growth based on user input.

## Components

- **`App.js`**: The main component that manages state and handles user input.
- **`Header.jsx`**: Displays the header of the application.
- **`UserInput.jsx`**: Renders the form for user input and handles changes.
- **`Results.jsx`**: Displays the calculated results based on the user's input.

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/itsrajadarsh/react.git
   ```

2. **Navigate into the project directory:**

   ```bash
   cd investmentCalculator
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open `http://localhost:5173/` in your browser to view the application.

## Code Overview

- **`App.js`**: Contains the main logic for managing user input and validating the duration.
- **`components/Header.jsx`**: Provides a simple header for the application.
- **`components/UserInput.jsx`**: A form for collecting investment details from the user.
- **`components/Results.jsx`**: Displays the investment outcome based on the input values.

## Usage

1. Enter your initial investment amount.
2. Input your expected annual contributions.
3. Specify the expected return rate (in percentage).
4. Set the investment duration (in years).
5. The results will display the projected investment growth over the selected period.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.


## Contact

For any questions or feedback, feel free to reach out via [adarshraj6113@gmail.com] or open an issue on the [GitHub repository](https://github.com/itsrajadarsh/react/tree/main/investmentCalculator).