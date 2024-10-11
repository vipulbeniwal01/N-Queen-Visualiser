N-Queens Visualizer

This project is a visual representation of the N-Queens problem, allowing users to explore the possible arrangements of queens on an N x N chessboard. The program supports boards up to 8x8 and provides visual feedback as it places each queen.

## Demo

Check out the live version [here](https://vipulbeniwal01.github.io/N-Queen-Visualiser/)

Features

	•	Interactive UI for adjusting board size using a slider and number input.
	•	Visual feedback for valid and invalid queen placements using color changes.
	•	Shows possible arrangements of queens on the board.
	•	Includes controls to start (Play) and pause the visualization process.

Usage

	1.	Setup: Ensure the HTML and CSS files are properly linked to this JavaScript file (app.js).
	2.	Controls:
	•	Use the number input (numberbox) to set the size of the board (maximum 8x8).
	•	Adjust the speed of the visualization using the slider (slider).
	•	Click the Play button to start the N-Queens visualization.
	3.	Visualization:
	•	The board is dynamically generated based on the chosen size.
	•	The visualization places queens on the board, showing each step of the algorithm.
	•	Invalid placements are highlighted with different colors.
	4.	Reset: Upon completion or resetting the size, the board will be cleared.

Code Overview

	•	Classes and Methods:
	•	Queen: Contains methods to visualize the N-Queens problem.
	•	nQueen: Main function that starts the solving process.
	•	isValid: Checks if the current queen placement is valid.
	•	clearColor: Resets the board colors for each step.
	•	delay: Controls the speed of the visualization.
	•	solveQueen: Recursively attempts to place queens on the board.
	•	UI Elements:
	•	numberbox: Input element for the user to set board size.
	•	slider: Controls the speed of the visualization.
	•	progressBar: Displays the current speed setting.
	•	playButton, pauseButton: Start and pause the visualization.

Limitations

	•	The maximum supported board size is 8x8 to ensure smooth visualization.
	•	Only displays a subset of possible solutions due to pre-defined arrays for arrangements.

Future Enhancements

	•	Implement a more comprehensive solution set for larger board sizes.
	•	Add the ability to pause and resume the visualization.
	•	Improve the UI with more detailed explanations and controls.

How to Run

	1.	Download or clone the repository.
	2.	Open the main HTML file (index.html) in a web browser.
	3.	Use the provided controls to explore the N-Queens problem.

Dependencies

	•	This project uses Font Awesome for the queen icon representation.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to modify this as needed before uploading to GitHub!
