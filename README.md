# 🎮 KBC - Kaun Banega Crorepati (Python Game)

A text-based Python game inspired by India's iconic quiz show **Kaun Banega Crorepati (KBC)**. Answer 17 progressively harder questions and climb your way to ₹7,00,00,000!

---

## 🕹️ How to Play

1. Clone or download this repository
2. Run the game using Python:
   ```bash
   python kbc.py
   ```
3. Enter your name and follow the on-screen instructions
4. Answer each question by typing the option letter: `A`, `B`, `C`, or `D`
5. Type `quit` at any time to exit with your current winnings
6. Type `50-50` to use your lifeline *(see Lifelines section)*

---

## 💰 Prize Ladder

| Question | Prize |
|----------|-------|
| Q1 | ₹1,000 |
| Q2 | ₹2,000 |
| Q3 | ₹3,000 |
| Q4 | ₹5,000 |
| **Q5 — Pehla Padav 🏁** | **₹10,000** |
| Q6 | ₹20,000 |
| Q7 | ₹40,000 |
| Q8 | ₹80,000 |
| Q9 | ₹1,60,000 |
| **Q10 — Dusara Padav 🏁** | **₹3,20,000** |
| Q11 | ₹6,40,000 |
| Q12 | ₹12,50,000 |
| Q13 | ₹25,00,000 |
| Q14 | ₹50,00,000 |
| Q15 | ₹75,00,000 |
| Q16 | ₹1,00,00,000 |
| **Q17 — Final Question 🏆** | **₹7,00,00,000** |

---

## 🏁 Padavs (Checkpoints)

The game has **2 Padavs** (safe checkpoints):

- **Pehla Padav** — After Question 5 (₹10,000)
- **Dusara Padav** — After Question 10 (₹3,20,000)

If you answer incorrectly after a Padav, you take home the Padav amount instead of losing everything.

---

## 🆘 Lifelines

| Lifeline | Command | Description |
|----------|---------|-------------|
| 50-50 | `50-50` | Eliminates 2 incorrect options, leaving 1 wrong and 1 correct |
| Quit | `quit` | Exit the game and take your current winnings home |

---

## 📋 Requirements

- Python 3.x
- No external libraries required — runs on standard Python

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/ZenSensi/KBC.git

# Navigate into the project folder
cd kbc-python

# Run the game
python kbc.py
```

---

## 📁 Project Structure

```
kbc-python/
│
└── kbc.py       # Main game file
```

---

## 🙌 Author

Made with ❤️ by a KBC fan. Feel free to fork, improve, and add your own questions!

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
