This Battleship game implementation focuses on adhering to Object-Oriented Programming (OOP) principles, ensuring modularization, encapsulation, and code reuse. It follows a structured approach with namespaces, access modifiers, polymorphism, and logical class organization.

Classes Overview
Battleship
Purpose: Highest level class orchestrating the game.
Responsibilities:
Displaying the main menu.
Handling user input for starting a new game, displaying high scores, or exiting.
Usage:
Contains a loop for the game's execution.
Display
Purpose: Handles all display-related functionalities.
Responsibilities:
Printing the game menu.
Printing the board during ship placement and gameplay.
Printing the outcome of the game.
Usage:
Ensures no Console.WriteLine() occurs outside this class.
Input
Purpose: Manages user input.
Responsibilities:
Gathering user input.
Providing separate methods for different input cases.
Handling input validation.
Usage:
Ensures input is validated and processed appropriately.
Game
Purpose: Manages the game's logic and flow.
Responsibilities:
Looping through player moves.
Determining round flow.
Deciding game end conditions.
Providing different game modes with distinct round flows.
Usage:
Ensures seamless execution of the game.
Implementation Details
Namespace: Classes are organized within namespaces for better organization and to prevent naming conflicts.
Access Modifiers: Content is exposed with minimal visibility to maintain encapsulation.
Properties with Private Setters: Wherever applicable, properties with private setters are used instead of fields.
Logical Structure: Classes are logically structured, eliminating code duplication through inheritance.
Method Communication: Public methods are used for external communication, while private methods handle internal logic, enhancing readability and reducing redundancy.
Polymorphism: Employed extensively to enhance code universality and avoid duplication.
No Static Contexts: The program doesn't rely on static contexts, promoting instance-based behavior.
How to Use
Clone this repository.
Navigate to the project directory.
Build and run the application.
Follow the on-screen instructions to play Battleship.
Contributors
[Your Name]
Acknowledgements
Special thanks to [mention any resources or individuals who contributed to your learning or project development].

License
This project is licensed under the [License Name] License - see the LICENSE.md file for details.
