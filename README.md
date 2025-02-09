# Maze Game

An interactive maze game built with Matter.js physics engine where players navigate a ball through procedurally generated mazes.

![Maze Game Demo](demo.gif)

## Features

- Procedurally generated mazes ensuring a unique experience every time
- Physics-based ball movement
- Collision detection for walls and goal
- Responsive design that adapts to screen size
- Victory animation with falling walls
- Simple controls using arrow keys

## Live Demo

Try the game here: [Maze Game](https://maze-game-nu.vercel.app/)

## How to Play

1. Use the arrow keys to control the blue ball:
   - ⬆️ Up Arrow: Move up
   - ➡️ Right Arrow: Move right
   - ⬇️ Down Arrow: Move down
   - ⬅️ Left Arrow: Move left
2. Navigate through the red walls
3. Reach the green square to win
4. Watch the walls collapse when you win!
5. Click "Play Again" to generate a new maze

## Technologies Used

- Matter.js - 2D physics engine
- Vanilla JavaScript (ES6+)
- HTML5 Canvas
- CSS3

## Customization

You can modify the game by adjusting these variables in `index.js`:

- `cellsHorizontal` and `cellsVertical`: Change maze size
- `unitLengthX` and `unitLengthY`: Adjust cell size
- Colors can be modified in the `render` options

## Acknowledgments

- Built with inspiration from Colt Steele and Stephen Grider's Modern JavaScript Bootcamp Course
- Powered by [Matter.js](https://brm.io/matter-js/)
