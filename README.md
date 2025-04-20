Live Test: Odd or Even Number Checker (Console-Based PHP)


You will create a simple console-based program in PHP to check whether a number entered by the user is odd or even .



Instructions
Input a Number

Prompt the user to enter a single number.

Validate the input to ensure it is a valid integer. If invalid, display an error message and ask the user to re-enter the number.

Check Odd or Even

Use the modulus operator (%) to determine if the number is odd or even:

A number is even if number % 2 == 0.

A number is odd if number % 2 != 0.

Display Result

Display the result clearly:

Example: "The number 4 is Even."

Example: "The number 7 is Odd."

Exit Option

Allow the user to exit the program by typing exit when prompted for input.

If the user chooses to continue, they can check another number.

Menu-Driven Interface

Use a loop to allow repeated checks until the user decides to exit.

Important Notes :

✅ Your code logic must work correctly.

❌ Extra features will NOT increase your score.



⚠️ Restrictions (Must Follow) : 

🚨 Do NOT modify or remove the provided template structure, function names, variable names, arrays, or objects ..etc.

✅ You can add more functions, variables, or additional logic if necessary, but the existing template must remain unchanged.

Template : 

<?php

// Main program loop

while (true) {

	echo "=== Odd or Even Checker ===\n";

	echo "Enter a number (or type 'exit' to quit): ";

	$input = trim(fgets(STDIN));



	// Exit condition

	if () {

	}



	// Validate input

	if () {

	}



	// Convert input to integer if needed



	// Check if the number is odd or even

	if () {

	} else {

	}

}
