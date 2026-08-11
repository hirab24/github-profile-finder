# GitHub Profile Finder

A clean, terminal-inspired web app to look up any GitHub user's profile — followers, repos, bio, location, and top starred repositories — all in one search.

![GitHub Profile Finder Screenshot](githubdashboard.jpeg)

## Features

- 🔍 Search any GitHub username in real time
- 🧑‍💻 Displays avatar, name, bio, location, and company
- ⭐ Shows top 3 starred repositories with direct links
- 📊 Follower, following, and public repo counts
- ⏳ Animated loading state while fetching data
- ⚠️ Friendly error handling for invalid usernames
- 📱 Fully responsive — works on mobile and desktop
- ⌨️ Search by pressing Enter or clicking the button

## Built With

- **HTML5** — structure
- **CSS3** — styling, animations, responsive layout
- **JavaScript (Vanilla)** — API calls, DOM manipulation
- **GitHub REST API** — live user and repository data

## How It Works

1. Enter a GitHub username in the search box
2. The app fetches the user's public profile via the [GitHub API](https://api.github.com)
3. Their top starred repositories are fetched separately and sorted by star count
4. Results are rendered dynamically in a terminal-style card

## Demo

Open `index.html` directly in your browser, or enable **GitHub Pages** in this repository's settings to get a live link.

## Local Setup

```bash
git clone https://github.com/hirab24/github-profile-finder.git
cd github-profile-finder
```

Then simply open `index.html` in your browser — no build steps or dependencies required.

## Possible Improvements

- Add a dark/light theme toggle
- Save recent searches (localStorage)
- Show contribution graph
- Add pagination for repositories

## Author

**hirab24**
[GitHub Profile](https://github.com/hirab24)
