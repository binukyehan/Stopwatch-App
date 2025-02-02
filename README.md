# Stopwatch Application

A simple stopwatch application built using React that allows users to start, stop, and reset the timer with millisecond precision.

## Features

- Start, stop, and reset functionality
- Displays elapsed time in MM\:SS\:MS format
- Uses `useState`, `useEffect`, and `useRef` for efficient time tracking

## Technologies Used

- React.js
- JavaScript (ES6+)
- HTML/CSS

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/stopwatch-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd stopwatch-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the application:
   ```sh
   npm start
   ```

## Usage

- Click the **Start** button to begin the stopwatch.
- Click the **Stop** button to pause the timer.
- Click the **Reset** button to reset the time to 00:00:00.

## Code Overview

- **useState** is used to manage the running state and elapsed time.
- **useRef** stores references to prevent unnecessary re-renders.
- **useEffect** manages the interval for updating elapsed time dynamically.

## License

This project is licensed under the MIT License.

