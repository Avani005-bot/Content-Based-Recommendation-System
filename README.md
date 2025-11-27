🎬 Content-Based Movie Recommendation System

A content-based recommendation system built using React.js and machine learning concepts (TF-IDF + Cosine Similarity).
This project recommends movies to users based on the similarity of movie descriptions, allowing personalized suggestions without user history.

🚀 Project Overview

This project applies content-based filtering, a popular recommendation system technique, to suggest movies similar to a selected title. Movie similarity is calculated using:

Text Vectorization (TF-IDF)

Cosine Similarity

Metadata comparison (genre, description, keywords)

The frontend is built with React.js, providing a clean UI for users to search and discover similar movies.

🧠 How It Works

Each movie description is converted into a TF-IDF vector (Term Frequency–Inverse Document Frequency).

The cosine similarity is calculated between movies to determine how alike they are.

When a user selects a movie, the system returns the top N most similar movies.

✨ Features

✔ Search any movie
✔ Display movie recommendations visually
✔ Fast & responsive React UI
✔ Content-based filtering (no user login needed)
✔ Expandable architecture for ML backend integration
✔ Clean folder structure and modular components

🛠️ Tech Stack
Frontend

React.js

JavaScript (ES6+)

CSS

Machine Learning Concepts

TF-IDF Vectorization

Cosine Similarity

NLP preprocessing

📂 Project Structure
├── public/
│   ├── index.html
│   ├── favicon.ico
│   ├── manifest.json
│   └── robots.txt
│
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
│
├── package.json
├── package-lock.json
├── README.md
└── .gitignore

🧭 How to Run the Project
1️⃣ Install Dependencies
npm install

2️⃣ Start Development Server
npm start

3️⃣ Open in Browser
http://localhost:3000

📸 Screenshots (Optional)

Add screenshots of your UI here later: e.g., home screen, results page

![App Screenshot](./screenshots/home.png)

📈 Future Improvements

🔹 Add backend using Python (Flask / FastAPI)
🔹 Add TMDB API integration
🔹 Add user-based collaborative filtering
🔹 Deploy on Netlify / Vercel

👩‍💻 Author

Avani Parashar
B.Sc. IT | Machine Learning Enthusiast | React Developer

⭐ Support

If you like this project, don’t forget to ⭐ the repository!
