# Color Sequence Puzzle
![Color Sequence Puzzle Banner]("./Screenshot 2025-03-21.png")

## Overview

Color Sequence Puzzle is an interactive browser-based memory game that challenges players to remember and recreate color patterns. This project demonstrates front-end development skills using vanilla JavaScript, CSS, and HTML, with no external dependencies.

## Features

- **Progressive Difficulty**: The game starts simple and gradually increases in complexity
- **Memory Training**: Enhances short-term memory and pattern recognition skills
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Hint System**: Limited hints available for when players get stuck
- **Real-time Feedback**: Visual cues indicate correct and incorrect answers
- **Timer**: Tracks your play duration to challenge yourself or friends

## How to Play

1. A sequence of colored dots will appear briefly on the screen
2. Memorize the pattern before it disappears
3. Recreate the pattern by clicking on the colored buttons
4. Click "Submit" to check your answer
5. If correct, you'll advance to the next level with a longer sequence
6. If incorrect, you'll see the correct pattern and can try again
7. Use hints wisely - you only have 3 throughout the game!

## Installation

No installation required! This game runs entirely in the browser.

```
git clone https://github.com/bhagyashree-j/color-sequence-puzzle.git
cd color-sequence-puzzle
```

Then simply open `index.html` in any modern web browser.

## Technologies Used

- HTML5
- CSS3 (with Flexbox for layout)
- Vanilla JavaScript (ES6)

## Game Mechanics

The game follows these core mechanics:

- Each level adds one more color to the sequence (starting with 3 colors at level 1)
- Display time increases with each level to account for increased difficulty
- Players must recreate the exact sequence to progress
- Visual feedback shows which colors were incorrect after a failed attempt

## Customization

You can easily customize various aspects of the game:

- Change the color palette in the HTML file
- Adjust difficulty by modifying the timing variables in JavaScript
- Add more colors or change the starting sequence length

## Future Enhancements

- [ ] High score leaderboard
- [ ] Sound effects and background music
- [ ] Additional game modes (reverse order, color pairs, etc.)
- [ ] Difficulty settings (easy, medium, hard)
- [ ] Social media sharing integration

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Inspired by classic memory games like Simon
- Color palette selected for accessibility and visual appeal
- Special thanks to all contributors and testers

---

Made with ❤️ by Bhagyashree
