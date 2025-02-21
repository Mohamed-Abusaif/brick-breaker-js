# Brick Breaker Project Plan

### _Team Assignments and Responsibilities_

---

### _Abusaif: Paddle_

#### _Responsibilities:_

1. _Design Phase:_

   - Create the paddle design (size, color, positioning) using CSS.
   - Ensure the paddle fits well within the canvas dimensions.

2. _Logic and Implementation:_

   - Add movement logic using keyboard inputs (e.g., ArrowLeft and ArrowRight).
   - Ensure paddle stays within canvas boundaries.
   - Make paddle movement smooth and responsive.

3. _Integration:_
   - Test paddle interaction with the ball for proper collision detection.
   - Adjust the angle of the ball based on where it hits the paddle.

---

### _Aya and Gohar: Ball_

#### _Responsibilities:_

1. _Design Phase:_

   - Create the ball design (size, color, shadow effects) using CSS.
   - Position the ball at the starting point in the canvas.

2. _Logic and Implementation:_

   - Add initial movement logic (randomized direction and speed).
   - Implement bouncing mechanics off walls and paddle.
   - Handle ball resetting if it misses the paddle (life lost).

3. _Integration:_
   - Work with Team Member 1 (Paddle) to ensure collision detection is accurate.
   - Test ball speed adjustments based on difficulty levels.

---

### _El Banna: Bricks_

#### _Responsibilities:_

1. _Design Phase:_

   - Design the bricks (different colors or textures for crackable and unbreakable bricks).
   - Set up a grid layout for the bricks in the canvas.

2. _Logic and Implementation:_

   - Add logic for brick states: cracked (first hit) and broken (second hit).
   - Implement collision detection between the ball and bricks.
   - Handle unbreakable bricks (ball bounces but doesn’t destroy them).

3. _Integration:_
   - Test the interaction between the ball and bricks.
   - Ensure cracked bricks visually update after the first hit.

---

### _For all Team Members: Game Mechanics & Bonus Features_

#### _Responsibilities:_

1. _Game Flow Management:_

   - Implement and display lives and scoring logic on the screen.
   - Create a game-over screen and restart functionality.

2. _Difficulty Levels:_

   - Add a difficulty selection menu (easy, medium, hard).
   - Adjust ball speed and other parameters based on difficulty.

3. _Bonus Features:_

   - Implement life-dropping mechanics:
     - Drop a life icon randomly when bricks are hit.
     - Detect if the paddle catches the life icon and increase lives.
   - Ensure proper display and functionality of unbreakable bricks.

4. _Integration:_
   - Test all game flows, from start to game over, ensuring smooth transitions.
   - Debug issues related to overlapping features (e.g., bonus icons colliding with bricks).

---

### _Task Dependencies and Collaboration_

#### _Dependencies:_

- Ball logic depends on paddle movement and collision.
- Brick collision depends on ball mechanics.
- Game mechanics (lives, score) depend on interactions between ball, bricks, and paddle.

#### _Collaboration:_

- Abusaif (Paddle), Aya and Gohar (Ball) need to collaborate for collision detection.
- El Banna (Bricks) should coordinate with Aya and Gohar (Ball) to ensure bricks break correctly.
- The whole Team (Game Mechanics) should oversee integration and test for smooth gameplay.

---

### _Deliverables for Each Team Member_

1. _Abusaif Paddle_

   - Responsive paddle movement and collision with the ball.
   - Paddle design and smooth interaction with the canvas.

2. _Aya and Gohar: Ball_

   - Ball movement and bouncing mechanics.
   - Proper collision handling with walls, paddle, and bricks.

3. _El Banna: Bricks_

   - Visually distinct bricks (cracked, broken, unbreakable).
   - Accurate brick collision and state management.

4. _All the Team: Game Mechanics_
   - Functional lives and scoring system.
   - Difficulty levels, bonus life mechanics, and restart flow.

---

### _Milestones and Deadlines_

Each Sprint is 2 Days Period

#### _First Sprint: Setup & Initial Design_

- Team members finalize the design of their respective elements.
- Initial setup of canvas and rendering of paddle, ball, and bricks.

#### _Second Sprint: Core Functionality_

- Paddle and ball movement implemented.
- Bricks rendered and basic collision detection added.

#### _Third Sprint: Game Features_

- Lives and scoring implemented.
- Bonus features (life drops, unbreakable bricks) added.

#### _Fourth Sprint: Testing and Final Touches_

- Full integration and gameplay testing.
- Styling, animations, and sound effects added.
- Deployment and team review.
