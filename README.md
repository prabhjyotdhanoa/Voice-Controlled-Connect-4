# Voice-Controlled-Connect-4
A Connect 4 program that can be controlled with both the keyboard and your voice with additional game mechanics added
This project was done for the hackathon TurnerHacks

# Inspiration
During the time we thought about this project, we were really attached to the board game Connect 4. As a result, we based our project upon this board game and use it as a means of learning about using voice inputs in case we may want to use it in future projects.

# What it does
Our program runs the Connect 4 board game which can be controlled both by the keyboard and by voice. The game is for 2 players. Aside from regular connect 4 mechanics, you can also pop out the bottom piece in any column. In case you or the program ever makes a mistake, you can also tell it to undo the previous move.

# Controls

Buttons 1-7: Place piece in each appropriate column

Buttons 0: Undo the last move

Buttons "q"-"u": Pop out the bottom piece of the corresponding column. ("q" = 1, "w" = 2, "e" = 3, etc.)

Button "p": Clear the board

Voice Controls

keyword "play #": Places piece in the column number specified

keyword "undo": Undo the last move

keyword "pop #": Pop out the bottom piece of the column specified

keyword "clear": Clears the board

# How we built it
We coded the project in Python, using the PyGraphics module. We used the Google Speech Recognition API to control the voice recognition.

# Challenges we ran into
Since the speech recognition requires a stable internet connection, the program can be slow to respond.

# What we learned
We learned how to use speech recognition and learned how to use dictionaries. This was also our first time learning to organize functions in multiple files to improve overall efficiency.

# What's next for Voice-Controlled Connect 4
We need to find a way to make the inputs run smoother, since there's too much delay when both voice input and key input are enabled at the same time. Another idea would be to have the ability to undo a pop, since at the moment it is only possible to undo a placement.

# Built With
python
pycharm
speech-api
pygraphics

# Link to Devpost (original post)
https://devpost.com/software/voice-controlled-connect-4#updates
