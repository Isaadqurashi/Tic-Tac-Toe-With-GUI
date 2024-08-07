# Second semester Project with GUI  
by https://github.com/umer6016
and https://github.com/Isaadqurashi

**Tic Tac Toe with GUI**
=====================

**Overview**
-----------

This repository contains the source code for a Tic Tac Toe game implemented with a graphical user interface (GUI) using the Windows API. The game allows two players to play against each other, with the option to start a new game at any time.


**Features**
-----------

*   A 3x3 game board with interactive cells
  
    ![Screenshot 2024-05-17 190300](https://github.com/user-attachments/assets/033d629a-5087-4d63-b66e-deae0a332dc5)
    
*   Players can make moves by clicking on empty cells
  
    ![Screenshot 2024-05-17 190347](https://github.com/user-attachments/assets/429176fe-b204-4643-b4d1-d5662b1c09d2)
    
*   The game checks for a winner after each move and displays a message box announcing the winner or a draw
  
    ![Screenshot 2024-05-17 190454](https://github.com/user-attachments/assets/faf3be1a-109c-4b46-80f2-95a77e9f982a)
    
    ![Screenshot 2024-05-17 190535](https://github.com/user-attachments/assets/80b97eb9-a86e-456d-a1eb-b0ceb70c964b)
    
*   Players can start a new game at any time using the "New Game" menu option
  
    ![Screenshot 2024-05-17 190603](https://github.com/user-attachments/assets/07fb64da-c0ba-4cf4-9fd3-32e573da02f9)
    
*   The game window is resizable, but it cannot be minimized to a size that would hide the game board

**Technical Details**
--------------------

*   The game is implemented in C++ using the Windows API for creating the GUI
*   The game logic is handled in the `WndProc` function, which processes messages for the main window
*   The game state is stored in global variables, including the game board, player turn, and winner
*   The game uses icons and brushes to display player symbols and highlight winning cells

**Building and Running**
----------------------

To build and run the game, you will need to compile the provided C++ code using a Windows-compatible compiler, such as Visual Studio. The game requires the Windows API headers and libraries to be installed on your system.

**License**
---------

This software is provided under the MIT License. See the https://github.com/Isaadqurashi/Tic-Tac-Toe-With-GUI?tab=MIT-1-ov-file# file for details.

**Contributing**
------------

Contributions to the game are welcome. If you have any suggestions or bug fixes, please open an issue or submit a pull request.

**Acknowledgments**
----------------

This game was created using the Windows API and various online resources for learning GUI programming in C++.

