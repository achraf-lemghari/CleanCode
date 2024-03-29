# Clean Code - Masterclass

Welcome !  
This repository is a series of C++ projects, submitted in order to respond to the assignments of a Masterclass **Clean Code** leaded by [Jules Fouchy](https://github.com/JulesFouchy) & [Guillaume Haerinck](https://github.com/guillaume-haerinck) .

## TP1
- [x] Install a VScode and the necessary packages (for MacOS) .
- [x] Download the simple_code provided and test it .result : -hello world- apears after compiling .
- [x] Understanding Git .
- [x] Create a repository .

## TP2
- [x] Install GitKraken .
- [x] Making the first commit using pulling .
- [x] Read and understand the two lessons **Naming** and **Stack vs Heap** .

## TP3
- [x] Making everthing ready for TPs exercises (TP template,Git repo...) .
- [x] Understand writing with **Markdown** in order to write a clear Readme that i will be using to follow my progress and share it with my tutors.
- [x] Start working on **Guess the number** assignment
- [x] Doing the minimal asked with a code that worked 

## TP4
- [x] Added the option to the player for choosing how hard the game they want to play . leaving the possibility to upgrade the game so the player pass into next level with a higher range where potentialy the "number to guess" exists . example : level 1 : 0-10 || level 2 : 0-50 || level 3 : 0-100 .for the moment the player choose from the menu . the upgrade should include the automatisation of this process starting from the lowest level to the upper .
- [x] Adding input control : An input check is necessary  in order to ensure that the player will type valid data . and range control is a reminder to the player which set of number they should be choosing from .
- [x] Choosing wisely variables and functions name and using comments to ensure clarity for future me and other programmers .
- [x] Finishing **Guess the number** assignment .  
 ![Screenshot Guess the number assignment](https://user-images.githubusercontent.com/25162712/156742995-016ef2af-e80e-4c38-a260-579857b48845.png)
- [x] Start working on **assignment Hangman**  .  

## TP5
- [x] Reading Level 2 courses :   
  * Make it work, then make it good :what a good advice , so many times i find myself overwhelmed and unable to solve a programming assignement ,that is because i limit my thinking to find a solutions that fits to what the corrector expects from me , which make it harder since it is less complicated to improve something that already exists and make it better than redo it from scratch .
   *Structs, Free functions and classes :it is simple (it seeems to be for the moment) Use Free Functions like u used to do before u knew about OOP (create plenty of them and call them in main , use them for tests etc ...) , you need to handle a groupe of data ? is this data Public ? use structs , it is not use Classes 

## Rest of TPs
- [x] Finishing **Hangman** assignment .
- [x] Finish reading Level 2 courses :
 * Enums:enum and enum class, a good solution to use with 'switch' to avoid using meaningless integers to indicate an option. I wanted to use it with the switch I used to create Menu and game hardness choices but I think it's easier to control a user input when they have to enter a single number to make a choice than entering a string of characters .
- [x] Fixing a bug after getting Jules' feedback : I used a global variable that is supposed to generate a random name from a list (Guess the number assignment) . problem : same word will be associated with the variable until we close the console. solution : moved the variables inside the function that give access to play the game .
- [x] start working on Noughts and Crosses :
 * First difficulty :  
 
- [x] Finishing **Hangman** assignment .
- [x] Finish reading Level 2 courses :
 * Enums:enum and enum class, a good solution to use with 'switch' to avoid using meaningless integers to indicate an option. I wanted to use it with the switch I used to create Menu and game hardness choices but I think it's easier to control a user input when they have to enter a single number to make a choice than entering a string of characters .
- [x] Fixing a bug after getting Jules' feedback : I used a global variable that is supposed to generate a random name from a list (Guess the number assignment) . problem : same word will be associated with the variable until we close the console. solution : moved the variables inside the function that give access to play the game .
- [x] start working on Noughts and Crosses :
 * First difficulty (Adding the P6 library to the project) : CMake and Git submodules lessons were a good help to understand how to do so . The problem was that I have a macbook M1 with an integrated graphic card . But fortunately Jules ( the designer of the p6 ) has already thought about that . solution was using the “render-directly-to-screen” Branch.
- [x] Reading the rest of Lessons and trying to apply what I have learned to write a clean code for the math project : https://github.com/Hraf-C/IMAC-WORRIOR.git



