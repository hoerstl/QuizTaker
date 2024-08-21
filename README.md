# QuizTaker

This project implements only a single key functionality. Take a screenshot of a quiz page, feed it to gemini, and return it.

This project is intended to be used with quizzes that are trivial. e.g. "Which of these words are nouns?", "Which of these images contain bicycles", etc.


# Get Started
The instructions are simple:
1. Simply add your Gemini API key to a `.env` file.
2. Call the `init()` function from the module.
2. Call the `answerVisableQuizQuestion()` function in the `main.py` file.
