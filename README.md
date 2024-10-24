# Snake-Game
**SnakeMania - A Snake Game**

**Technologies Used:**

* HTML: Used for structuring the web page layout, including the game board, score and high score displays.
* CSS: Responsible for styling the game elements (snake, food, board) with visually appealing colors, borders, and background images.
* JavaScript: The core logic behind the game's functionality. It handles:
    * Snake movement and direction changes based on keyboard input (arrow keys)
    * Food generation and collision detection
    * Scorekeeping and high score tracking using localStorage
    * Game loop management with `window.requestAnimationFrame` for smooth animation
    * Sound effects and background music integration for a more immersive experience

**Key Features:**

* Responsive Design: The game adjusts to different screen sizes using viewport units (vmin) for the board and snake size.
* Smooth Animation: Leveraging `requestAnimationFrame` ensures a visually smooth game experience.
* High Score Tracking: The game stores the highest achieved score in the browser's localStorage, allowing users to track their progress.
* Engaging Audio: Sound effects for food consumption and game over, complemented by background music, enhance gameplay immersion.
