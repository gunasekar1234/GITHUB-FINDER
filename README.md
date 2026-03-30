# 🔍 GitHub User Finder

A modern web app to **search and explore GitHub users** using the GitHub API.
View profile details, stats, and repositories in a clean UI.

---

## 🚀 Features

- 🔎 Search any GitHub username
- 👤 View profile (avatar, bio, location, join date)
- 📊 See followers, following, and repositories count
- 📦 Display latest repositories
- 🔗 Direct link to GitHub profile
- ⚡ Fast and responsive UI
- ❌ Error handling for invalid users

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- **GitHub REST API**
- **Font Awesome Icons**

---

## 📁 Project Structure

```id="gh-structure"
github-user-finder/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## ⚙️ How It Works

- User enters a GitHub username
- App fetches data from:

```id="gh-api"
https://api.github.com/users/{username}
```

- Displays:
  - Profile details
  - Stats
  - Repositories

---

## ▶️ How to Run

1. Clone the repository

```id="gh-clone"
git clone https://github.com/your-username/github-user-finder.git
```

2. Open folder
3. Run `index.html` in browser

---

## 💡 Usage

- Type a GitHub username
- Click **Search**
- View user profile instantly

---

## 📸 Preview

> Displays GitHub profile with avatar, stats, and repositories

---

## 🌟 Future Improvements

- 🌙 Dark mode toggle
- 📊 Repo sorting (stars, forks)
- 🔍 Search suggestions
- 📱 Better mobile UI
- ⚡ Debounce search input
- ❤️ Favorite users feature

---

## ⚠️ Note

- GitHub API has **rate limits** (60 requests/hour without auth)

---

## 🤝 Contributing

Feel free to fork and improve the project!

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Gunasekar M

---

⭐ If you like this project, give it a star!
