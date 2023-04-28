# quiz-game-in-python
This is a simple quiz game that tests the player's knowledge on a set of questions and answers. The game is built using three modules:

question_model.py: This module contains the Question class, which represents a single question and its correct answer.

data.py: This module contains the data for the quiz, which is a list of dictionaries, each containing a question and its corresponding answer.

quiz_brain.py: This module contains the QuizBrain class, which manages the quiz and keeps track of the current question, the player's score, and whether there are more questions to ask.

ui.py: This module contains the QuizInterface class, which uses the tkinter module to create a graphical user interface for the quiz.

The main logic of the program is contained in the question_bank list comprehension, which iterates over the question_data list and creates a new Question object for each question-answer pair. These objects are then added to the question_bank list, which is passed to the QuizBrain constructor to create a new quiz object.

The QuizInterface object is then created using the quiz object, which displays the questions and answer choices to the player and waits for their response. The QuizBrain object handles the player's response and updates their score accordingly.

Once the quiz is complete, the program prints the player's final score.
