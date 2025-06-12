📘 PopX Landing React App

A pixel-perfect React.js application built from an Adobe XD design. It features seamless navigation between four essential screens: Landing, Signup, Login, and Profile. This app uses React, React Router DOM, and CSS for a smooth, responsive user experience — without Tailwind or external state management.
📌 Features

    🔹 Pixel-perfect responsive UI based on Adobe XD

    🔹 Smooth navigation between pages:

        Landing → Signup → Login → Profile

    🔹 Static Profile Page UI

    🔹 Clean, maintainable CSS styling

    🔹 No backend integration or global state library

🛠️ Tech Stack

    React.js

    React Router DOM

    CSS

📁 Project Structure

popx-landing/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Landing.jsx
│   │   ├── Signup.jsx
│   │   ├── Login.jsx
│   │   └── Profile.jsx
│   │
│   ├── styles/
│   │   ├── Landing.css
│   │   ├── Signup.css
│   │   ├── Login.css
│   │   └── Profile.css
│   │
│   ├── App.js
│   └── index.js
│
├── package.json
└── README.md

🚀 Getting Started
1. Clone the Repository

git clone https://github.com/aliabrar21/Educase.git
cd popx-landing

    🔄 (Make sure the folder name matches your cloned repo if changed.)

2. Install Dependencies

npm install

3. Run the Development Server

npm start

4. Open in Browser

http://localhost:3000

🔄 Page Navigation Flow
From Page	Action	Navigates To
/ (Landing)	Click "Create Account"	/signup
/signup	Submit form	/login
/login	Submit form (dummy auth)	/profile
/profile	Static profile UI (read-only)	-
🎨 Adobe XD Reference

    This project replicates the UI design provided via Adobe XD for precision and styling consistency.

📦 Installation Notes

Install required dependencies:

npm install react-router-dom

👨‍💻 Author

Gaurav Mehra
Frontend Developer (React.js)
📍 Delhi, India
