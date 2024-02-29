# Turtle Race Game

This Python script is a simple turtle race game where users can bet on a turtle to win the race. The turtles move randomly, and the user has the opportunity to choose a turtle color before the race begins.

## Getting Started

1. Ensure you have Python installed on your machine.
2. Clone or download the repository to your local machine.

## Prerequisites

This script requires the `turtle` module, which is included in the standard library of Python.

## Running the Code

1. Open a terminal or command prompt.
2. Navigate to the directory where the script is located.
3. Run the script using the following command:

   ```bash
   python turtle_race.py

A pop-up window will appear with a text input prompt asking you to choose a turtle color.
    Enter the color of the turtle you believe will win the race.

Watch the turtle race unfold, and the script will display the winner at the end.

## Code Explanation

1. The script uses the turtle module to create a turtle race on the screen.
2. The create_turtle function initializes six turtles with different colors and positions.
3. The main loop (while is_race_on) moves each turtle forward by a random distance in each iteration.
4. The race ends when the first turtle reaches the right edge of the screen (xcor() > 230).
5. The script then checks the winner's color and compares it with the user's input, providing the outcome.
6. The screen.exitonclick() ensures the window closes when clicked.

## Customization

Feel free to modify the script to add more turtles, change colors, or adjust the random distance for a more dynamic race experience.

_Note: Close the turtle graphics window after the race is complete by clicking on it._

**Enjoy the turtle race! 🐢🏁**