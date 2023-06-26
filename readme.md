# React Stopwatch App

This is a React.js stopwatch app that allows users to create and manage multiple stopwatches. Users can perform various operations such as start, stop, lap, and pause on each stopwatch.

## Features

- Create and manage multiple stopwatches
- Start a stopwatch
- Stop a stopwatch
- Record lap times
- Pause and resume a stopwatch

## Installation

1. Clone the repository:

    git clone https://github.com/donfranklie/multiple-stopwatches.git

2. Navigate to the project directory:

    cd stopwatch-app


3. Install the dependencies:

    npm install
    npm install react-icons


## Usage

1. Start the development server:

    npm run start

2. Open your web browser and visit `http://localhost:3000` to access the stopwatch app.

## Implementation Details

### Use of useEffect

The stopwatch app utilizes the `useEffect` hook to repeatedly run a function that updates the stopwatch state autonomously. This ensures that the stopwatch is always displaying the accurate elapsed time.

### Object Manipulation

Object manipulation is performed while updating the stopwatch state. This allows for easy tracking of each stopwatch's status, lap times, and other relevant information.

### Stopwatch Operations

The following operations can be performed on each stopwatch:

- **Start**: Begin the stopwatch and start tracking time.
- **Stop**: Stop the stopwatch and record the total elapsed time.
- **Lap**: Record the current lap time without stopping the stopwatch.
- **Pause**: Pause the stopwatch without resetting the elapsed time. The stopwatch can be resumed from the paused state.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
