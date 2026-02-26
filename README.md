# 🪨 📄 ✂️ Rock Paper Scissors - Hack the Stack

Contributed by [deboraht07], CSE

<img width="1280" height="593" alt="image" src="https://github.com/user-attachments/assets/84e0f695-0602-4e9c-8512-b15ebfdf573d" />

A modern, animated Rock Paper Scissors game built with HTML, CSS (Tailwind), and JavaScript. Face off against the computer in a best-of-10 match featuring smooth animations and immersive sound effects!

## ✨ Features

- **Responsive UI**: Fully styled using Tailwind CSS for a clean, modern aesthetic.
- **Animated Gameplay**: Custom CSS `@keyframes` create a realistic hand-shaking effect before moves are revealed.
- **Audio Experience**: Integrated sound effects for shaking hands, winning rounds, and losing rounds.
- **Game Logic**:
  - Dynamic scoring system for both Player and Computer.
  - Maximum limit of 10 rounds per game.
  - Adaptive Difficulty Levels: Play against a smart AI that analyzes your past moves to predict your next one. Choose from Easy (random), Medium (predictive), or Hard (analytical counter-strategies).
  - Smart "End Game" state with final result display and a restart option.
- **Asset Preloading**: JavaScript logic to preload images and sounds for a lag-free experience.

## 🛠️ Project Structure

- **HTML**: Semantic structure utilizing Tailwind utility classes for layout.
- **CSS**: Custom animations (`shakePlayer`, `shakeComputer`) for interactive visual feedback.
- **JavaScript**: Modular game function handling DOM manipulation, score tracking, and win/loss logic.

## 🚀 How to Play

### Online

Go to [Rock-Paper-Scissors](https://fossclub-lbsitw.github.io/rock_paper_scissors/)

### Local

#### 1. Clone the repository
```bash
git clone https://github.com/FOSSCLUB-LBSITW/rock-paper-scissors.git
```

#### 2. Launch
Open the `index.html` file in your preferred browser.

## 🎮 Gameplay Instructions

1. **Start**: Select your desired difficulty (Easy, Medium, or Hard) on the intro screen, then click the "Let's Play" button.
2. **Choose**: Click on Rock, Paper, or Scissors.
3. **The Shake**: Wait 1 second for the "shake" animation to complete before results appear.
4. **Winning**: The game tracks your score. Reach the end of 10 rounds to see the final winner!
5. **Restart**: Once the game ends, click "Play Again" to reset the scores and start fresh.

## 🤝 Contributing to Hack the Stack

Feel free to fork this and add your own flair! Some ideas for contribution:
- Add a "Win Streak" counter using `localStorage`.
- Implement multiplayer support so two players can play against each other over the network.
- Create new themes or skins for the hands.

**Happy Learning & Happy Hacking!!!**
