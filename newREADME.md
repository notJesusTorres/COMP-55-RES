# COMP-55-RES
Section 1:
The feature that will be implemented for the resurrection of the COMP 55 project will allow
the game to have interative menu options. 

Previously, the option for music, sound fx, and difficulty buttons worked by allowing you to
switch between on and off, but they did not work as intded. As they did not allow for these values
to be updated.

In order to pass these values of to the appropriate methods, a file will be written to hold the
values of the selected option of off or on. In the case of difficulty it will be easy, medium, and hard.
Then, the file will be read from the methods containing the variables for sound and difficulty. 
Based of the selection, it will assigned those values to the variables and result in the selected option

Section 2: 
Borrowing implemented logic within the program. Since the logic for all the settings work
similiarly, the pseudo will follow closely to each other.

/* This function writes into a file to update the settings in the game. 
    it will then be read and input to off or on in the appropriate method.
    Since it will be going to different classes, it will react according to that class.
*/

// Set a default value (on) to the variable 
// If option one is on
//    change option 2 as off
//    write and overwrite result into file
// If option two is on
//    change option 1 as off
//    write and overwrite result into file

For the case of three options such as the difficulty

// Set a default value (on) to the variable 
// If option one is on`
//    change option 2 as off
//    change option 3 as off
//    write and overwrite result into file
// If option two is on
//    change option 1 as off
//    change option 3 as off
//    write and overwrite result into file
// If option three is on
//    change option 1 as off
//    change option 2 as off
//    write and overwrite result into file

For updating the values in the same section as WAVE
//read and input values into where difficulty is assigned.

Section 3: 

When starting the game, the user is prompted with the options as stated before.
The user chooses the settings option and can change the difficulty and sound.
Depending on the option selected, the routine will write a string, assigned to the prefernce, into
the appropriate file. Each option will have its own file.
In order to have these change saved, the program will have a soft reset. 
This soft reset will just terminate the program to allow the files to update.
If the player decides to change their mind they are able to repear the process and the
soft reset will overwrite the option when leaving the settings menu.
When the player decides to finally play. The following files will be read and assgined to the 
the difficulty and sound. If the strings are equal to the chosen option, the
difficulty will be assigne appropriately. So if music is selected as on, it will play and
if difficulty is easy, the enemy will not be as deadly. 




 
