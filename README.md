# 🎬 Movie Bluff

Movie Bluff is a responsive movie browsing web application that allows users to explore popular movies with ratings, search functionality, sorting options, and a smooth Dark Mode experience.

---

## 🚀 Features

- 🔍 Search movies by name
- 📅 Sort movies by year
- ⭐ View IMDb-style ratings
- 🌙 Dark Mode toggle
- 📱 Fully responsive UI
- ➕ Load more movies using "Show More" button

---

## 🖼️ Screenshots

### 🔆 Light Mode
![Light Mode](screenshots/light-mode-1.png)
![Light Mode](screenshots/light-mode-2.png)

### 🌙 Dark Mode
![Dark Mode](screenshots/dark-mode.png)

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Responsive Design (Flexbox / Grid)

---

## 📂 Project Structure

movie-website/
│
├── node_modules/          # Installed npm packages (auto-generated)
│
├── public/                # Static files (favicon, etc.)
│
├── src/
│   ├── assets/            # Images, icons, static assets
│   │
│   ├── components/        # Reusable UI components
│   │   ├── styles/        # Component-specific CSS files
│   │   │   ├── Header.css
│   │   │   ├── MovieCard.css
│   │   │   └── MovieModal.css
│   │   │
│   │   ├── Header.jsx     # App header (search, sort, dark mode)
│   │   ├── MovieCard.jsx  # Individual movie card UI
│   │   └── MovieModal.jsx # Movie details popup/modal
│   │
│   ├── data/
│   │   └── mockMovies.js  # Mock movie data (title, rating, year, poster)
│   │
│   ├── App.css            # Global app styles
│   ├── App.jsx            # Root component
│   ├── index.css          # Base styles
│   └── main.jsx           # Application entry point
│
├── .gitignore             # Files ignored by Git
├── eslint.config.js       # ESLint configuration
├── index.html             # HTML entry file
├── package.json           # Project metadata & dependencies
├── package-lock.json      # Dependency lock file
├── vite.config.js         # Vite configuration
└── README.md              # Project documentation

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-bluff.git
2.Open the project folder:

cd movie-bluff


3.Open index.html in your browser
(or use Live Server in VS Code)
🌟 Future Enhancements

🎥 Movie details page

🧠 Filter by genre

🌐 API integration (TMDB / OMDb)

❤️ Favorites list

👨‍💻 Author

Rakesh
Frontend Developer | Java & Web Enthusiast

If you like this project, don’t forget to ⭐ the repository!
