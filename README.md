Text Editor
Overview:

This project is a Text Editor implemented in C++ that allows users to perform various text editing operations such as writing, deleting, moving the cursor, searching, replacing words, and more. It also supports undo and redo functionalities.
The program provides options to either create a new file or edit an existing one, and it uses a linked list structure to represent and manipulate the text.

Features:

Text Editing: Write, delete, copy, cut, paste, and replace text.
Cursor Movement: Navigate through the text using cursor control.
Search: Find specific words in the text.
Undo/Redo: Save operation states and revert or redo changes.
File Operations: Create new files, edit existing files, and save changes.

How to Run:

Prerequisites:
C++ compiler (e.g., GCC or MSVC).
Windows system (due to usage of <Windows.h> and console attributes).
Optionally, a terminal emulator that supports colored output.
Steps:
Clone the repository or copy the source code into your local machine.
Compile the program using the following command:
g++ -o Text_editor main.cpp

File Structure:

main.cpp: The main source file containing the implementation of the text editor.
README.md: Documentation for the program.

Functionalities:

1. Create New File
Prompts the user to enter a filename.
Starts with a blank file and allows the user to input text.
2. Edit Existing File
Opens a specified file.
Loads the file content into the editor.
3. Text Operations
Write Text: Add new text.
Delete Word: Delete the word under the cursor.
Move Cursor: Navigate through the text.
Delete Specific Text: Remove a sequence of words.
Search Word: Highlight specific occurrences of a word.
Cut and Copy: Copy or cut a range of words.
Paste: Paste the most recently copied or cut text.
Replace: Replace a word with another.
4. Undo/Redo
Save and restore the state of the text editor.
5. Save Changes
Option to save changes before exiting.

Limitations:

The program is designed for Windows systems due to its usage of Windows-specific libraries.
Large text files may cause performance issues since all operations are performed in memory.

Acknowledgements:

This project was developed by:
Nivithasri A

License:
This project is licensed under the MIT License. You are free to use, modify, and distribute the code with proper attribution.
