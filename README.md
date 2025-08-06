DSA Search Engine 🚀
A specialized search engine for Data Structures & Algorithms (DSA) enthusiasts that scrapes coding problems from LeetCode and Codeforces. This project allows users to quickly find relevant DSA problems through a clean and responsive search interface — eliminating the hassle of navigating multiple platforms.

🌟 Features
🔍 Search DSA Problems Instantly — Find problems by keywords across LeetCode & Codeforces.

🤖 Web Scraping with Puppeteer — Automatically collects problem data in real-time.

📊 Relevance-driven Search using TF-IDF — Indexing and ranking powered by the natural and stopword libraries.

🌐 Clean & Responsive UI — Simple frontend to display search results elegantly.

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Node.js, Express.js
Scraping	Puppeteer
Search Logic	natural, stopword (TF-IDF ranking)

📂 Project Structure
pgsql
Copy
Edit
az-dsa-search-engine/
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── scraper/
│   ├── leetcodeScraper.js
│   └── codeforcesScraper.js
├── server/
│   ├── searchEngine.js
│   └── app.js
├── data/
│   └── problems.json
├── package.json
└── README.md
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/aaqib605/az-dsa-search-engine.git
cd az-dsa-search-engine
2. Install Dependencies
bash
Copy
Edit
npm install
3. Run the Scrapers
bash
Copy
Edit
node scraper/leetcodeScraper.js
node scraper/codeforcesScraper.js
This will generate a problems.json file containing scraped DSA problems.

4. Start the Server
bash
Copy
Edit
node server/app.js
5. Open in Browser
Navigate to http://localhost:3000 to use the DSA Search Engine.

🔧 How It Works
Scraping: Puppeteer automates browsers to scrape problem titles and links from LeetCode and Codeforces.

Indexing & Ranking: Using TF-IDF (Term Frequency-Inverse Document Frequency) via natural and stopword libraries, the problem data is indexed and ranked based on search relevance.

Search Interface: A minimalistic frontend allows users to input queries and view ranked results dynamically.

📚 Useful Resources
Puppeteer Documentation

natural (NLP) Library

TF-IDF Explained

🎯 Roadmap
 Add filters (difficulty, tags)

 Deploy live version (Vercel/Netlify)

 Add support for more platforms (GeeksforGeeks, HackerRank)

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📄 License
This project is open-source and available under the MIT License.

💡 Inspiration
This project is part of an AlgoZenith DSA Search Engine Walkthrough, designed to simplify problem discovery for coders preparing for technical interviews and competitive programming contests.

