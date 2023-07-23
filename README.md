# Quiz App
## This is a simple Quiz App created using Python and the Tkinter library. The app presents a series of True/False questions to the user, and the user can answer each question by clicking the corresponding buttons. The app provides instant feedback on the correctness of the user's response and displays the final score at the end of the quiz.

## How to Run the App
Clone the repository to your local machine using the following command:

`git clone https://github.com/Alisadaintanvir/quiz-app.git`
Navigate to the project directory:
`cd quiz-app`
Make sure you have Python and Tkinter installed on your machine.

Run the main.py file to start the Quiz App:
`python main.py`

## App Structure
The Quiz App is divided into several files to keep the code organized:

question_model.py: Defines the Question class, which represents a single question with its text and correct answer.

data.py: Contains a list of dictionaries, each representing a question with its text and correct answer.

quiz_brain.py: Implements the QuizBrain class, which manages the quiz logic, keeps track of the current question number and score, and provides methods to check the user's answers.

ui.py: Creates the graphical user interface (GUI) using the Tkinter library. It displays the quiz questions and buttons for user interaction.

images: Contains image files for the True and False buttons.

## App Functionality
The app loads the questions from the data.py file and creates a list of Question objects.

The QuizBrain class is responsible for managing the quiz and handling user interactions.

The QuizInterface class creates the GUI using Tkinter and displays the questions one by one.

The user can click the True or False buttons to answer each question.

After answering a question, the app provides instant feedback by changing the canvas background to green for a correct answer and red for an incorrect answer.

The app updates the score label after each question.

When all questions are answered, the app displays a message indicating the end of the quiz and disables the True and False buttons.

## Dependencies
The app requires the following Python libraries:

tkinter: To create the GUI for the Quiz App.
html: To unescape string

## Contributions
Contributions to the Quiz App are welcome. If you find any issues or want to add new features, please feel free to open a pull request.

## License
The Quiz App is open-source and available under the MIT License. Feel free to use and modify the code as per the terms of the license.
