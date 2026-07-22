# BUGLOG

Name: Elio Reyes

## Bug #1
    Symptom: Error when compiling
    Cause: in character.h in line 2, it says #define CHARACTER_H_, which is different from the #ifndef CHARACTER_H.
    Fix: I removed the extra _, which helps match the two definitions together.
## Bug #2
    Symptom: Wins was not being tallied correctly.
    Cause: Wins was in main.cpp line 69, where it checked if the hero was alive
    Fix: I moved it so where wins was added on each monster death. 
    
## Bug #3
    Symptom: The message displaying the player defeated a monster was not showing.
    Cause: in main.cpp, there was no way to break out of the for while loop when the monster is defeated
    fix: I added a break that occurs when the monster is defeated. 

## Bug #4 
## Bug #5

## Bug #6
