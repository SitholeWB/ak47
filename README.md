# AK47 Card Game — Human vs. Machine

A fast-paced, responsive strategy card game built with HTML5 Canvas and JavaScript. Challenge a smart AI to see who can assemble the legendary **AK47** hand first!

## 🃏 How to Play

The objective is simple: be the first player to hold the cards **Ace (A), King (K), 4, and 7** in your hand.

1. **Start:** Both you and the computer start with 4 random cards.
2. **Draw:** On your turn, drag a card from the top of the **Deck** or the **Discard Pile**.
3. **Action:**
   - **Swap:** Drop the new card onto one of your existing cards to replace it. Your old card moves to the discard pile.
   - **Discard:** If you don't need the card, drop it anywhere else on the screen to discard it.
4. **Win:** The first to have all four required ranks (A, K, 4, 7) wins the game!

## 🤖 AI Difficulty Levels

- **Easy:** The computer's hand is visible. This is great for learning the mechanics.
- **Medium:** The computer's hand is hidden. You must track the discard pile to guess what they have.
- **Difficult:** The "Machine" mode. The AI tracks your discards. If you throw away a card, the AI knows you don't need it and will use that information to block you or optimize its own hand.

## 🚀 Features

- **Mobile Friendly:** Fully responsive design with touch support (drag and drop).
- **Input Locking:** The screen is disabled while the computer "thinks" to prevent accidental moves.
- **Visual Effects:** Smooth animations, turn indicators, and a confetti celebration for winners.
- **Lightweight:** Zero dependencies. Just one HTML file.

## 🛠️ Technical Details

- **Language:** JavaScript (ES6+), HTML5, CSS3.
- **Rendering:** High-DPI Canvas scaling for crisp graphics on mobile and retina screens.
- **AI Logic:** Conditional probability-based decision making for the "Difficult" setting.

## 📂 Installation

1. Clone this repository.
2. Open `index.html` in any modern web browser.
3. Enjoy the game!

---
*Created with ❤️ for humans who think they can beat the machine.*
