# Breakout Game - Advanced Edition

A modern, feature-rich implementation of the classic Breakout arcade game built with Phaser 3.

## 🎮 Features

### Core Gameplay

Classic Breakout mechanics with modern physics

Progressive difficulty (ball speeds up as you progress)

Multiple lives system

Score tracking

### Advanced Features

Multi-ball Power-up: Creates additional balls for chaotic fun

Laser Paddle: Shoot lasers to destroy bricks (press SPACE)

Moving Bricks: Some bricks move horizontally for added challenge

Online Leaderboard: Track high scores across sessions

Power-up System: Collect special abilities throughout the game

### Visual Enhancements

Modern gradient UI with smooth animations

Screen shake effects on brick destruction

Particle effects and visual feedback

Responsive design that works on different screen sizes

### 🚀 How to Play

#### Getting Started

Download the breakout.html file

Open it in any modern web browser

Enter your name when prompted for the leaderboard

Click "START GAME" to begin

#### Controls

Mouse Movement: Move the paddle left and right

SPACE Key: Shoot lasers (when laser power-up is active)

Click: Start game and navigate menus

#### Game Rules

Break all bricks to win the level

Don't let the ball fall below the paddle

You start with 3 lives

Collect power-ups for special abilities:

🔵 Blue: Multi-ball (creates 2 additional balls)

🔴 Red: Laser (press SPACE to shoot)

#### 🛠 Technical Details

Built With Phaser 3.90.0 - Game framework

HTML5 Canvas - Rendering

CSS3 - UI and animations

JavaScript - Game logic

Local Storage - Leaderboard persistence

#### File Structure

breakout.html          # Complete game (single file)
No external dependencies required - all graphics are generated programmatically!

### 🎯 Game Mechanics

#### Scoring

Regular bricks: 10 points

Different colored bricks: 10-30 points

Points multiply based on brick type

#### Power-ups

Multi-ball: Active for 10 seconds

Laser: Active for 15 seconds with 300ms cooldown between shots

Power-ups have a 20% chance to drop from destroyed bricks

#### Difficulty Progression

Ball speed increases every 5 bricks destroyed

Moving bricks add unpredictable challenges

Multiple balls increase the chaos factor

##### 🔧 Customization

The game is easily customizable by modifying these variables in the code:

```bash
// In the BreakoutGame class constructor:
this.ballSpeed = 200;        // Initial ball speed
this.lives = 3;              // Starting lives
this.powerUpChance = 0.2;    // 20% chance for power-ups

// Brick layout in initBricks():
count: { row: 7, col: 5 }    // Grid size
```

#### 🌟 Future Enhancements

Potential features that could be added:

Multiple levels with different brick patterns

Sound effects and background music

Different ball types with unique behaviors

Online multiplayer leaderboard

Mobile touch controls

Level editor

##### 📝 License

Copyleft

##### 🐛 Troubleshooting

Game won't start?

Ensure you're using a modern browser (Chrome, Firefox, Safari, Edge)

Check that JavaScript is enabled

Make sure the Phaser CDN is accessible

Performance issues?

Close other browser tabs

Update your browser to the latest version

Ensure hardware acceleration is enabled

##### 🤝 Contributing

Feel free to fork this project and submit pull requests for:

Bug fixes

New features

Performance improvements

Additional game modes

##### 📞 Support

If you encounter any issues or have questions:

Check the browser console for error messages

Ensure all game assets are loading properly

Verify your browser supports HTML5 Canvas

Enjoy the game! 🎯

### Created with Phaser 3 - The fast, fun, and free open source HTML5 game framework
