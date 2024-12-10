# techQuize
Description

This repository contains a Tech Quiz application designed to help aspiring developers test their technical knowledge and improve their skills. The application is built using the MERN stack (MongoDB, Express.js, React, and Node.js). Users can take a quiz with ten random questions.

This project has been enhanced with Cypress for both component and end-to-end (E2E) testing to ensure a seamless user experience and robust functionality.

Features

User Stories

As an aspiring developer:
I want to take a tech quiz so that I can test my knowledge and improve my skills.
Acceptance Criteria
Starting the Quiz:

When the user clicks the "Start" button, the quiz begins, and a question is displayed.
Answering Questions:

When a question is answered, the user is presented with the next question.
Quiz Completion:

When all questions are answered, the quiz ends, and the final score is displayed.
Restarting the Quiz:

After the quiz is over, the user can restart the quiz by clicking a "Start New Quiz" button.
Tech Quiz Test Suite
This project includes a Cypress test suite for validating both components and end-to-end workflows.


Install Cypress as a development dependency.

Configure Cypress for:

Component Testing: Focused on individual UI components, ensuring each works as expected in isolation.
End-to-End Testing: Validates the entire quiz workflow from start to finish. https://share.vidyard.com/watch/knaTwQinvRC5ymXMgGr2bB
Installation
Clone the repository: https://github.com/nadiahashe/techQuize

git clone 
cd tech-quiz-app
Install dependencies:

npm install
Set up Cypress:

npm install cypress --save-dev
Run the development server:

npm start
npm run cypress
Component Testing

Run all tests directly in the Cypress interface.
Tech Stack
Frontend: React
Backend: Node.js, Express.js
Database: MongoDB
Testing: Cypress
How to Contribute
Fork the repository.
