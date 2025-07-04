# FakeCoin

FakeCoin is an interactive web-based game that challenges users to find a single fake (lighter) coin among a set of coins using the minimum number of weighings. The project demonstrates the application of dynamic programming and optimal search strategies in a fun, educational setting.

## Features

### 1. User Authentication
- Login system for users and an admin account (special admin features for user 'ganashree').
- User sessions are managed via local storage.

### 2. Gameplay
- Choose the number of coins (3-32) to play with.
- One coin is randomly selected as the fake (lighter) coin.
- Drag and drop coins onto a virtual balance scale to compare their weights.
- Receive feedback after each weighing: which side is lighter, or if both sides are equal.
- Track the number of attempts and time taken.
- Make a final guess to identify the fake coin.
- Tutorial for first-time users.
- Sound effects and accessibility options.

### 3. Hints System
- Up to 3 hints per game, based on dynamic programming (DP) analysis.
- Hints suggest optimal ways to split the coins for the next weighing.

### 4. Dynamic Programming (DP) Analysis
- Real-time DP analysis panel shows the optimal strategy and information gain for each weighing.
- Visualizes the divide-and-conquer approach and expected steps to solve.
- Users can toggle the DP analysis panel during the game.

### 5. Game Analysis Visualization
- After each game, users can view a binary state-space tree of their moves and the optimal path.
- The analysis page highlights the user's path, the fake coin, and possible outcomes at each step.

### 6. Leaderboard
- Tracks best performances by attempts, time, and coin count.
- Filter leaderboard by number of coins.
- Shows fastest attempts per user and all attempts (toggleable).
- Admin can clear the leaderboard.

### 7. Achievements
- Earn achievements for perfect solves, speed, no hints, and first win.
- Achievements are displayed on the result page after each game.

### 8. Responsive and Modern UI
- Fully responsive design for desktop and mobile.
- Animated backgrounds, stylish buttons, and clear feedback messages.

## How to Play
1. Login or create a new user.
2. Select the number of coins and start the game.
3. Drag coins onto the left and right pans of the scale and click "Weigh Coins".
4. Use hints or DP analysis if needed.
5. Make your final guess when confident.
6. View your results, achievements, and analysis.
7. Compete on the leaderboard!

## Technologies Used
- React.js
- React Router
- Local Storage for persistence
- Custom CSS for styling and animations

---

Enjoy learning and testing your logic with FakeCoin!
