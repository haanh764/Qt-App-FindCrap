# Qt-App-FindCrap
<br />
A **Qt Widgets Application** to search, highlight and point the cursor to words requested by user.<br />
Motivated by : C++ GUI Qt Tutorials with Bucky [thenewboston]

The application basically creates a UI. Furthermore, functionalties are implemented for getting the text file and adding push button click events.

UI
------------
 
 * Consists of a Text Edit Area (**QTextEdit**), **QLabels**, **QLineEdits** and **QPushButtons**.
 * Text Edit Area includes the text file which is imported as a **Qt Resource File**.
 <br />
 <br />
 
Functions
------------

There are basically two functions.

 * **getTextFile** :  <br />
          Creates a **QFile** for reading from a file which we need to work with. <br />
          Opens that file, so we can use it. <br />
          Converts the text in the file into a stream and store them in a **QString** variable. <br />
          Closes the file. <br />
          Displays the text on the Text Edit Area of the UI. <br />
          Moves the cursor into a place so that whenever the user searches for the next term, they can see where the words they are looking for.

          
 * **goButton_clicked** :  <br />
          Takes the word user is searching for and store it as a **QString**. <br />
          Finds the next occurence of that word, basically takes the cursor and moves it to the word if it appears in the Text Edit Area.
          
 <br />


Want to try
------------

Creates a **QFile** for reading from a file which we need to work with.
          Opens that file, so we can use it.
          Converts the text in the file into a stream and store them in a **QString** variable.
          Closes the file.
