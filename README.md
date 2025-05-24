
````markdown
# 🥘 FoodPrep Manager

A simple command-line food recipe tracker built with **Python** and **SQLite**. This project allows you to store, search, and manage your favorite foods, their cooking methods, and ratings.

---

## 📦 Features

- 📝 Add new food items with preparation method and rating
- 📋 View all stored foods
- 🔍 Search for food by name
- ⭐ Get the best-rated cooking method for a food
- ❌ Delete foods by name
- 💾 Data stored locally in a lightweight SQLite database

---

## 🗃️ Database Schema

A single table called `foods`:

| Column Name | Type    | Description             |
|-------------|---------|-------------------------|
| id          | INTEGER | Primary key (auto increment) |
| name        | TEXT    | Name of the food        |
| preparation | TEXT    | Cooking method used     |
| rating      | INTEGER | Rating from 1 to 100    |

---

## 🚀 How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/foodprep-manager.git
   cd foodprep-manager
````

2. **Run the main file**

   ```bash
   python menu.py
   ```

3. **Follow the on-screen menu**

   ```
   -- FOOD LIST --

   Please choose one of these options:

   1) Add new food
   2) See all foods
   3) Find food by name
   4) See which cooking method is best for food
   5) Delete food
   6) Exit
   ```

---

## 📁 File Structure

```
foodprep-manager/
│
├── FLIST1.py         # Contains database setup and functions
├── menu.py           # Main menu and user interface
├── foods.db          # SQLite database (created after first run)
└── README.md         # Project description and usage
```

---

## 🧠 Sample Usage

* Add a new food:

  ```
  Enter food name: Adobo
  Enter cooking method: Braised
  Enter rating from (1-100): 90
  ```

* View all foods:

  ```
  Adobo (Braised) - 90/100
  ```

* Get best cooking method for a food:

  ```
  The best cooking method for Adobo is: Braised.
  ```

---

## 📌 Requirements

* Python 3.x
* No external libraries needed (uses built-in `sqlite3`)

---

## 🛠️ Future Improvements

* Input validation (e.g., rating limits)
* Unique food names or ID-based deletion
* Search with partial names or case-insensitive matching
* Add a GUI (Tkinter or Streamlit)
* Export to CSV or JSON

---

## 👨‍💻 Author

**Eli**
A Python and crochet enthusiast who loves combining creativity and logic.

---
