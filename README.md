# online-quiz-examination
 1. Login Class:
 ● Thisclass represents the initial login window for the quiz.
 ● Itcontains a JTextField for the user to enter their name.
 ● TwoJButtons, one for displaying rules (rules) and another for going back (back).
 ● TheactionPerformed method handles button clicks. If the "Rules" button is clicked, it
 gets the name entered by the user and opens a new window for quiz rules (Rules class). If
 the "Back" button is clicked, it closes the login window.
 
 2. Rules Class:
  ● Thisclass displays the rules of the quiz.
 ● Ittakes the user's name as a parameter, displays a welcome message, and provides some
 rules for the quiz.
 ● TwoJButtons: "Start" to begin the quiz and "Back" to return to the login screen.
 ● TheactionPerformed method handles button clicks. If the "Start" button is clicked, it
 opens a new window for the quiz (Quiz class). If the "Back" button is clicked, it returns
 to the login window.

 3. Score Class:
 ● Thisclass is responsible for displaying the user's score after completing the quiz.
 ● Ittakes the user's name and score as parameters.
 ● Displays a thank you message and the user's score.
 ● Provides a "Try Again" button to start a new quiz.
 ● TheactionPerformed method handles the "Try Again" button click, closing the score
 window and returning to the login window.

 4. Quiz Class:
 ● Thisclass represents the main quiz window.
 ● Itincludes an array of questions, answers, and user answers, along with various Swing
 components for question display and user interaction.
 ● TheactionPerformed method handles button clicks for "Next," "Clue" (lifeline),
 "Submit," and "Back" buttons.
 ● Atimeris implemented to limit the time for each question.
 ● Thepaint method is used to display the timer countdown and handle automatic
 progression to the next question or submission when time runs out.
➔ Theapplication's flow is as follows: Rules-> Quiz-> Score-> Login.
 ➔ Aparticular window or feature of the quiz application is represented by each
 class.
 ➔ Thequiz's graphical user interface is made possible by the usage of Swing
 components (JFrame, JLabel, JButton, etc.).
 ➔ Thearrays including questions, answers, and user replies are used to determine
 the score, which is contingent on the accuracy of the answers.
 ➔ Inorder to give a hint, lifeline functionality disables some response choices.
 ➔ Timers are used to set a time limit for each question, and when the timer hits zero,
 the program moves on to the next one automatically.




