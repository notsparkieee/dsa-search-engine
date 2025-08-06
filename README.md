# 📚 DSA Search Engine

A specialized search engine for Data Structures & Algorithms (DSA) problems scraped from popular platforms like **LeetCode** and **Codeforces**. Built to help students, interviewees, and competitive programmers quickly find relevant problems based on keywords and topic relevance.

🔗 **Live Project**: [GitHub Repo](https://github.com/notsparkieee/dsa-search-engine)

---

## 🚀 Features

- 🧠 **TF–IDF Based Search** — Relevance-ranked results using term frequency–inverse document frequency
- 🕸 **Web Scraping** — Automatically scrapes problems from LeetCode & Codeforces
- 💬 **Natural Language Processing** — Uses `natural` and `stopword` libraries for better search
- ⚡ **Fast & Lightweight** — No DB required, runs entirely on indexed data
- 📱 **Clean UI** — Simple frontend to view results

---

## 🔧 Tech Stack

| Layer      | Tech                            |
|------------|---------------------------------|
| Frontend   | HTML, CSS, JavaScript           |
| Backend    | Node.js, Express.js             |
| Scraping   | Puppeteer                       |
| Search     | TF–IDF via `natural`, `stopword`|

---

## 🛠 Installation

```bash
# Clone the repo
git clone https://github.com/notsparkieee/dsa-search-engine.git
cd dsa-search-engine

# Install backend dependencies
npm install

# Start the server
node app.js
