<<<<<<< HEAD
Project Report: Memory Game
Project Name: Memory Game
Subject: Fundamentals of Web Technologies
________________________________________________________________________________________________________________________
1. Project Goal
The goal of this project is to develop an interactive "Memory Game" where the player matches pairs of identical elements (in this case, emojis). The game aims to improve memory and concentration.
________________________________________________________________________________________________________________
2. How to Use the Code (How to Play)
Open the Game in a Browser:
1.Save the HTML and CSS code in files named midka2.html and midka2.css.
2.Open midka2.html in a web browser.

Objective:
Match all pairs of cards to win the game.

Gameplay:
1.The game starts with all cards face-down.
2.Click on a card to flip it and reveal the emoji.
3.Click on another card to try and find a matching emoji.

Rules:
If the two open cards match:
-They remain face-up and are marked as matched.
If the two open cards do not match:
-Both cards flip back face-down after a short delay.
Continue until all pairs are matched.

Winning the Game:
When all pairs are matched, a congratulatory alert will appear:
"Congratulations! You Win!!"

Reset the Game:
Click the "Reset Game" button to shuffle the cards and start a new game.
________________________________________________________________________________________________________________________
2. Implementation Description
HTML
•	Utilized HTML5 structure:
o	A <div> element with the class container houses the game title, the game board (.game), and a reset button (Reset Game).
o	The Reset Game button reloads the page to restart the game.
CSS
•	Styling highlights:
o	Flexbox is used to center the game elements and make the layout visually appealing.
o	Background colors and fonts enhance the design and theme of the game.
•	Special Features:
o	Card flip animations (rotateY) add dynamic visuals.
o	Different element states:
	.boxOpen — indicates an open card.
	.boxMatch — indicates a matched pair.
JavaScript
•	Game logic:
o	The cards are represented as an array of emojis.
o	The array is shuffled randomly using the .sort() method with a random comparator.
o	Cards are dynamically created as <div> elements and appended to the .game container.
o	On card click:
	The card flips (by adding the .boxOpen class).
	If two cards are open, their contents are compared:
	If they match, both cards receive the .boxMatch class.
	If all pairs are matched, the player receives a congratulatory alert.
	If the cards do not match, they close after a slight delay (setTimeout).
o	Reset Game:
	The game can be reset by clicking the "Reset Game" button, which reloads the page
________________________________________________________________________________________________________________________
3. Results and Features
1.	Functionality:
o	The game correctly identifies matching pairs.
o	The game ends with a success message when all pairs are matched.
o	The Reset Game button restarts the game.
2.	Visual Design:
o	The design uses a harmonious color palette.
o	Smooth animations and transitions enhance the user experience.
3.	Responsiveness:
o	The game uses a fixed board size, but flexbox ensures it is centered on any screen width.
________________________________________
4. Conclusion
The "Memory Game" project effectively demonstrates knowledge of HTML, CSS, and JavaScript. It includes:
•	Dynamic element creation with JavaScript.
•	Event handling and animations for interactivity.
•	Modern CSS techniques for styling.
The game is simple, user-friendly, and showcases fundamental skills in web development.
Suggestions for Improvement:
1.	Implement a scoring system (based on time or attempts).
2.	Create a mobile-friendly version of the game with a responsive layout.

=======
# project.endterm
>>>>>>> 1db027af6b789ad0bdcd06dc3da02672da09958d
