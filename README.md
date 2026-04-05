# AK47 Card Game — Human vs. Machine

A fast-paced, responsive strategy card game built with HTML5 Canvas and JavaScript. Challenge a smart AI to see who can assemble the legendary **AK47** hand first!

**[▶ Click Here to Play the Game](https://sitholewb.github.io/ak47/)**

---

## 🃏 How to Play

The objective is simple: be the first player to hold the cards **Ace (A), King (K), 4, and 7** in your hand.

1. **Start:** Both you and the computer start with 4 random cards.
2. **Draw:** On your turn, drag a card from the top of the **Deck** or the **Discard Pile**.
3. **Action:**
   - **Swap:** Drop the new card onto one of your existing cards to replace it. Your old card moves to the discard pile.
   - **Discard:** If you don't need the card, drop it anywhere else on the screen to discard it.
4. **Win:** The first to have all four required ranks (A, K, 4, 7) wins the game!

## 🤖 AI Difficulty Levels

- **Easy:** The computer's hand is visible. Great for learning the mechanics.
- **Medium:** The computer's hand is hidden. You must track the discard pile to guess their strategy.
- **Difficult (Machine):** The AI tracks your discards. If you throw away a card, the AI remembers you don't need it and will use that information to block you or optimize its own hand.

## 🚀 Features

- **Mobile First:** Fully responsive design with touch support (drag and drop optimized for glass).
- **Input Locking:** The screen is disabled while the computer "thinks" to prevent accidental moves.
- **Rules Modal:** In-game instructions available at any time via the "Rules" button.
- **Visual Celebration:** Confetti animations and custom victory/defeat messages.
- **Lightweight:** Zero external dependencies—runs entirely in a single HTML file.

## 🛠️ Technical Stack

- **Graphics:** HTML5 Canvas API.
- **Logic:** Vanilla JavaScript (ES6+).
- **Styling:** CSS3 with Flexbox and CSS Variables.
- **Responsiveness:** Dynamic coordinate scaling based on device aspect ratio.

## 📂 Installation & Deployment

1. Clone this repository:
   ```bash
   git clone https://github.com
