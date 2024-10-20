## Quiz Application

This project is a simple **Quiz Application** built using HTML, CSS, and JavaScript. The application presents multiple-choice questions to the user, tracks their score, and allows them to navigate through the quiz. The quiz includes functionality for selecting answers, showing feedback (correct/incorrect), and keeping track of the score.

### Features
- **Start the Quiz**: The user can start the quiz by clicking the "Start" button.
- **Multiple-Choice Questions**: Each question has multiple answer options, and only one of them is correct.
- **Answer Feedback**: After selecting an answer, the app provides feedback by highlighting the correct and incorrect answers.
- **Next Question**: After answering, the user can proceed to the next question.
- **Score Tracking**: The user’s score is displayed and updated after each correct answer.
- **Restart Option**: At the end of the quiz, the user can restart the quiz.

---

### File Structure
```
project-directory/
│
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
└── script.js           # JavaScript logic
```

### How to Run the Project

1. **Clone the Repository**:
    ```bash
   [ git clone https://github.com/your-username/quiz-app.git](https://github.com/abdul-moominis-haq/Quiz-application-with-html--css-and-JavaScript.git)
    ```

2. **Open the `index.html` File**:
   Navigate to the project directory and open `index.html` in your browser.

3. **Start the Quiz**:
   Click the "Start" button to begin the quiz.

---

### Code Explanation

- **HTML (`index.html`)**:
    - Defines the structure of the quiz.
    - Contains buttons for starting the quiz, answering questions, and proceeding to the next question.
  
- **CSS (`style.css`)**:
    - Styles the buttons, layout, and provides visual feedback for correct/incorrect answers.
  
- **JavaScript (`script.js`)**:
    - Handles the quiz logic:
        - **startGame()**: Initializes the game, shuffles the questions, and sets up the first question.
        - **setNextQuestion()**: Displays the next question.
        - **showQuestion()**: Dynamically generates the question and answer buttons.
        - **selectAnswer()**: Evaluates the user's answer and updates the score.
        - **setStatusClass()**: Provides feedback on correct and incorrect answers by changing the background color.

---

### Key JavaScript Functions

- **startGame()**: 
  - Starts the quiz, hides the start button, and displays the first question.
  
- **setNextQuestion()**: 
  - Resets the state for the next question and shows the next question.
  
- **showQuestion()**: 
  - Dynamically creates buttons for each answer and adds event listeners to handle answer selection.

- **selectAnswer()**: 
  - Checks if the selected answer is correct, updates the score, and highlights the correct/incorrect answers.

- **resetState()**: 
  - Clears the previous question and resets button styles for the next question.

---

### Future Enhancements

- **Add a Timer**: Implement a timer to challenge the user to answer questions within a certain time limit.
- **Randomized Questions**: Load questions from an external source or API for a wider range of quiz questions.
- **Leaderboard**: Track and display high scores for the user.

---

### Credits

- Developed by ABDUL-MOOMIN IS-HAQ.
- Inspired by various JavaScript quiz applications.

---

### License

This project is licensed under the MIT License.
