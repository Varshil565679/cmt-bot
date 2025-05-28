# 🌟 Git Fake Commits 🌟

Feeling like your GitHub graph could use a glow-up? Say hello to **git_fake_commits**, the ultimate tool for spicing up your activity graph with authentic-looking commits!

No one will ever suspect your productivity wasn’t 100% real. 😉

---

## 📖 Purpose

This script:

- Generates **random commits** for a specified date range.
- Skips days randomly to add authenticity.
- Pushes all changes to your GitHub repo automatically.

Perfect for recruiters, colleagues, or just your ego.

---

## 🚀 Usage Guide

### 1️⃣ Prerequisites

- **Python 3.6+** installed.
- Git installed and configured with a remote repository.
- A Git repository ready to work its magic.

### 2️⃣ Setup

1. Place the `script.py` file in your repository.
2. Ensure the repo is initialized with `git init` and connected to a remote.

### 3️⃣ Running the Script

Run the script like so:

```bash
python script.py
```

---

## ✏️ Variables to Customize

Here’s how to tailor the script to your needs:

- **`start_date`**: The starting date for commits.
- **`end_date`**: The ending date for commits.
- **`min_commits`**: Minimum commits per day.
- **`max_commits`**: Maximum commits per day.
- **`skipping`**: Enable random day skipping (`True/False`).
- **`max_skip_days`**: Max days to skip at a time (if skipping is enabled).

Example:

```python
start_date = datetime(2023, 1, 1)
end_date = datetime(2023, 1, 10)
min_commits = 1
max_commits = 5
skipping = True
max_skip_days = 2
```

---

## 🎥 Demo Video

Want to see how it works? Check out the video tutorial here:  
[Watch the Video](https://www.youtube.com/watch?v=JKA3IOJRwX0)

---

## 🛠️ Script in Action

- Commits are made to `info.txt` with details like date and commit number.
- Random skips make the activity graph look organic.
- Changes are automatically pushed to your remote repo.

---

## 🕶️ Why Use git_fake_commits?

1. **Boost your graph**: Fill up those dull gray squares.
2. **Impress recruiters**: Productivity? You’ve got it.
3. **Fun randomness**: A graph as unique as you are.

---

## ⚠️ Disclaimer

This script is purely for fun and educational purposes. Use responsibly—fake commits won’t write your next big app! 😅

Happy committing! 🎉  
