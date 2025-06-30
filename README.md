🃏 Blackjack 

This is a simple terminal-based Blackjack game written in Python. The game uses standard Blackjack rules and allows you to bet virtual money, hit, stand, or double down. It’s a great example of procedural programming and terminal interaction.

---

Rules of the Game

- Try to get as close to 21 as possible without going over.
- Number cards are worth their face value.
- Jacks, Queens, and Kings are each worth 10 points.
- Aces are worth either 1 or 11, whichever benefits the hand.
- On your turn, you can:
  - **(H)** Hit – take another card.
  - **(S)** Stand – end your turn.
  - **(D)** Double Down – double your bet and receive only one more card.
- The dealer hits until they reach at least 17.
- If both you and the dealer tie, the bet is returned.
- You start with `$5000` in virtual currency.

---

Features

- Full Blackjack gameplay logic
- Bet management system
- ASCII-based card graphics using `chr()` symbols:
  - ♥, ♦, ♠, ♣
- Card deck built from `rank` and `suit` tuples
- Randomized shuffle using `random.shuffle()`
- Game ends if you run out of money or quit

---

Requirements

This game is built with the Python Standard Library only — no external packages are needed.

Used modules:
- `random`
- `sys`

---

How to Run

1. Make sure you have Python 3 installed.
2. Save the code to a file, e.g., `blackjack.py`.
3. Open your terminal and navigate to the file's directory.
4. Run the game:

```bash
python blackjack.py
