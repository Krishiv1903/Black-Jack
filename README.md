# 🎴 Blackjack Game — JavaScript, HTML, CSS

A simple, interactive, and visually engaging **Blackjack (21)** game built using **JavaScript**, **HTML**, and **CSS**. The game includes standard Blackjack mechanics like hitting, standing, dealer logic, ace adjustments, and random shuffling.

---

## 🌟 Demo Screenshot

> *(Replace the image with your actual screenshot)*
> ![Blackjack Screenshot](https://via.placeholder.com/900x450.png?text=Blackjack+Game+Preview)

---

## 🚀 Features

* ♠ **Fully functional Blackjack gameplay**
* ♥ **Dynamic card rendering using images**
* ♣ **Random deck generation & Fisher–Yates shuffle**
* ♦ **Correct Ace handling (11 → 1 when needed)**
* 🃏 **Dealer's hidden card reveal**
* 🔄 **Play again / reload button**
* 🎨 **Custom styling with smooth UI**

---

## 🧠 Game Logic Overview

### ▶️ Player Actions

* **Hit**: Draw a card until you stand or bust.
* **Stay**: Dealer reveals their hidden card and draws until 17+.

### 🏦 Dealer Rules

* Dealer draws automatically until `sum ≥ 17`.
* Ace also adjusts automatically to avoid busts.

### 🂡 Ace Adjustment Logic

```
If total > 21 and player has Ace(s):
    Convert Ace from 11 → 1
```

---

## 📂 Project Structure

```
📁 BlackJack/
│── index.html
│── BlackJack2.js
│── BlackJack.css
└── 📁 Cards/
      ├── A-S.png
      ├── 2-H.png
      ├── BACK.png
      └── ... (52 cards)
```

---

## 🛠️ How to Run

### **1. Download the project**

```
git clone https://github.com/your-username/blackjack-game.git
```

### **2. Open the game**

Simply open **index.html** in your browser.
No installations, frameworks, or servers required.

---

## 📜 How the Deck Works

* Deck is built from:

  * **Values**: A,2,3,4,5,6,7,8,9,10,J,Q,K
  * **Suits**: C, D, H, S
* Total 52 unique cards
* Shuffling uses a variation of the **Fisher–Yates algorithm**

---

## 🧩 Key JavaScript Functions

| Function        | Purpose                           |
| --------------- | --------------------------------- |
| `buildDeck()`   | Creates all 52 card combinations  |
| `shuffleDeck()` | Randomly shuffles the deck        |
| `startGame()`   | Deals cards & sets up game UI     |
| `hit()`         | Player draws a card               |
| `stay()`        | Dealer logic + result calculation |
| `reduceAce()`   | Adjusts Ace to avoid bust         |
| `getValue()`    | Converts card to numeric value    |

---

## 🎨 UI Highlights

* Clean card layout
* Dealer’s first card hidden
* Dynamic sums
* Result message display

---

## 📌 Future Enhancements (Optional)

* ✔️ Add sound effects
* ✔️ Add betting system
* ✔️ Add score tracking
* ✔️ Add animations (fade, slide)
* ✔️ Add mobile responsive UI

---

## 🙌 Contributing

Feel free to fork this repo, open issues, or submit pull requests!

---

## 📄 License

MIT License — free to use and modify.

---

If you want, I can also:

✅ Generate a **professional project logo**
✅ Make a **GIF gameplay preview**
✅ Create a **fancy README with emojis + CSS style badges**
✅ Auto-generate **Markdown tables, code blocks, or images**
