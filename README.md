# React Quiz

React Quiz is an interactive quiz app built with React. It features a sleek design, 15 questions, a timer, and a scoring system up to 280 points. The app tracks the best score and is a great practice project for state management, hooks, and other React concepts.

## Features

- **15-Question Quiz**: Test your knowledge with a series of questions.
- **Timer**: Keep track of time while taking the quiz.
- **Scoring System**: Earn up to 280 points and track the best score.
- **State Management**: Demonstrates React state management and hooks.

## Getting Started

To run the application locally, follow these steps:

### 1. Clone the repository
git clone https://github.com/your-username/react-quiz.git
### 2. Install dependencies
Navigate to the project folder and run the following command to install the necessary packages:
npm install

### 3. Start the local server
Before running the app, you need to start a local server to serve the quiz questions data. Use the following command to start the server:
npm run server

This will start the server on http://localhost:8000 and watch the data/questions.json file for changes.

### 4. Run the app
In a separate terminal, start the React app with:

npm start
This will start the app on http://localhost:3000 and allow you to interact with the quiz.

### 5. Build for production
To create a production build, run:

npm run build
The build files will be outputted to the /build directory.

### 6. Run tests
To run tests, use:

npm test

### 8. Eject (Optional)
If you need to customize the configuration, you can eject the app with:

npm run eject

### Project Structure
src/: Contains all the source code including components, hooks, and utilities.
public/: Contains static assets and the HTML template.
data/questions.json: JSON file with quiz questions served by the local server.
