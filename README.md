**Welcome to Dodge 'Em   Game README**

---

**Introduction**

Take a nostalgic journey back to the golden era of gaming with Dodge 'Em, the classic   game developed by Carla Meninsky in 1980. Experience the thrill of maneuvering a brown car through a maze of blue opponent cars while collecting rewards and avoiding collisions. Dodge 'Em has stood the test of time, captivating players with its simple yet engaging gameplay.

---

**Overview**

Dodge 'Em is set in a racing arena where players control a brown car, aiming to collect rewards while avoiding head-on collisions with blue opponent cars controlled by the computer. The game unfolds on a single screen with concentric roadways, adding an extra layer of challenge as players navigate the twists and turns.

---

**Player Vs. Opponent**

The player's car moves anti-clockwise, while opponent cars move clockwise. Lives are at stake, and collisions with opponent cars result in a loss of life. The goal is to collect rectangular-shaped gift-boxes for reward points.

---

**Driving Rules**

Each roadway in the arena has four turns, and the player starts from the middle of the topmost roadway. Arrow keys control the player's car, allowing turns and acceleration with the spacebar for double speed. Opponent cars make strategic turns based on their distance from the player.

---

**Game Levels**

Dodge 'Em features progressive levels of difficulty:

- **Level 1:** Opponent cars take only top and bottom turns.
- **Level 2:** Opponent cars can take any turn, similar to the player.
- **Level 3:** Increased opponent speed.
- **Level 4:** Two opponent cars chase the player.

Upon completing Level 4, players are greeted with a victorious "You won!" message.

---

**High Scores**

The game keeps track of high scores, storing them in a file named highscores.txt on the hard disk. The top 10 scores are displayed, and new high scores overwrite the lowest score in the list.

---

**Menu**

The game is menu-driven, offering the following options:

- Start a new game
- See high scores
- Help
- Exit

During gameplay, the 'P' key can be pressed to pause the game and access a menu with options to continue, start a new game, see high scores, get help, or exit.

---

**Gameplay**

The core gameplay involves skillful navigation, strategic moves to avoid collisions, and collecting rewards to progress through levels. The game's difficulty increases with each level, providing a challenging yet enjoyable experience.

---

**Setting Up the Game**

The game utilizes basic C++ functions and features, making it accessible for beginners. Here's a breakdown of key functionalities:

1. **Board Initialization:** The game starts with the initialization of the game board, creating a road track for cars to move on.
2. **Player's Car Movement:** The player controls a car using input functions (_kbhit() and _getch()). The car can move left, right, up, or down, depending on the user's input.
3. **Opponent Cars:** The game includes opponent cars that move on predefined roads. Opponent cars change roads based on specific conditions.
4. **Scoring System:** Players earn points by collecting food items placed on the roads. Advancing to a higher level increases the difficulty and score.

---

**Gameplay Mechanics**

1. **Collision Detection:** Collisions with opponent cars result in a decrease in the player's lives. The game ends if lives reach zero.
2. **Level Progression:** Levels increase as the player collects all the food items on the screen. Each level intensifies the game with faster opponent cars.
3. **Speed Control:** Players can control their car's speed using specific keys. Adjusting speed adds an extra layer of challenge.

---

**Adding a Personal Touch**

The code includes personal touches, such as:

- Dynamic road changes for opponent cars.
- Random starting positions for opponent cars.
- Unique ASCII art for cars and roads.

---

**Conclusion**

Dodge 'Em   game encapsulates the simplicity and thrill of classic arcade games. Its timeless design and engaging gameplay make it a standout title in the history of video games. So, why not dust off that   console or try out an emulator to relive the excitement of Dodge 'Em?

Whether you're a gaming enthusiast or just curious about the roots of video gaming, Dodge 'Em offers a delightful journey back to the golden age of arcade games.

Get ready to dodge, maneuver, and win!

---
