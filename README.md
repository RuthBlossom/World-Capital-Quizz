
# Express.js Quiz Application

## Description
This is a simple quiz application built using Node.js with Express.js and PostgreSQL. The application quizzes users on world capitals, randomly selecting questions from a database and tracking their score.

![world quizz](https://github.com/user-attachments/assets/8c097147-0ea6-40b5-8e22-1e05f204a5ac)
![world quizz 2](https://github.com/user-attachments/assets/29c4cf26-7984-453e-907a-d5984d819b4b)


## Features
- **Random Quiz Questions:** Questions are randomly selected from a PostgreSQL database (`world` schema, `capitals` table).
- **Score Tracking:** Tracks the user's total score based on correct answers.
- **User Interaction:** Allows users to submit answers and see immediate feedback on correctness.
- **Dynamic Content:** Uses EJS (Embedded JavaScript templates) for rendering dynamic content on the client side.

## Technologies Used
- **Node.js:** Backend JavaScript runtime environment.
- **Express.js:** Web framework for Node.js.
- **PostgreSQL:** Database management system.
- **Body-parser:** Middleware for handling form data.
- **EJS:** Templating engine for rendering HTML with JavaScript.

## Installation
1. Clone this repository to your local machine.
   
2. Navigate into the project directory.
   ```bash
   cd express-quiz-app
   ```
3. Install dependencies.
   ```bash
   npm install
   ```
4. Set up your PostgreSQL database:
   - Ensure PostgreSQL is installed and running.
   - Create a database named `world` (or use an existing one).
   - Create a table named `capitals` with columns for quiz questions and answers.

5. Configure the database connection in `app.js`:
   - Modify the `db` variable to match your PostgreSQL configuration (`user`, `host`, `database`, `password`, `port`).

6. Start the application.
   ```bash
   npm start
   ```
7. Open your web browser and go to `http://localhost:3000` to view the application.

## Usage
- Navigate to the homepage (`/`) to start the quiz.
- Answer each question by typing the capital city name and submitting the form.
- See immediate feedback on whether your answer was correct.
- Keep track of your total score as you progress through the quiz.

