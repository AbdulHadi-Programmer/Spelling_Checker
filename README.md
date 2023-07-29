# Spelling_Checker
# Simple Spelling Correction GUI

Introduction:
The provided Python code demonstrates a simple Graphical User Interface (GUI) application for spelling correction using the TextBlob library. The application allows users to input words with spelling errors, and upon clicking the "Done" button, it corrects the misspelled words and displays the corrected version on the GUI.

Code Explanation:

1) Imports: The code begins with the necessary imports. It imports TextBlob from the TextBlob library for spelling correction and Tk from tkinter for creating the GUI.

2) correct_spelling() Function: This function is called when the "Done" button is clicked. It reads the input text from the first Entry widget (enter1), creates a TextBlob object with the input data, performs spelling correction using the correct() method of TextBlob, and displays the corrected text in the second Entry widget (enter2).

3) main_window() Function: This function sets up the main window for the GUI application. It creates a Tk object named win, sets its size, background color, and title. It then proceeds to create and arrange various widgets in the main window.

4) GUI Widgets:
Label: Two labels are created to display the purpose of each input field. One label indicates "Incorrect Spelling," and the other indicates "Correct Spelling."
Entry: Two Entry widgets (enter1 and enter2) are provided for entering the incorrect and corrected spellings, respectively.
Button: A "Done" button is included, which triggers the correct_spelling() function upon clicking.

5) Start GUI Main Loop: The main loop (mainloop()) is called to start the GUI event loop, allowing the application to respond to user interactions and events.

Conclusion:
The code showcases a basic spelling correction GUI application that utilizes the TextBlob library to provide simple spelling corrections. Users can input words with spelling errors, and the application promptly suggests the corrected versions. Although the code is straightforward, it provides an excellent starting point for building more sophisticated spelling correction applications or incorporating additional NLP features using TextBlob and tkinter.
