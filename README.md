get_grade Function:

This function takes a numeric mark as input and returns the corresponding grade based on the provided grading scale.
main Function:

A while loop is used to continuously prompt the user for input.
The user can type "exit" to break the loop and terminate the program.
The program attempts to convert the user input to a float and checks if it's within the valid range (0-100).
If the input is valid, it calculates the grade using the get_grade function and displays it.
If the input is invalid (either not a number or out of range), it provides an appropriate error message and prompts the user again.
Execution:

The script runs the main function when executed, allowing for continuous input until the user decides to exit by typing "exit".
This approach ensures that the program can handle various types of user input gracefully and continues to operate until the user explicitly chooses to terminate it.
